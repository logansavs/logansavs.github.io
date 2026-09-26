# Raycast themes for Alfred

Two Alfred 5 themes modeled on Raycast's launcher: a flat, frosted panel,
a borderless search field with a hairline divider, compact single-line rows,
and a soft gray pill for the selected result (no accent-colored highlight).

| File | Look |
| --- | --- |
| `Raycast Light.alfredappearance` | Light gray frosted glass, near-black text |
| `Raycast Dark.alfredappearance`  | Dark graphite glass, off-white text |

## Install

1. Download a `.alfredappearance` file and double-click it. Alfred opens
   **Preferences → Appearance** and adds the theme to the list.
2. Select it.

## Match Raycast more closely

A theme only controls colors, fonts, and spacing. These Alfred settings get
you the rest of the way:

- **Appearance → Options**: hide the hat and the menu icon, and hide result
  shortcuts (Raycast doesn't show `⌘1`–`⌘9`).
- **Appearance → Options**: hide subtext if you want single-line rows like
  Raycast's.
- **Features → Universal Actions**: Raycast opens its Actions panel with `⌘K`.
  Alfred's equivalent is the result action panel (`→` or `⌘`-return by
  default). Set it to a key you'll remember.
- To follow macOS light/dark mode, install both: Appearance →
  Options lets you pick a separate theme for each mode.

## Limits

Alfred has no persistent action bar at the bottom of the window, no
"Results" section header, and no right-aligned type label ("Application",
"Command"). Those parts of Raycast can't be reproduced with a theme.
