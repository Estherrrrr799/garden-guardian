# 🌿 Garden Guardian

### A Two-Player WebAR Puzzle Adventure

English | [简体中文](README_ch.md)

A magical storm has shattered the fairy village. Two guardians follow separate paths through the garden, then reunite to compare star patterns, discuss clues, and restore their home together.

**Garden Guardian** is a browser-based AR game prototype combining physical exploration, distinct player roles, printed materials, and face-to-face collaboration.

👉 **[Open the game](https://estherrrrr799.github.io/garden-guardian/)**

> The full experience requires two players, two phones, four AR marker cards, the game booklet, and the shared constellation reference. Read the game and rune rules before starting.

## ✨ The Experience

**Explore separately, then solve together.** Each player has a different starting point and clues. After reaching the benches, players reunite to consult the shared reference, compare phone screens, and discuss their answer.

| Role | Stage 1: Direction Task | Stage 2: Constellation Task |
|---|---|---|
| Player A — Detective | Pine tree, marker 1 | Left bench, marker 3 |
| Player B — Scout | Dead stump, marker 2 | Right bench, marker 4 |

Both players finish with a rune-ordering challenge at the lawn centre. Marker numbers 1–4 identify scanning locations, not four sequential stages.

## 🎮 Rules and Experience Flow

### 1. Prepare and Choose Roles

Open the game on both phones, allow camera access, and select different roles. Agree on a meeting point near the benches and prepare one constellation sheet for joint viewing.

### 2. Complete Your Direction Tasks

- Player A scans marker 1 at the pine tree and selects a direction using the on-screen clue.
- Player B scans marker 2 at the stump and interprets the storm clue.
- Follow the prompts to your assigned benches.
- Once both direction tasks are complete, record the first rune in the booklet: **🌿 Leaf**.

### 3. Scan at the Benches, Then Solve the Stars Together

1. Player A scans marker 3 at the left bench; Player B scans marker 4 at the right bench.
2. Once both star clues are open, meet at your agreed nearby spot.
3. Describe your star positions, brightness, and patterns first. Then consult the shared reference; you may also compare phone screens.
4. Compare the six constellation candidates. Names and diagrams are presented equally, with no candidate marked as correct.
5. Agree on an answer, then enter the same **English constellation name** on each phone.
6. Wait until both players succeed, record the second rune, **🔮 Crystal Ball**, and head to the lawn centre.

This shared-play format permits joint viewing after reunion. Use on-screen instructions to describe positions as the first discussion step, then compare and reason together using the printed rules.

### 4. Reunite at the Lawn and Complete the Finale

When both players reach the lawn centre, record the third rune: **🍄 Mushroom**. If a final puzzle has already opened on one phone, wait for your partner before submitting.

Recall the order in which you earned the runes, arrange them on each phone, and confirm. The team finishes once both phones show victory.

## 🪄 Rune Rules

Explain these milestones to both players at the briefing. Tick them off in the booklet as your team completes the journey. You may refer back to the record during the finale.

| Milestone | Rune | Story Meaning |
|---|---|---|
| Both players complete their starting direction tasks | 🌿 Leaf | Life returns |
| Both players solve the shared constellation puzzle | 🔮 Crystal Ball | Magic returns |
| Both players arrive at the lawn centre | 🍄 Mushroom | A home is ready to be rebuilt |

These are printed game rules, not features that depend on the phones automatically awarding items or detecting both players' locations.

## ⭐ Energy and Team Progress

- Each phone starts with three energy stars. An incorrect answer removes one star from that phone.
- If stars remain, wait for the on-screen countdown before continuing.
- If one player is still solving or waiting, the other waits and helps with the discussion.
- If either player runs out of stars, restart together under the team rule. Each player uses the replay button or reloads the game.
- The phones track progress separately. Confirm readiness face to face; submissions do not need to be simultaneous.

## 📱 Printing and Site Setup

1. Prepare two camera-equipped phones, an internet connection, and mobile browsers with camera access.
2. Download the three PDFs. Read the booklet together, including the rune rules, before play.
3. Print the AR marker sheet on **A4 at actual size / 100%**. Keep every pattern and frame intact. Protect cards from water and avoid glare.
4. Place the four markers at the labelled locations: pine tree, dead stump, left bench, and right bench.
5. Set a shared-reference meeting point near the benches and a final meeting point at the lawn centre.
6. Start scanning from approximately 30–60 cm away, adjusting distance until the complete marker is clearly visible.

Scan the **images on the AR marker cards**, not ordinary trees or benches, the game booklet, or the constellation reference. The lawn finale needs no additional marker.

## 📂 Supporting Materials

| File | Purpose |
|---|---|
| [AR Marker Cards](Garden%20Guardian%20%E2%80%94%20AR%20Marker%20Cards.pdf) | The four existing marker images, with roles, stages, and placement instructions. |
| [Game Rules and Task Cards — English](Garden%20Guardian%20%E2%80%94%20Game%20Cards%20%28English%29.pdf) | Briefing, exploration routes, reunion instructions, and rune milestone records. |
| [Shared Constellation Reference](Constellation_Reference.pdf) | Both players' clue summaries and six named candidate patterns for joint reasoning. |

The reference supplies candidate names without identifying the correct answer. Its diagrams are simplified game references, not precise astronomical charts.

The four framed marker images are unchanged and continue to use the existing `targets.mind`. This printed-rules update does not require target recompilation.

## 💡 Design Focus

- **Distinct roles:** Different starting points and routes give both players individual tasks.
- **Reunion and discussion:** Independent exploration leads to shared comparison, explanation, and agreement.
- **Environmental storytelling:** Trees, benches, and the lawn become part of the fairy village's story.
- **Physical and digital interaction:** Printed materials provide shared references and journey records; phones provide AR interactions and puzzles.
- **Progress feedback:** Fairy prompts, energy stars, and result screens respond to player actions.

## 🛠 Technology and Repository Files

| Technology / File | Purpose |
|---|---|
| HTML, CSS, and JavaScript | Interface, puzzle interactions, and game logic. |
| MindAR | Image recognition and tracking. |
| A-Frame | AR scene elements and animations. |
| GitHub Pages | Website hosting. |
| `index.html` | Game entry point. |
| `targets.mind` | Compiled targets matching the marker images. |
| `README.md` / `README_ch.md` | English / Chinese documentation. |

## 🔧 Usage Tips

- Camera does not start: Check browser camera permissions, allow access, and reload.
- Marker is not recognised: Confirm you are scanning the matching marker and adjust lighting, angle, and distance.
- No task appears: Check that the marker matches your current role and stage.
- Players are at different stages: Wait for your partner to complete the current task before continuing together.

## 🚧 Project Status

Garden Guardian is a WebAR interactive prototype. The project creator has verified scanning and gameplay progression. Experience across different phones, browsers, and outdoor lighting conditions can be tested and refined further.

The current format uses face-to-face cooperation, shared printed references, and separate confirmation on each phone. Further on-site feedback can guide improvements to material readability, meeting locations, and puzzle difficulty.
