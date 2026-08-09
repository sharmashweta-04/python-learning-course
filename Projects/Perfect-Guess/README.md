# 🔢 Project 2: The Perfect Guess

A fun number guessing game where the player attempts to guess a randomly generated number. The program keeps track of the number of attempts and records the user's high score.

## 📝 Workflow
1. The program generates a random number between 1 and 100.
2. The user enters their guess.
3. The program guides the user with "Higher number please" or "Lower number please".
4. Once guessed correctly, it displays the total number of attempts.
5. It checks a local high score file (`hiscore.txt`). If the current attempt count is lower than the recorded high score, it updates it.

---

## 🛠️ Concepts Used
* Random number generation (`random.randint`)
* Infinite loop (`while True`) with break controls
* File I/O for saving and updating high score history
