# The Fall of Caine

A pulp noir walkabout in Coquina City, built with three.js. It's a single page with no build step.

**Play:** open `index.html` through any static server, or turn on GitHub Pages for this repo.

## Controls
- **WASD / arrow keys:** walk. With the overhead camera you move as seen on screen; over the shoulder, left and right turn.
- **Click the floor:** send him somewhere.
- **On phones:** drag anywhere to walk (a joystick appears under your thumb). Tap to send him somewhere.
- **Glowing markers:** walk onto one to go through a door or get in your car.
- **C** or the camera button (bottom bar, between music and menu): switch between the overhead and over-the-shoulder cameras.
- **☰** (or M / Esc): open the map of Coquina City, change the camera, pause, set the mood.
- **Map of Coquina City:** the whole city drawn as a gray ink engraving, with the place names on it (where Caine is shows in red). Tap a name: the camera dives down onto it, and a film reel carries you into the scene.
- **Phone** (bottom bar, or **P**): Caine's phone comes up. Tap the screen to open apps and items; drag the trackball to scroll and tap it to click; the back key goes back and the red end key puts the phone away (the green key opens Messages, the menu key goes home). Drag the map to pan, mouse wheel scrolls. Hold it how you like: drag the phone's body to tilt it, pinch (or ctrl + scroll / trackpad pinch) to bring it closer, double tap the body to reset. While the phone is up the view moves into Caine's eyes, so the camera app shows what he sees. Keys work too: arrows / WASD, Enter, Esc. Clicks give a little tick (and a buzz on phones that support it). Messages, Camera (snaps what Caine sees), Notes, Map (shows where you are) and Snake.
- **Music button:** tap to mute, hold to pick a song.
- **Driving:** pick where you're going when you get in the car (**Q** or **E**), then arrow keys / WASD steer.

## The map
Coquina City sits on both sides of Ánimas Bay. **Old Town** (St. Augustine) is on the mainland: the Doorway, the Alley, the Parking lot, the Precinct on Bayshore. **Isla Luz** (a little Puerto Rico) is across the water: the Warehouse at the port, the Cemetery under the fort, El Malecón along the seawall.

Doorway → Alley → Parking lot → Precinct (back door) or your car. The Skyway is the only road across: it always lands at the port (the Warehouse), and trips to the Cemetery carry on up El Malecón. Each side's skyline painting looks across the bay at the other.

## Concept mocks
- [Handheld mocks](mocks/handheld/): Caine's phone, built in three.js. It runs messages, camera, notes, the city map and Snake. (The pocket notebook and folded map are saved in the code for later, as props to view in his office.) Also in the game as **Dev mode**: tap the logo three times quickly, then open ☰.

## Files
- `index.html`: the whole game
- `casemap.html`: the map of Coquina City (opened from ☰)
- `music/`: soundtrack (Theme, Investigate, Intense, Unsure End)
- `mocks/handheld/`: concept mock for the phone, notebook and map
