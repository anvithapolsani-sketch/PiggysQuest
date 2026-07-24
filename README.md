# PiggysQuest
GameLink:https://piggysquest.lovable.app

Very Interesting foodie game,best for kids to gain knowledge on food and food enthusiastic people
# 🐷 Piggy's Food Quest 🍛

> **Piggy is hungry again! Can you solve the foodie challenges and help Piggy reach the ultimate Biryani?** 🐷🍛

## 🎮 About the Game

**Piggy's Food Quest** is a cute, interactive grid-based food adventure game.

The player controls **Piggy**, a cute pink piglet who loves food more than anything. Piggy travels through an **8 × 8 grid**, visiting different food homes and solving clever foodie challenges to earn the right to eat.

But be careful! Piggy's hunger keeps increasing. If Piggy becomes extremely hungry and fails a challenge, Piggy cries and must restart the journey from the beginning! 😭🐷

---

## ✨ Features

* 🐷 Cute human-like pink piglet character
* 🏠 Interactive 8 × 8 grid-based world
* 🍭 Different food homes
* ⭐ Food difficulty levels from 1 to 5 stars
* 🧠 Clever foodie challenges
* 🍫 Snacks and sweets
* 🥤 Milkshakes and drinks
* 🍎 Fruits and vegetables
* 🍔 Fast food
* 🍛 Ultimate Biryani challenge
* ❤️ Hunger and happiness system
* 🎵 Cute sound effects
* 🎉 Victory celebrations
* 📱 Responsive design for desktop and mobile
* 🎮 Keyboard and on-screen controls

---

## 🗺️ Game Objective

Help Piggy travel through the 8 × 8 grid and find different food locations.

Piggy cannot eat food immediately.

At each food home:

```text
Reach Food Home
      ↓
Solve Foodie Challenge
      ↓
Correct Answer?
   ↙          ↘
 YES           NO
  ↓             ↓
Eat Food    Hunger Check
                ↓
       Hunger > 80?
          ↙      ↘
        YES       NO
         ↓         ↓
       FAIL     Continue
         ↓
 Piggy Cries 😭
         ↓
Restart from Start
```

The ultimate goal is to successfully solve the final challenge and reach the **5-star Biryani Home** 🍛🐷.

---

## ⭐ Food Level System

| Level | Food Category        | Examples                      |
| ----- | -------------------- | ----------------------------- |
| ⭐     | Light Snacks         | Sweets, chocolates, cookies   |
| ⭐⭐    | Drinks & Light Meals | Milkshakes, smoothies, juices |
| ⭐⭐⭐   | Healthy Food         | Fruits, vegetables, salads    |
| ⭐⭐⭐⭐  | Fast Food            | Burgers, pizza, fries         |
| ⭐⭐⭐⭐⭐ | Ultimate Food        | Biryani 🍛                    |

---

## 🧠 Foodie Challenge System

Before Piggy can eat, Piggy must solve a food-related challenge.

### Challenge Types

* 🍩 Food riddles
* 🍫 Food counting
* 🍎 Food matching
* 🧠 Food logic puzzles
* 🥗 Healthy food choices
* 🔍 Find the odd food
* 🧂 Guess the missing ingredient
* 🍌 Guess the food from clues
* 🧩 Food memory challenges

### Example

> I am yellow, curved, and monkeys love me. What am I?

**Answer:** Banana 🍌

If Piggy answers correctly:

```text
Challenge Solved 🎉
       ↓
Food Unlocked 🍔
       ↓
Piggy Eats 😋
       ↓
Hunger Decreases
```

---

## 🍽️ Hunger System

Piggy has a hunger level from **0 to 100**.

| Hunger | Condition        | Piggy's Behavior                          |
| ------ | ---------------- | ----------------------------------------- |
| 0–30   | Comfortable      | Happy and cheerful 😊                     |
| 31–60  | Getting Hungry   | Starts thinking about food 😋             |
| 61–80  | Very Hungry      | Holds stomach and looks worried 😟        |
| 81–100 | Extremely Hungry | Desperate and cries if challenge fails 😭 |

---

## 🚨 Critical Failure Rule

If:

```text
Hunger > 80
        +
Foodie Challenge Failed
        =
GAME FAILURE
```

Piggy will:

1. Look shocked 😳
2. Drop its ears
3. Start crying cutely 😭
4. Lose the current journey
5. Return to the starting position

The player must start the journey again.

> **“Poor Piggy couldn't solve the foodie problem!”** 😭🐷

---

## 🎉 Victory

The ultimate goal is the **5-star Biryani Home**.

When Piggy solves the final challenge:

* 🍛 Biryani is unlocked
* 🎊 Confetti appears
* ✨ Sparkles fill the screen
* 🐷 Piggy celebrates
* 🎵 A special victory sound plays

### Victory Message

> **Piggy solved the ultimate foodie challenge! 🐷🍛🎉**

---

## 🎨 Design Style

The game uses a:

* Cute cartoon style
* Bright and colorful environment
* Rounded UI components
* Soft shadows
* Playful animations
* Cute character expressions
* Food-themed visuals

Piggy has:

* A round face
* Pink skin
* Big expressive eyes
* Cute ears
* Chubby cheeks
* Adorable snout
* Cute human-like clothes

---

## 🔊 Sound Effects

The game includes cute and pleasant sound effects for:

* 👣 Piggy walking
* ✨ Entering a food home
* 🎉 Solving a challenge
* 😋 Eating food
* ⭐ Collecting stars
* 😭 Failing a challenge
* 🏆 Completing the game

A sound toggle is available so players can turn sound effects on or off.

---

## 🎮 Controls

### Desktop

```text
↑  Move Up
↓  Move Down
←  Move Left
→  Move Right
```

WASD controls are also supported.

### Mobile

Use the on-screen movement controls.

---

## 🛠️ Technologies

This project is built using modern web technologies.

Possible technologies include:

* React
* TypeScript
* HTML
* CSS
* Tailwind CSS
* JavaScript
* Vite

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/piggys-food-quest.git
```

### Navigate to the project

```bash
cd piggys-food-quest
```

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

Open the local development URL shown in your terminal.

---

## 📁 Project Structure

```text
src/
├── components/
│   ├── Piggy.tsx
│   ├── GameGrid.tsx
│   ├── FoodHome.tsx
│   ├── FoodieChallenge.tsx
│   ├── HungerMeter.tsx
│   └── VictoryScreen.tsx
│
├── data/
│   ├── foodData.ts
│   ├── challengeData.ts
│   └── gridData.ts
│
├── pages/
│   ├── Home.tsx
│   └── Game.tsx
│
├── assets/
│   ├── piggy/
│   ├── food/
│   └── sounds/
│
└── App.tsx
```

---

## 🔮 Future Improvements

Future versions may include:

* 🗺️ Multiple maps
* 🐷 More Piggy outfits
* 🍕 More food categories
* 🧠 More challenging puzzles
* 🏆 Leaderboards
* 🎯 Daily challenges
* 🪙 Collectible food coins
* 🐶 New characters
* 👾 Obstacles and enemies
* 🌍 Multiplayer mode
* 📈 Multiple game levels

---

## 👩‍💻 Author

Created with ❤️ and lots of food by **Anvitha** 🐷🍛

---

## 📜 License

This project is created for educational and entertainment purposes.
