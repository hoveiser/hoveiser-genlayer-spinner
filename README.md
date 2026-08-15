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

## License
MIT
