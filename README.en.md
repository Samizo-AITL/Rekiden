# 🏯 Rekiden – A ChatGPT-Powered Historical Simulation Framework

**Rekiden** is a text-based, open-source simulation game framework that lets you relive—and reshape—turning points in Japanese history.  
By interacting with ChatGPT, you take the role of key historical figures and make critical decisions that alter the course of history.

Rekiden is not just a game. It's an **educational, interactive, and expandable framework** for simulating historical what-ifs.

---

## 🎯 Project Overview

- **Genre**: Historical Simulation / Strategy (Text-based)
- **Format**: Markdown-based turn scenarios with decision branches
- **Supported Eras**:
  - 🏯 Sengoku Period (1555–1615) → Fully implemented
  - 🎌 Bakumatsu / Late Edo Period (1860s) → In progress
- **Purpose**: Learn and experience history by interacting with AI to explore alternate paths and possible outcomes

---

## 📂 Directory Structure


Rekiden/
├─ README.md                 ← Japanese version
├─ README.en.md              ← English version (this file)
├─ docs/
│  └─ game_spec.md           ← Rules, parameters, and turn flow
├─ scenarios/
│  ├─ sengoku/               ← Sengoku period scenarios (7 key eras)
│  │  ├─ README.md
│  │  ├─ periods/
│  │  ├─ busho_stats.md      ← Character stats: Leadership, Strategy, etc.
│  │  ├─ province_data.md    ← Nation data: Population, Army, Economy
│  │  └─ diplomacy_matrix.md ← Alliance / Rival relationship chart
│  └─ bakumatsu/             ← Coming soon
├─ templates/
│  └─ scenario_template.md   ← Scenario format with choices
├─ play_logs/
│  └─ okehazama_oda_user001.md ← Example play log


---

## 🎮 Key Features

- **Turn-based Simulation**: Seasonal turns (Spring, Summer, Fall, Winter) with decision prompts
- **Character Stats**: Leadership, Combat, Intelligence, Politics, Charisma
- **Nation Stats**: Population, Army size, Economy, Defense, Food supply
- **Event-based Flow**: Battles, Betrayals, Natural Disasters, Diplomacy, Uprisings

---

## 🤖 Play with ChatGPT

Rekiden is built to be played with ChatGPT (GPT-4 or later), acting as your **Game Master**.

- Simply paste a scenario Markdown file into ChatGPT
- Choose a historical character (e.g., Oda Nobunaga)
- Make decisions turn by turn (“Invade Mino”, “Form alliance with Tokugawa”)
- ChatGPT dynamically generates the consequences and events

> GPT is not just a tool—it is the game master, narrator, and opponent.

---

### 🧠 Benefits of GPT Integration

| Feature            | What GPT does                                  |
|--------------------|-------------------------------------------------|
| Strategic Feedback | Suggests options based on terrain and forces    |
| Alt-History Logic  | Generates plausible "what-if" branches          |
| Immersive Events   | Narrates battles, betrayal, diplomacy scenes    |
| Dynamic Flow       | Adapts story to your decisions and alliances    |
| Educational Value  | Explains history interactively and contextually |

---

## 📘 Example Play Log

- [Battle of Okehazama – Oda Nobunaga](play_logs/okehazama_oda_user001.md)
- Markdown-based, reproducible, and forkable for custom playthroughs

---

## 🚀 How to Use

- 🧑‍🏫 As a learning tool with students
- 🧙 As an RPG-like GPT experience
- 🛠️ As a base for developing UI-based historical games

No coding required. Just Markdown, ChatGPT, and imagination.

---

## 🛠 Roadmap

- ✅ Full Sengoku period scenario (7 eras)
- 🔜 Bakumatsu period scenario (Saigo, Katsu, Tokugawa, etc.)
- 🔜 Web UI / GUI version (HTML or Python Streamlit)
- 🔜 Save/Load functionality via Markdown or JSON

---

## 📜 License

MIT License © 2025 Shinichi Samizo  
See [LICENSE](LICENSE) for full terms.

---

## 👤 Author

**Shinichi Samizo**  
Engineer (Semiconductors & Control Systems) / AI & Education Developer  
[GitHub](https://github.com/Samizo-AITL) / [Email](mailto:shin3t72@gmail.com)

---

> Rekiden is a unique blend of history, AI, and creativity.  
> Fork it. Translate it. Build your own alternate history.

---
