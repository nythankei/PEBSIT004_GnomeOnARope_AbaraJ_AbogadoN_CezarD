# 🧭 HOW TO RUN — GNOMEWELL

## 🎮 Game Overview

**Gnomewell** is a 2D mobile action game where players guide a gnome lowered into a dangerous well.
The objective is to **collect treasures** while avoiding traps using precise **rope controls** at varying speeds.

---

## ⚙️ Prerequisites

Before running or testing Gnomewell, ensure the following are installed on your system:

* **Unity Hub**
* **Unity Editor 2021.3.5f1**
* **Android Build Support** (for mobile builds)
* **Git** (optional, for cloning the repository)

---

## 🧩 1. Clone the Repository

Open a terminal or Git Bash, then run:

```bash
git clone https://github.com/nythankei/PEBSIT004_GnomeOnARope_AbaraJ_AbogadoN_CezarD.git
```

Alternatively, you can download the ZIP from GitHub and extract it to your workspace.

---

## 🧱 2. Open the Project in Unity

1. Launch **Unity Hub**.
2. Click **“Open”** and select the folder containing the Gnomewell project.
3. Wait for Unity to import assets and compile scripts.

> 💡 Tip: If Unity asks to upgrade or downgrade versions, **choose 2021.3.5f1** to maintain compatibility.

---

## ▶️ 3. Run the Game in Unity Editor

1. Inside the **Project** window, navigate to:

   ```
   Assets/Scenes/MainScene.unity
   ```
2. Open the scene.
3. Click the **▶ Play** button on the top toolbar to start testing.
4. Use your mouse or on-screen buttons to simulate Android touch controls.

---

## 📱 4. Build for Android

1. Go to **File → Build Settings**.
2. Select **Android** as the target platform and click **Switch Platform**.
3. Under **Scenes in Build**, make sure `MainScene` is checked.
4. Click **Build and Run**.
5. Choose an output location and wait for the APK file to generate.
6. Transfer and install the `.apk` file to your Android device.

---

## 🎮 Game Controls (Android)

| Control       | Function               |
| ------------- | ---------------------- |
| **Up Fast**   | Quickly raise the rope |
| **Up Slow**   | Slowly raise the rope  |
| **Down Fast** | Quickly lower the rope |
| **Down Slow** | Slowly lower the rope  |

Avoid traps, collect treasures, and keep your gnome safe!

---

## 🧾 Known Issues

* Rope movement may feel inconsistent on certain Android devices.
* Visual glitches can occur during rapid rope direction changes.
* Restarting scenes may cause a minor delay in audio playback.

---

## 💡 Developer Notes

* Ensure all contributors are using **the same Unity version**.
* Use **Git LFS** for managing large files (like sprites and sound assets).
* Regularly pull updates to stay synced with your team’s latest changes.

