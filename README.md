<h1 align="center">Paul Nercessian</h1>

<p align="center">
  <b>Machine learning &nbsp;·&nbsp; Simulation &nbsp;·&nbsp; Games &nbsp;·&nbsp; Teaching Python</b>
</p>

<p align="center">
  Student developer in Dubai, in the final year of the IB Diploma.<br>
  Applying to AI and computer science degree programmes for autumn 2027.
</p>

<p align="center">
  <a href="https://linkedin.com/in/paul-nercessian-b00427383"><img src="https://img.shields.io/badge/LinkedIn-4F46E5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:nercessianpaul@gmail.com"><img src="https://img.shields.io/badge/Email-4F46E5?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://paulspythoncourse.com/"><img src="https://img.shields.io/badge/Python_Course-4F46E5?style=for-the-badge&logo=python&logoColor=white" alt="Paul's Python Course"></a>
</p>

<p align="center">
  <a href="#featured">Featured</a> &nbsp;·&nbsp;
  <a href="#machine-learning-and-simulation">ML and simulation</a> &nbsp;·&nbsp;
  <a href="#games">Games</a> &nbsp;·&nbsp;
  <a href="#tools-and-apps">Tools and apps</a> &nbsp;·&nbsp;
  <a href="#skills">Skills</a>
</p>

---

I started out making games in C# and Unity, and I still work the same way now that my focus is machine learning: build the whole thing end to end, get it running live, then test it and write down what did not work. My current interests are world models, sequence models, reinforcement learning, computer vision and NLP.

I study at Dubai International Academy Al Barsha (HL: Design Technology, Business, Mathematics AI).

## Featured

<a href="https://github.com/Bouwles/lucid">
  <img src="https://raw.githubusercontent.com/Bouwles/lucid/main/docs/media/banner.svg" alt="LUCID: a neural game engine that learns to dream the games I make" width="100%">
</a>

**[LUCID](https://github.com/Bouwles/lucid)** is a neural game engine. A diffusion world model watches recorded play, then generates the game one frame at a time from your key presses, with no game engine, physics code or level data in the loop. It uses EDM preconditioning and context-noise augmentation against drift, and an evaluation suite measures image quality, long-run stability and whether the dream obeys the controls.

`Python` `PyTorch` `Unity` `FastAPI`

> **Status:** the whole pipeline is built and tested end to end on a synthetic test game. Training it on my own Unity games is the next stage.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://paulspythoncourse.com/"><img src="https://raw.githubusercontent.com/Bouwles/pauls-python-course/main/docs/readme/lesson.png" alt="A lesson in Paul's Python Course beside the code editor" width="100%"></a>
      <br><br>
      <b><a href="https://github.com/Bouwles/pauls-python-course">Paul's Python Course</a></b>
      <br>
      The site for the Python class I teach. 116 projects climb nine floors of a clocktower, from a first <code>print</code> to a neural network from scratch, a tiny GPT and reinforcement learning. Python runs in the browser, and a class register shows me each student's progress.
      <br><br>
      <code>TypeScript</code> <code>Next.js</code> <code>Pyodide</code> <code>Supabase</code>
      <br><br>
      <a href="https://paulspythoncourse.com/">Open the site</a> &nbsp;·&nbsp; <a href="https://github.com/Bouwles/pauls-python-course">Source</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Bouwles/DriftSync"><img src="https://raw.githubusercontent.com/Bouwles/DriftSync/main/docs/assets/driftsync-workspace.png" alt="The DriftSync desktop workspace" width="100%"></a>
      <br><br>
      <b><a href="https://github.com/Bouwles/DriftSync">DriftSync</a></b>
      <br>
      Predicts whether a user will make an error in the next 5 trials from their last 20 trials of behaviour. LSTM and Transformer models, MC-dropout uncertainty and live inference in a desktop app. The Transformer reaches 0.89 ROC AUC on synthetic data.
      <br><br>
      <code>Python</code> <code>PyTorch</code> <code>Pygame</code>
      <br><br>
      <a href="https://github.com/Bouwles/DriftSync">Source</a> &nbsp;·&nbsp; <a href="https://github.com/Bouwles/DriftSync/releases">Windows download</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://bouwles.github.io/mbzuai-screening-prep/"><img src="https://raw.githubusercontent.com/Bouwles/mbzuai-screening-prep/main/docs/screenshots/lesson.png" alt="A lesson in Screening Prep" width="100%"></a>
      <br><br>
      <b><a href="https://github.com/Bouwles/mbzuai-screening-prep">Screening Prep</a></b>
      <br>
      Unofficial revision site for the MBZUAI BSc in AI screening exam: 65 lessons, 1,484 questions, 177 question generators, timed mocks and spaced repetition. 876 tests check every question and 2,000 variants of each generator.
      <br><br>
      <code>TypeScript</code> <code>React</code> <code>Vite</code>
      <br><br>
      <a href="https://bouwles.github.io/mbzuai-screening-prep/">Open the site</a> &nbsp;·&nbsp; <a href="https://github.com/Bouwles/mbzuai-screening-prep">Source</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://bouwles.github.io/SCRATCH/"><img src="https://raw.githubusercontent.com/Bouwles/SCRATCH/main/docs/screenshots/01-table.jpg" alt="A SCRATCH table mid-run" width="100%"></a>
      <br><br>
      <b><a href="https://github.com/Bouwles/SCRATCH">SCRATCH</a></b>
      <br>
      A billiards roguelite with its own physics. Every table, texture, song and sound effect is generated in code, so the repo contains no image, audio or model files.
      <br><br>
      <code>JavaScript</code> <code>Three.js</code> <code>Vite</code>
      <br><br>
      <a href="https://bouwles.github.io/SCRATCH/">Play in the browser</a> &nbsp;·&nbsp; <a href="https://github.com/Bouwles/SCRATCH">Source</a>
    </td>
  </tr>
</table>

## Machine learning and simulation

| Project | About | Stack |
| :-- | :-- | :-- |
| [**RL Chess and Snake Lab**](https://github.com/Bouwles/rl-chess-snake-lab) | DQN agent for a custom Snake environment and a self-play chess experiment, with replay memory, checkpointing, seeded configs and tests. | `Python` `PyTorch` `Gymnasium` |
| [**ASL Interpreter**](https://github.com/Bouwles/ASL-Interpreter)<br><sub>[Live demo](https://bouwles.github.io/ASL-Interpreter/)</sub> | Turns webcam hand landmarks into English sentences in the browser, using gesture heuristics, a vote-based stability filter and a tested sentence engine. | `JavaScript` `MediaPipe` |
| [**Arabic Sentiment Analyzer**](https://github.com/Bouwles/arabic-sentiment-analyzer) | Arabic NLP pipeline with text preprocessing, a pretrained Transformer model wrapper, CLI, batch mode and Streamlit demo. | `Python` `Hugging Face` `Streamlit` |
| [**Four-Way Traffic Simulation**](https://github.com/Bouwles/Four-Way-Stochastic-Traffic-Simulation)<br><sub>[Live demo](https://bouwles.github.io/Four-Way-Stochastic-Traffic-Simulation/)</sub> | Seeded stochastic simulation comparing equal-time and adaptive signal control over 250 paired trials with confidence intervals. Built for my IB Mathematics internal assessment. | `JavaScript` |
| [**Magnus Effect Simulation**](https://github.com/Bouwles/Physics-Magnus-Effect-Simulation)<br><sub>[Live demo](https://bouwles.github.io/Physics-Magnus-Effect-Simulation/)</sub> | Interactive 3D simulation of spin, drag and Magnus force, with force arrows, trajectory trails and live telemetry. | `JavaScript` `Three.js` |

## Games

| Project | About | Stack |
| :-- | :-- | :-- |
| [**Hand Cannon**](https://github.com/Bouwles/3D-Finger-Tracking-Shooter-Game)<br><sub>[Play](https://bouwles.github.io/3D-Finger-Tracking-Shooter-Game/)</sub> | Browser shooter you aim with your index finger and fire with your thumb, using webcam hand tracking. | `JavaScript` `MediaPipe` |
| [**RAJIS**](https://github.com/Bouwles/RAJIS)<br><sub>[Play](https://bouwles.github.io/RAJIS/)</sub> | First-person 3D missile defence game with wave survival and online 1v1. | `JavaScript` `Three.js` |
| [**Shatterdome Earth**](https://github.com/Bouwles/Pacific-Rim-Shatterdome-Earth)<br><sub>[Play](https://bouwles.github.io/Pacific-Rim-Shatterdome-Earth/)</sub> | Open-world Pacific Rim fan game, with a headless scenario runner that tests for determinism. | `TypeScript` `Babylon.js` |
| [**Mach 20**](https://github.com/Bouwles/assassination-classroom-last-bell)<br><sub>[Play](https://bouwles.github.io/assassination-classroom-last-bell/)</sub> | Assassination Classroom fan game about tracking the real target through afterimages. | `JavaScript` `Vite` |
| [**Breaktime**](https://github.com/Bouwles/breaktime) | Fast top-down action roguelite for five-minute breaks. | `JavaScript` |
| [**Horse Tinder**](https://github.com/Bouwles/horse-tinder)<br><sub>[Play](https://bouwles.github.io/horse-tinder/)</sub> | A joke made with a friend: 45 horses to swipe on, and they text back. | `JavaScript` |

## Tools and apps

| Project | About | Stack |
| :-- | :-- | :-- |
| [**Assumption Archaeologist**](https://github.com/Bouwles/assumption-archaeologist) | Claude Code plugin that records the unwritten assumptions in a codebase and tracks whether they still hold. | `Claude Code` |
| [**Comment Rot Detector**](https://github.com/Bouwles/comment-rot-detector) | Claude Code plugin that flags comments which stop matching the code after an edit. | `Claude Code` |
| [**KenKen for Paul**](https://github.com/Bouwles/kenken-for-paul)<br><sub>[Play](https://bouwles.github.io/kenken-for-paul/)</sub> | Puzzle generator with a solver that guarantees exactly one solution, as a website and a native Mac app. | `JavaScript` `Swift` |
| [**Calculus Practice**](https://github.com/Bouwles/calculus-practice)<br><sub>[Open](https://bouwles.github.io/calculus-practice/)</sub> | Randomly generated derivative and integral questions, each with the rule behind its answer. One HTML file that works offline. | `JavaScript` `KaTeX` |
| [**Silo**](https://github.com/Bouwles/Silo) | macOS focus timer, task list and study analytics. | `SwiftUI` `SwiftData` |
| [**PromptForge**](https://github.com/Bouwles/PromptForge) | Local prompt writer for coding agents. | `Ollama` |
| [**PR Tracker**](https://github.com/Bouwles/nercessians-pr-tracker) | Desktop app for gym personal records and progress charts. | `Electron` `React` |

## Skills

**Languages**

![Python](https://img.shields.io/badge/Python-334155?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-334155?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-334155?style=flat-square&logo=javascript&logoColor=white)
![C#](https://img.shields.io/badge/C%23-334155?style=flat-square)
![Swift](https://img.shields.io/badge/Swift-334155?style=flat-square&logo=swift&logoColor=white)
![HTML and CSS](https://img.shields.io/badge/HTML%2FCSS-334155?style=flat-square&logo=html5&logoColor=white)

**ML and data**

![PyTorch](https://img.shields.io/badge/PyTorch-334155?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-334155?style=flat-square&logo=huggingface&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-334155?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-334155?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-334155?style=flat-square&logo=pandas&logoColor=white)
![Gymnasium](https://img.shields.io/badge/Gymnasium-334155?style=flat-square)
![MediaPipe](https://img.shields.io/badge/MediaPipe-334155?style=flat-square&logo=mediapipe&logoColor=white)

**Web and apps**

![React](https://img.shields.io/badge/React-334155?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-334155?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-334155?style=flat-square&logo=vite&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-334155?style=flat-square&logo=threedotjs&logoColor=white)
![Babylon.js](https://img.shields.io/badge/Babylon.js-334155?style=flat-square&logo=babylondotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-334155?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-334155?style=flat-square&logo=streamlit&logoColor=white)
![Pygame](https://img.shields.io/badge/Pygame-334155?style=flat-square)
![SwiftUI](https://img.shields.io/badge/SwiftUI-334155?style=flat-square&logo=swift&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-334155?style=flat-square&logo=electron&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-334155?style=flat-square&logo=unity&logoColor=white)

**Engineering**

![Git](https://img.shields.io/badge/Git-334155?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-334155?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-334155?style=flat-square&logo=pytest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-334155?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-334155?style=flat-square)

---

<p align="center">
  <sub>Open to conversations about AI, research and anything I have built. <a href="mailto:nercessianpaul@gmail.com">nercessianpaul@gmail.com</a></sub>
</p>
