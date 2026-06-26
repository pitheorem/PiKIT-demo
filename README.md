# PiKit

> An artist-friendly toolkit for building **generative, interactive, and real-time visuals** inside TouchDesigner.

PiKit brings a modern layer-based workflow to TouchDesigner, making it easier to build complex visual systems without sacrificing the flexibility and power of node-based programming.

Whether you're creating interactive installations, live visuals, generative art, or educational projects, PiKit helps you work faster through reusable layers, intuitive parameter management, and procedural workflows.

> **Status:** 🚧 Demo Alpha Release

---

## Main Features

* 🎨 Layer-based workflow
* ⚡ Real-time graphics in TouchDesigner
* 🔗 Visual parameters interface
* 📺 Interactive Canvas panel
* 🛠 Support for custom developer layers
* 👋 Beginner-friendly while remaining powerful for advanced users

---

## Installation

### Requirements

* TouchDesigner
* Modern GPU recommended for real-time graphics

### Install

1. Download the latest `PiKit.tox`
2. Open your TouchDesigner project
3. Drag `PiKit.tox` into the Network Editor
4. Select the PiKit component
5. Open the Parameters panel (`P`)
6. Click **Open GUI**

---

## Quick Start

Create your first procedural animation:

1. Create a new project.
2. Add a **Circle** image layer.
3. Add an **Oscillator** signal layer.
4. Connect the Oscillator output to the Circle's **Radius** parameter.
5. Adjust the Oscillator settings and watch the circle animate in real time.

---

## Core Concepts

PiKit is built around a few simple concepts:

* **Workspace** — customizable production environment
* **Panels** — dockable UI for editing and viewing data
* **Layers** — build visual and signal hierarchies
* **Parameters** — control layer behavior
* **Attributes** — export data between layers
* **Connections** — create procedural relationships without scripting

---

## Custom Layers

PiKit is designed to be extensible.

Developers can create their own custom layers using standard TouchDesigner components, allowing studios and artists to integrate proprietary tools directly into the PiKit ecosystem.

---

## Roadmap

| Module     | Status     |
| ---------- | ---------- |
| PiKIT      | ✅ Demo     |
| PiLAYERS   | ✅ Demo     |
| PiCANVAS   | ✅ Demo     |
| PiHOC      | 🚧 TBA     |
| PiKEYBOARD | 🚧 TBA     |
| PiPRESETS  | 🚧 TBA     |
| PiEFFECTS  | 🚧 TBA     |
| PiNODES    | 🚧 TBA     |
| PiTIMELINE | 🚧 TBA     |

---

## Current Limitations

PiKit is currently in **Alpha**.

Known limitations include:

* No Undo system yet
* Occasional UI performance drops
* Heavy operations may be slower than intended
* Not yet recommended for production work

---

## Documentation

Full documentation is available here:
[PiKit Documentation](https://pitheorem.notion.site/Documentation-118c2176e10580d5b082e2852ff9574a)

---

## Community

Join the community to share artwork, report bugs, and discuss future features.

* Discord
* GitHub Issues

---

## Support

If PiKit helps your work, consider supporting its development:
https://pitheorem.xyz/pikit#ways_to_support

---

## Vision

PiKit aims to bridge the gap between artistic workflows and real-time technology by providing an intuitive, extensible, and modern creative toolkit for TouchDesigner.

Our goal is to empower artists, designers, educators, and developers to build advanced visual systems faster, with greater creative freedom and less technical friction.
