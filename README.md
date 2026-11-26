<h1 align="center">Paul Nercessian</h1>

<p align="center">
  <b>I build machine learning systems end to end, and I teach Python to beginners.</b><br>
  IB Diploma student in Dubai &nbsp;·&nbsp; applying to AI and computer science degrees for autumn 2027
</p>

<p align="center">
  <a href="https://paulspythoncourse.com/"><img src="https://img.shields.io/badge/Paul's_Python_Course-1%2C000%2B_users-4F46E5?style=for-the-badge&logo=python&logoColor=white" alt="Paul's Python Course: 1,000+ users"></a>
  <a href="https://linkedin.com/in/paul-nercessian-b00427383"><img src="https://img.shields.io/badge/LinkedIn-334155?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:nercessianpaul@gmail.com"><img src="https://img.shields.io/badge/Email-334155?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<table align="center">
  <tr>
    <td align="center" width="20%"><h2>1,000+</h2><sub>users on Paul's Python Course</sub></td>
    <td align="center" width="20%"><h2>116</h2><sub>course projects, from <code>print</code> to a tiny GPT</sub></td>
    <td align="center" width="20%"><h2>1,484</h2><sub>exam questions in Screening Prep, checked by 876 tests</sub></td>
    <td align="center" width="20%"><h2>0.89</h2><sub>ROC AUC for DriftSync's Transformer (synthetic data)</sub></td>
    <td align="center" width="20%"><h2>20+</h2><sub>public projects across ML, simulation, games and tools</sub></td>
  </tr>
</table>

<p align="center">
  <a href="#flagship-pauls-python-course">Flagship</a> &nbsp;·&nbsp;
  <a href="#machine-learning">Machine learning</a> &nbsp;·&nbsp;
  <a href="#simulation-and-learning-tools">Simulation and learning tools</a> &nbsp;·&nbsp;
  <a href="#games-and-apps">Games and apps</a> &nbsp;·&nbsp;
  <a href="#skills">Skills</a>
</p>

---

### About

I started out making games in C# and Unity, and I still work the same way now that my focus is machine learning: build the whole system end to end, ship it, then test it hard and write down what did not work. I care most about whether a result is real, so my projects come with held-out evaluation, seeded experiments and automated tests.

**Interests:** world models · sequence models · reinforcement learning · computer vision · NLP

**Now:** training LUCID on my own Unity games, and growing Paul's Python Course.

**School:** Dubai International Academy Al Barsha, IB Diploma (HL Design Technology, Business, Mathematics AI)

---

## Flagship: Paul's Python Course

<a href="https://paulspythoncourse.com/">
  <img src="images/pauls-python-course.png" alt="A lesson in Paul's Python Course beside the code editor" width="100%">
</a>

**[paulspythoncourse.com](https://paulspythoncourse.com/)** started as the website for the Python class I teach and has grown to **more than 1,000 users**.

- **116 projects across nine floors of a clocktower**, from a first `print` to a neural network from scratch, a tiny GPT and reinforcement learning
- **Python runs in the browser** through Pyodide, so learners need nothing installed
- **A class register** shows me each student's progress, and I still teach the live class every week
- Built and maintained by me: front end, accounts, database and lesson content

`TypeScript` `Next.js` `Pyodide` `Supabase`

**[Open the site](https://paulspythoncourse.com/)**

---

## Machine learning

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Bouwles/lucid"><img src="https://raw.githubusercontent.com/Bouwles/lucid/main/docs/media/banner.svg" alt="LUCID: a neural game engine" width="100%"></a>
      <br><br>
      <b><a href="https://github.com/Bouwles/lucid">LUCID</a></b> &nbsp;<sub>neural game engine</sub>
      <br>
      A diffusion world model watches recorded play, then generates the game one frame at a time from your key presses, with no game engine, physics code or level data in the loop. EDM preconditioning and context-noise augmentation fight drift, and an evaluation suite measures image quality, long-run stability and whether the dream obeys the controls.
      <br><br>
      <sub><b>Status:</b> pipeline built and tested end to end on a synthetic test game; training on my own Unity games is next.</sub>
      <br><br>
      <code>Python</code> <code>PyTorch</code> <code>Unity</code> <code>FastAPI</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Bouwles/DriftSync"><img src="https://raw.githubusercontent.com/Bouwles/DriftSync/main/docs/assets/driftsync-workspace.png" alt="The DriftSync desktop workspace" width="100%"></a>
      <br><br>
      <b><a href="https://github.com/Bouwles/DriftSync">DriftSync</a></b> &nbsp;<sub>error prediction from behaviour</sub>
      <br>
      Predicts whether a user will make an error in the next 5 trials from their last 20. LSTM and Transformer models, MC-dropout uncertainty and live inference in a desktop app. The Transformer reaches 0.89 ROC AUC on synthetic data; testing on real people is the next step.
      <br><br>
      <code>Python</code> <code>PyTorch</code> <code>Pygame</code>
      <br><br>
      <a href="https://github.com/Bouwles/DriftSync">Source</a> &nbsp;·&nbsp; <a href="https://github.com/Bouwles/DriftSync/releases">Windows download</a>
    </td>
  </tr>
</table>

| Project | What it does | Stack |
| :-- | :-- | :-- |
| [**RL Chess and Snake Lab**](https://github.com/Bouwles/rl-chess-snake-lab) | DQN agent for a custom Snake environment and a self-play chess experiment, with replay memory, checkpointing, seeded configs and tests. | `Python` `PyTorch` `Gymnasium` |
| [**ASL Interpreter**](https://github.com/Bouwles/ASL-Interpreter) · [demo](https://bouwles.github.io/ASL-Interpreter/) | Turns webcam hand landmarks into English sentences in the browser, with a vote-based stability filter and a tested sentence engine. | `JavaScript` `MediaPipe` |
| [**Arabic Sentiment Analyzer**](https://github.com/Bouwles/arabic-sentiment-analyzer) | Arabic NLP pipeline with text preprocessing, a pretrained Transformer model wrapper, CLI, batch mode and a Streamlit demo. | `Python` `Transformers` `Streamlit` |

---

## Simulation and learning tools

| Project | What it does | Stack |
| :-- | :-- | :-- |
| [**Screening Prep**](https://github.com/Bouwles/mbzuai-screening-prep) · [open](https://bouwles.github.io/mbzuai-screening-prep/) | Unofficial revision site for the MBZUAI BSc in AI screening exam: 65 lessons, 1,484 questions, 177 question generators, timed mocks and spaced repetition. 876 tests check every question and 2,000 variants of each generator. | `TypeScript` `React` `Vite` |
| [**Four-Way Traffic Simulation**](https://github.com/Bouwles/Four-Way-Stochastic-Traffic-Simulation) · [demo](https://bouwles.github.io/Four-Way-Stochastic-Traffic-Simulation/) | Seeded stochastic simulation comparing equal-time and adaptive signal control over 250 paired trials with confidence intervals. Built for my IB Mathematics internal assessment. | `JavaScript` |
| [**Magnus Effect Simulation**](https://github.com/Bouwles/Physics-Magnus-Effect-Simulation) · [demo](https://bouwles.github.io/Physics-Magnus-Effect-Simulation/) | Interactive 3D simulation of spin, drag and Magnus force, with force arrows, trajectory trails and live telemetry. | `JavaScript` `Three.js` |
| [**Calculus Practice**](https://github.com/Bouwles/calculus-practice) · [open](https://bouwles.github.io/calculus-practice/) | Randomly generated derivative and integral questions, each with the rule behind its answer. One HTML file that works offline. | `JavaScript` `KaTeX` |

---

## Games and apps

<a href="https://bouwles.github.io/SCRATCH/"><img src="https://raw.githubusercontent.com/Bouwles/SCRATCH/main/docs/screenshots/01-table.jpg" alt="A SCRATCH table mid-run" width="100%"></a>

**[SCRATCH](https://github.com/Bouwles/SCRATCH)** is a billiards roguelite with its own physics. Every table, texture, song and sound effect is generated in code, so the repo contains no image, audio or model files. **[Play in the browser](https://bouwles.github.io/SCRATCH/)**

<details>
<summary><b>More games (6)</b></summary>
<br>

| Project | What it is | Stack |
| :-- | :-- | :-- |
| [**Hand Cannon**](https://github.com/Bouwles/3D-Finger-Tracking-Shooter-Game) · [play](https://bouwles.github.io/3D-Finger-Tracking-Shooter-Game/) | Browser shooter you aim with your index finger and fire with your thumb, using webcam hand tracking. | `JavaScript` `MediaPipe` |
| [**RAJIS**](https://github.com/Bouwles/RAJIS) · [play](https://bouwles.github.io/RAJIS/) | First-person 3D missile defence game with wave survival and online 1v1. | `JavaScript` `Three.js` |
| [**Shatterdome Earth**](https://github.com/Bouwles/Pacific-Rim-Shatterdome-Earth) · [play](https://bouwles.github.io/Pacific-Rim-Shatterdome-Earth/) | Open-world fan game with a headless scenario runner that tests for determinism. | `TypeScript` `Babylon.js` |
| [**Mach 20**](https://github.com/Bouwles/assassination-classroom-last-bell) · [play](https://bouwles.github.io/assassination-classroom-last-bell/) | Fan game about tracking the real target through afterimages. | `JavaScript` `Vite` |
| [**Breaktime**](https://github.com/Bouwles/breaktime) | Fast top-down action roguelite for five-minute breaks. | `JavaScript` |
| [**Horse Tinder**](https://github.com/Bouwles/horse-tinder) · [play](https://bouwles.github.io/horse-tinder/) | A joke made with a friend: 45 horses to swipe on, and they text back. | `JavaScript` |

</details>

<details>
<summary><b>Developer tools and apps (6)</b></summary>
<br>

| Project | What it does | Stack |
| :-- | :-- | :-- |
| [**Assumption Archaeologist**](https://github.com/Bouwles/assumption-archaeologist) | Claude Code plugin that records the unwritten assumptions in a codebase and tracks whether they still hold. | `Claude Code` |
| [**Comment Rot Detector**](https://github.com/Bouwles/comment-rot-detector) | Claude Code plugin that flags comments which stop matching the code after an edit. | `Claude Code` |
| [**KenKen for Paul**](https://github.com/Bouwles/kenken-for-paul) · [play](https://bouwles.github.io/kenken-for-paul/) | Puzzle generator with a solver that guarantees exactly one solution, as a website and a native Mac app. | `JavaScript` `Swift` |
| [**Silo**](https://github.com/Bouwles/Silo) | macOS focus timer, task list and study analytics. | `SwiftUI` `SwiftData` |
| [**PromptForge**](https://github.com/Bouwles/PromptForge) | Local prompt writer for coding agents. | `Ollama` |
| [**PR Tracker**](https://github.com/Bouwles/nercessians-pr-tracker) | Desktop app for gym personal records and progress charts. | `Electron` `React` |

</details>

---

## Skills

**Languages** &nbsp;
![Python](https://img.shields.io/badge/Python-334155?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-334155?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-334155?style=flat-square&logo=javascript&logoColor=white)
![C#](https://img.shields.io/badge/C%23-334155?style=flat-square)
![Swift](https://img.shields.io/badge/Swift-334155?style=flat-square&logo=swift&logoColor=white)
![HTML and CSS](https://img.shields.io/badge/HTML%2FCSS-334155?style=flat-square&logo=html5&logoColor=white)

**ML and data** &nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-334155?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-334155?style=flat-square&logo=huggingface&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-334155?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-334155?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-334155?style=flat-square&logo=pandas&logoColor=white)
![Gymnasium](https://img.shields.io/badge/Gymnasium-334155?style=flat-square)
![MediaPipe](https://img.shields.io/badge/MediaPipe-334155?style=flat-square&logo=mediapipe&logoColor=white)

**Web and apps** &nbsp;
![React](https://img.shields.io/badge/React-334155?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-334155?style=flat-square&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-334155?style=flat-square&logo=supabase&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-334155?style=flat-square&logo=vite&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-334155?style=flat-square&logo=threedotjs&logoColor=white)
![Babylon.js](https://img.shields.io/badge/Babylon.js-334155?style=flat-square&logo=babylondotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-334155?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-334155?style=flat-square&logo=streamlit&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-334155?style=flat-square&logo=swift&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-334155?style=flat-square&logo=electron&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-334155?style=flat-square&logo=unity&logoColor=white)

**Engineering** &nbsp;
![Git](https://img.shields.io/badge/Git-334155?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-334155?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-334155?style=flat-square&logo=pytest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-334155?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-334155?style=flat-square)

---

<p align="center">
  <sub>Get in touch: <a href="mailto:nercessianpaul@gmail.com">nercessianpaul@gmail.com</a></sub>
</p>
