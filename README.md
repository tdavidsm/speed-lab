# 🏎️ Speed Lab — Distance vs. Time

A browser-based kinematics activity for exploring **constant velocity vs. acceleration**. Runs entirely in the browser — no install, no accounts.

**▶ Play:** https://tdavidsm.github.io/speed-lab/

## The activity

The screen is a virtual lab bench (left) and a distance–time graph (right).

1. **Pick a car** from the garage. Most colors move at a steady speed — but **two of them accelerate** (one gently, one hard).
2. **Drag the checkered flag** (or tap the ruler) to set how far the car must travel.
3. **Press Start.** The car's nose starts on the line and it drives while the stopwatch times it. The clock **stops the instant the nose crosses the finish flag** — dropping that trial's **(time, distance)** point onto the graph in the car's color — while the car keeps rolling to the end of the track (so you can watch an accelerating car pull away).
4. Run the same car at several distances to build its line, then compare cars.

**Student mission:** figure out which cars are accelerating. Constant-speed cars make **straight lines** through the origin; an accelerating car makes an upward **curve** — and the harder it accelerates, the more sharply it bends.

## Teaching notes

- **The speeds and which colors accelerate are randomized every time the page loads**, so one class can't just tell the next "it's the purple one." Reload to reshuffle.
- **🔑 Answer key** (top right) reveals each car's speed / acceleration in the legend — handy for the debrief.
- **Connect each car's points** overlays a line per car to make the straight-vs-curved contrast pop.
- **⬇ CSV** exports the trial log for a lab notebook or a spreadsheet follow-up.
- Works on Chromebooks, laptops, and tablets (pointer + touch).

## Tech

Single self-contained `index.html` — plain HTML/CSS/JS, canvas for the graph, no dependencies. Deployed via GitHub Pages from the `main` branch.
