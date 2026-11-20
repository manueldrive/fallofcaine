# The Fall of Caine

A pulp noir walkabout in Coquina City, built with three.js. It's a single page with no build step.

**Play:** open `index.html` through any static server, or turn on GitHub Pages for this repo.

## Controls
- **WASD / arrow keys:** walk. With the overhead camera you move as seen on screen; over the shoulder, left and right turn.
- **Click the floor:** send him somewhere.
- **On phones:** drag anywhere to walk (a joystick appears under your thumb). Tap to send him somewhere.
- **Glowing markers:** walk onto one to go through a door or get in your car.
- **C** or the camera button (bottom bar, between music and menu): switch between the overhead and over-the-shoulder cameras.
- **☰** (or M / Esc): jump to a location, change the camera, pause, set the mood.
- **Phone** (bottom bar, or **P**): Caine's phone comes up. Arrow keys / WASD move the trackball, Enter clicks, Esc goes back (Esc on the home screen puts it away). Messages, Camera (snaps what Caine sees), Notes, Map (shows where you are) and Snake.
- **Music button:** tap to mute, hold to pick a song.
- **Driving:** arrow keys / WASD steer. Pick a destination with **Q** or **E**.

## The map
Doorway → Alley → Parking lot → Precinct (back door) or your car → drive to the Cemetery or the Warehouse, and from there back to the Precinct.

## Concept mocks
- [Handheld mocks](mocks/handheld/): Caine's phone, built in three.js. It runs messages, camera, notes, the city map and Snake. (The pocket notebook and folded map are saved in the code for later, as props to view in his office.) Also in the game as **Dev mode**: tap the logo three times quickly, then open ☰.

## Files
- `index.html`: the whole game
- `music/`: soundtrack (Theme, Investigate, Intense, Unsure End)
- `mocks/handheld/`: concept mock for the phone, notebook and map
