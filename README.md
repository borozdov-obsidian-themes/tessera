# Borozdov Tessera

A theme from the Borozdov collection. Two faces — light **Paperwhite**, a research console
on white paper, and dark **Deepfield**, the same console on a midnight-ink band. Black type,
square 4px corners, monospace labels and flat pastel tiles for callouts; a periwinkle marks
what is active.

![Borozdov Tessera in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/tessera/main/screenshots/light.png)

![Borozdov Tessera in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/tessera/main/screenshots/dark.png)

## Principles

- **Hierarchy by weight and size, never by colour.** Headings are black, in the platform's
  sans at 500 with tight tracking; text is 400.
- **A mono voice for the machinery.** IBM Plex Mono sets callout labels, table headers,
  tags, property names, buttons, the status bar and code, in small tracked capitals where
  it labels something.
- **Pastels tag categories.** Each callout type is a flat tile in its own pastel: sky,
  mint, peach, blush, lilac. By night the pastel is mixed low into the page and the label
  takes the pastel.
- **Square and flat.** 4px corners on every card, button, badge and field; no shadows on
  the page. The periwinkle is punctuation only: link underlines, ticks, toggles, the
  quote rule and the highlighter.
- **A midnight band, not black.** Deepfield is midnight ink with white type, the one dark
  band of the system turned into a whole face.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as flat pastel tiles with a monospace label
- Links in black on a periwinkle underline that turns black under the pointer
- Tags as monospace category badges behind a hairline
- Buttons in monospace capitals: ghosts behind a hairline, the main one solid black by
  day and white by night
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory:** Settings → Appearance → Themes → Manage, search for
**Borozdov Tessera**, then **Install and use**.

**By hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/tessera/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Tessera/`, then choose Borozdov Tessera under
Settings → Appearance → Themes.

## Font

IBM Plex Mono Regular (© 2017 IBM Corp.) is embedded in `theme.css` as base64 WOFF2 under
the SIL Open Font License 1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). One weight, Latin
and Cyrillic, for labels, tags, buttons and code.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Белая бумага» —
исследовательская консоль на белой бумаге, и тёмный «Глубокое поле» — та же консоль на
полосе полуночных чернил. Чёрный текст, прямые углы 4px, моноширинные подписи
(IBM Plex Mono) и плоские пастельные плитки для колаутов; барвинковый цвет отмечает
активное. Устанавливается из каталога: Настройки → Оформление → Темы → Настроить →
Borozdov Tessera → Установить и применить.
