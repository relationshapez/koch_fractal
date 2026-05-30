# Relationshapez: Koch Snowflake

This project is a single-file HTML explorer for the Koch Snowflake fractal. It is designed for use on a desktop computer, tablet, or phone, with a simple interface.

Remote URL:

<https://relationshapez.github.io/koch_fractal/>

## Files

- `index.html` — the main interactive browser tool
- `README.md` — repository overview and usage guide
- `LICENSE` — MIT license text

## How to Use

Open `index.html` in a web browser, or visit the remote URL.

Use the **Animate** button to start or pause the construction of the Koch Snowflake. The display begins with an equilateral triangle. At each iteration, the middle third of every side is replaced by two sides of a smaller outward-pointing equilateral triangle, creating the familiar snowflake boundary.

Use **Reset** to return to iteration 0 and restore the original view.

When the animation is paused, use the arrow buttons:

- **◀** goes back one iteration.
- **▶** goes forward one iteration.

The arrow buttons are inactive while the snowflake is animating.

## Controls

### Max

The **Max** box controls the largest iteration shown by the animation. The allowed range is 1 through 7.

The number of line segments grows quickly. At iteration \(n\), the boundary has

\[
3\cdot 4^n
\]

segments. For this reason, larger values can be more demanding on small mobile devices.

### Speed

The **Speed** slider controls how quickly the animation moves from one iteration to the next.

At the lowest speed setting, the app shows a slower step-by-step transition: the new triangular pieces are outlined and then fade into the snowflake. This makes it easier to see that the Koch Snowflake is built by adding triangles along the sides.

## Zooming and Panning

The drawing area supports zooming and panning.

On a desktop or laptop:

- Use a trackpad or mouse wheel to zoom.
- Click and drag to pan.

On a phone or tablet:

- Pinch to zoom.
- Drag to pan.

Zooming and panning do not reset when the animation is resumed. The view only returns to the original position after pressing **Reset**.

## Classroom Notes

The Koch Snowflake is a useful example of a shape with a simple rule that creates surprising complexity. Each stage adds smaller triangular bumps to every side of the previous stage.

This makes the snowflake a good companion to classroom discussions of:

- recursive construction rules,
- perimeter growth,
- self-similarity,
- fractal boundaries,
- and the difference between finite approximations and limiting objects.

## License

Copyright (c) 2026 Alan Miller.

This project is released under the **MIT License**.

See the [`LICENSE`](LICENSE) file for the full license text.
