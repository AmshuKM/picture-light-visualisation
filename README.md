# Light Visualiser

Preview how **lighting would look in a real room** before you buy or install anything. Load a photo of the space, dim it, then place bulbs, spotlights and LED backlighting to see the glow on the actual surfaces.

It's a single `index.html` file with no install and no build step. Your photo stays in the browser and is never uploaded.

## Features

- **Photo or camera**: upload or drag in a photo, or take one with your device camera.
- **Three light types**:
  - **Spot / bulb**: click anywhere to place a point light in front of the scene.
  - **Backlight box**: drag a rectangle over a TV, mirror or headboard, and light spills out from behind its edges.
  - **Backlight freehand**: draw around any shape (an arch mirror, a plant, a curved headboard) for an outline glow.
- **Per-light controls**: colour, intensity and size/spread.
- **Animated backlights**: static, flowing rainbow, or a flowing colour chase, at an adjustable speed.
- **Scene controls**: *Room darkness* dims the photo and *Bloom* controls how much visible glow shows.
- **Export**: save the lit photo as a PNG, or **save the light only** as a transparent PNG to layer over the photo in another editor (Screen/Add blend).

## Usage

Open `index.html` in a modern browser. Click a light to select it and drag to move it. `Delete` removes the selected light.

## Example: LED strip behind a TV

1. Take a photo of your living room wall with the TV on it, then drop it onto the page.
2. Set **Room darkness** to about `0.75` to simulate evening.
3. Choose **Backlight box** and drag a rectangle exactly over the TV.
4. With that light selected, set **Colour** to a cool blue (`#4da3ff`) and **Size / spread** to `250`. Light now glows out from behind the TV onto the wall, and the TV itself stays dark.
5. Want the gaming-setup look? Set **Effect** to *Flowing rainbow* and **Flow speed** to `1.5`.
6. Add a warm reading lamp: choose **Spot / bulb**, set colour `#ffcf8a`, and click next to the sofa.
7. Click **Save PNG** to get `lit-photo.png` to share, or **Save light only** for a transparent overlay.
