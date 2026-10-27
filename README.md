# Velum

A camera app made only for the **Samsung Galaxy S24 Ultra**. Free, no ads, no account, and no internet permission:
it cannot send anything anywhere.

This repo holds the downloads and bug reports. The app is in beta, and I'm looking for real users to tell me what
works and what doesn't.

## Download

Get the latest APK from **[Releases](../../releases/latest)**.

1. Download `velum-x.y.z.apk` on your S24 Ultra.
2. Open it. Android will ask you to allow installs from your browser or file manager. Allow it once.
3. Play Protect may say the app is unknown, because it isn't on the Play Store yet. Tap "Install anyway".

**Check the file is genuine (optional):** every release lists the file's SHA-256. Every Velum build is signed with the
same key, certificate SHA-256:

```
F1:AF:B1:EA:DD:D8:7A:5C:8F:6C:97:44:98:F5:0B:D6:1D:42:70:A7:34:90:FD:11:8E:C4:09:85:93:5D:93:A8
```

Updates install over the old version and keep your settings. A file signed with any other key is not from me.

## Permissions

Camera, microphone (video sound), vibration, and a background service to finish saving long videos. **No internet,
no location, no contacts.** You can confirm this in Settings > Apps > Velum > Permissions.

## What it does

- **Looks** shown live in the viewfinder and saved into photos *and* recorded video: Essentials, film, mono, cinema,
  your own `.cube` LUTs, a custom look editor, presets you can share as a QR code
- **Signature looks**, Velum's own grades inspired by how camera makers describe their colour:

  | In the app | Inspired by |
  |---|---|
  | Rangefinder | Leica's published look descriptions |
  | Optic | vivo's ZEISS colour modes |
  | Studio | OnePlus/OPPO Hasselblad colour and filters; Pano = panoramic film |
  | Cine | Sony's S-Cinetone and Creative Looks |

  Velum is not affiliated with or endorsed by these companies, and their in-camera processing is not available to
  other apps.
- Panoramic 65:24 frame, film recipes, cine aspect ratios
- Long exposure (silk water, light trails, light painting, star trails) and Astro stacking
- Pro photo and video with zebra, focus peaking, false colour and histogram
- Movie mode (background blur, tap to rack focus, subject tracking), Portrait at 3x/5x, Macro, Best shot, Clone,
  Motion photo, Dual video, 120/240 fps slow motion, Horizon lock, 4K HLG 10-bit, RAW+JPEG, Ultra HDR

## What it can't do

Samsung keeps some things for its own camera app, so no third-party app can do them:

- no 4K 60 fps, no 200 MP, no Log / HDR10+ video
- no Samsung multi-frame / AI photo processing

For quick auto photos, Samsung Camera is still the better choice. Velum is for when you want a look straight out of
the camera, more control, or less processing.

Known issues in Velum itself:

- Movie mode is capped at 30 fps; hair edges can look soft in Movie and Portrait 3x/5x
- Dual video: the front-camera picture is upside down when the phone is held sideways
- Best shot picks the sharpest frame only, it does not detect closed eyes

## Help test it

These haven't been tested yet. Any of them helps a lot:

1. Daylight, backlit and sunset scenes: same scene with Samsung Camera and Velum
2. People, different skin tones, hair
3. 3x and 5x zoom compared with Samsung
4. Astro mode on a real night sky (phone on a steady surface, 60 s)
5. Moving subjects in low light (kids, pets)
6. Battery and heat during long Movie or Motion photo use

## Report a problem or share a comparison

Open an **[issue](../../issues/new/choose)** and pick a form. Please include your One UI version
(Settings > About phone > Software information). Side-by-side photos with Samsung Camera are the most useful thing
you can send.

---

Velum is free to install and use. The app and its source code remain all rights reserved.
Bundled third-party material and its licences: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
