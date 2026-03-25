# I Hate You - IzotopJam ☄️🔄

> **A chaotic co-op endless survival game created during IzotopJam (DePark Gamejam).**

**I Hate You** is a fast-paced, 2-player survival game where you and your partner must dodge obstacles, survive random catastrophic events, and stay alive as long as possible. The longer you survive, the higher your score—but the game will try everything in its power to stop you!

---

<!-- 🎥 Fiuby (YouTube/Itch.io) Oynanış Videosu Linki Buraya Gelecek -->
📺 **[Oynanış Videosunu İzle / Watch Gameplay Here](PLACEHOLDER_FIUBY_LINK)**

<!-- 📸 Klasör içindeki GIF dosyasının adı buraya gelecek (Örn: oynanis.gif) -->
![I Hate You Gameplay](PLACEHOLDER_GAMEPLAY_GIF)

---

## 🎮 Gameplay & Mechanics

This endless survival experience relies on constant adaptation. Both players share a limited pool of lives, making teamwork (or shared suffering) essential.

- **Dynamic Events (`EventManager`)**: The core mechanic of the game is its unpredictability. Every few seconds, a random event is triggered to ruin your run:
  - ☄️ **Meteor Strike:** Deadly meteors rain down on the arena.
  - ⏩ **Speed Up:** The entire game speeds up (`Time.timeScale x3`), requiring lightning-fast reflexes.
  - 🔄 **Exchange (Swap):** Player 1 and Player 2 suddenly swap positions, inducing pure chaos.
  - 🌑 **Darkness (Flashbang):** The screen flashes black and white, obscuring your vision.
  - 💥 **Screen Shake / Earthquake:** The camera violently shakes, throwing off your coordination.
- **Shared Lives (`PlayerSpawner`)**: Players 1 and 2 share the same life pool. If the total lives drop to zero, it's Game Over for both!
- **Score System**: Your score constantly increases as long as you stay alive. Coordinate, survive the random events, and break the high score!

## 🛠️ Technical Details

Developed in **Unity (C#)** for a Game Jam under tight time constraints. 
The project features an `EventManager` system that handles randomized chaos on timers, and a unified `PlayerSpawner` that manages camera shaking, player respawns with immunity frames, and the shared pool of lives. 

---

## License & Copyright

&copy; Ucmaz pc. All Rights Reserved.  
This project is proprietary and intended solely for educational, academic, and portfolio purposes. It is not licensed for commercial use, distribution, or modification without explicit permission.
