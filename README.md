<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SoulGlow Studio | Official Hub</title>
    <style>
        :root {
            --bg-gradient: linear-gradient(135deg, #0f0c20 0%, #15102a 50%, #1d1233 100%);
            --card-bg: rgba(255, 255, 255, 0.04);
            --card-border: rgba(255, 255, 255, 0.08);
            --text-main: #ffffff;
            --text-muted: #b3a9cf;
            --glow-color: #bc78ec;
            --accent-gradient: linear-gradient(45deg, #a855f7, #ec4899);
        }

        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: var(--bg-gradient);
            background-attachment: fixed;
            color: var(--text-main);
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            max-width: 580px;
            width: 100%;
            padding: 3rem 1.5rem;
            box-sizing: border-box;
            text-align: center;
        }

        /* Profile Section */
        .profile-img {
            width: 96px;
            height: 96px;
            border-radius: 50%;
            background: var(--accent-gradient);
            margin: 0 auto 1.2rem auto;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
            box-shadow: 0 0 20px rgba(188, 120, 236, 0.4);
        }

        h1 {
            font-size: 1.8rem;
            margin: 0 0 0.4rem 0;
            letter-spacing: -0.5px;
            font-weight: 700;
        }

        .bio {
            color: var(--text-muted);
            font-size: 1rem;
            margin-bottom: 2.5rem;
            line-height: 1.5;
        }

        /* Dropdown Links Section */
        .links-wrapper {
            display: flex;
            flex-direction: column;
            gap: 1.2rem;
        }

        .link-card {
            background: var(--card-bg);
            border: 1px solid var(--card-border);
            border-radius: 14px;
            padding: 1.2rem;
            text-decoration: none;
            color: var(--text-main);
            font-weight: 600;
            font-size: 1.1rem;
            display: flex;
            align-items: center;
            justify-content: space-between;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
        }

        .link-card:hover {
            background: rgba(255, 255, 255, 0.08);
            border-color: var(--glow-color);
            transform: translateY(-2px);
            box-shadow: 0 8px 20px rgba(188, 120, 236, 0.15);
        }

        .link-info {
            display: flex;
            align-items: center;
            gap: 1rem;
            text-align: left;
        }

        .icon {
            font-size: 1.4rem;
        }

        .link-text span {
            display: block;
            font-size: 0.85rem;
            color: var(--text-muted);
            font-weight: 400;
            margin-top: 0.2rem;
        }

        .arrow {
            color: var(--text-muted);
            transition: transform 0.2s;
        }

        .link-card:hover .arrow {
            transform: translateX(4px);
            color: var(--text-main);
        }

        /* Footer Socials */
        footer {
            margin-top: auto;
            padding: 2rem 0;
            font-size: 0.9rem;
            color: var(--text-muted);
        }

        .instagram-btn {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            color: var(--text-main);
            text-decoration: none;
            font-weight: 500;
            background: rgba(255, 255, 255, 0.05);
            padding: 0.6rem 1.2rem;
            border-radius: 30px;
            border: 1px solid var(--card-border);
            transition: all 0.2s;
        }

        .instagram-btn:hover {
            background: var(--accent-gradient);
            border-color: transparent;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Brand Profile -->
        <div class="profile-img">✨</div>
        <h1>SoulGlow Studio</h1>
        <p class="bio">Premium digital products and assets to illuminate your creative projects.</p>

        <!-- Dropdown Links / Navigation -->
        <div class="links-wrapper">
            
            <!-- Link 1: Store Main -->
            <a href="https://payhip.com/SoulGlowStudiio" target="_blank" class="link-card">
                <div class="link-info">
                    <span class="icon">🛍️</span>
                    <div class="link-text">
                        Browse Full Digital Store
                        <span>Download instant e-books, assets, and guides</span>
                    </div>
                </div>
                <span class="arrow">➔</span>
            </a>

            <!-- Link 2: Featured/Latest Product -->
            <a href="https://payhip.com/SoulGlowStudiio" target="_blank" class="link-card">
                <div class="link-info">
                    <span class="icon">🔥</span>
                    <div class="link-text">
                        Shop Best Sellers
                        <span>Check out what everyone is loving right now</span>
                    </div>
                </div>
                <span class="arrow">➔</span>
            </a>

            <!-- Link 3: Custom Contact / Support -->
            <a href="https://www.instagram.com/soulglowstudiio/" target="_blank" class="link-card">
                <div class="link-info">
                    <span class="icon">💬</span>
                    <div class="link-text">
                        Send a DM for Inquiries
                        <span>Got questions? Let's connect on Instagram</span>
                    </div>
                </div>
                <span class="arrow">➔</span>
            </a>

        </div>
    </div>

    <footer>
        <a href="https://www.instagram.com/soulglowstudiio/" target="_blank" class="instagram-btn">
            📸 Follow @soulglowstudiio
        </a>
        <p style="margin-top: 1.5rem;">© 2026 SoulGlow Studio. All rights reserved.</p>
    </footer>

</body>
</html>
