# EndOfWorld // Crisis Response OS

A browser-based, realistic geopolitical techno-thriller crisis simulator exploring the subtle, high-stakes trade-offs of autonomous systems, algorithmic governance, and emergency human intervention.

Includes a comprehensive **Easy-to-Read Edition** designed for dyslexic students, neurodivergent readers, and classroom accessibility.

## Highlights & Features

- **Executive Role Selection**: Choose from 4 distinct operational jurisdictions across civilian and critical sectors:
  1. **Dr. Maya Lin** — Chief AI Safety Auditor (*Frontier AI Oversight & Model Registry*)
  2. **Marcus Vance** — Grid Resilience Director (*Continental Energy & SCADA Networks*)
  3. **Dr. Elena Rostova** — Chief Medical Officer (*Public Health, Bio-Ethics & Epidemic Defense*)
  4. **Julian Sterling** — Market Integrity Director (*High-Frequency Algorithmic Capital & Settlement*)
- **Branching 3-Act Narrative Tracks**: Each role features an independent storyline with subtle, nuanced dilemmas where every choice involves legitimate operational trade-offs (response latency vs. mathematical verification, false alarm panic vs. catastrophic systemic risk).
- **Interactive Telemetry HUD**: Sector-specific metric gauges and an animated 60 FPS real-time oscilloscope canvas (neural loss spectra, 60 Hz power grid harmonics, cardiac triage queues, order-book depth).
- **System Controls**: Persistent `⟲ REBOOT` button with confirmation modal, show full text controls, and Web Audio API synthesized terminal sound effects (with audio toggle).
- **Comprehensive After-Action Debrief**: Detailed post-mortem report tracking all decisions, institutional fallout, final telemetry ratings, and export-to-clipboard functionality.

### ♿ Easy-to-Read & Dyslexia Accessibility Suite

- **Dyslexia-Friendly Typography**: One-click toggle between **Lexend** (proven by educational research to reduce visual crowding and increase reading fluency) and **Atkinson Hyperlegible** (developed by the Braille Institute for visual distinction), with clean system sans fallbacks.
- **Low-Glare Contrast Themes**:
  - **Warm Paper Cream**: Off-white paper background (`#fbf8f2`) with deep slate text to eliminate retinal glare and soothe visual stress (Irlen syndrome / scotopic sensitivity).
  - **Soft Pastel Tint**: Butter-yellow parchment tint (`#fefae0`) proven to aid tracking for dyslexic readers.
  - **High-Contrast Dark Mode**: Crisp, non-glare dark slate (`#0d1217`) with clear white text.
  - **Cyber Terminal (Default)**: Authentic retro CRT green phosphor.
- **Reading Ruler (Line Guide)**: Interactive horizontal focus bar that follows mouse/touch cursor to prevent skipping lines.
- **Distraction-Free Reading**: Strips away CRT scanlines, flicker, and screen glitch animations.
- **Instant Text Delivery**: Skips typewriter delays to reduce cognitive tracking fatigue.
- **Text Resizing**: Scalable to 100%, 120%, and 140% font sizes with generous line-height (1.85+) and relaxed letter/word spacing.
- **Persistent Preferences**: Saves student accessibility choices to `localStorage`.

## Run Locally

Open `index.html` in any modern web browser. No installation or build step is required.

```bash
# Optional: run a local server
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Project Structure

- `index.html` — Self-contained application containing the UI, stylesheets, dyslexia accessibility engine, audio synthesizer, and state machine.
- `assets/` — Sector scenario visual banners.
