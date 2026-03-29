# Rust Audio DSP Processor

Real-time audio effects in the browser using Rust + WebAssembly.

**[Live demo](https://mohammedx6.github.io/rust-audio-dsp/)**

DSP formulas based on the [Audio EQ Cookbook](https://webaudio.github.io/Audio-EQ-Cookbook/audio-eq-cookbook.html).

---

## Effects

- Gain
- Low-pass / High-pass filters
- Distortion
- Delay / Echo

## Presets

15 ready-made presets (Podcast, Radio, Robot, Cave, Stadium, Psychedelic, etc.) for quick testing.

## Visuals

Waveform, spectrum, bars, and circle views with live level meters and performance stats.

---

## Getting Started

**Prerequisites:** Rust (via [rustup](https://rustup.rs/)), [wasm-pack](https://rustwasm.github.io/wasm-pack/installer/), Node.js
```bash
git clone https://github.com/mohammedX6/rust-audio-dsp.git
cd rust-audio-dsp
npm install
npm run build
npm start
```

Open http://localhost:8000

---

## Stack

- Rust — DSP logic compiled to WebAssembly
- Web Audio API — audio pipeline
- Canvas — visualizations

---

## License

MIT
