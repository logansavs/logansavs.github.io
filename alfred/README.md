# Raycast themes for Alfred

Raycast Light and Raycast Dark, Alfred 5 themes modeled on Raycast's launcher,
by Signynt, originally published on
[Packal](https://www.packal.org/theme/raycast-light). Packal is archived, so
copies are kept here.

| File | Look |
| --- | --- |
| `Raycast Light.alfredappearance` | Light frosted glass, soft off-white tint, black text |
| `Raycast Dark.alfredappearance` | Dark frosted glass, black tint, white text, slate-blue selection |

Both share the same layout:

- Native macOS frosted glass
- 700pt-wide window, 10pt corners, borderless search field
- Compact rows: 19pt icons, 15pt system font, small gray subtext
- Rounded gray pill (8pt corners) for the selected result

## Install

**Easiest: import link.** Copy one of these, paste it into Safari's address
bar on your Mac, and press Return. Alfred asks to import the theme.

Raycast Light:

```
alfred://theme/?t=eyJhbGZyZWR0aGVtZSI6eyJyZXN1bHQiOnsidGV4dFNwYWNpbmciOjUsInN1YnRleHQiOnsic2l6ZSI6MTAsImNvbG9yU2VsZWN0ZWQiOiIjMDAwMDAwNjYiLCJmb250IjoiU3lzdGVtIiwiY29sb3IiOiIjMDAwMDAwNjYifSwic2hvcnRjdXQiOnsic2l6ZSI6MTYsImNvbG9yU2VsZWN0ZWQiOiIjRkZGRkZGRkYiLCJmb250IjoiU3lzdGVtIiwiY29sb3IiOiIjNTU2MDdGRTQifSwiYmFja2dyb3VuZFNlbGVjdGVkIjoiIzAwMDAwMDE5IiwidGV4dCI6eyJzaXplIjoxNSwiY29sb3JTZWxlY3RlZCI6IiMwMDAwMDBGRiIsImZvbnQiOiJTeXN0ZW0iLCJjb2xvciI6IiMwMDAwMDBFNCJ9LCJpY29uUGFkZGluZ0hvcml6b250YWwiOjEwLCJyb3VuZG5lc3MiOjgsInBhZGRpbmdWZXJ0aWNhbCI6NSwiaWNvblNpemUiOjE5fSwic2VhcmNoIjp7ImJhY2tncm91bmRTZWxlY3RlZCI6IiNBN0M0RThGRiIsInBhZGRpbmdIb3Jpem9udGFsIjo3LCJzcGFjaW5nIjo5LCJ0ZXh0Ijp7InNpemUiOjIwLCJjb2xvclNlbGVjdGVkIjoiIzAwMDAwMEZGIiwiZm9udCI6IlN5c3RlbSIsImNvbG9yIjoiIzAwMDAwMEZGIn0sImJhY2tncm91bmQiOiIjRjhGOEY4MDAiLCJyb3VuZG5lc3MiOjgsInBhZGRpbmdWZXJ0aWNhbCI6Nn0sIndpbmRvdyI6eyJjb2xvciI6IiNGOEY4Rjg2QiIsInBhZGRpbmdIb3Jpem9udGFsIjo1LCJ3aWR0aCI6NzAwLCJib3JkZXJQYWRkaW5nIjowLCJib3JkZXJDb2xvciI6IiMwMDAwMDA3RiIsImJsdXIiOjAsInJvdW5kbmVzcyI6MTAsInBhZGRpbmdWZXJ0aWNhbCI6NX0sImNyZWRpdCI6IlNpZ255bnQiLCJ2aXN1YWxFZmZlY3RNb2RlIjoxLCJzZXBhcmF0b3IiOnsiY29sb3IiOiIjQ0JDQkNCRjMiLCJ0aGlja25lc3MiOjB9LCJzY3JvbGxiYXIiOnsiY29sb3IiOiIjM0I0NjVGNzEiLCJ0aGlja25lc3MiOjR9LCJuYW1lIjoiUmF5Y2FzdCBMaWdodCJ9fQ==
```

Raycast Dark:

```
alfred://theme/?t=eyJhbGZyZWR0aGVtZSI6eyJyZXN1bHQiOnsidGV4dFNwYWNpbmciOjUsInN1YnRleHQiOnsic2l6ZSI6MTAsImNvbG9yU2VsZWN0ZWQiOiIjRkZGRkZGNjYiLCJmb250IjoiU3lzdGVtIiwiY29sb3IiOiIjRkZGRkZGNjYifSwic2hvcnRjdXQiOnsic2l6ZSI6MTYsImNvbG9yU2VsZWN0ZWQiOiIjRkZGRkZGRkYiLCJmb250IjoiU3lzdGVtIiwiY29sb3IiOiIjNTU2MDdGRTQifSwiYmFja2dyb3VuZFNlbGVjdGVkIjoiIzdCODlBNjMwIiwidGV4dCI6eyJzaXplIjoxNSwiY29sb3JTZWxlY3RlZCI6IiNGRkZGRkZGRiIsImZvbnQiOiJTeXN0ZW0iLCJjb2xvciI6IiNGRkZGRkZFNCJ9LCJpY29uUGFkZGluZ0hvcml6b250YWwiOjEwLCJyb3VuZG5lc3MiOjgsInBhZGRpbmdWZXJ0aWNhbCI6NSwiaWNvblNpemUiOjE5fSwic2VhcmNoIjp7ImJhY2tncm91bmRTZWxlY3RlZCI6IiNBN0M0RThGRiIsInBhZGRpbmdIb3Jpem9udGFsIjo3LCJzcGFjaW5nIjo5LCJ0ZXh0Ijp7InNpemUiOjIwLCJjb2xvclNlbGVjdGVkIjoiIzAwMDAwMEZGIiwiZm9udCI6IlN5c3RlbSIsImNvbG9yIjoiI0ZGRkZGRkZGIn0sImJhY2tncm91bmQiOiIjN0I4OUE2MDAiLCJyb3VuZG5lc3MiOjgsInBhZGRpbmdWZXJ0aWNhbCI6Nn0sIndpbmRvdyI6eyJjb2xvciI6IiMwMDAwMDA2NiIsInBhZGRpbmdIb3Jpem9udGFsIjo1LCJ3aWR0aCI6NzAwLCJib3JkZXJQYWRkaW5nIjowLCJib3JkZXJDb2xvciI6IiMwMDAwMDA3RiIsImJsdXIiOjAsInJvdW5kbmVzcyI6MTAsInBhZGRpbmdWZXJ0aWNhbCI6NX0sImNyZWRpdCI6IlNpZ255bnQiLCJ2aXN1YWxFZmZlY3RNb2RlIjoyLCJzZXBhcmF0b3IiOnsiY29sb3IiOiIjQ0JDQkNCRjMiLCJ0aGlja25lc3MiOjB9LCJzY3JvbGxiYXIiOnsiY29sb3IiOiIjM0I0NjVGNzEiLCJ0aGlja25lc3MiOjR9LCJuYW1lIjoiUmF5Y2FzdCBEYXJrIn19
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
