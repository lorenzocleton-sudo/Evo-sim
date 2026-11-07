# Primordia — evolution simulator

A single self-contained `index.html` (no dependencies, no build). Open it in any modern browser, desktop or phone.

Life starts as single cells in the water. Everything else has to emerge through mutation, mate choice and selection.

## Body plans (bacteria → complex life)
- A **complexity** gene moves bodies through single cell → colony → multicellular → segmented → specialized.
  Each stage caps which body parts can be expressed, and complex bodies grow bigger, digest better and run more efficiently.
- Parts evolve gradually: **cilia → flagellum → fins → legs**, **light-spot → simple eye → camera eye**,
  **soft body → shell → armor plates** (+ spikes), **pore → mouth → jaws**, plus **lungs** and **dry skin** for land.
- Creatures are drawn procedurally from their genome (segments, limbs, fins, eyes, jaws, stripes, colours).
- Water and land zones with shorelines, rivers and mountains. Without lungs, the shoreline is a wall;
  land needs lungs and dry skin to breathe and legs to move, so leaving the water has to be earned.
- Species get a generated name plus a body-plan label ("Finned swimmer", "Armored six-legged crawler", …).
- Milestone popups mark the first time something new evolves ("Gen 282: First creature walked on land!").

## Mating
- Every creature has a visible **fitness score** (energy, health, age, feeding success).
- Mate choice combines the evolving preferences (size, glow, spikes, colour) with **assortative fitness matching**:
  strong creatures reject much weaker partners, so strong pairs with strong. Strong pairs raise better-fed young.
  A little randomness remains so the gene pool stays diverse.

## Genetics
- DNA strip per creature: one block per gene, coloured underline for parent A/B, glowing marker for mutations; tap for details.
- Mendelian loci with dominant/recessive alleles: **pigment** (pp = albino), **stripes**, **spikes** (ss = spiky),
  so these traits can skip generations.

## Trees & history
- Full-screen, pinch-zoomable **tree of life**: time runs downward, thickness = population, extinct branches fade with ✝ and
  the cause, gold path from the first cell to the dominant species. Tap a branch for its traits and typical body.
- **Individual family tree** (grandparents, parents, siblings, children, grandchildren), tappable, pruned to ~4 generations.
- Population graph with a **timeline scrubber**, event log, stats screen with all-time records and a **Hall of Fame**.

## World
- Day/night cycle and seasons (plant growth, activity, night vision; nocturnal hunters can evolve).
- Disease spreads by contact; immunity genes are selected for after outbreaks. Pack hunting and herding via a social gene.
- Camouflage: colour close to the terrain makes prey harder to spot.
- God mode: ice age, heat wave, drought, flood, meteor, plague, food boom, **raise mountain**, **split land**, sunlight/temperature.
- Save to the browser (autosave every 90 s, "Continue" on the start screen) and export/import the world as a code or file.

Controls: drag to pan, pinch/scroll to zoom, tap a creature to inspect it. Keys: space = pause, 1–5 = speeds.
