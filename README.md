# ELA Quest — Five Temples Adventure

This version keeps the existing ELA Quest dashboard, practice passages, 6 modes, Guild Market, coins, music, ranks, and writing tools. Only **Quest Adventure** has been redesigned as a five-temple 3D journey.

## Publish to GitHub Pages

1. Extract `ELAQuest_Five_Temples_GitHub.zip`.
2. Open your existing `Streamsintowealth/ELAQuest` repository.
3. Upload the new **`index.html`** to the repository root, replacing the existing `index.html`.
4. Commit. Visit `https://streamsintowealth.github.io/ELAQuest/` once GitHub Pages finishes deploying. Refresh the page if your browser cached the previous version.

This website is self-contained. There is no server, account, or external 3D library to install. A browser that supports WebGL gets the WebGL view; devices blocking WebGL use a rendered software 3D scene instead. The visuals are deliberately stylized low-poly 3D, **not** photorealistic/AAA 3D.

## Controls — Quest Adventure

| Control | Action |
| --- | --- |
| ↑ ↓ ← → / W A S D | Walk around the temple |
| Hold Shift while moving | Sprint, using additional stamina |
| Space | Sword attack when a guardian is close |
| F | Special attack (requires charge, energy, and stamina) |
| Q | Guard and reduce an incoming attack |
| E | Collect a nearby relic, activate a shrine, or enter the cleared temple gate |
| Click **Study & recharge** | Pause exploration to read and answer questions for more resources |

Touchscreen devices display direction and action controls on the adventure scene.

## Five temples

1. **Land Temple:** Explore the forest, recover two earth seals, defeat two stone guardians.
2. **Water Temple:** Find tide pearls, follow the temple bridge, and defeat water sentries. Wading away from the central route costs more energy.
3. **Snow Temple:** Activate three frost beacons and defeat icy enemies. The cold gradually reduces endurance as you travel.
4. **Air Temple:** Activate three sky chimes and defeat sky knights. Wind affects horizontal movement.
5. **Fire Temple:** Recover two fire sigils, defeat the ember guards, then face **the Dragon King**. Lava terrain can reduce life when you leave the safe path.

Defeat enemies and collect every objective to unlock the temple gate. The final stage ends after defeating the Dragon King. Guardians are **computer-controlled opponents**, not other students or online players.

## Reading fuels gameplay

- Correct answers replenish life, energy, stamina and endurance and earn special attack charges.
- Stronger swords are unlocked at reading milestones; equipped Guild gear also boosts attacks.
- When resources are too low, the environment automatically pauses and asks the student to earn more strength through an ELA question.
- The session timer pauses during required study. If play time expires, choose **Continue +5 minutes** to keep the journey. Progress can be resumed from a saved temple checkpoint on the same browser.

## Notes

- Student rewards, Guild inventory, and rankings are stored locally in each browser; rankings compare the student with fictional rivals. There is no real multiplayer mode.
- The original reading content and other game modes have been preserved. No material from the user's reference images has been copied into the website; the screenshots inspired the layout.
- Use the old `index.html` as a backup before uploading this version.
