# DJDEV.IN — "ONE NIGHT" — Design Bible

## One-line Design Read
The website is a single night out: scroll is time (22:00 → 06:00), the page is the set, and a living electric storm breathes with the phase of the night.

## Concept
No generic artist template. Every element is DJ-specific: a fixed telemetry HUD tracks phase / night-time / BPM as you scroll; the background storm intensifies toward peak and dissolves toward sunrise; copy is written as a set arc, not a bio.

## Palette (locked, no exceptions)
- `--void: #050505` — page ground (deeper than prmx builds)
- `--orange: #F97316` — the current
- `--ember: #EA580C` — deep heat
- `--hot: #FFB066` — plasma core
- `--bone: #FAFAFA` — text
- `--ash: #A3A3A3` — muted
- No other hues. Discipline is the luxury.

## Typography
- Display: Inter 800, uppercase, -0.04em (giant DEV wordmark, phase titles)
- Headlines: Inter 600, -0.025em
- Telemetry/labels: JetBrains Mono, 11px, 0.22em tracking, uppercase
- Body: Inter 400/500

## Signature systems
1. **Night HUD** — fixed nav: `DEV ●` | live phase (`DOORS`/`WARM-UP`/`PEAK`/`AFTERHOURS`/`SUNRISE`) | night clock 22:00→06:00 mapped to scroll | real IST clock | BOOK pill.
2. **Storm canvas** — fixed full-viewport flow-field particles (electric wind). Intensity + speed driven by scroll phase; mouse repels. Pauses when tab hidden.
3. **Scroll wire** — SVG path on the left rail draws itself with scroll progress.
4. **Kinetic manifesto** — word-by-word ignition: words light orange as they enter view.
5. **Phase marquees** — giant outlined-text dividers between phases.
6. **Custom cursor** — plasma dot + trailing ring (pointer:fine only), grows on interactives.
7. **Preloader** — "CHARGING THE WIRE" 0→100 with plasma line, curtain lift.
8. **Grain** — SVG-noise overlay, 5% opacity, fixed.
9. **Plasma tube CTA** — the approved smooth-tube wire button (from prmx-vortex v3), subtle magnetic pull.
10. **Waveform mixes** — canvas-drawn seeded waveforms per mix row.
11. **Booking ritual** — "CLOSE THE CIRCUIT" form; submit fires the discharge flash.
12. **Footer lamp** — the approved cursor-tracked etched-glass DEV.

## Scroll → night mapping
- progress 0.00–0.20 → DOORS 22:00, 118 BPM, storm 0.25
- 0.20–0.40 → WARM-UP 23:00, 118→122 BPM, storm 0.45
- 0.40–0.62 → PEAK 01:00, 124→128 BPM, storm 1.0
- 0.62–0.85 → AFTERHOURS 03:00, 128→OPEN, storm 0.6
- 0.85–1.00 → SUNRISE 06:00, OPEN, storm 0.25

## Copy voice
First-person current. Short lines. No bio fluff, no "passionate about music". The manifesto is the bio.

## Anti-slop gates (from skill + standing rules)
- Reference-first: AURA-VORTEX tokens locked above.
- No Inter-for-everything slop: Inter display + JetBrains Mono telemetry is the system, not a default.
- No purple-blue gradients, no nested cards, no 3-identical-cards, no robotic CTAs.
- No emojis as icons (SVG only), visible :focus-visible, reduced-motion respected, canvases pause offscreen/hidden, no nested interactives, aria-hidden on decorative canvas.
- Real pixels judged in headless Chromium, desktop 1440 + mobile 390.
- No invented facts: venues/dates/quotes only if verified; otherwise evocative non-factual copy.
