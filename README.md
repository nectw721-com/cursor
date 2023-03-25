
# Cursor

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/getcursor/cursor/blob/main/LICENSE) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)]() [![](https://dcbadge.vercel.app/api/server/PJEgRywgRy?style=flat&compact=true)](https://discord.gg/PJEgRywgRy)

**[Cursor](cursor.so) is an editor made for programming with AI.** It's early days, but right now Cursor can help you with a few things...

- **Write**: Generate 10-50 lines of code with an intelligent AI
- **Diff**: Ask the AI to edit a block of code, see only proposed changes
- **Chat**: ChatGPT-style interface that understands your current file
- **And more**: ask to fix lint errors, generate tests/comments on hover, etc.

<p align="center">
<a href="https://cursor.so/">
<img src="https://user-images.githubusercontent.com/4297743/227696390-0c1886c7-0cda-4528-9259-0b2944892d4c.png" width="1000"><br>
</a>
</p>

## Getting Started

Head over to [our website](https://cursor.so/) to download and try out the editor.

## Roadmap

Feel free to file tickets for bugs or feature requests. Upvote 👍 the ones you'd like us to prioritize.

Longterm, we're building Cursor into the world's most productive development environment. We want to: 
- Auto-fix errors as soon as they show up in your terminal
- Embed AI-written documentation into the UI 
- "Heal" your repository when you're halfway through a refactor

If you're excited about this future, reach out to hiring@cursor.so

## Development

We welcome PRs! To get started:

```
git clone git@github.com:getcursor/cursor.git
cd cursor
npm i
```

Then, download some non-versioned dependencies (ripgrep binaries and language server js):
```
./setup.sh # Mac/Linux
./setup.ps1 # Windows
```

Finally, to run the client:

```
npm start
```
