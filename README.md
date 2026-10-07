# Hi, I'm Braden

I'm 14, based in Maryland, USA. I build **[Skynode](https://github.com/bsalsa2/Skynode)**, a low-cost passive sky-tracking sensor: a webcam on a pan-tilt mount, a YOLO model that finds aircraft and birds, a Raspberry Pi Pico that drives the servos, and a logger that records each sighting.

**Website:** [skynode-si.netlify.app](https://skynode-si.netlify.app)

## Where it stands

- **Working in software:** the detection and tracking loop, pan-tilt control, the sighting logger, and a live dashboard. They're covered by 200 automated tests and run on recorded video.
- **Tested on real footage:** the v2 detection model was tested on 43 real videos. It wrongly called 7.5% of frames on real aircraft a drone. v3 is in training.
- **Not built yet:** the physical node. Nothing has run on the real hardware yet, and the project's README says so at the top of its status table.

## What I'm learning

- Computer vision: training and evaluating a detector, and what its false positives teach you
- Control: turning a pixel error into a servo move, and why the gain and deadband matter
- Embedded code: MicroPython on a Pico, and a simple command protocol over Wi-Fi and USB
- CAD for 3D-printed parts
- Writing tests for code that talks to hardware you don't have yet

If you find a bug or have a question about the project, open an issue on the Skynode repo.
