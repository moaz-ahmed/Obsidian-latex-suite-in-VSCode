## Obsidian LaTeX Suite — VS Code port

A minimal, partial port of the Obsidian LaTeX Suite snippets to Visual Studio Code using the HyperSnips extension. Simple, single-trigger snippets work. Fancy stuff that rely on Tab stops, multi-stage placeholders, or advanced Obsidian features doesn't.

### Features

- Core LaTeX snippets (environment wrappers, common math macros, Greek letters, arrows, fractions as single-trigger inserts).

### Requirements

- VS Code
- A TeX toolchain (pdflatex, xelatex, lualatex, etc.). Recommended extension: **LaTeX Workshop** — https://github.com/James-Yu/LaTeX-Workshop
- HyperSnips extension — https://marketplace.visualstudio.com/items?itemName=draivin.hsnips

### Installation

1. Install LaTeX Workshop and HyperSnips in VS Code.
2. Press `Shift+Cmd+P`  and run: `> HyperSnips: Open Snippets Directory`
3. Copy `latex.hsnips` into the opened directory.
4. In VS Code again run: `> HyperSnips: Reload Snippets`
5. Snippets are now available 

### Limitations

The following are a bunch of examples of what doesn't work :

- Tab-stop navigation / multi-stage placeholder chaining
- Visual snippets that require selection-based transforms (underbrace, overbrace, etc.)
- Conceal features
- Auto-generated matrix entry/tabbing
- Any snippet behavior that depends on Obsidian’s Tab mechanics

### Future Plans 

-[ ] Figure out if auto fractions are even possible 
-[ ] Tabbing out behaviour implementation ? 


### Acknowledgments
Thanks to Sleepmalc’s repo for guidance: https://github.com/sleepymalc/VSCode-LaTeX-Inkscape

 

