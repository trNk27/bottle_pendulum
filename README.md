# Pendulum Painter

A playful browser simulation of pendulum pour painting: fill a cup with layers of paint, poke holes in it, then let it swing over a canvas.

Open `index.html` in any modern browser. It's a single file with no dependencies, and it works with mouse or touch. You can also serve it with GitHub Pages.

1. **Fill**: press and hold a paint pot to pour. Each colour becomes a layer. The rainbow pot adds your own colour.
2. **Poke**: tap the cup to make a hole, either in the bottom or in the side wall. Hold to make it bigger, and tap a hole again to patch it.
3. **Swing**: drag the cup anywhere over the canvas and let go. Flick as you release to make it swing in ellipses.

The swing is a real spherical pendulum, which gives the slowly turning rosette patterns. Paint drains through each hole faster when there's more paint above it. Side holes squirt sideways, and each hole drips whichever layer sits at its height. Lines are thin where the cup moves fast and pool where it slows down. The toolbar lets you change the string length, run at 3× speed, pick the canvas colour, clear the canvas and save the painting as a PNG.
