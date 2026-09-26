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
- 700pt-wide window, 24pt corners, even 12pt padding, borderless search field
  aligned with the icon column
- Set in [Inter](https://rsms.me/inter/) throughout
- Rows with 30pt icons, 13pt text, 11pt subtext, 12pt shortcut labels
- Rounded pill (12pt corners) for the selected result, concentric with the
  window corners
- Neutral black and white tints only, no accent colors

## Install

The themes use the Inter font. Install it first (free from
[rsms.me/inter](https://rsms.me/inter/) or `brew install --cask font-inter`),
otherwise Alfred falls back to a default font.

**Easiest: import link.** Copy one of these, paste it into Safari's address
bar on your Mac, and press Return. Alfred asks to import the theme.

Raycast Light:

```
alfred://theme/?t=eyJhbGZyZWR0aGVtZSI6eyJyZXN1bHQiOnsidGV4dFNwYWNpbmciOjgsInN1YnRleHQiOnsic2l6ZSI6MTEsImNvbG9yU2VsZWN0ZWQiOiIjMDAwMDAwQTUiLCJmb250IjoiSW50ZXIiLCJjb2xvciI6IiMwMDAwMDBBNSJ9LCJzaG9ydGN1dCI6eyJzaXplIjoxMiwiY29sb3JTZWxlY3RlZCI6IiNGRkZGRkZGRiIsImZvbnQiOiJJbnRlciIsImNvbG9yIjoiIzAwMDAwMEE1In0sImJhY2tncm91bmRTZWxlY3RlZCI6IiMwMDAwMDAxOSIsInRleHQiOnsic2l6ZSI6MTMsImNvbG9yU2VsZWN0ZWQiOiIjMDAwMDAwRkYiLCJmb250IjoiSW50ZXIiLCJjb2xvciI6IiMwMDAwMDBFNCJ9LCJpY29uUGFkZGluZ0hvcml6b250YWwiOjEyLCJyb3VuZG5lc3MiOjEyLCJwYWRkaW5nVmVydGljYWwiOjYsImljb25TaXplIjozMH0sInNlYXJjaCI6eyJiYWNrZ3JvdW5kU2VsZWN0ZWQiOiIjMDAwMDAwMjYiLCJwYWRkaW5nSG9yaXpvbnRhbCI6MTIsInNwYWNpbmciOjksInRleHQiOnsic2l6ZSI6MjAsImNvbG9yU2VsZWN0ZWQiOiIjMDAwMDAwRkYiLCJmb250IjoiSW50ZXIiLCJjb2xvciI6IiMwMDAwMDBGRiJ9LCJiYWNrZ3JvdW5kIjoiI0Y4RjhGODAwIiwicm91bmRuZXNzIjo4LCJwYWRkaW5nVmVydGljYWwiOjEwfSwid2luZG93Ijp7ImNvbG9yIjoiI0Y4RjhGODZCIiwicGFkZGluZ0hvcml6b250YWwiOjEyLCJ3aWR0aCI6NzAwLCJib3JkZXJQYWRkaW5nIjowLCJib3JkZXJDb2xvciI6IiMwMDAwMDA3RiIsImJsdXIiOjAsInJvdW5kbmVzcyI6MjQsInBhZGRpbmdWZXJ0aWNhbCI6MTJ9LCJjcmVkaXQiOiJMb2dhbiBTYXZhZ2UiLCJ2aXN1YWxFZmZlY3RNb2RlIjoxLCJzZXBhcmF0b3IiOnsiY29sb3IiOiIjQ0JDQkNCRjMiLCJ0aGlja25lc3MiOjB9LCJzY3JvbGxiYXIiOnsiY29sb3IiOiIjMDAwMDAwNTkiLCJ0aGlja25lc3MiOjZ9LCJuYW1lIjoiUmF5Y2FzdCBMaWdodCJ9fQ==
```

Raycast Dark:

```
alfred://theme/?t=eyJhbGZyZWR0aGVtZSI6eyJyZXN1bHQiOnsidGV4dFNwYWNpbmciOjgsInN1YnRleHQiOnsic2l6ZSI6MTEsImNvbG9yU2VsZWN0ZWQiOiIjRkZGRkZGQTUiLCJmb250IjoiSW50ZXIiLCJjb2xvciI6IiNGRkZGRkZBNSJ9LCJzaG9ydGN1dCI6eyJzaXplIjoxMiwiY29sb3JTZWxlY3RlZCI6IiNGRkZGRkZGRiIsImZvbnQiOiJJbnRlciIsImNvbG9yIjoiI0ZGRkZGRkE1In0sImJhY2tncm91bmRTZWxlY3RlZCI6IiMwMDAwMDAzMCIsInRleHQiOnsic2l6ZSI6MTMsImNvbG9yU2VsZWN0ZWQiOiIjRkZGRkZGRkYiLCJmb250IjoiSW50ZXIiLCJjb2xvciI6IiNGRkZGRkZFNCJ9LCJpY29uUGFkZGluZ0hvcml6b250YWwiOjEyLCJyb3VuZG5lc3MiOjEyLCJwYWRkaW5nVmVydGljYWwiOjYsImljb25TaXplIjozMH0sInNlYXJjaCI6eyJiYWNrZ3JvdW5kU2VsZWN0ZWQiOiIjMDAwMDAwNjYiLCJwYWRkaW5nSG9yaXpvbnRhbCI6MTIsInNwYWNpbmciOjksInRleHQiOnsic2l6ZSI6MjAsImNvbG9yU2VsZWN0ZWQiOiIjRkZGRkZGRkYiLCJmb250IjoiSW50ZXIiLCJjb2xvciI6IiNGRkZGRkZGRiJ9LCJiYWNrZ3JvdW5kIjoiIzAwMDAwMDAwIiwicm91bmRuZXNzIjo4LCJwYWRkaW5nVmVydGljYWwiOjEwfSwid2luZG93Ijp7ImNvbG9yIjoiIzAwMDAwMDY2IiwicGFkZGluZ0hvcml6b250YWwiOjEyLCJ3aWR0aCI6NzAwLCJib3JkZXJQYWRkaW5nIjowLCJib3JkZXJDb2xvciI6IiMwMDAwMDA3RiIsImJsdXIiOjAsInJvdW5kbmVzcyI6MjQsInBhZGRpbmdWZXJ0aWNhbCI6MTJ9LCJjcmVkaXQiOiJMb2dhbiBTYXZhZ2UiLCJ2aXN1YWxFZmZlY3RNb2RlIjoyLCJzZXBhcmF0b3IiOnsiY29sb3IiOiIjQ0JDQkNCRjMiLCJ0aGlja25lc3MiOjB9LCJzY3JvbGxiYXIiOnsiY29sb3IiOiIjMDAwMDAwNTkiLCJ0aGlja25lc3MiOjZ9LCJuYW1lIjoiUmF5Y2FzdCBEYXJrIn19
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
