# Password Forge 🔐

> A sleek, browser-based random password generator with real-time strength meter and visual feedback.

## Features

- 🔢 Adjustable length (8–64 characters)
- 🔤 Toggle: uppercase, lowercase, numbers, symbols
- 📊 Live password strength meter
- 📋 One-click copy to clipboard
- 🎨 Dark-mode UI that looks great
- ⚡ Zero dependencies — pure vanilla JS

## Usage

Open `index.html` in any browser. No server needed.

```bash
# Or serve locally
npx serve .
```

## Screenshots

```
┌──────────────────────────────────────┐
│  🔐 Password Forge                   │
│                                      │
│  ┌──────────────────────────────┐    │
│  │ xK9#mP2$vL7nQ4rT              │    │
│  └──────────────────────────────┘    │
│                                      │
│  Strength: ████████░░ Strong (82)    │
│                                      │
│  Length: ──●────────────── 16        │
│  [A-Z] [a-z] [#!] [0-9] [Symbols]    │
│                                      │
│         [ Generate ]  [ Copy ]       │
└──────────────────────────────────────┘
```

## Tech

- HTML5 + CSS3 + Vanilla JS
- Zero npm packages, zero build step
- Single `index.html` — deploy anywhere

## License

MIT
