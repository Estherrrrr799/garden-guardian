# 🌿 Garden Guardian

### A Two-Player WebAR Puzzle Adventure

English | [简体中文](README_ch.md)

A magical storm has shattered the fairy village. Two guardians must follow different paths, uncover hidden clues, and work together to rebuild what was lost.

**Garden Guardian** is a browser-based AR game prototype that combines physical exploration, distinct player roles, printed game materials, and face-to-face collaboration.

👉 **[Open the prototype](https://estherrrrr799.github.io/garden-guardian/)**

> The full experience requires two phones, matching AR marker cards, and supporting game materials. Read the setup instructions below before playing.

## ✨ About the Project

Two players use their own phones, choose different roles, and follow separate routes through the garden:

| Role | Exploration Route | Player Task |
|---|---|---|
| Player A — Detective | Pine tree → Left bench | Interpret clues and describe the information you discover. |
| Player B — Scout | Dead stump → Right bench | Investigate environmental clues and exchange information with your partner. |

Players describe, listen, and reason together to combine their partial clues, before meeting at the centre of the lawn.

The game design includes fairy hints, energy stars, feedback on incorrect answers, and countdown penalties to communicate progress and the consequences of player choices.

## 💡 Design Focus

Garden Guardian explores how AR can encourage players to engage with both a physical place and another person.

- **Distinct roles:** Separate routes give each player an individual exploration task.
- **Complementary information:** Dividing clues between players encourages conversation and collaborative reasoning.
- **Environmental storytelling:** Trees, benches, and the lawn become locations within the adventure.
- **Physical and digital interaction:** Printed cards support the on-site experience, while phones display AR elements and interactive puzzles.
- **Guided exploration:** Fairy hints, progress indicators, and visual feedback help players understand their current task.

## 🎮 Experience Flow

The following describes the intended experience. Follow the current website prompts during play.

### 1. Choose Your Roles

Open the game on two phones, allow camera access, and select Player A and Player B.

### 2. Scan and Explore

Go to your starting location and scan the designated AR marker to reveal story prompts and puzzles. Follow the clues to your assigned bench.

### 3. Exchange Clues

At the benches, describe your star positions and patterns to your partner. Use the constellation reference card to reason through the shared puzzle.

### 4. Meet and Complete the Challenge

Meet at the centre of the lawn, discuss the clues you encountered, and work together on the final rune-sequencing challenge.

Players coordinate face to face and interact with the game on their own devices.

## 📱 Getting Ready

### Devices and Materials

- Two players, each with a camera-equipped smartphone.
- An internet connection and a mobile browser that supports camera access.
- AR marker cards matching the current game version.
- The English game cards and constellation reference card.

### Printing and Site Setup

1. Download the supporting PDFs below.
2. Print the AR marker sheet in colour at full A4 size and cut out the four cards.
3. Protect outdoor cards from water while avoiding glare that obscures the images.
4. Follow the location labels to place the markers at the pine tree, dead stump, left bench, and right bench.
5. Use the centre of the lawn as the final meeting point.
6. Provide the constellation reference card during the constellation puzzle.

Begin scanning from approximately 30–60 cm away, then adjust the distance while keeping the entire marker clearly visible in the camera.

**This project uses image-tracking AR.** The camera must see the designated images matching `targets.mind`; ordinary trees or benches cannot replace the image markers.

## 📂 Supporting Materials

| File | Purpose |
|---|---|
| [AR Marker Cards](Garden%20Guardian%20%E2%80%94%20AR%20Marker%20Cards.pdf) | Four image markers, with printing, placement, and target-compilation instructions. |
| [Game Cards — English](Garden%20Guardian%20%E2%80%94%20Game%20Cards%20%28English%29.pdf) | Story background, game rules, player tasks, and finale instructions. |
| [Constellation Reference Card](Constellation_Reference.pdf) | A sky map, constellation features, and player clue references for the collaborative puzzle. |

**Using the materials:**

- Use the AR marker cards for scanning and the game cards for reading the story and tasks.
- The constellation reference includes names and detailed hints. Open it when you reach the relevant puzzle.
- Players do not need to regenerate `targets.mind`. If the marker images change, the maintainer must update the target file accordingly.

## 🛠 Built With

| Technology | Purpose |
|---|---|
| HTML, CSS, and JavaScript | Interface, puzzle interactions, and game logic. |
| MindAR | Image-target recognition and tracking. |
| A-Frame | AR scene elements and animations. |
| GitHub Pages | Website hosting and online access. |

### Repository Files

- `index.html`: Website entry point containing the interface, AR scene, and game logic.
- `targets.mind`: Compiled image targets loaded by MindAR.
- `README.md`: English project documentation.
- `README_ch.md`: Chinese project documentation.
- Three PDFs: Marker cards, game cards, and constellation reference materials for on-site play.

## 🔧 Scanning and Usage Tips

- **Camera does not start:** Check the browser's camera permissions, allow access, and reload the page.
- **Marker is not recognised:** Confirm that you are using the matching AR marker card. Improve lighting and adjust the camera distance and angle.
- **No task appears after scanning:** Check that the marker matches your current role and stage.
- **You only have the website link:** You can open the prototype's entry screen; the full scanning and puzzle experience requires the supporting materials.

## 🚧 Project Status and Known Limitations

This is an interactive prototype exploring collaborative WebAR gameplay in a physical setting.

- **Material versions need alignment:** The printed materials and website differ in stage numbering and some interaction descriptions. Follow the current website prompts during play.
- **Some effects remain design goals:** Voice clues, synchronised submissions across devices, and village-rebuilding animations described in the printed cards have not all been verified as implemented in the current website.
- **The full experience needs validation:** Mobile compatibility, marker-to-target matching, and the complete on-site journey require further testing.

### Planned Improvements

- Align stage names, rules, and terminology across the website and printed materials.
- Test scanning and gameplay across mobile devices.
- Add gameplay screenshots, a demonstration video, and a site setup diagram.
- Refine hints, puzzle difficulty, and collaboration pacing through player feedback.
