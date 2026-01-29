# ai-roast

[![npm version](https://img.shields.io/npm/v/ai-roast.svg)](https://www.npmjs.com/package/ai-roast)
[![npm downloads](https://img.shields.io/npm/dm/ai-roast.svg)](https://www.npmjs.com/package/ai-roast)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Get your code roasted. Funny, brutal, but always with actionable feedback.

## Install

```bash
npm install -g ai-roast
```

## Usage

```bash
npx ai-roast ./src/index.ts
# Medium roast (default)

npx ai-roast ./src/index.ts --intensity savage
# No mercy mode
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## Options

- `-i, --intensity` - mild, medium, or savage (default: medium)

## License

MIT
