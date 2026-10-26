# Dream Villa VR

**Live demo: [pscsc220024.vercel.app](https://pscsc220024.vercel.app/Examination/)**

An interactive 3D walkthrough of a modern villa that runs in the browser, on desktop, phone or a VR headset. Built with A-Frame (WebXR) as a Computer Graphics practical project at the University of Cape Coast.

## What's in the scene
- A furnished villa: bed, wardrobe, couch, armchair, TV, chandeliers, air conditioner and glass doors
- Outdoor compound with a gate, trees, a parked car and a swimming pool with animated water
- Animated characters: walking security guards and a dog
- Realistic textures for walls, laminate floors, paving, grass and pool tiles
- Day lighting with directional and ambient lights, plus an aerial camera

## Controls
- **W A S D** or arrow keys to walk, **mouse drag** to look around
- On a phone, drag to look; on a VR headset, click **VR** in the corner

## Challenges I solved
- **Flickering wall textures:** fixed by adjusting material sides and removing overlapping faces
- **Gate models not showing:** loaded the GLB models through A-Frame's asset manager with corrected scale and position
- **Water motion:** simulated with opacity, a moving texture and plane animation
- **Slow loading:** reduced model sizes and optimised textures

The full write-up is in [`Examination/Final Practical Quiz Project Report.pdf`](Examination/Final%20Practical%20Quiz%20Project%20Report.pdf).

## Built with
A-Frame · WebXR · JavaScript · HTML · GLB 3D models · Vercel

## Run it locally
The 3D models must be served over HTTP, so open it through a local server rather than double-clicking the file:
```bash
npx serve .
```
Then visit http://localhost:3000/Examination/

By [Bright Akwasi Kodua](https://github.com/KODUAAA)
