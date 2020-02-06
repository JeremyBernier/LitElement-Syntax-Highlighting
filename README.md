# Lit-Element Syntax Highlighting for Sublime Text 3

This enables syntax highlighting when using the [lit-element](https://lit-element.polymer-project.org/) and [lit-html](https://lit-html.polymer-project.org/) libraries. It also includes Babel (eg. for decorators).

### NOTE: This package triggers a bug with Sublime Text that will pop up an error message on window load: "Apparent recursion within a with_prototype action: 25000 context sanity limit hit" (https://github.com/sublimehq/sublime_text/issues/2444). It's a known bug with Sublime Text. Yes it's annoying as hell, and I hope that it gets fixed (I've actually moved on to VS Code partially because of this). Anybody who solves it is welcome to submit a PR!

## Installation

1. Install [Package Control](https://packagecontrol.io/) for Sublime Text 3
2. Ctrl+Shift+P -> "Install Package" -> "LitElement Syntax Highlighting" (pending approval)
3. View -> Syntax -> Lit-Element

Note: Only the lit-element.sublime-syntax file is valid. The tmLanguage file will not work (only included it because I had to to get the PR approved by the robot). Unless you're using an older version of Sublime Text, this should not matter.
