# Hi, I'm Pipe 👋

I'm **Felipe "Pipe" Fonseca** — an IB student in Costa Rica, aspiring engineer, and
student-athlete. I like building real things across the whole stack: from a
self-hosted fleet of AI agents, to web apps, to firmware for a physical
calculator. Most of what I build starts as *"could I run this myself?"*

I like owning the whole stack — from the kernel scheduler up to the UI — and
actually understanding every layer I depend on, not just the one I'm working in.

---

## 🔧 What I build

**🏠 [Homelab — a self-hosted multi-agent AI system](https://github.com/kubinokitsune/homelab)**
A dozen AI agents running on a single second-hand mini-PC — no cloud, no GPU.
They run my 3D printer, watch the server, block ads network-wide, and file a
morning briefing. I designed the architecture: container isolation, grounding
the agents in real data so they can't make things up, and remote access over
Tailscale. → **[Read the wiki](https://github.com/kubinokitsune/homelab/wiki)**

**🧠 [homelab-agent-skills](https://github.com/kubinokitsune/homelab-agent-skills)** · *public code*
The shared Python library the whole fleet is built on — one base class, and
every agent is an identity plus a few commands on top. Vault memory, local LLMs,
Moonraker control, classical-ML failure detection, monitoring.

**🧪 [Chemistry Calculator](https://github.com/kubinokitsune/chem-calculator)** · *live web app*
An interactive physical-chemistry calculator for IB Chemistry — 22 topics, a CLI,
a browser UI, and two ports for the Casio fx-CG50 graphing calculator (a Python
port and a native C++ add-in). Publicly hosted.

**🔢 [chemcalc-handheld](https://github.com/kubinokitsune/chemcalc-handheld)** · *hardware*
Taking the calculator off the screen and onto a physical, handheld device.

**📚 [sat-trainer](https://github.com/kubinokitsune/sat-trainer)** · *ed-tech*
A website for studying for the SAT.

---

## 🛠️ Tools I reach for

`Python` · `JavaScript` · `C++` · `Flask` · `Docker` · `Proxmox / LXC` ·
`Linux` · `local LLMs (Ollama)` · `vector search (Qdrant)` · `Klipper / Moonraker`

I also work with AI-assisted development — I care about designing the system and
making the right calls, and I use good tools to build faster than I could alone.

---

## 📫 Reach me

Discord **kitsune_pipe** · or open an issue on any repo.

### 🚧 What's next

- A **custom PCB** for the handheld calculator, once the firmware and key layout have earned it
- A **server upgrade** (i7 / more threads) so the homelab can run larger local models
- Finishing IB — then studying engineering

<sub>Built by Felipe "Pipe" Fonseca · Costa Rica</sub>
