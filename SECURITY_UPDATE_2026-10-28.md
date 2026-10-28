# Parallax Core Mainnet Security & Network Update — 28 October 2026

Parallax Core has completed an important mainnet security and consensus update following the recent attack against the network.

This update strengthens difficulty-retarget protection, restores Parallax's intended 4-minute block target, preserves the 2,016-block difficulty-adjustment interval, and introduces a new hardcoded checkpoint for the rebuilt mainnet chain.

## Security Improvements

### Zeitgeist2 / Difficulty-Manipulation Protection

Parallax Core now explicitly uses the full difficulty-adjustment period when calculating the next mining difficulty.

This protection is designed to prevent short-window timestamp manipulation, including the class of Time Warp / Zeitgeist2 attacks where majority hashpower could otherwise attempt to manipulate timestamps and force the network difficulty downward.

The difficulty calculation now uses the complete retarget interval rather than a short local window.

### Hardcoded Mainnet Checkpoint

A new hardcoded checkpoint has been added at:

**Block height:** 319

**Block hash:**

`d22a5d33c500b57fc1cf6981b6a99e265726654ee297d72234797fdb69357af1`

The hash was verified directly against the active Parallax mainnet blockchain before deployment.

This checkpoint protects established blockchain history by preventing alternative chains from rewriting blocks prior to the checkpoint.

## Parallax Block Time Restored

Parallax was designed with a **4-minute target block time** — positioned between Litecoin's faster block timing and Bitcoin's slower block timing.

The mainnet consensus parameters have now been restored to:

- **Target block time:** 4 minutes
- **Difficulty adjustment interval:** 2,016 blocks
- **Difficulty adjustment timespan:** 5.6 days
- **Mainnet minimum-difficulty blocks:** disabled
- **Difficulty retargeting:** enabled

This means difficulty adjustments occur at:

**2,016 → 4,032 → 6,048 → 8,064 → and every 2,016 blocks thereafter.**

## Proof-of-Work

Parallax continues to use **Scrypt Proof-of-Work**.

The mining algorithm itself has not been changed by this update.

## Deployment Verification

The updated Parallax mainnet daemon was rebuilt and deployed successfully.

Post-deployment checks confirmed:

- Parallax Core daemon starts normally.
- Mainnet P2P is listening on port **19339**.
- Mainnet RPC is listening locally on port **19340**.
- The active blockchain continues normally.
- The new mainnet checkpoint is recognised.
- The network continues operating without blockchain warnings.

## A Personal Note

I also want to explain why this security update took longer than I would normally allow following an attack on the Parallax network.

Shortly before this work was completed, I was involved in a serious accident. I was unconscious for several days and have since undergone three operations.

Much of this update has been completed from a hospital bed.

I am sharing this not for sympathy, but because I believe the people following and supporting Parallax deserve to know why development was temporarily delayed.

Even under those circumstances, I was determined to get back to the network, understand exactly what had happened, strengthen the consensus code, rebuild the mainnet daemon and get Parallax moving forward again.

Parallax Core is something I am deeply committed to building.

A serious accident, three operations and days of unconsciousness delayed the work — but they did not stop it.

## Moving Forward

The Parallax network is active, and development is continuing.

The current security model now includes:

- Full-period difficulty-retarget protection.
- Protection against short-window difficulty manipulation.
- A 4-minute target block time.
- A 2,016-block retarget interval.
- Hardcoded checkpoint protection.
- Scrypt Proof-of-Work.
- Accumulated chainwork validation.
- Existing fork-detection and network-validation protections.

No Proof-of-Work blockchain can truthfully claim to be immune from every possible majority-hashpower attack. These changes are designed to make specific attack techniques substantially more difficult and to protect established Parallax blockchain history.

Parallax Core will continue to be monitored, tested and strengthened as the network grows.

The attack did not end Parallax.

Neither did the accident.

**Parallax Core continues.**

---

Official website: https://paraplx.com/

Block explorer: https://explorer.paraplx.com/

GitHub: https://github.com/ParallaxCoreDevelopers/parallax_wallet_miner
