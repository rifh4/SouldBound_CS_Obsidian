# Soulbound Character Sheet for Obsidian

An interactive, two-page **Age of Sigmar: Soulbound** character sheet for Obsidian, built with the **Meta Bind** community plugin and custom CSS.

The editor fields save their values directly inside the Markdown note, while the graphical character sheet updates automatically.

## Features

- User-friendly character editor inside Obsidian
- Persistent values stored in the note's Properties/frontmatter
- Two-page graphical character sheet
- Identity, attributes, skills, Training, and Focus
- Goals, Connections, Talents, and Natural Awareness
- Combat abilities, Initiative, Mettle, Armour, Toughness, and Wounds
- Attacks, equipment, currency, spells, miracles, background, and notes
- Character portrait support
- Hidden raw Properties panel for a cleaner interface
- No separate custom JavaScript file required
- Background artwork embedded in the CSS snippet

## Requirements

- Obsidian desktop
- The **Meta Bind** community plugin
- The included Markdown note and CSS snippet

## Files

```text
Soulbound Character Sheet - Fully Wired Meta Bind - Fixed v3.md
soulbound-character-sheet-fixed-v3.css
README.md
```

## Installation

### 1. Install Meta Bind

1. Open Obsidian.
2. Go to **Settings → Community plugins**.
3. Enable community plugins if required.
4. Select **Browse**.
5. Search for **Meta Bind**.
6. Install and enable it.

### 2. Install the CSS snippet

Copy:

```text
soulbound-character-sheet-fixed-v3.css
```

into:

```text
Your Vault/.obsidian/snippets/
```

Then:

1. Open **Settings → Appearance**.
2. Scroll to **CSS snippets**.
3. Select **Reload snippets**.
4. Enable `soulbound-character-sheet-fixed-v3`.
5. Disable any older Soulbound CSS snippets.

Only the newest Soulbound snippet should be enabled.

### 3. Add the character-sheet note

Copy:

```text
Soulbound Character Sheet - Fully Wired Meta Bind - Fixed v3.md
```

into any folder inside your Obsidian vault.

Open the note and switch to **Reading view**.

On Windows, the default shortcut for switching between editing and reading views is:

```text
Ctrl + E
```

## Creating a Character

Keep the original note as a reusable template.

1. Right-click the template note in Obsidian.
2. Select **Duplicate**.
3. Rename the copy to your character's name.
4. Open the copy in Reading view.
5. Fill in the editor fields near the top of the note.

Meta Bind saves each value directly into that note. The graphical sheet below the editor updates from those saved values.

Each duplicated note is therefore a separate character.

## Adding a Portrait

Place the portrait image somewhere inside your vault, for example:

```text
Attachments/Characters/astrid.png
```

Enter that vault-relative path into the portrait field:

```text
Attachments/Characters/astrid.png
```

Use forward slashes `/` in the path.

A simple folder structure could look like:

```text
Characters/
├── Astrid.md
├── Brokk.md
└── Portraits/
    ├── astrid.png
    └── brokk.webp
```

In that case, a portrait path could be:

```text
Characters/Portraits/astrid.png
```

## How the Data Is Stored

The visible Meta Bind controls are connected to properties stored at the beginning of the Markdown note.

For example:

```yaml
character_name: Astrid Stormborn
body: 3
mind: 2
soul: 4
```

The CSS hides Obsidian's normal Properties panel for this note, but the data remains stored inside the file.

You normally do not need to edit these properties manually.

## Printing or Exporting

Use Obsidian's print or PDF export option while viewing the completed sheet.

Before exporting, confirm that:

- The CSS snippet is enabled.
- The note is in Reading view.
- Both character-sheet pages are visible.
- The portrait and all entered values appear correctly.

## Customizing the Layout

Most graphical positioning is controlled by:

```text
soulbound-character-sheet-fixed-v3.css
```

The values use percentage-based positioning so they remain aligned when the sheet is resized.

You can customize:

- Font size and family
- Text alignment
- Marker size and shape
- Page width
- Shadows and borders
- The divider between the Talents columns
- Print behavior

Keep a backup before changing field coordinates.

## Troubleshooting

### The page appears as a large blue callout

The CSS snippet is not enabled or was not loaded.

Go to:

```text
Settings → Appearance → CSS snippets
```

Reload the snippets and enable only the newest Soulbound CSS file.

### Values appear on the left side instead of on the sheet

An older CSS version may still be enabled.

Disable all previous Soulbound snippets and enable only:

```text
soulbound-character-sheet-fixed-v3
```

### Meta Bind expressions or error messages appear

Confirm that the Meta Bind community plugin is installed and enabled.

Also confirm that you are using the latest Markdown note included with this repository.

### The background image is missing

Confirm that the CSS file:

- Is inside `.obsidian/snippets/`
- Has a `.css` extension rather than `.css.txt`
- Is enabled in Obsidian
- Has not been truncated or modified while copying

### The second page does not render correctly

Do not add blank lines inside the generated graphical-sheet markup. Obsidian may split raw HTML blocks when blank lines are inserted.

## Privacy

All character information is stored locally in the Markdown note inside your Obsidian vault. This project does not require a server or external account.

## Usage and Rights

This is an unofficial, fan-made personal-use project. No affiliation with or endorsement by the original publishers is claimed.

The graphical sheet contains artwork derived from the original character sheet. Keep the repository private unless you have permission to redistribute that material.

## Credits

- Obsidian
- Meta Bind by Moritz Jung
- The creators and publishers of *Age of Sigmar: Soulbound*
