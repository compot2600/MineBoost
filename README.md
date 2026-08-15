# MineBoost - Minecraft Optimizer

<p align="center">
  <img src="https://shields.io" alt="Downloads">
  <img src="https://shields.io" alt="Views">
  <img src="https://shields.io" alt="Language">
  <img src="https://shields.io" alt="Size">
</p>

---

**MineBoost** is a lightweight and fast C# (WPF) graphical utility designed for instant Minecraft settings optimization. It rewrites the `options.txt` configuration file, reducing CPU and GPU load to provide a significant FPS boost on low-end PCs.

---

### Features

*   **Versatility:** Supports all major game eras from old *Beta 1.7.3* to modern *1.21 - 1.23+* versions.
*   **Safety:** The program automatically creates a backup of your original file (`options.txt.bak`) before making any changes.
*   **Custom Launchers:** Ability to manually specify the path to the configuration file if you use third-party launchers.
*   **Smart Optimization:** Disables heavy ambient occlusion, removes clouds, sets optimal render distance (4 chunks), and limits simulation distance (5 chunks).

---

### How to Use

1. Completely close Minecraft before running the program.
2. Go to the **Releases** tab on the right side of this page and download the latest `MineBoost.exe`.
3. Launch the utility. It will automatically attempt to locate your `.minecraft` folder. If you use a custom launcher, click the **Browse...** button and select your `options.txt` file manually.
4. Select the version era you intend to play.
5. Click the **Optimize** button. The program will play a system sound upon successful completion.
6. Launch the game and enjoy your boosted FPS!

---

### 🛠️ Tech Stack

*   **Language:** C#
*   **Interface:** WPF (Windows Presentation Foundation)
*   **Platform:** .NET
