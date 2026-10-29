# Unit 5 Review · Analytic Geometry

Grade 10 math (MPM2D) review for Unit 5: lessons L1–L8 (analytic geometry) and L9–L10 (similar triangles).

| Page | Folder | What it is |
|---|---|---|
| Landing page | `unit5/` | Links to the practice page and the game |
| Unit 5 Practice | `unit5/practice/` | New questions for every lesson at three levels, with hints and worked steps |
| Where in Ottawa? | `unit5/magpie/` | Review game: a detective chase across Ottawa with two reading checkpoints and hand-in codes |

Address once uploaded: `https://USERNAME.github.io/g10/unit5/`

## Adding this unit to the site

1. In the `g10` repository on GitHub, choose **Add file → Upload files**.
2. Drag the whole `unit5` folder in and commit.
3. Add a Unit 5 row to the root `README.md`.

## Hand-in codes

The game's "Hand in my code" button opens the teacher's Google Form with the student's name and code filled in. The link is set in `magpie/index.html` (`const HANDIN_URL = "…"`, near the top of the script). Results are decoded into the "Where in Ottawa? · Results" Google Sheet by the teacher's Apps Script (`WhereInOttawa-HandIn.gs`, kept outside this repository). Teachers can also check any code with **Check a case code** on the game's title screen.

## Privacy

- The pages store nothing about students and send nothing on their own.
- Names typed into the game are only used to make the case code on screen. They're never saved.
- A code is sent only when a student presses Submit on the Google Form.
- The practice page remembers the last skill and level in the browser (localStorage).
- Nothing loads from outside this folder; fonts are local.

## Fonts

| Font | Used for | Licence |
|---|---|---|
| Atkinson Hyperlegible | body text and all numbers | SIL Open Font License 1.1 |
| Kalam | practice page "pen" and headings | SIL Open Font License 1.1 |
| Alfa Slab One | game titles | SIL Open Font License 1.1 |
| Special Elite | short labels in the game | Apache License 2.0 |

Latin-subset WOFF files from Fontsource. Licence texts are in `fonts/licenses/`.
