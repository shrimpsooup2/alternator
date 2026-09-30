# GD Alternator Trainer

A single-file browser tool (`index.html`, no dependencies) for learning to **alternate** (two-finger clicking) in Geometry Dash.

- **Path**: 7 levels from basics to "GD Ready". Each test must be passed several times *in a row* to unlock the next level.
- **Learn**: short lessons on setup, finger mechanics, rhythm, speed, endurance, and using it in-game.
- **Practice**: free alternate, sprint, metronome lock, and a tailored daily session.
- **Wave Academy**: an adaptive wave-spam simulator. **Hold to go up, release to go down**; alternating fingers means the wave climbs while either key is down. Physics use values measured from Geometry Dash 2.2 (recorded in `shrimpsooup2/physics-lab`): horizontal speeds 251.16 / 311.58 / 387.42 / 468 / 576 units/s for 0.5x-4x, a 45° normal wave (vertical speed = horizontal speed) and a 63.4° mini wave (2x vertical), 1 block = 30 units, stepped at 240 Hz. Ten corridor types (straight, slope, hold/release diagonals, staircase, slalom, wavy, breathing, funnel, drifting, mixed gauntlets), speed and size portals mid-course, 20 challenges in 5 tiers with star ratings, and custom courses. The HUD shows the CPS the current gap needs and the hold % the current slope needs. A coach diagnoses *why* you crash (double-hits, uneven rhythm, too slow, wrong hold ratio, corner timing, portal changes), tracks flaws across all drills, and builds targeted runs with assists (strict alternation, guide beat) that fade as you improve.
- **Tools**: open-ended CPS tester, metronome, CPS / ms / frame converter.
- **Analysis**: speed, variation, alternation accuracy, L/R balance, drift, on-beat timing; rating, trends, and recommendations.

Open `index.html` in a browser (or serve the folder). Default keys are F and J; rebind them in Settings. Progress is stored in `localStorage`.
