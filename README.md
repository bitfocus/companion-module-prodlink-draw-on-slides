# ProdLink: Draw on Slides — Companion Module

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A [Bitfocus Companion](https://bitfocus.io/companion) module for controlling the **Draw on Slides** iPad app over the local network.

## Features

- **Drawing Presets** — Switch between 3 presets with color/size/opacity feedback
- **Slide Navigation** — Next/previous slide with ProPresenter action cue support
- **Canvas Controls** — Clear, undo, zoom toggle/reset
- **Tool Selection** — Pen, marker, pencil, crayon, eraser
- **Color/Size/Opacity Presets** — Quick-select with active-state feedback
- **Settings Toggles** — Toggle app settings with ON/OFF visual feedback
- **Bonjour Auto-Discovery** — Automatically find iPads on the network
- **Auto-Reconnect** — Port scanning fallback if the iPad restarts on a different port

## Requirements

- [Bitfocus Companion](https://bitfocus.io/companion) v4.0 or later
- [Draw on Slides](https://apps.apple.com/app/draw-on-slides/id6738948517) iPad app with HTTP API enabled

## Installation

### From Companion
The module will be available in Companion's module list once approved by Bitfocus.

### Development / Manual Install
1. Clone this repo into your Companion developer modules directory
2. `yarn install`
3. `yarn build`
4. Restart Companion and add a "ProdLink: Draw on Slides" connection

## Setup

1. In the iPad app, go to **Settings → HTTP API** and enable the server
2. In Companion, add a **ProdLink: Draw on Slides** connection
3. Select the iPad from the **Auto-Discover** dropdown, or enter the IP/port manually
4. Click **Save** — buttons will start showing real-time state

## Development

```bash
yarn install
yarn dev       # Watch mode — recompiles on changes
```

## License

[MIT](LICENSE)
