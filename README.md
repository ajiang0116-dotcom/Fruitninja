# 🍉 Fruit Ninja

A fast-paced browser-based fruit-slicing game inspired by Fruit Ninja.

## How to Play

1. Open `index.html` in any modern browser — no server or build step required.
2. Click **Play** to start.
3. **Slice fruits** by clicking and dragging the mouse (or swiping on touch screens).
4. **Avoid bombs** — slicing one costs a life.
5. **Don't miss fruits** — each fruit that falls off the screen costs a life.
6. You have **3 lives**. The game ends when they're all gone.

## Features

- **12 fruit types (10+)**: 🍎 Apple, 🍊 Orange, 🍉 Watermelon, 🍌 Banana, 🍓 Strawberry, 🥭 Mango, 🍍 Pineapple, 🍇 Grape, 🥝 Kiwi, 🍋 Lemon, 🍑 Peach, 🍒 Cherry
- **5 bomb variants (5+)**: Classic, Red, Blue, Green, and Gold bombs
- Smooth blade trail with glow effect
- Juice particle burst on slice
- Fruit splits into two halves when sliced
- Increasing difficulty over time (faster spawn rate)
- High score saved in `localStorage`

## Running the Game

Simply open `index.html` in a browser:

```bash
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows
```

Or serve it with any static file server:

```bash
npx serve .
```

