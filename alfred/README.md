# Raycast themes for Alfred

Raycast Light and Raycast Dark, Alfred 5 themes modeled on Raycast's launcher.
They're customized versions of Signynt's themes, originally published on
[Packal](https://www.packal.org/theme/raycast-light), with roomier spacing,
larger icons, and rounder corners.

| File | Look |
| --- | --- |
| `Raycast Light.alfredappearance` | Light frosted glass, soft off-white tint, black text |
| `Raycast Dark.alfredappearance` | Dark frosted glass, black tint, white text, slate-blue selection |

Both share the same layout:

- Native macOS frosted glass
- 700pt-wide window, 24pt corners, borderless search field
- Rows with 28pt icons, 14pt system font, small gray subtext
- Rounded pill (12pt corners) for the selected result

## Install

**Easiest: import link.** Copy one of these, paste it into Safari's address
bar on your Mac, and press Return. Alfred asks to import the theme.

Raycast Light:

```
alfred://theme/?t=eyJhbGZyZWR0aGVtZSI6eyJyZXN1bHQiOnsidGV4dFNwYWNpbmciOjUsInN1YnRleHQiOnsic2l6ZSI6MTAsImNvbG9yU2VsZWN0ZWQiOiIjMDAwMDAwNjYiLCJmb250IjoiU3lzdGVtIiwiY29sb3IiOiIjMDAwMDAwNjYifSwic2hvcnRjdXQiOnsic2l6ZSI6MTQsImNvbG9yU2VsZWN0ZWQiOiIjRkZGRkZGRkYiLCJmb250IjoiU3lzdGVtIiwiY29sb3IiOiIjNTY1MTU0RTIifSwiYmFja2dyb3VuZFNlbGVjdGVkIjoiIzAwMDAwMDE5IiwidGV4dCI6eyJzaXplIjoxNCwiY29sb3JTZWxlY3RlZCI6IiMwMDAwMDBGRiIsImZvbnQiOiJTeXN0ZW0iLCJjb2xvciI6IiMwMDAwMDBFNCJ9LCJpY29uUGFkZGluZ0hvcml6b250YWwiOjEyLCJyb3VuZG5lc3MiOjEyLCJwYWRkaW5nVmVydGljYWwiOjYsImljb25TaXplIjoyOH0sInNlYXJjaCI6eyJiYWNrZ3JvdW5kU2VsZWN0ZWQiOiIjQTdDNEU4RkYiLCJwYWRkaW5nSG9yaXpvbnRhbCI6Nywic3BhY2luZyI6OSwidGV4dCI6eyJzaXplIjoyMCwiY29sb3JTZWxlY3RlZCI6IiMwMDAwMDBGRiIsImZvbnQiOiJTeXN0ZW0iLCJjb2xvciI6IiMwMDAwMDBGRiJ9LCJiYWNrZ3JvdW5kIjoiI0Y4RjhGODAwIiwicm91bmRuZXNzIjo4LCJwYWRkaW5nVmVydGljYWwiOjEwfSwid2luZG93Ijp7ImNvbG9yIjoiI0Y4RjhGODZCIiwicGFkZGluZ0hvcml6b250YWwiOjEwLCJ3aWR0aCI6NzAwLCJib3JkZXJQYWRkaW5nIjowLCJib3JkZXJDb2xvciI6IiMwMDAwMDA3RiIsImJsdXIiOjAsInJvdW5kbmVzcyI6MjQsInBhZGRpbmdWZXJ0aWNhbCI6MTJ9LCJjcmVkaXQiOiJTaWdueW50IiwidmlzdWFsRWZmZWN0TW9kZSI6MSwic2VwYXJhdG9yIjp7ImNvbG9yIjoiI0NCQ0JDQkYzIiwidGhpY2tuZXNzIjowfSwic2Nyb2xsYmFyIjp7ImNvbG9yIjoiIzNCNDY1RjcxIiwidGhpY2tuZXNzIjo0fSwibmFtZSI6IlJheWNhc3QgTGlnaHQifX0=
```

Raycast Dark:

```
alfred://theme/?t=eyJhbGZyZWR0aGVtZSI6eyJyZXN1bHQiOnsidGV4dFNwYWNpbmciOjUsInN1YnRleHQiOnsic2l6ZSI6MTAsImNvbG9yU2VsZWN0ZWQiOiIjRkZGRkZGNjYiLCJmb250IjoiU3lzdGVtIiwiY29sb3IiOiIjRkZGRkZGNjYifSwic2hvcnRjdXQiOnsic2l6ZSI6MTQsImNvbG9yU2VsZWN0ZWQiOiIjRkZGRkZGRkYiLCJmb250IjoiU3lzdGVtIiwiY29sb3IiOiIjNTY1MTU0RTIifSwiYmFja2dyb3VuZFNlbGVjdGVkIjoiIzdCODlBNjMwIiwidGV4dCI6eyJzaXplIjoxNCwiY29sb3JTZWxlY3RlZCI6IiNGRkZGRkZGRiIsImZvbnQiOiJTeXN0ZW0iLCJjb2xvciI6IiNGRkZGRkZFNCJ9LCJpY29uUGFkZGluZ0hvcml6b250YWwiOjEyLCJyb3VuZG5lc3MiOjEyLCJwYWRkaW5nVmVydGljYWwiOjYsImljb25TaXplIjoyOH0sInNlYXJjaCI6eyJiYWNrZ3JvdW5kU2VsZWN0ZWQiOiIjQTdDNEU4RkYiLCJwYWRkaW5nSG9yaXpvbnRhbCI6Nywic3BhY2luZyI6OSwidGV4dCI6eyJzaXplIjoyMCwiY29sb3JTZWxlY3RlZCI6IiMwMDAwMDBGRiIsImZvbnQiOiJTeXN0ZW0iLCJjb2xvciI6IiNGRkZGRkZGRiJ9LCJiYWNrZ3JvdW5kIjoiIzdCODlBNjAwIiwicm91bmRuZXNzIjo4LCJwYWRkaW5nVmVydGljYWwiOjEwfSwid2luZG93Ijp7ImNvbG9yIjoiIzAwMDAwMDY2IiwicGFkZGluZ0hvcml6b250YWwiOjEwLCJ3aWR0aCI6NzAwLCJib3JkZXJQYWRkaW5nIjowLCJib3JkZXJDb2xvciI6IiMwMDAwMDA3RiIsImJsdXIiOjAsInJvdW5kbmVzcyI6MjQsInBhZGRpbmdWZXJ0aWNhbCI6MTJ9LCJjcmVkaXQiOiJTaWdueW50IiwidmlzdWFsRWZmZWN0TW9kZSI6Miwic2VwYXJhdG9yIjp7ImNvbG9yIjoiI0NCQ0JDQkYzIiwidGhpY2tuZXNzIjowfSwic2Nyb2xsYmFyIjp7ImNvbG9yIjoiIzNCNDY1RjcxIiwidGhpY2tuZXNzIjo0fSwibmFtZSI6IlJheWNhc3QgRGFyayJ9fQ==
```

**Or from the file.** Open the `.alfredappearance` file on GitHub and click
the **Download raw file** button (↓). Check the saved name ends in exactly
`.alfredappearance`; some browsers add `.txt` or `.json`, which stops Alfred
from recognizing it. Then double-click it, and Alfred opens
**Preferences → Appearance** with the theme added.

To follow macOS light/dark mode, install both and pick one for each mode in
**Appearance → Options**.

## Match Raycast more closely

A theme only controls colors, fonts, and spacing. In **Appearance → Options**
you can also hide the hat, the menu icon, and the `⌘1`–`⌘9` result shortcuts.
Raycast's bottom action bar, "Results" header, and right-aligned type labels
can't be reproduced with an Alfred theme.
