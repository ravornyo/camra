# Camra

Camra is a desktop viewer and recorder for ONVIF-compatible network cameras. It provides a live multi-camera grid for monitoring, plus a separate perspective for browsing and playing back recorded video.

This repository distributes the **built application** — there's no source code here.

## Features

- **Live camera grid** — view multiple RTSP/ONVIF camera feeds at once, with a configurable grid size and per-camera tiles you can maximize, minimize, pause, or mute independently.
- **Adding cameras** three ways:
  - ONVIF discovery (WS-Discovery) on the local network
  - Manual entry for a known ONVIF device address
  - Plain RTSP URL, with no ONVIF device behind it
- **Recording & scheduling** — per-camera recording schedules, configurable segment length, storage cap, and save location, with automatic ring-buffer cleanup.
- **Recordings perspective** — a zoomable timeline for browsing and playing back recorded segments, independent of the live grid.
- **PTZ controls** — pan/tilt/zoom for cameras that support it, with a settable home position.
- **Media profile switching** — select between a camera's available stream qualities/resolutions when it exposes more than one.
- **Snapshots** — capture the currently displayed frame to PNG.
- **Global preferences** — network caching (latency vs. reliability trade-off), default RTSP transport for new cameras, default snapshot folder.

## Download

See the [Releases](../../releases) page for the latest build.

Downloads are available for:

- Windows (x86_64)

No separate Java installation is required — each build bundles a matching Java runtime.

## Installing

1. Download the archive for your platform from the latest release.
2. Extract it anywhere.
3. Run the `camra` executable (`camra.exe` on Windows).

## Updates

Camra checks for updates itself, from within the app: **Help → Check for Updates**. You don't need to manually download and reinstall for future versions.

## Support

For bugs or feature requests, please open an issue in this repository.
