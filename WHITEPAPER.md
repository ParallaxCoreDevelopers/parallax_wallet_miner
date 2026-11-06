<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parallax (PLX) Whitepaper | Layer 1 Blockchain</title>
    
    <meta name="description" content="Read the official Parallax (PLX) whitepaper. Explore our independent Layer 1 Scrypt Proof-of-Work blockchain architecture, consensus, and security model.">
    <meta name="robots" content="index, follow">
    <link rel="canonical" href="https://paraplx.com">
    <link rel="icon" type="image/png" href="logo.png">

    <style>
        :root {
            --bg-color: #0b130f;
            --container-bg: #111a15;
            --text-color: #cfdcd5;
            --text-muted: #8fa399;
            --accent-green: #10b981;
            --accent-hover: #059669;
            --nav-bg: #16221c;
            --nav-border: #1f3229;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            padding: 0;
        }

        header {
            text-align: center;
            padding: 40px 20px 20px 20px;
        }

        .logo-container img {
            width: 80px;
            height: auto;
        }

        .brand-name {
            font-size: 1.2rem;
            font-weight: 700;
            letter-spacing: 2px;
            text-transform: uppercase;
            margin-top: 10px;
            color: #ffffff;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin: 20px auto 40px auto;
            max-width: 600px;
            background-color: var(--nav-bg);
            padding: 8px;
            border-radius: 8px;
            border: 1px solid var(--nav-border);
        }

        nav a {
            color: var(--text-muted);
            text-decoration: none;
            padding: 8px 16px;
            font-size: 0.9rem;
            font-weight: 500;
            border-radius: 6px;
            transition: all 0.2s ease;
        }

        nav a:hover, nav a.active {
            color: #ffffff;
            background-color: var(--nav-border);
        }

        main {
            max-width: 800px;
            margin: 0 auto 60px auto;
            padding: 0 20px;
        }

        h1 {
            font-size: 2.5rem;
            font-weight: 700;
            text-align: center;
            margin-bottom: 10px;
            color: #ffffff;
        }

        .subtitle {
            font-size: 1.1rem;
            color: var(--text-muted);
            text-align: center;
            margin-bottom: 40px;
        }

        .meta-table-container {
            background-color: var(--container-bg);
            border: 1px solid var(--nav-border);
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 40px;
        }

        .meta-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 12px;
            font-size: 0.95rem;
        }

        .meta-item {
            display: flex;
            justify-content: space-between;
            border-bottom: 1px solid #1f3229;
            padding-bottom: 8px;
        }

        .meta-item:last-child {
            border-bottom: none;
            padding-bottom: 0;
        }

        .meta-label {
            color: var(--text-muted);
        }

        .meta-value {
            font-weight: 600;
            color: #ffffff;
        }

        .meta-links {
            grid-column: span 2;
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 10px;
            justify-content: center;
        }

        .meta-links a {
            color: var(--accent-green);
            text-decoration: none;
            font-size: 0.9rem;
        }

        .meta-links a:hover {
            text-decoration: underline;
        }

        section {
            margin-bottom: 35px;
        }

        h2 {
            font-size: 1.4rem;
            color: #ffffff;
            margin-bottom: 15px;
            border-bottom: 1px solid var(--nav-border);
            padding-bottom: 5px;
        }

        p {
            margin-bottom: 15px;
            color: var(--text-color);
            font-size: 1rem;
        }

        ul {
            margin-bottom: 15px;
            padding-left: 20px;
        }

        li {
            margin-bottom: 8px;
            color: var(--text-color);
        }

        .hash-box {
            background-color: #070d0a;
            border: 1px solid var(--nav-border);
            padding: 12px;
            border-radius: 6px;
            font-family: monospace;
            font-size: 0.9rem;
            word-break: break-all;
            margin-top: 5px;
            margin-bottom: 15px;
            color: var(--accent-green);
        }

        footer {
            text-align: center;
            padding: 40px 20px;
            border-top: 1px solid var(--nav-border);
            color: var(--text-muted);
            font-size: 0.85rem;
        }

        @media (max-width: 600px) {
            .meta-grid {
                grid-template-columns: 1fr;
            }
            .meta-links {
                grid-column: span 1;
            }
            h1 {
                font-size: 2rem;
            }
            nav {
                flex-wrap: wrap;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="logo-container">
            <img src="logo.png" alt="Parallax Logo">
        </div>
        <div class="brand-name">Parallax PLX</div>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="support.html">Support</a>
        <a href="whitepaper.html" class="active">Whitepaper</a>
        <a href="sponsorship.html">Sponsorship</a>
        <a href="faq.html">FAQ</a>
    </nav>

    <main>
        <h1>Parallax (PLX) Whitepaper</h1>
        <div class="subtitle">Independent Layer 1 Scrypt Proof-of-Work Cryptocurrency</div>

        <div class="meta-table-container">
            <div class="meta-grid">
                <div class="meta-item"><span class="meta-label">Project</span><span class="meta-value">Parallax</span></div>
                <div class="meta-item"><span class="meta-label">Ticker</span><span class="meta-value">PLX</span></div>
                <div class="meta-item"><span class="meta-label">Blockchain</span><span class="meta-value">Parallax Mainnet</span></div>
                <div class="meta-item"><span class="meta-label">Asset Type</span><span class="meta-value">Native Layer 1</span></div>
                <div class="meta-item"><span class="meta-label">Consensus</span><span class="meta-value">Proof of Work</span></div>
                <div class="meta-item"><span class="meta-label">Algorithm</span><span class="meta-value">Scrypt</span></div>
                <div class="meta-item"><span class="meta-label">Block Reward</span><span class="meta-value">50 PLX</span></div>
                <div class="meta-item"><span class="meta-label">Official Client</span><span class="meta-value">Parallax Core</span></div>
                <div class="meta-links">
                    <a href="https://paraplx.com">Official Website</a>
                    <a href="https://explorer.paraplx.com">Block Explorer</a>
                    <a href="https://github.com/ParallaxCoreDevelopers/parallax_wallet_miner">Source Code</a>
                </div>
            </div>
        </div>

        <section>
            <h2>1. Introduction</h2>
            <p>Parallax (PLX) is an independent open-source Layer 1 cryptocurrency operating on its own blockchain.</p>
            <p>PLX is the native currency of the Parallax network. It is not an ERC-20, BEP-20 or other token issued on top of another blockchain and therefore does not require a token contract address for native transfers.</p>
            <p>The Parallax blockchain begins from its own Genesis Block 0 and maintains its own independent block history, transaction history, peer-to-peer network and consensus rules.</p>
            <p>Parallax uses Scrypt Proof-of-Work consensus. Miners contribute computational hashing power to create blocks, confirm transactions, extend the blockchain and participate in securing the network.</p>
            <p>The current block subsidy is 50 PLX per block.</p>
            <p>The official desktop application, Parallax Core, combines a full blockchain node, native PLX wallet, integrated Scrypt mining controls, wallet encryption, backup tools, message signing and verification, peer information, network traffic information, blockchain information and RPC tools in one Windows application.</p>
            <p>Parallax Core should therefore not be viewed merely as a Layer 1 wallet. Parallax is the Layer 1 blockchain. Parallax Core is the official full-node software used to participate directly in that Layer 1 network.</p>
        </section>

        <section>
            <h2>2. Project Objectives</h2>
            <p>Parallax was created around several core objectives:</p>
            <ul>
                <li>Operate an independent public blockchain.</li>
                <li>Maintain its own native PLX cryptocurrency.</li>
                <li>Use Scrypt Proof-of-Work consensus.</li>
                <li>Allow users to independently operate full blockchain nodes.</li>
                <li>Provide a native wallet without requiring custodial services.</li>
                <li>Integrate optional mining directly into the official desktop application.</li>
                <li>Provide wallet encryption and security tools.</li>
                <li>Provide peer, network traffic and node information.</li>
