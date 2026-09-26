# Raycast themes for Alfred

Raycast Light and Raycast Dark, Alfred 5 themes by Logan Savage, modeled on
Raycast's launcher. Adapted from Signynt's
[Raycast Light](https://www.packal.org/theme/raycast-light) theme on Packal.

| File | Look |
| --- | --- |
| `Raycast Light.alfredappearance` | Light frosted glass, soft off-white tint, black text |
| `Raycast Dark.alfredappearance` | Dark frosted glass, black tint, white text |

Both share the same layout:

- Native macOS frosted glass
- 700pt-wide window, 24pt corners, borderless search field
- Set in [Inter](https://rsms.me/inter/) throughout
- Rows with 30pt icons, 14pt text, 11pt subtext
- Rounded pill (12pt corners) for the selected result
- Neutral black and white tints only, no accent colors

## Install

The themes use the Inter font. Install it first (free from
[rsms.me/inter](https://rsms.me/inter/) or `brew install --cask font-inter`),
otherwise Alfred falls back to a default font.

**Easiest: import link.** Copy one of these, paste it into Safari's address
bar on your Mac, and press Return. Alfred asks to import the theme.

Raycast Light:

```
alfred://theme/?t=eyJhbGZyZWR0aGVtZSI6eyJyZXN1bHQiOnsidGV4dFNwYWNpbmciOjgsInN1YnRleHQiOnsic2l6ZSI6MTEsImNvbG9yU2VsZWN0ZWQiOiIjMDAwMDAwQTUiLCJmb250IjoiSW50ZXIiLCJjb2xvciI6IiMwMDAwMDBBNSJ9LCJzaG9ydGN1dCI6eyJzaXplIjoxNCwiY29sb3JTZWxlY3RlZCI6IiNGRkZGRkZGRiIsImZvbnQiOiJJbnRlciIsImNvbG9yIjoiIzAwMDAwMEE1In0sImJhY2tncm91bmRTZWxlY3RlZCI6IiMwMDAwMDAxOSIsInRleHQiOnsic2l6ZSI6MTQsImNvbG9yU2VsZWN0ZWQiOiIjMDAwMDAwRkYiLCJmb250IjoiSW50ZXIiLCJjb2xvciI6IiMwMDAwMDBFNCJ9LCJpY29uUGFkZGluZ0hvcml6b250YWwiOjEyLCJyb3VuZG5lc3MiOjEyLCJwYWRkaW5nVmVydGljYWwiOjYsImljb25TaXplIjozMH0sInNlYXJjaCI6eyJiYWNrZ3JvdW5kU2VsZWN0ZWQiOiIjMDAwMDAwMjYiLCJwYWRkaW5nSG9yaXpvbnRhbCI6Nywic3BhY2luZyI6OSwidGV4dCI6eyJzaXplIjoyMCwiY29sb3JTZWxlY3RlZCI6IiMwMDAwMDBGRiIsImZvbnQiOiJJbnRlciIsImNvbG9yIjoiIzAwMDAwMEZGIn0sImJhY2tncm91bmQiOiIjRjhGOEY4MDAiLCJyb3VuZG5lc3MiOjgsInBhZGRpbmdWZXJ0aWNhbCI6MTB9LCJ3aW5kb3ciOnsiY29sb3IiOiIjRjhGOEY4NkIiLCJwYWRkaW5nSG9yaXpvbnRhbCI6MTAsIndpZHRoIjo3MDAsImJvcmRlclBhZGRpbmciOjAsImJvcmRlckNvbG9yIjoiIzAwMDAwMDdGIiwiYmx1ciI6MCwicm91bmRuZXNzIjoyNCwicGFkZGluZ1ZlcnRpY2FsIjoxMn0sImNyZWRpdCI6IkxvZ2FuIFNhdmFnZSIsInZpc3VhbEVmZmVjdE1vZGUiOjEsInNlcGFyYXRvciI6eyJjb2xvciI6IiNDQkNCQ0JGMyIsInRoaWNrbmVzcyI6MH0sInNjcm9sbGJhciI6eyJjb2xvciI6IiMwMDAwMDA1OSIsInRoaWNrbmVzcyI6Nn0sIm5hbWUiOiJSYXljYXN0IExpZ2h0In19
```

Raycast Dark:

```
alfred://theme/?t=eyJhbGZyZWR0aGVtZSI6eyJyZXN1bHQiOnsidGV4dFNwYWNpbmciOjgsInN1YnRleHQiOnsic2l6ZSI6MTEsImNvbG9yU2VsZWN0ZWQiOiIjRkZGRkZGQTUiLCJmb250IjoiSW50ZXIiLCJjb2xvciI6IiNGRkZGRkZBNSJ9LCJzaG9ydGN1dCI6eyJzaXplIjoxNCwiY29sb3JTZWxlY3RlZCI6IiNGRkZGRkZGRiIsImZvbnQiOiJJbnRlciIsImNvbG9yIjoiI0ZGRkZGRkE1In0sImJhY2tncm91bmRTZWxlY3RlZCI6IiMwMDAwMDAzMCIsInRleHQiOnsic2l6ZSI6MTQsImNvbG9yU2VsZWN0ZWQiOiIjRkZGRkZGRkYiLCJmb250IjoiSW50ZXIiLCJjb2xvciI6IiNGRkZGRkZFNCJ9LCJpY29uUGFkZGluZ0hvcml6b250YWwiOjEyLCJyb3VuZG5lc3MiOjEyLCJwYWRkaW5nVmVydGljYWwiOjYsImljb25TaXplIjozMH0sInNlYXJjaCI6eyJiYWNrZ3JvdW5kU2VsZWN0ZWQiOiIjMDAwMDAwNjYiLCJwYWRkaW5nSG9yaXpvbnRhbCI6Nywic3BhY2luZyI6OSwidGV4dCI6eyJzaXplIjoyMCwiY29sb3JTZWxlY3RlZCI6IiNGRkZGRkZGRiIsImZvbnQiOiJJbnRlciIsImNvbG9yIjoiI0ZGRkZGRkZGIn0sImJhY2tncm91bmQiOiIjMDAwMDAwMDAiLCJyb3VuZG5lc3MiOjgsInBhZGRpbmdWZXJ0aWNhbCI6MTB9LCJ3aW5kb3ciOnsiY29sb3IiOiIjMDAwMDAwNjYiLCJwYWRkaW5nSG9yaXpvbnRhbCI6MTAsIndpZHRoIjo3MDAsImJvcmRlclBhZGRpbmciOjAsImJvcmRlckNvbG9yIjoiIzAwMDAwMDdGIiwiYmx1ciI6MCwicm91bmRuZXNzIjoyNCwicGFkZGluZ1ZlcnRpY2FsIjoxMn0sImNyZWRpdCI6IkxvZ2FuIFNhdmFnZSIsInZpc3VhbEVmZmVjdE1vZGUiOjIsInNlcGFyYXRvciI6eyJjb2xvciI6IiNDQkNCQ0JGMyIsInRoaWNrbmVzcyI6MH0sInNjcm9sbGJhciI6eyJjb2xvciI6IiMwMDAwMDA1OSIsInRoaWNrbmVzcyI6Nn0sIm5hbWUiOiJSYXljYXN0IERhcmsifX0=
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
