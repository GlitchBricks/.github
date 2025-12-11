# GlitchBricks

GlitchBricks is a modular playground for creative manipulation of analog A/V signals. Its primary goal is to make circuit bending accessible, modular, and (optionally) programmable — empowering artists, hackers, experimenters, and beginners to build their own evolving glitch instruments.

---

## What Is GlitchBricks?

GlitchBricks is an **open modular format** designed for building creative A/V instrument chains. Think of it as a mashup of:
- the immediacy of classic analog video gear,  
- the playfulness of circuit bending,  
- the modularity of synth ecosystems, and  
- the precision of digital control protocols.

It’s designed to scale from simple hands-on tiles to advanced hybrid modules with internal DSP, programmable behavior, or custom hardware.

---

## The Platform

The GlitchBricks platform stands on two foundational pillars:

- **OAVCP (Open Analog Voltage Control Protocol)**  
  A lightweight, open, addressable control protocol that provides centralized or distributed control across an entire modular rig. It allows automation, preset recall, scripting, synchronized modulation, and deep integration with custom “brain” modules or external controllers.

- **GBCB (GlitchBricks Communication Bus)**  
  The hardware bus that lets modules chain together physically and electronically. It carries analog video, sync, power rails, and the OAVCP control signals — enabling a consistent, open-ended way to combine modules into powerful creative pipelines.

Together, these two systems form a hybrid analog/digital ecosystem where experimentation is encouraged, chaos is welcome, and structured control is available when you want it.

---

## Ecosystem Components

### 🧱 **Modules (“Bricks”)**
Each brick performs a specific job — input, processing, mixing, distortion, audio reactivity, output, etc. Bricks snap together left-to-right and share:
- RGB + Sync analog video signals  
- +12V and +5V power rails  
- An I²C-like digital control bus (OAVCP)

Some modules are purely analog. Others blend analog paths with digital brains. Many are intentionally unstable.

### 🔌 **The GBCB Bus**
A simple 10-pin standard that:
- Maintains video integrity through buffered RGB + H/V sync
- Passes power down the chain
- Exposes the OAVCP control lines for automation and discovery  
- Encourages community-made modules through a stable, open pinout

### 🎛️ **OAVCP Control Protocol**
OAVCP turns a modular glitch rig into a controllable system:
- Module auto-discovery  
- Hardware identity + capabilities  
- Parameter descriptors (names, ranges, types)  
- Read/write control  
- Presets and potentially scripting/tempo sync

Controllers can be dedicated “brain” modules, external microcontrollers, or desktop software — or omitted entirely for a purely analog workflow.

---

## Philosophy

GlitchBricks is designed to be:

- **Open** — The protocol and bus standards are community-friendly and modder-friendly. Anyone can build modules.
- **Playable** — You should be able to get wild, gorgeous results in seconds.
- **Modular** — Combine bricks however you want; build instruments that never existed before.
- **Hybrid** — Analog where it matters; digital where it empowers.
- **Glitch-positive** — Stability is optional. Chaos is a feature.
- **Beginner-friendly** — No EE degree required; this is a sandbox for learning and experimentation.

---

## Goals of the Project

- Create an approachable entry point into analog video hacking.
- Allow artists to build evolving, reconfigurable glitch rigs.
- Encourage a community of third-party builders.
- Provide a fully open hardware/software specification for interoperability.
- Blend circuit-bending energy with modular-synth elegance.

---

## Status

This project is in active development. Specs, reference modules, example firmware, and hardware layouts will appear here as they stabilize. Community feedback and experimentation are highly encouraged.

---

## Learn More

- **OAVCP Specification** (in progress)
- **GBCB Bus Standard** (in progress)
- **Example Bricks + reference designs** (coming soon)
- **Community modules showcase** (planned)

If you'd like to get involved, contribute ideas, or build your own module, join the discussion and help shape the standard.
