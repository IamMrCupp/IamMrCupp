# hey, i'm aaron. 👋

Senior Infrastructure Engineer by trade. Bass music by compulsion. Building things at the intersection of sound, light, and infrastructure since before it was cool.

Founder of **[Tech-Noid Systems](https://tech-noid.net)** — a bass music collective, internet radio station, sound system, and general chaos engine running since 2008. Based in West Sacramento, CA. Performing DJ (Autonomic · Halftime DnB · Grey Area) and VJ. NorCal DnB scene.

---

## what i'm actually building

### 🔊 sound & light

**[audiophore](https://github.com/audiophore/audiophore)** — a low-latency Rust bridge from Synesthesia to every light in the room. Hue Entertainment, Nanoleaf, WLED over sACN/DDP, Art-Net DMX, Ether Dream lasers, OSC. Tauri + Svelte native app, pluggable input adapters, mlua scripting. It started as "I want my lights to react to my music" and turned into an actual project. The [brand kit](https://github.com/audiophore/branding) is public too — logos, wordmark, and palette, all reproducibly generated from one `brand.toml`.

**[obs-radio-output](https://github.com/Tech-Noid-Systems/obs-radio-output)** — a native OBS Studio plugin that streams audio straight to Icecast and SHOUTcast. The usual answer is a second encoder app and a virtual audio cable; this is one less thing to babysit mid-set. Lives in the [Tech-Noid Systems](https://github.com/Tech-Noid-Systems) org alongside the radio infrastructure — Kubernetes, Flux GitOps, Icecast, the works.

### 🔬 the bench

Microsoldering and board-level repair — microscope, hot air, thermal camera, and a lot of very small tweezers. The software side is a small stack of bench utilities I'm building for myself: a telemetry HUD that feeds OBS, an intake tracker for boards coming in, and a parts inventory the rest of it reads from. All private for now — it's held together with assumptions about my specific bench, and it'd be a bad time for anyone else.

The printed fixtures that hold it together *are* public — see below.

### 🖨️ printing & fixtures

**[3d-printer-models](https://github.com/IamMrCupp/3d-printer-models)** — parametric OpenSCAD, printed, then published as STL plus source. Mostly things that hold other things: a bench cleaning station, an instrument tray for the Owon SPM8104, a rotary tool station, a UV mask station, a drybox splitter stand, a VJ rig stand. CC BY-NC.

**[SnapmakerU1-Firmware-Helper-Scripts](https://github.com/IamMrCupp/SnapmakerU1-Firmware-Helper-Scripts)** — scripts for patching custom filament profiles into the Snapmaker U1 GUI binary, plus RFID/NFC utilities for when spool detection starts lying to you.

**[OpenSpool NFC tag generator](https://github.com/IamMrCupp/OpenSpool-Filament-NFC-Tag-Generator-iOS-App)** — an iOS app for writing OpenSpool filament tags from your phone, covering the full extended field set the U1 understands.

### 🛠️ tools & infra

**[annoybots](https://github.com/IamMrCupp/annoybots)** — eggdrop and BMotion, rebuilt as one Go binary. IRC, Twitch, and Discord all at once, a shared Redis bus so the bots behave like an actual botnet, a Markov brain, a cross-platform partyline, and eggdrop-style channel keeping. Distroless image, GitOps-deployed to Kubernetes, because of course it is.

**[claude-project-kit](https://github.com/IamMrCupp/claude-project-kit)** — behavioral scaffolding and session conventions for AI coding workflows. Working-folder templates, structured handoff docs, and sane defaults for working with AI assistants on real projects. The templates aren't the point — what they do *to* the assistant is. Open source. Use it.

**[pwnagotchi-plugins](https://github.com/IamMrCupp/pwnagotchi-plugins)** — custom plugins for pwnagotchi units, built against the jayofelony image.

### 📎 odds and ends

**[recipe-card-maker](https://github.com/IamMrCupp/recipe-card-maker)** — a personal recipe collection where markdown is the source of truth. Generates full-page PDFs for the kitchen binder and 4×6 cards for the recipe tin. Containerized, because apparently that's how I make cookies now.

**[mrcupp-project](https://github.com/IamMrCupp/mrcupp-project)** — the Hugo source behind [mrcupp.com](https://mrcupp.com). Markdown pages, a pile of custom shortcodes, and some framework hacks I'd rather not describe.

---

## day job stuff

30+ years in computers and electronics. Senior Infrastructure Engineer doing the full stack of SRE/DevOps work: Terraform/IaC, Linux administration, Python/Go/Rust development, heavy multi-cloud across AWS, GCP, and Azure, Kubernetes (cloud and bare metal), networking, and yes — on-call. I care a lot about reliability, observability, and not being paged at 3am.

Tech I live in: `Terraform` `AWS` `GCP` `Azure` `Kubernetes` `Linux` `Python` `Go` `Rust` `Networking`

---

## also me

- 🎛️ Performing DJ — Autonomic, Halftime DnB, Grey Area  
- 🎨 VJ — GLSL/ISF shaders in Synesthesia  
- 📻 Internet radio — [Tech-Noid.net](https://tech-noid.net)  
- 🍵 Gongfu tea nerd (Jesse's Tea Club)  
- 🐱 Cat dad  
- 🔫 New to shooting, learning fast  

---

## find me

[mrcupp.com](https://mrcupp.com) · [linkedin.com/in/mrcupp](https://linkedin.com/in/mrcupp) · [linktr.ee/IamMrCupp](https://linktr.ee/IamMrCupp)

[![Ko-fi](https://img.shields.io/badge/Ko--fi-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/IamMrCupp) [![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/IamMrCupp)
