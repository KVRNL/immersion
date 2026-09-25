<div align="center">

<img src=".github/banner.png" alt="Immersion — Audio-reactive OBS overlays for streamers" width="100%">

# Immersion

### Audio-reactive OBS overlays for streamers

<a href="https://github.com/KVRNL/immersion/releases/latest"><img alt="Latest version" src="https://img.shields.io/github/v/release/KVRNL/immersion?display_name=tag&label=version&color=F5A623&labelColor=0d0d0f&style=for-the-badge"></a>
<a href="https://github.com/KVRNL/immersion/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/KVRNL/immersion/total?label=downloads&color=F5A623&labelColor=0d0d0f&style=for-the-badge"></a>
<img alt="Platform" src="https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0d0d0f?style=for-the-badge&labelColor=0d0d0f">
<img alt="Price" src="https://img.shields.io/badge/price-FREE-F5A623?style=for-the-badge&labelColor=0d0d0f">
<a href="./LICENSE"><img alt="License" src="https://img.shields.io/badge/license-Proprietary%20Freeware-0d0d0f?style=for-the-badge&labelColor=0d0d0f"></a>

<br>

Live synced lyrics that pulse to your music, plus visualizers, timers, counters, tickers, and goal bars — a whole audio-reactive overlay toolkit that runs from your system tray and drops straight into OBS.

### **[⬇&nbsp; Download Immersion — free at kvrnl.io](https://kvrnl.io/products/immersion/)**

</div>

<br>

---

## What it does

Immersion is an audio-reactive overlay toolkit for streamers. Its centerpiece is live, time-synced lyrics that pulse and animate in time with whatever's playing, so your stream moves with the music. Around that sits a full kit of broadcast widgets: spectrum and waveform visualizers, countdown and stopwatch timers, counters, scrolling tickers, and goal bars.

Everything runs quietly from the Windows system tray and adds into OBS as a browser source in seconds — style it, position it, and go live. Free to use; claim your license key and download it straight from this page.

## Features

- **Live synced lyrics that pulse to the music**
- **Spectrum & waveform audio visualizers**
- **Stream timers, counters, tickers & goal bars**
- **Runs in the system tray, drops into OBS**

## Download &amp; install

Immersion is **completely free**. Downloads run through a free KVRNL account so every
install gets its own license key.

1. Go to **[kvrnl.io/products/immersion/](https://kvrnl.io/products/immersion/)**
2. Create a free account — email verification, nothing else
3. Claim your license key — instant, no waiting
4. Download and install

> [!NOTE]
> Immersion isn't code-signed yet, so Windows SmartScreen may warn you on first run.
> Click **More info → Run anyway**. Code signing is on the roadmap.

## Your license key

- **Free, one per product**, issued from your KVRNL account.
- **A key activates on one machine.** The first device to activate it claims it.
- **Switching computers?** Hit **Release device** on your
  [account page](https://kvrnl.io/account/) and the key is free to use again.
- Keys are checked over HTTPS at launch. See [Privacy](#privacy).

## Requirements

- **Windows 10 or 11** (64-bit)
- A free [KVRNL account](https://kvrnl.io/signup/) for your license key

## Privacy

Immersion sends KVRNL only what's needed to validate your license: **the key, the
product name, and a hardware ID**. No telemetry, no analytics, no tracking, and
none of your files. Full policy: **[kvrnl.io/privacy](https://kvrnl.io/privacy/)**

## What's new

**v1.0.6** — 2026-09-06
  - Visualizer overhaul: bars now cover the whole musical range evenly (the bass end used to be a block of identical bars and the top end sat flat), move smoothly instead of flickering, and the glow is far lighter on your PC so it stays at 60 fps in OBS. Wave style is now a smooth curve.
  - 'Pulse to the beat' actually pulses now: beat detection picks up kicks much more reliably, and the timer and counter bounce is bigger and easier to see.
  - The audio engine restarts itself when you switch output devices (speakers to headphones, a new USB device), so the visualizer no longer goes dead until you relaunch.
  - Now-playing strip in the control panel: long titles trim cleanly and the lyrics status sits in its own slot instead of crowding the title.
  - A beat light in the Audio meter blinks on every beat Immersion hears, so you can tell at a glance that the pulse is working.
  - Smoother control panel while dragging sliders.

**v1.0.5** — 2026-09-06
  - Updates now install and restart Immersion automatically, the same way the other KVRNL apps do. No more downloading the installer yourself.
  - If OBS has overlays open when an update finishes downloading, Immersion waits until they've been off air for a couple of minutes before restarting, so a live stream never loses its overlays. A green 'ready — restart now' button appears at the top if you'd rather not wait.
  - 'Check for updates' in Settings now downloads and installs directly, with a progress bar, instead of sending you to a browser download.

**v1.0.4** — 2026-09-06
  - Brand-new control panel, rebuilt from the ground up: cleaner layout, clearer flow, and nothing gets cut off at the window edge any more — every section scrolls on its own.
  - A status strip across the top shows what's playing, whether Immersion can hear your audio, and that the overlay server is up.
  - Each overlay page now leads with a true-to-size live preview and a one-click 'Add to OBS' strip: the URL, the exact width/height, and the FPS to use.
  - Live controls moved up front: big readouts for counters, timers and goals, one-click countdown presets, and a 'set to' box for counters.
  - The lyrics page shows the current line as it plays; the visualizer page shows live audio levels and BPM so you can tell at a glance that capture works.
  - Hotkeys are now recorded by pressing the keys, with a warning if a combo is already taken by another app.
  - Appearance settings use sliders, colour swatches, switches and segmented controls, plus a one-click reset to defaults.
  - Ticker messages are a proper list you can add to, edit, reorder and remove.
  - Adding an overlay is a picker with a description and OBS size for each type; removing one asks first.
  - A quick three-step guide appears on first use, and the activation window got the same fresh look.

**v1.0.3** — 2026-09-05
  - Fixed the app closing itself right after activating a license key on a fresh install.
  - Fixed countdown timers breaking the control panel.
  - Update downloads are now shown in Settings, with a Restart button once they're ready.
  - Goal bar now shows correctly on older OBS versions.
  - Ticker no longer jumps when you tweak its settings.
  - More accurate synced-lyrics matching.

**v1.0.2** — 2026-08-18
  - Downloads and automatic updates now come straight from KVRNL's own servers instead of a third-party host. Updates are quicker and more reliable, and nothing inside the app itself has changed.
  - If you installed this app before today, please download it once more from kvrnl.io. Older copies still look for updates at the old location and can't carry themselves across the move — this one time has to be done by hand.

Full history → **[kvrnl.io/changelog/immersion](https://kvrnl.io/changelog/immersion/)**

## Documentation

Setup guides and how-tos → **[kvrnl.io/docs/immersion](https://kvrnl.io/docs/immersion/)**

## Support

> [!IMPORTANT]
> **We don't use GitHub Issues.** Report bugs from inside the app — it's the
> fastest route to us and it attaches the details we need automatically.

- 🐛 **Found a bug?** Use **Report a Problem** inside Immersion
- 💬 **Chat with us** → **[Discord](https://discord.gg/Ub4SdAuhu)**
- ✉️ **Anything else** → **[kvrnl.io/contact](https://kvrnl.io/contact/)**
- ❓ **FAQ** → [kvrnl.io/faq](https://kvrnl.io/faq/)

## License

**Proprietary freeware — free to use, not open source.**

This repository hosts the installer releases, documentation, and license for
Immersion. **The application source code is not published.** See
**[LICENSE](./LICENSE)** for the full terms.

---

<div align="center">
<br>

**[kvrnl.io](https://kvrnl.io)** &nbsp;·&nbsp; **[All products](https://kvrnl.io/products/)** &nbsp;·&nbsp; **[Changelog](https://kvrnl.io/changelog/)** &nbsp;·&nbsp; **[Discord](https://discord.gg/Ub4SdAuhu)** &nbsp;·&nbsp; **[Contact](https://kvrnl.io/contact/)**

<sub>© 2026 <b>KVRNL</b> — an AI-powered software studio shipping free desktop tools.</sub>

</div>
