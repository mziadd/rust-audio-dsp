Audio DSP Processor

Real-time audio effects in the browser using Rust + WebAssembly.

Try it: https://mziadd.github.io/rust-audio-dsp/

What it does

A lightweight audio processor with a few core effects and some fun presets. Runs fully in the browser with live visual feedback.

Effects
Gain (volume)
Low-pass / High-pass filters
Distortion
Delay / Echo
Presets

15 built-in presets like Podcast, Radio, Robot, Cave, Stadium, Psychedelic, etc. — quick ways to shape the sound without tweaking everything manually.

Visuals
Waveform, spectrum, bars, and circular views
Shows levels, frequency, and performance stats in real time
Performance
Very low CPU usage
Near-zero latency
Fast enough to run comfortably in the browser
Run locally
git clone https://github.com/mohammedX6/rust-audio-dsp.git
cd rust-audio-dsp
npm install
npm run build
npm start

Then open http://localhost:8000

Stack
Rust (DSP)
WebAssembly
Web Audio API
Canvas (visuals)
Notes
Requires Rust (via rustup) + wasm-pack
Uses Audio EQ Cookbook formulas:
https://webaudio.github.io/Audio-EQ-Cookbook/audio-eq-cookbook.html
License

MIT
