# rediohead theme 🌶️

A spicy red dark theme inspired by chili peppers, [Vesper](https://github.com/raunofreiberg/vesper) and [Silent Red Theme](https://github.com/seanjan00/SilentRed). Designed for comfort and clarity with strong yet calm contrast.

- Developed for Go, Python, and TypeScript (but hopefully works with everything) ✨
- Red-forward accenting with balanced neutrals for long coding sessions
- Works in both VS Code and Cursor

## Look & Feel
![Go demo](screenshots/golang.gif)
![Python demo](screenshots/python.gif)

## For contributors:
## Run locally with launch.json (Dev Host)
If you want to iterate quickly using an Extension Development Host:
1. Open Run and Debug (Ctrl/Cmd+Shift+D), pick “Run rediohead Theme”, then press F5.
2. In the new “Extension Development Host” window: Cmd+K, Cmd+T → choose “rediohead theme”.
3. Make changes → reload Dev Host (Developer: Reload Window) to see updates. 🚀

## Install (from repo clone)
0. Clone this repo
1. Install vsce:
```bash
npm install -g @vscode/vsce
```
2. Package the theme:
```bash
cd rediohead_theme
vsce package
```
3. In VS Code or Cursor: Extensions → “…” → Install from VSIX… → select the generated `.vsix`.
4. Activate: File → Preferences → Color Theme → “rediohead theme”.

## Language UX highlights
- Go: clearer package/type/builtin separation; operators readable but subtle; function calls accented.
- Python: decorators and magic (dunder) names stand out; punctuation de-emphasized; strings easy on eyes.
- TypeScript: imports, keywords, and types clearly distinguished; properties readable without glare.

## License
Apache-2.0 (feel free to use source code)
