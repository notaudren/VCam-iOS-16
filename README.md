<div align="center">

# VCam — Fake Camera for iOS 16

**System‑wide virtual camera & microphone for jailbroken iOS 16.**
Replace what every app sees and hears — with a photo, or a live OBS stream.

`Fake Cam` · `VCam iOS` · `Virtual Camera` · `iPhone 8` · `OBS` · `roothide`

</div>

---

## What it is

VCam swaps the **real camera and microphone** at the system level, so **every app** that
opens the camera (Snapchat, Instagram, TikTok, FaceTime, the stock Camera app, …) receives
your chosen content instead of the physical sensor — with **no in‑app modification**, so apps
see a normal camera feed.

Perfect when your camera is broken, for content creation, or for streaming an **OBS** scene
straight into any app as if it were your live camera.

## Features

- 🖼️ **Image mode** — pick a photo from your library; it becomes the camera feed everywhere.
- 🎥 **Video via OBS** — stream an OBS scene to your iPhone over the network and it plays as
  your live camera, **with audio**.
- 🎙️ **Camera *and* microphone** — the OBS audio replaces the mic too, perfectly **lip‑synced**.
- 🫥 **Seamless** — the replacement happens below the apps, so the feed looks like a real camera.
- 🔁 **Live controls** — rotate (90°) and mirror on the fly from a single Home‑button menu.
- ⚙️ **Clean Settings panel** — license activation, status and expiry, right in Settings.
- 🪶 **Lightweight & stable** — hardware‑accelerated, low latency (wired connection recommended).

## Requirements

- **iOS 16** (built and tested on **iPhone 8**).
- A **rootless / roothide** jailbreak.
- Dependencies (installed automatically): **ElleKit**, **PreferenceLoader**.

## Installation

1. Download the latest `.deb` from the [**Releases**](../../releases) page
   (or add it through Sileo).
2. Install and **respring**.
3. Open **Settings → VCam** and activate your license key (see below).

## Usage

- **Long‑press the Home button** to open the VCam menu:
  - **🖼️ Image** — choose a photo from your library.
  - **🎥 Video (OBS)** — shows the address to point OBS at, then starts the live feed.
  - **🔄 Rotate** · **🪞 Mirror** · **❌ Disable**.
- Open any camera app — it now shows your VCam feed.

### OBS (live video + audio)

1. In the VCam menu, tap **Video (OBS)** and start the live feed.
2. In **OBS → Settings → Output → Custom Output (FFmpeg)**, point the output at the address
   shown by VCam (container `mpegts`, video `libx264`, audio `aac`).
3. Start the OBS output — your scene appears as the iPhone camera, with sound.

> 💡 For the smoothest result, connect the iPhone to the computer **by cable**.

## License

VCam is license‑gated. A key is **permanently linked to one iPhone**.

👉 **To get a license key, contact me on Telegram: [@n0taudren](https://t.me/n0taudren)**

## Disclaimer

Provided as‑is, for personal and content‑creation use. You are responsible for how you use it
and for complying with the terms of the apps and services you use it with.

---

<div align="center">
<sub>VCam · Fake Cam for iOS 16 · by <b>notaudren</b></sub>
</div>
