# Smoothie Showdown (Unity, Minimax AI)

A turn-based strategy game: two players take turns picking ingredients for their smoothie. Good ingredients (strawberry, mango, banana…) score; bad ones (kale, toothpaste, cheese…) don't. Play against a friend or against the AI.

## What I built
- **Minimax AI with alpha-beta pruning** (`AIUtility1.cs`) that searches future picks to choose the best ingredient.
- **Three difficulty levels**: easy and medium add controlled randomness to the move score; hard plays the optimal line.
- **Game state model** (`GameState`, `GameResult`) separate from the UI, so the AI can simulate moves without touching the scene.
- Local two-player mode with separate cursors, a menu and a results screen.

🎥 **Demo / presentation video:** [smoothie-showdown-docs](https://github.com/Hakeemshaik/smoothie-showdown-docs)

## Run it
Open `SMoothieGame_` in **Unity 2022.3.7f1** and start from `Assets/Scenes/Menu.unity`.

---
Built by **Hakeem Shaik** during my BSc (game development modules). See my AI work: [Pursuit](https://github.com/Hakeemshaik/pursuit-ai-job-agent) · [Fitted](https://github.com/Hakeemshaik/fitted) · [Boom & Crash Desk](https://github.com/Hakeemshaik/boom-crash-desk)
