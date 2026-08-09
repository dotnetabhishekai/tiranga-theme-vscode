# Tiranga Theme for VS Code

A dark VS Code color theme inspired by the Indian national flag (Tiranga):

- **Saffron (#FF9933)** — keywords, tags, active line numbers, accents
- **White (#FFFFFF / #F5F3EE)** — primary text, class names
- **Green (#138808)** — added/inserted code, git additions, namespaces
- **Navy Blue (#000080)** — status bar (evoking the Ashoka Chakra), info highlights

## Install (without publishing to the Marketplace)

**Option A — Copy into your VS Code extensions folder:**

1. Copy the whole `tiranga-theme` folder into your VS Code extensions directory:
   - macOS/Linux: `~/.vscode/extensions/`
   - Windows: `%USERPROFILE%\.vscode\extensions\`
2. Restart VS Code.
3. Open the Command Palette (`Ctrl/Cmd+Shift+P`) → **Preferences: Color Theme** → select **Tiranga**.

**Option B — download it from vscode extensions marketplace.
https://marketplace.visualstudio.com/items?itemName=dotnetabhishekai.tiranga-theme-2026

## Customize

All colors live in `themes/tiranga-color-theme.json`. Tweak the hex values under `"colors"` (UI) or `"tokenColors"` (syntax highlighting) to taste.
