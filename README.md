# hoveiser-genlayer-spinner

# Neural Consensus — GenLayer Portal Spinner

Submission for the **"Design the GenLayer Spinner"** mission.

## Concept
Eight validator nodes on a ring; a Kinetic Cobalt pulse travels node-to-node —
a minimal retelling of GenLayer's decentralized AI consensus, small enough to
sit in a button.

## Specs
- Self-contained SVG + CSS animation (no JS, no dependencies, ~1 KB)
- Seamless infinite loop (1.6 s cycle)
- Brand tokens only: Kinetic Cobalt `#110FFF`, Asphalt `#606060`;
  verified on Ceramic `#F5F5F5` and Carbon `#070707`
- Crisp from 16 px to 96 px
- Accessibility: `role="img"`, `aria-label`, honors `prefers-reduced-motion`

## Files
- `neural-consensus.svg` — primary spinner
- `hex-chain.svg` — alternate concept (blockchain core)
- `index.html` — live demo (light/dark, size ramp)

## Usage
HTML: `<img src="neural-consensus.svg" width="32" height="32" alt="Loading…">`
React: `import spinner from "./neural-consensus.svg"` → `<img src={spinner} alt="Loading…" />`

## Brand compliance
Built against the official GenLayer Design System (genlayer-foundation/genlayer-design):
- Signature gradient #E37DF7 → #9B6AF6 → #110FFF (the brand's primary motif) drives the active pulse
- Idle nodes use neutral ink #6B6B6B; single accent #110FFF
- Motion: 1.6s gentle ease loop — inside the brand's 1.5–3s window; no bounce/spring
- The official mark (GenLayer_Mark_White.svg) is used unmodified and never rotated,
  on a gradient tinted container — the brand's own small-icon pattern

## License
MIT
