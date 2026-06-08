# Valor Glory Screensaver

A cinematic military-inspired screensaver featuring animated flags, tactical radar displays, and glowing medal showcases — abstract ceremonial visuals honoring discipline and service, with no real national symbols or political content.

**Developed by [Cybesis Studios](https://cybesis.com) — an indie solo developer**

---

## ✨ Features

### Three Cinematic Display Modes

#### Honor Flag
- **Spring Cloth Simulation**: 24×16 point-mass mesh with wind turbulence — the flag billows and ripples with realistic physics
- **5-Stripe Design**: Abstract flag using your chosen color theme; no real national flags
- **Edge Sparkle Particles**: Sparks trail off the free edge of the flag as it snaps in the wind
- **Decorative Pole**: Radial finial, banded shaft, and a soft glow matching the theme
- **Emblem Overlay**: Abstract shield with central star and corner star accents

#### Tactical Glory
- **Full Radar HUD**: Rotating sweep with trailing arc, 3 range rings, and a pulsing center beacon
- **Compass Rose**: Degree marks at every 10° (major at 30°, cardinal at 90°) with N/E/S/W labels
- **Corner Data Panels**: Real-time contact count, position readout, and status lines in each screen corner
- **EKG Waveform**: Scrolling cardiac-style waveform along the bottom third of the display
- **Lock Indicator**: A four-corner bracket flashes on the nearest blip when the sweep passes — with a pulsing `LOCK` label in the corner
- **Scrolling Status Ticker**: Monospace status messages scroll across the screen edge

#### Medal Showcase
- **Three Medals**: Silver, Gold, and Bronze — each with its own color, ribbon, and spin rate
- **Bob Animation**: All three medals float up and down out of phase with each other for a living, breathing feel
- **Spotlight Cones**: Angled light beams descend from the top toward each medal
- **Rising Particles**: Golden dust motes drift upward from the pedestals
- **Trapezoid Pedestals**: Each medal rests on a beveled, gradient-lit plinth
- **Specular Highlights**: Radial gloss effect on each medal face

### Visual Customization
- **7 Color Themes** (2 free, 5 Pro): Steel Honor, Midnight Regiment, Bronze Victory, Crimson Standard, Desert Dawn, Naval Command, Air Force Blue
- **Custom Motto** (Pro): Your own text as a cinematic overlay on any mode
- **Atmospheric Fog** (Pro): Depth fog gradients at the screen edges for added drama
- **Animation Speed**: Global speed multiplier from 0.25× to 2.0×
- **Intensity**: Controls glow brightness and particle density

### Performance & Accessibility
- **Pure Canvas 2D**: No WebGL dependency — works on any modern Windows PC including Intel integrated graphics
- **Reduce Motion** (Pro): Disables all physics and particle systems for accessibility
- **Burn-In Protection**: Slow canvas drift guards OLED and AMOLED displays (always free)
- **Multi-Monitor** (Pro): Synchronized display across all connected screens
- **Smooth 60 FPS**: Optimized render loop via Microsoft Edge WebView2

---

## 🎯 Free vs Pro

The free tier opens with Honor Flag — a fully animated cloth-simulation scene with two beautiful themes. **Pro** unlocks everything.

| | Free | Pro |
|---|:---:|:---:|
| Honor Flag mode (cloth simulation + particles) | ✅ | ✅ |
| Steel Honor & Midnight Regiment themes | ✅ | ✅ |
| Burn-in protection (OLED drift) | ✅ | ✅ |
| Edge sparkle particles | ✅ | ✅ |
| Digital clock overlay | ✅ | ✅ |
| Tactical Glory mode (radar + HUD) | ❌ | ✅ |
| Medal Showcase mode (medals + spotlights) | ❌ | ✅ |
| Auto-Rotate mode | ❌ | ✅ |
| All 7 color themes | ❌ | ✅ |
| Custom motto overlay | ❌ | ✅ |
| Atmospheric fog | ❌ | ✅ |
| Tactical grid / blip density control | ❌ | ✅ |
| Medal particles / spotlight toggle | ❌ | ✅ |
| Reduce motion (accessibility) | ❌ | ✅ |
| Multi-monitor support | ❌ | ✅ |
| Priority support | ❌ | ✅ |

**Pro upgrade: $4.99 one-time purchase** — lifetime access, no subscription.

---

## 📥 Installation

### From the Microsoft Store
Get the latest version with automatic updates from the Microsoft Store *(coming soon)*.

After installing:
1. Open **Valor Glory** from the Start Menu — it sets itself up as your active screensaver and opens settings.
2. Choose your mode and theme, then click **Save Settings**.
3. Use the **Preview** button to see it full-screen, or let it kick in when your PC goes idle.

---

## ⚙️ Configuration

Open the **Valor Glory** settings from the Start Menu or from Windows Screen Saver Settings.

### Scene Tab
The left panel shows mode thumbnails — click to switch. The right panel shows mode-specific options.

| Mode | Access | What it Shows |
|---|---|---|
| Honor Flag | Free | Cloth-simulated waving flag with emblem |
| Tactical Glory | Pro | Rotating radar HUD with blips and data panels |
| Medal Showcase | Pro | Three medals with spotlights and rising particles |
| Auto-Rotate | Pro | Cycles through all three modes every 45 seconds |

### Display Tab
- **Animation Speed**: 0.25× to 2.0× (applies to all modes)
- **Intensity**: 0–100% (controls glow and particle density)
- **Digital Clock**: Toggle on/off, choose position and color
- **Atmospheric Fog** (Pro): 0–100% depth haze at screen edges
- **Burn-In Protection**: Enable canvas drift to protect OLED panels

### Color Themes

| Theme | Primary | Accent | For |
|---|---|---|---|
| Steel Honor | Steel Blue | Silver | Clean, modern |
| Midnight Regiment | Deep Navy | Gold | Classic military |
| Bronze Victory *(Pro)* | Burnished Bronze | Copper | Warm, historic |
| Crimson Standard *(Pro)* | Deep Crimson | Gold | Bold, dramatic |
| Desert Dawn *(Pro)* | Sandy Tan | Amber | Warm desert tones |
| Naval Command *(Pro)* | Ocean Blue | Cyan | Naval aesthetic |
| Air Force Blue *(Pro)* | Royal Blue | Ice Blue | Sky and flight |

---

## 🔧 Troubleshooting

**Screensaver doesn't start automatically**
- Set an idle wait time in Windows **Screen Saver Settings** (search "screen saver" in the Start menu).
- Open the Valor Glory app from the Start Menu once to register it.

**Settings don't save**
- Settings are stored in `%LOCALAPPDATA%\ValorGlorySaver\config.json`.
- If they won't persist, your antivirus may be blocking the app — allow it and re-launch.

**Performance issues**
- Lower the Animation Speed or Intensity in the Display tab.
- If using many monitors, Tactical Glory and Medal Showcase are the most GPU-friendly.

**Black screen instead of animation**
- Install the [Microsoft Edge WebView2 Runtime](https://go.microsoft.com/fwlink/p/?LinkId=2124703) (usually pre-installed on Windows 10/11).

---

## 📋 Content Safety

Valor Glory is abstract and ceremonial — not political.

- Honor Flag shows a **generic, fictional flag design** — no real national flags appear by default
- No Nazi, extremist, terrorist, or hate symbols — hard-coded exclusions apply
- No real political slogans; the custom motto field has no default text
- Medal designs are entirely fictional — no imitation of real official decorations
- Tactical Glory is clearly science-fiction / abstract HUD, not a real military system

---

## 💬 Support & Contact

- **Issues & Bugs**: Use **Report a Bug** in the About tab, or open a [GitHub Issue](https://github.com/cybesis/screensavers/issues) with label `valor-glory`
- **Email**: support@cybesis.com
- **Website**: [cybesis.com](https://cybesis.com)

---

## 🌟 Other Screensavers

- [**Digital Rain**](digitalrain.md) — Available now on the Microsoft Store
- [**Aurora**](aurora.md) — Coming soon
- [**Fireside Cats**](fireside-cats.md) — Coming soon
- [**Vortext**](vortext.md) — Coming soon
- [**Video Link**](video-link.md) — Coming soon
- [**Magic Mirror**](magic-mirror.md) — Coming soon
- [**Crypto Pulse**](crypto-pulse.md) — Coming soon

---

## ☕ Support the Developer

Valor Glory is built with passion by an indie solo developer. If you enjoy it, consider buying me a coffee — it directly funds new scenes and features.

**[☕ Buy Me a Coffee](https://buymeacoffee.com/miztizm)**

---

## Build Info

| | |
|---|---|
| Version | 1.0.0 (pre-release) |
| Platform | Windows 10 / 11 (x64) |
| Status | Under active development |

---

*© 2026 Cybesis Studios. All rights reserved.*
