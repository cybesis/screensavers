# Crypto Pulse Screensaver

> **Status: Available now on the [Microsoft Store](https://apps.microsoft.com/detail/9N64L6PVMXJK)**

A cinematic, display-only crypto price dashboard that turns your idle screen into a live market monitor. Rotates through your favorite coins showing real-time price, 24h change, market cap, volume, and sparkline charts — all animated with futuristic backgrounds and no API key required.

**Developed by [Cybesis Studios](https://cybesis.com) — an indie solo developer**

---

## ✨ Features

### Five Cinematic Display Modes

#### Dashboard
The flagship mode — a full-screen HUD with a large coin logo, current price, 24h change percentage with directional color, market cap, volume, and a smooth sparkline chart. Animated particle backgrounds pulse to match price movement direction (green rising, red falling).

#### Minimal
Distraction-free: just the ticker symbol, price, and a single color-coded change indicator. Maximally readable on any screen. Ideal for secondary monitors or low-power setups.

#### Terminal
Retro trading terminal aesthetic — monospace font, scrolling ticker tape across the bottom, a price table with multiple coins visible simultaneously, and a blinking cursor. All the nostalgia, none of the commissions.

#### Orbit
Coins orbit around a central anchor in a 3D-projected ring. Each coin shows its logo and price label. Orbit speed adjusts with the configured animation speed. Pro users can customize which coins appear in the ring.

#### Bubbles
Market-cap-weighted bubbles float and drift across the screen. Larger bubbles = bigger market cap. Green bubbles for positive 24h change, red for negative. A mesmerizing way to scan the whole market at a glance.

### Live Market Data
- **Powered by CoinGecko**: Free public API — no API key, no account, no costs
- **Auto-Refresh**: Configurable refresh interval (default 60 seconds, Pro: 15–3600s)
- **Offline Fallback**: Cached prices shown when internet is unavailable, with a subtle "cached" indicator
- **Multi-Currency**: USD, EUR, GBP, JPY, and more (Pro)

### Customization
- **Custom Coin List** (Pro): Set exactly which coins to track and in what order
- **Rotation Speed**: How long each coin is displayed before rotating (default 10s, Pro: 5–120s)
- **5 Visual Themes**: Each with a distinct cinematic palette

### Visual Themes

| Theme | Palette | Vibe |
|---|---|---|
| Cyber Blue | Cyan + electric blue | Futuristic trading floor |
| Terminal Green | Matrix green + black | Hacker terminal |
| Gold Bull | Gold + amber | Premium bull market |
| Red Alert | Crimson + dark red | Bear market war room |
| Minimal Glass | White + frosted grey | Clean and professional |

### Performance & Reliability
- **Lightweight**: Canvas 2D rendering — no WebGL required
- **Background Refresh**: Data updates happen off-screen; no animation stutters during fetch
- **Graceful Degradation**: Works fully offline with cached data; live badge shown when connected
- **Smooth 60 FPS**: Optimized via Microsoft Edge WebView2

---

## 🎯 Free vs Pro

The free tier shows the Dashboard with Bitcoin, Ethereum, Solana, and BNB on the Cyber Blue theme. **Pro** unlocks all modes, themes, and full coin customization.

| | Free | Pro |
|---|:---:|:---:|
| Dashboard mode | ✅ | ✅ |
| Default coin set (BTC, ETH, SOL, BNB, XRP, DOGE) | ✅ | ✅ |
| Cyber Blue theme | ✅ | ✅ |
| Offline cached prices | ✅ | ✅ |
| Digital clock overlay | ✅ | ✅ |
| Minimal mode | ❌ | ✅ |
| Terminal mode | ❌ | ✅ |
| Orbit mode | ❌ | ✅ |
| Bubbles mode | ❌ | ✅ |
| All 5 visual themes | ❌ | ✅ |
| Custom coin list (any CoinGecko coin) | ❌ | ✅ |
| Custom fiat currency (EUR, GBP, JPY…) | ❌ | ✅ |
| Refresh interval control (15s–3600s) | ❌ | ✅ |
| Coin rotation interval control | ❌ | ✅ |
| Multi-monitor support | ❌ | ✅ |
| Priority support | ❌ | ✅ |

**Pro upgrade**: one-time in-app purchase, $2.99 — made inside the screensaver's Settings window through the Microsoft Store. Lifetime access, no subscription.

---

## 📥 Installation

### From the Microsoft Store
Get the latest version with automatic updates from the [Microsoft Store](https://apps.microsoft.com/detail/9N64L6PVMXJK).

After installing:
1. Open **Crypto Pulse** from the Start Menu — it registers itself as your active screensaver and opens settings.
2. Choose your mode, theme, and coins, then click **Save Settings**.
3. Set your idle wait time in Windows **Screen Saver Settings**, or click **Preview** to test immediately.

---

## ⚙️ Configuration

Open the **Crypto Pulse** settings from the Start Menu or Windows Screen Saver Settings.

### Appearance Tab
- **Display Mode**: Dashboard, Minimal, Terminal, Orbit, or Bubbles
- **Visual Theme**: Cyber Blue, Terminal Green, Gold Bull, Red Alert, or Minimal Glass
- **Coin Rotation Interval**: How many seconds each coin displays before rotating (Pro: 5–120s)

### Data Tab
- **Coin List**: The coins to track. Pro users can enter any CoinGecko coin ID (e.g. `bitcoin`, `ethereum`, `solana`). Free: default 6 coins.
- **Currency**: Display prices in USD, EUR, GBP, JPY, CAD, AUD (Pro)
- **Refresh Interval**: How often to fetch new prices from CoinGecko (Pro: 15–3600s)

### Display Tab
- **Digital Clock**: Toggle, position, and color
- **Animation Speed**: 0.5×–2.0× controls orbit speed and bubble drift
- **Burn-In Protection**: Slow canvas drift for OLED panels (always free)

---

## 🔧 Troubleshooting

**Prices not updating / showing "cached"**
- Check your internet connection — Crypto Pulse needs access to `api.coingecko.com`
- Your firewall or corporate proxy may be blocking outbound HTTPS — allow the app
- CoinGecko's free API has rate limits; Crypto Pulse staggers requests and will retry automatically

**Unknown coin / price missing**
- Verify the coin ID at [coingecko.com](https://www.coingecko.com) — search your coin, and the ID is in the URL (`coingecko.com/en/coins/**bitcoin**`)
- Coins with very low liquidity may not appear in CoinGecko's free-tier API responses

**Screensaver doesn't start automatically**
- Set an idle wait time in Windows **Screen Saver Settings** (search "screen saver" in Start menu)
- Open the Crypto Pulse app from the Start Menu once to register it

**Black screen instead of animation**
- Install the [Microsoft Edge WebView2 Runtime](https://go.microsoft.com/fwlink/p/?LinkId=2124703) (usually pre-installed on Windows 10/11)

**Settings don't save**
- Settings are stored in `%LOCALAPPDATA%\CryptoPulseSaver\config.json`
- If they won't persist, your antivirus may be blocking the app — allow it and re-launch

---

## ⚠️ Disclaimer

Crypto Pulse is a **display-only screensaver** — it shows market data for informational and entertainment purposes only. It does not provide investment advice, execute trades, or access any wallets or exchange accounts. Price data is sourced from CoinGecko and is subject to their terms of service. Always verify prices on your exchange before making any financial decisions.

---

## 💬 Support & Contact

- **Issues & Bugs**: Use **Report a Bug** in the About tab, or open a [GitHub Issue](https://github.com/cybesis/screensavers/issues) with label `crypto-pulse`
- **Email**: support@cybesis.com
- **Website**: [cybesis.com](https://cybesis.com)

---

## 🌟 Other Screensavers

- [**Digital Rain**](digitalrain.md) — Available now on the Microsoft Store
- [**Aurora**](aurora.md) — In Microsoft Store certification, launching very soon
- [**Fireside Cats**](fireside-cats.md) — Available now on the Microsoft Store
- [**Vortext**](vortext.md) — Available now on the Microsoft Store
- [**Video Link**](video-link.md) — Available now on the Microsoft Store
- [**Magic Mirror**](magic-mirror.md) — Available now on the Microsoft Store
- [**Living Flags**](living-flags.md) — Available now on the Microsoft Store
- [**Outpost Tower**](outpost.md) — Available now on the Microsoft Store

---

## ☕ Support the Developer

Crypto Pulse is built with passion by an indie solo developer. If you enjoy it, consider buying me a coffee — it directly funds new modes and features.

**[☕ Buy Me a Coffee](https://buymeacoffee.com/miztizm)**

---

## Build Info

| | |
|---|---|
| Platform | Windows 10 / 11 (x64) |
| Updates | Automatic via Microsoft Store |
| Status | Available now on the Microsoft Store |
| Requires | Internet connection (for live prices) |

---

*© 2026 Cybesis Studios. All rights reserved.*
