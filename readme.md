<img src="https://raw.githubusercontent.com/cybrcore/cybrcore/refs/heads/main/assets/repo-banners/cybr-obsidian-banner-top.png"/>

# Showcase
<img src="https://raw.githubusercontent.com/cybrcore/cybrcore/refs/heads/main/assets/showcase/cybr-obsidian.png"/>
<img src="https://raw.githubusercontent.com/cybrcore/cybrcore/refs/heads/main/assets/showcase/cybr-obsidian-all.jpg"/>
<img src="https://raw.githubusercontent.com/cybrcore/cybrcore/refs/heads/main/assets/showcase/cybr-obsidian-features.png"/>

# Style Settings
Requires [Style Settings](https://github.com/obsidian-community/obsidian-style-settings) plugin to unlock full potential.

## Wallpaper
Select from 11 [cybrpapers](https://github.com/cybrcore/cybrpapers) wallpapers (Samurai, Shibuya, Shinjuku, Chiyoda, Minato, Yoyogi, Roppongi, Taito, Ikebukuro, Harajuku, Akihabara), or disable wallpaper entirely and use a solid background in any palette color.

## Colors
Three role colors -- `primary`, `secondary`, `tertiary` -- each independently assignable to any [cybrcolor](https://github.com/cybrcore/cybrcolors) swatch.
- Primary drives text, headings, tags, and active states
- Secondary drives interactive elements, navigation, and buttons
- Tertiary drives external links

Individual color control extends to:
- Heading H1 to H6,
- Blockquotes,
- Properties,
- Status bar color

### Colored folders
The 8 top-level folders in the file explorer can each be assigned a distinct color (requires `Colored Folders` toggle in UI settings).

## UI
In-built Focus mode functionality, collapses both sidebars with option to reveal on hover.

In-built Hider functionality, gide
- `Rab headers`,
- `Ribbon`,
- `Right top bar`,
- `Sidebar toggle buttons`,
- `File explorer buttons`,
- `Vault profile`,
- `System icons`,
- `Status bar`,
- `Scrollbars`,
- `Tooltips`,
- `Search suggestions`,
- `Properties` in reading view.

Internal and external link underlining are toggled independently.

Media is maximized by default. Image grids can be toggled. Card column count (for notes with the cards CSS class) is selectable: 2, 3, 4, or auto.

# Steps
## 0. Before you start  
- Make sure [Geist Mono Nerd Font](https://www.nerdfonts.com/font-downloads) is installed
- Install [Style Settings](https://github.com/obsidian-community/obsidian-style-settings) plugin  
    - Open Obsidian Settings `[cmd/ctrl] + [,]`  
    - Go to `Community plugins` and turn off `Restricted mode`  
    - In `Community plugins` click `Browse`, search for `Style Settings` by mgmeyers and click `Install`  

## 1. Manual install
### GUI
- Download `theme.css` and `manifest.json` from this repo
- Navigate to `YOUR-VAULT-NAME/.obsidian/themes/`
- Create a new folder called `cybrcore`
- Place both files inside the `cybrcore` folder
- In Obsidian: Settings > Appearance > Themes > Select `cybrcore`

### CLI
Download and install:
```sh
git clone --filter=blob:none --sparse --depth 1 \
  https://github.com/cybrcore/cybr-obsidian.git \
  YOUR-VAULT/.obsidian/themes/cybrcore

cd YOUR-VAULT/.obsidian/themes/cybrcore
git sparse-checkout set --no-cone theme.css manifest.json
```
To update:
```sh
cd YOUR-VAULT/.obsidian/themes/cybrcore && git pull
```

## ~~Install theme with Obsidian~~  

> [!NOTE]
> Theme currently under review by the Obsidian team.  
> Once approved, it will be available directly from the community theme browser.  

- ~~Open Obsidian Settings `[cmd/ctrl] + [,]`~~
- ~~Go to `Appearance` and click `Manage`~~
- ~~Search for `cybr-obsidian` by cybrcore and click `Use`~~
