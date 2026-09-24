# hey, i'm aaron. 👋

Senior Infrastructure Engineer by trade. Bass music by compulsion. Building things at the intersection of sound, light, and infrastructure since before it was cool.

Founder of **[Tech-Noid Systems](https://tech-noid.net)** — a bass music collective, internet radio station, sound system, and general chaos engine running since 2008. Based in West Sacramento, CA. Performing DJ (Autonomic · Halftime DnB · Grey Area) and VJ. NorCal DnB scene.

---

## what i'm actually building

### 🔊 sound & light

**[audiophore](https://github.com/audiophore/audiophore)** — a low-latency Rust bridge from Synesthesia to every light in the room. Hue Entertainment, Nanoleaf, WLED over sACN/DDP, Art-Net DMX, Ether Dream lasers, OSC. Tauri + Svelte native app, pluggable input adapters, mlua scripting. It started as "I want my lights to react to my music" and turned into an actual project. The [brand kit](https://github.com/audiophore/branding) is public too — logos, wordmark, and palette, all reproducibly generated from one `brand.toml`.

**[obs-radio-output](https://github.com/Tech-Noid-Systems/obs-radio-output)** — a native OBS Studio plugin that streams audio straight to Icecast and SHOUTcast. The usual answer is a second encoder app and a virtual audio cable; this is one less thing to babysit mid-set. Public beta on macOS, Linux, and Windows. Lives in the [Tech-Noid Systems](https://github.com/Tech-Noid-Systems) org alongside the radio infrastructure — Kubernetes, Flux GitOps, Icecast, the works.

### 🔬 the bench

Microsoldering and board-level repair — microscope, hot air, thermal camera, and a lot of very small tweezers. The software that runs it is mine, and it's private for now while I settle how the source gets shared. Each piece has a page:

**[benchhud](https://mrcupp.com/page/benchhud/)** — the bench's command center. Live scope feed, a thermal camera registered right onto the scope image, and instrument telemetry, all in one window instead of three — and composited to a virtual camera, so it's also the stream. It started as "I want to see which part is overheating without looking away from the scope."

**[bench-parts](https://mrcupp.com/page/bench-parts/)** — the parts inventory. Knowing you have the part is half of quoting a repair. A tablet-friendly app plus a REST API that benchhud reads, so stock shows up on the HUD. Running on the cluster.

**[benchhud-intake](https://mrcupp.com/page/benchhud-intake/)** — the front door for incoming jobs. It's a separate service for one reason: anything benchhud can see might end up on a stream, so customer data lives nowhere near it.

**[OpenBoardView](https://mrcupp.com/page/openboardview/)** — not mine, but I patched it. Cross-probing — click a part on the board, the schematic PDF jumps to it — never worked on macOS. Now it does, via a PDF bridge I've sent [upstream](https://github.com/OpenBoardView/OpenBoardView/pull/363).

The bench is going on camera — follow on [Twitch](https://www.twitch.tv/iammrcupp) or [YouTube](https://www.youtube.com/@IamMrCupp) to catch the first stream.

### 🖨️ printing & making

**[3d-printer-models](https://github.com/IamMrCupp/3d-printer-models)** — thirty-two printable models, kept as parametric OpenSCAD source so you can regenerate them, not just download a fixed STL. Each one ships its own versioned release. Most of them hold the bench together: hot-air nozzle holders, soldering station mounts, a BGA rack, a thermal-cam mount, a heat-gun holder, spools for solder and wick. Models are CC BY-NC; the library and tooling are MIT, so you can build on them.

**[clickfinity-openscad](https://github.com/IamMrCupp/clickfinity-openscad)** — magnet-free Gridfinity baseplates. Flexible latch tongues catch a standard bin foot instead of magnets, plates join edge-to-edge with underside bowtie keys, and the whole thing is parametric — one command gets you any grid size. It clicks, and it tiles. Every release ships ready-to-print STLs.

**Snapmaker U1 tooling** — [firmware helper scripts](https://github.com/IamMrCupp/SnapmakerU1-Firmware-Helper-Scripts) for patching custom filament profiles into the U1's GUI binary and debugging RFID spool detection when it starts lying to you, plus an [iOS app](https://github.com/IamMrCupp/OpenSpool-Filament-NFC-Tag-Generator-iOS-App) that writes OpenSpool NFC tags with the full field set the U1 understands.

### 🛠️ tools & apps

**[claude-project-kit](https://github.com/IamMrCupp/claude-project-kit)** — scaffolding that starts every AI-assisted session already grounded. A bootstrap script, lifecycle commands for starting and ending sessions, and a lint that catches convention drift. The templates aren't the point — what they do *to* the assistant is. Open source. Use it.

**[apptracker](https://github.com/IamMrCupp/apptracker)** — a self-hosted job application and networking tracker. Most of them trap your data in one browser on one machine; this one is a single static Go binary with the web UI baked in and pure-Go SQLite behind it, so it runs in your own cluster and follows you across devices.

**[recipe-card-maker](https://github.com/IamMrCupp/recipe-card-maker)** — markdown recipes in, full-page binder PDFs and 4×6 recipe-tin cards out. Containerized, because apparently that's how I make cookies now.

**[mrcupp-project](https://github.com/IamMrCupp/mrcupp-project)** — the Hugo source behind [mrcupp.com](https://mrcupp.com), where every project above has a longer write-up.

### 💬 chat & bots

**[annoybots](https://github.com/IamMrCupp/annoybots)** — the eggdrop and BMotion era, rebuilt as one Go binary. IRC, Twitch, and Discord all at once, a shared Redis bus so the bots behave like an actual botnet, a Markov brain that still babbles, a cross-platform partyline, and eggdrop-style channel keeping. Distroless image, GitOps-deployed to Kubernetes, because of course it is.

**[pwnagotchi-plugins](https://github.com/IamMrCupp/pwnagotchi-plugins)** — two small plugins for the little Wi-Fi-handshake Tamagotchi: an age readout the current image lost, and a pcap cleaner.

### 🔜 coming up

**[sekrit](https://mrcupp.com/page/sekrit/)** — open, self-hostable event ticketing for independent promoters. No gatekeeping, you own your attendee list, and your money never touches the platform. Pre-alpha and private for now, open source once it's ready — and the first thing here built for the scene rather than the bench.

---

## day job stuff

30+ years in computers and electronics. Senior Infrastructure Engineer doing the full stack of SRE/DevOps work: Terraform/IaC, Linux administration, Python/Go/Rust development, heavy multi-cloud across AWS, GCP, and Azure, Kubernetes (cloud and bare metal), networking, and yes — on-call. I care a lot about reliability, observability, and not being paged at 3am.

Tech I live in: `Terraform` `AWS` `GCP` `Azure` `Kubernetes` `Linux` `Python` `Go` `Rust` `Networking`

---

## also me

- 🎛️ Performing DJ — Autonomic, Halftime DnB, Grey Area. Regular on EMP Radio's Demo Derby and Slappy Hour  
- 🎨 VJ — GLSL/ISF shaders in Synesthesia  
- 📻 Internet radio — [Tech-Noid.net](https://tech-noid.net)  
- 🍵 Gongfu tea nerd (Jesse's Tea Club)  
- 🐱 Cat dad  
- 🔫 New to shooting, learning fast  

---

## find me

[mrcupp.com](https://mrcupp.com) · [resume](https://mrcupp.com/page/resume/) · [linkedin.com/in/mrcupp](https://linkedin.com/in/mrcupp) · [twitch.tv/iammrcupp](https://www.twitch.tv/iammrcupp) · [youtube.com/@IamMrCupp](https://www.youtube.com/@IamMrCupp) · [linktr.ee/IamMrCupp](https://linktr.ee/IamMrCupp)

[![Ko-fi](https://img.shields.io/badge/Ko--fi-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/IamMrCupp) [![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/IamMrCupp)
