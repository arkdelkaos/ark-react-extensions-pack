# Ark's React Extensions Pack

- [Ark's React Extensions Pack](#arks-react-extensions-pack)
  - [FAQ](#faq)
    - [Why do I need all those extensions](#why-do-i-need-all-those-extensions)
    - [What about the extensions I've already installed](#what-about-the-extensions-ive-already-installed)
  - [Included Extensions](#included-extensions)
    - [Core](#core)
    - [Linting and Syntax highlighting](#linting-and-syntax-highlighting)
    - [Live Share](#live-share)
    - [Markdown](#markdown)
    - [Tricks](#tricks)
    - [UI](#ui)
  - [Configuration](#configuration)

This is a pack with the extensions I use and recommend to my coworkers, so we can activate/deactivate between workspaces easier.
For example, when working with react and angular projects the process of whitelisting workspace only extensions is kind of tedious.

## FAQ

### Why do I need all those extensions

Maybe. You can just disable any extension you don't want to use.
But I recommend you to try them.

- The ones with the icon 🔥 are my favorites!
- Those with the icon 🔒 are a must!

Having less extensions running at the same time will always return a better performance.
But remember that not all extensions are running in the background!: those "on demand" (command palette) extensions weight almost nothing performance wise.

- The extensions with the icon ⚙️ can be kind of heavy on performance

I'll try to explain why I use every extension and how to configure it, **but feel free to add a new PR with any change proposal**.

### What about the extensions I've already installed

Those that aren't included will not be affected.
The ones that are included but were already installed will work as the were, but will be managed with the pack:

- If you enable the pack for a workspace all its extensions (actual and future ones) will be enabled for that workspace
- The same if you disable the pack.
- If you set a unique status for a extension included in the pack, for example you disable the pack as a whole but enable a pair of extenions, the individual settings will prevail over the pack ones.

## Included Extensions

### Core

- 🔒 ESLint: Integrates ESLint into VS Code. As we have prettier rules inside our eslintrc file, we will only need to use this linter.
- 🔥 Project Manager: To switch between projects/workspaces easily, and take advantage of the automatic extension switch by workspace.
- Docker: All the Docker related tools you may need, from management to syntax highlighting.
- GitLens: The git swissknife, with blame
- Jira and Bitbucket (Official): To interact with Jira without having to switch to the app/web
- ⚙️ Path Intellisense: For VSC to be able to autocompletes filenames
- ⚙️ TabNine
- ⚙️ Visual Studio IntelliCode

### Linting and Syntax highlighting

- 🔥 LintLens
- Cucumber (Gherkin) Full Support
- DotENV
- JSON Tools
- Rainbow CSV
- Sippets and Syntax Highlight for Gherkin (Cucumber)
- SVG
- XML Formater
- YAML

### Live Share

- 🔥 Live Share: To edit and debug code coperatively. A must for remote working.
- 🆕 Live Share Audio: 100% integrated into live share and free! Audio for your live share sessions.

### Markdown

- Markdown all-in-one
- Markdown Checkbox
- Markdown Table Prettify
- Markdownlint

### Tricks

- 🔥 change-case
- 🔥 Sort Lines
- 🔥 Toggle Quotes
- 🔥 Turbo Console Log
- Better Comments
- File Utils
- Glean
- Jest-cucumber code generator
- Smart Column Indenter
- ⚙️ Javascript Booster

### UI

- 🔒 🔥 Error Lens
- 🆕 Peacock
- Bracket Pair Colorizer
- Color-Info
- colorize
- empty-indent
- Guides
- Jenkinsfile Support
- SVG Viewer
- ⚙️ Image Preview
- ⚙️ Log File Highlighter
- ⚙️ Output Colorizer

## Configuration

This is the first iteration of this idea, and I don't want to expend too much time adding complexity if the initiative doesn't feel useful after a while.
When needed I'll add some custom configurations for the extensions _(even vscode itself)_ here
