# Crab Crawler Deployment

This repository contains the deployment files for the Crab Crawler game, a 2D pixel art platformer containing 10 unique levels with a variety of challenges.

### 🎮 Play the Game

[Click here to play Crab Crawler](https://kaisequeira.github.io/Crabcrawler-Deployment/)

### 📁 Original Repository

For the source code and development history, please visit the [Crab Crawler Development Repository](https://github.com/kaisequeira/CrabCrawler).

# 🕹️ How to Play

## Controls

### Keyboard:
- **A** and **D** or **Left Arrow** and **Right Arrow** to move left and right
- **W** or **Up Arrow** to jump
- **S** or **Down Arrow** to crouch
- **Mouse** or **Arrow Keys** to navigate menus 

### Controller:
- **Left Joystick** to move left and right
- **South Button** (typically X on PlayStation or A on Xbox) to jump
- **East Button** (typically Circle on PlayStation or B on Xbox) to Crouch
- **D-pad** to navigate menus (refrain from using joystick due to a bug with WebGl deployment)

## Health & Oxygen

### Health

- Your crab has a health bar displayed at the top of the screen.
- In total, the player has three lives which can be depleted before needing to restart the level.
- Avoid taking damage from enemies and obstacles to maintain your health.
- Don't worry! You will restart from the last acquired checkpoint if you are hit. 

![Health](https://github.com/user-attachments/assets/3d0d5e71-7b42-41f2-9223-c9f10dc8e631)

### Oxygen

- The blue bar at the top of the screen shows the current oxygen level of the crab.
- Crabs require water to breathe oxygen! Make sure you don't leave the water for too long.
- If your oxygen is about to run out, an indicator will flash to warn you.

![Warning](https://github.com/user-attachments/assets/29e2e131-f62d-4dd4-8ee3-e955443c8e3f)

## Objectives

### Flagpole
- Reaching the flagpole will create a checkpoint for the crab.
- You also recieve an additional life each time you hit a checkpoint!
- Being hit will take you back to the last acquired checkpoint.

![Flagpole](https://github.com/user-attachments/assets/8a6b95de-6b08-4f9b-aab1-68d232fa7992)

### Sandcastle
- Reaching the sandcastle will complete the level and allow you to proceed to the next.

![image](https://github.com/user-attachments/assets/e5265906-7d9f-4a71-9d9d-acafdada440a)

### Geyser
- Crouching in a geyser will shoot the player up the bubble spout. Be careful though, you may not know where it leads!

![Geyser](https://github.com/user-attachments/assets/26917a42-f0fd-4d67-90a9-3582949cfaa6)

## Barnacles
- Avoid barnacles in order to keep the crab safe.
- Hitting a barnacle will deplete one life point and take the crab back to the last checkpoint.

![Barnacles](https://github.com/user-attachments/assets/70c14c80-888e-43df-8760-4a59667034d8)

## Enemies
Watch out for signs, they might tell you where a predator is hiding!

### Pufferfish
- The poisonous Pufferfish will inflate themselves, breathing in to rise out of the water, and breathing out to fall back in.
- Pufferfish will not actively chase you, but stay away or risk getting spiked when they float.

![Pufferfish](https://github.com/user-attachments/assets/83e7f1cb-1224-4b8a-92ca-7d8f9276c666)

### Seagulls
- Seagulls will perch themselves on the beach or fly around waiting for prey.
- Get too close and these pesky birds will begin to chase you until you are out of sight or out of reach.
- Evading the Seagull successfully or being hit by one will cause it to return to it's watch.

![Seagull](https://github.com/user-attachments/assets/a6dfcfda-f685-4b16-98a6-41155dfdaa68)

### Dogfish
- These silent stalkers will drift across the water until the crab crosses it's path.
- Stay out of direct sight to avoid being pursued.
- Fortunately, the Dogfish isn't smart enough to ascend/descend in water.

![Dogfish](https://github.com/user-attachments/assets/26bb1e38-7ed7-4f53-b14f-c3a7d582a300)

### Turtles
- Bouncing on a turtle's shell will allow the crab to gain incredible height and overcome various obstacles
- Get close but not too close! The crab will agressively swim in the direction of the crab if it crosses the turtle's path.

![Turtle](https://github.com/user-attachments/assets/792f41cc-eef8-426b-81ac-85649d0be421)

Remember, timing and precision are key to successfully navigating the beaches in Crab Crawler. Good luck, and enjoy your aquatic adventure!

## 💀 Hardmode
If you're up for the challenge, prepare yourself for hard mode. When entering hardmode, the following will apply:
- Flagpoles no longer give the player an additional life.
- Lives will carry across levels. That means you only have three lives the entire run!
- Losing all lives will reset the player back to the first level.
- The player loses oxygen faster and will need to rehydrate more frequently.

## 🛠️ Technical Details

This deployment was created using WebGL build from Unity and is hosted on GitHub Pages. For more information on the development process or to contribute to the project, please visit the original repository.

## 📝 License

This project is available under the [MIT License](LICENSE).

## 🤝 Contact

Kai Sequeira - [GitHub](https://github.com/kaisequeira)

---

Developed with ❤️ by Kai Sequeira
