# 🏎️ Speed Lab — Distance vs. Time

A browser-based kinematics activity for exploring **constant velocity vs. acceleration**. Runs entirely in the browser — no install, no accounts.

**▶ Play:** https://tdavidsm.github.io/speed-lab/

## The activity

The screen is a virtual lab bench (left) and a distance–time graph (right).

1. **Pick a car** from the garage. Each color has its own steady speed — **except one, which accelerates.**
2. **Drag the checkered flag** (or tap the ruler) to set how far the car must travel.
3. **Press Start.** The car drives while the stopwatch times it. When it reaches the flag, the trial's **(time, distance)** point drops onto the graph in that car's color.
4. Run the same car at several distances to build its line, then compare cars.

**Student mission:** figure out which car is accelerating. Constant-speed cars make **straight lines** through the origin; the accelerating car makes a **curve**.

## Teaching notes

- **The speeds and which color accelerates are randomized every time the page loads**, so one class can't just tell the next "it's the purple one." Reload to reshuffle.
- **🔑 Answer key** (top right) reveals each car's speed / acceleration in the legend — handy for the debrief.
- **Connect each car's points** overlays a line per car to make the straight-vs-curved contrast pop.
- **⬇ CSV** exports the trial log for a lab notebook or a spreadsheet follow-up.
- Works on Chromebooks, laptops, and tablets (pointer + touch).

## Tech

Single self-contained `index.html` — plain HTML/CSS/JS, canvas for the graph, no dependencies. Deployed via GitHub Pages from the `main` branch.
