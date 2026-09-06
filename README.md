# Zamorak Cue Board (Alt1)

Big on-screen visual cues for Zamorak, Lord of Chaos (especially 500%+ enrage).

## What it does

- Large coloured banners appear over the game when a mechanic is called.
- Manual buttons (or number keys 1–8) for instant cues.
- Auto mode that watches for the classic chat trigger phrases (best-effort).
- Designed to sit next to AfkWarden (Igor’s presets) – voice from AfkWarden + big visual text from this board.

## Key cues

| Key | Banner                  | Trigger text (chat)              | What to do                                      |
|-----|-------------------------|----------------------------------|-------------------------------------------------|
| 1   | STUN HIM NOW            | I will tear you asunder!         | Freedom/Anticipation → Stun                    |
| 2   | SLAM / DEBILITATE       | This world will burn             | Pray Melee, walk under, Debilitate              |
| 3   | CAGE – PRAY MAGE        | CHAOS, UNFETTERED!               | Pray Mage + Debilitate / Devotion               |
| 4   | CURL UP – RESONATE      | FEEL THE RAGE OF A GOD           | Equip shield + Resonate                         |
| 5   | INFERNUS                | Step into the dark…              | Match rune → Stun → finish demon (all on rune @500%+) |
| 6   | CHANNELER / WITCH       | HEED MY CALL!                    | Go kill the witch (starts Asphyxiate @500%+)    |
| 7   | RUNE SMOKE              | You're already dead.             | Anticipate / Freedom over black smoke           |
| 8   | DEFENSIVE               | (manual)                         | Debilitate / Reflect / Devotion / Protect       |

## How to install

1. Make sure Alt1 Toolkit is installed (https://runeapps.org/alt1).
2. Copy the whole `zamorak-cue` folder somewhere permanent (e.g. Documents).
3. In Alt1:
   - Right-click the Alt1 icon → **Add app**
   - Point it at the `appconfig.json` file inside the folder
   - Or open the folder in the Alt1 browser and click “Add app”
4. Grant **Pixel** and **Overlay** permissions when prompted (right-click the app → Permissions).

### Local file tip
If Alt1 complains about local files, relaunch Alt1 with the launch option:
```
--allow-file-access-from-files
```

## Recommended combo for 500%+

1. Load Igor’s Zamorak preset in **AfkWarden** (voice call-outs).
2. Keep this Cue Board open for the big visual banners.
3. When you hear the voice / see the chat line, either:
   - Let auto-read fire the banner, or
   - Just press the matching number key.

## 500%+ specifics this board already covers

- Channeler starts with **Asphyxiate** (banner reminds you).
- Infernus exit requires **everyone on their rune at the same time**.
- The core loop (stun, slam, cage, curl, demons, runes) is the same as lower enrage.

## Tips

- Keep chat timestamps on.
- Chat font size 12 works best.
- Interface scaling 100%.
- You can drag the app window wherever is convenient; the banners appear in the middle of the game screen regardless.

Enjoy the climb to 1000% for the combat blessing!
