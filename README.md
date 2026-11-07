# Primordia — evolution simulator

A single self-contained `index.html` (no dependencies, no build). Open it in any modern browser, desktop or phone.

Life starts as simple glowing blobs. Everything else emerges: herbivores, scavengers, predators,
spikes, fins, extra eyes, showy courtship crests and new species.

- **Genome**: size, speed, colour, brightness, sense range, diet (plant ↔ meat), reproduction threshold,
  lifespan, temperature preference/tolerance, mate preferences + pickiness, body parts, and a small
  neural net (18 sensors → 8 hidden → turn / move / eat / attack / flee / court).
- **Circle of life**: plants grow from sunlight, water and soil nutrients; corpses and metabolism return
  nutrients to the soil. Boom/bust cycles happen on their own.
- **Sexual selection**: each creature scores a potential mate with its own evolving preference weights;
  both partners must accept. Courtship costs energy and time.
- **Species** are clustered automatically by genome distance, named, tracked in a population graph and family tree.
- **God mode**: ice age, heat wave, drought, flood, meteor, plague, food boom, sunlight and temperature sliders.

Controls: drag to pan, pinch/scroll to zoom, tap a creature to inspect it. Keys: space = pause, 1–5 = speeds.
