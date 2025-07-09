# 🏯 Rekiden – A ChatGPT-Powered Historical Simulation Framework

**Rekiden** is a text-based, open-source simulation game that lets you relive—and reshape—turning points in Japanese history.  
Interact with ChatGPT to take on the role of historical figures and make critical decisions that change the course of history.

This is more than a game. Rekiden is an educational and interactive framework for exploring historical “what-ifs.”

---

## 🎯 Project Overview

- **Genre**: Historical Simulation / Strategy (Text-based)
- **Format**: Markdown-based scenarios with decision branches
- **Supported Eras**:
  - 🏯 Sengoku Period (1555–1615) → Fully implemented
  - 🎌 Bakumatsu Period (1860s) → In progress
- **Goal**: Learn and experience historical context by interacting with AI to explore alternative paths

---

## 📂 Directory Structure

```
Rekiden/
├─ README.md                   ← Japanese version
├─ README.en.md                ← English version (this file)
├─ docs/
│  └─ game_spec.md             ← Rules, stats, turn structure
├─ scenarios/
│  ├─ sengoku/
│  │  ├─ README.md
│  │  ├─ periods/
│  │  │  ├─ 1555_sangoku_alliance.md
│  │  │  ├─ 1560_okehazama.md
│  │  │  ├─ 1561_kawanakajima.md
│  │  │  ├─ 1561_kawanakajima_en.md   ← ← NEW
│  │  │  ├─ 1575_nagashino.md
│  │  │  ├─ 1582-1_honnoji.md
│  │  │  ├─ 1582-2_chugoku_ogaeshi.md
│  │  │  └─ 1590_odawara_if.md
│  │  ├─ busho_stats.md
│  │  ├─ province_data.md
│  │  └─ diplomacy_matrix.md
│  └─ bakumatsu/
│     └─ README.md
├─ templates/
│  └─ scenario_template.md
├─ play_logs/
│  └─ okehazama_oda_user001.md
```
---

## 🎮 Core Features

- **Turn-Based Gameplay**: Seasonal (Spring/Summer/Fall/Winter) choices with branching outcomes
- **Character Stats**: Leadership, Martial, Intelligence, Politics, Charisma
- **Nation Stats**: Population, Troop size, Economy, Fortifications, Food, etc.
- **Event System**: War, Revolts, Alliances, Betrayals, Natural Disasters, and more

---

## 🤖 ChatGPT Integration

Rekiden is designed to be played interactively with ChatGPT (GPT-4 or later):

- Paste any scenario `.md` file into ChatGPT
- Choose a playable faction or character (e.g., “Takeda Shingen”)
- Make decisions each turn (“Attack,” “Negotiate,” “Defend”)
- ChatGPT will generate outcomes dynamically and continue the story

> 🧠 ChatGPT acts as Game Master, Narrator, and Engine—all in one.

---

## 📘 How to Start

▶︎ See the [Getting Started Guide (how_to_play.md)](./docs/how_to_play_en.md)

---

## 📚 Available Scenarios

| Year    | Title                           | File (English version)                                           |
|---------|----------------------------------|------------------------------------------------------------------|
| 1555    | Three-Way Alliance (Sangoku)     | *(Not yet translated)*                                           |
| 1560    | Battle of Okehazama              | *(Not yet translated)*                                           |
| 1561    | **Battle of Kawanakajima**       | [1561_kawanakajima_en.md](./sengoku/periods/1561_kawanakajima_en.md) |
| 1575    | Battle of Nagashino              | *(Not yet translated)*                                           |
| 1582-1  | Incident at Honnō-ji             | *(Not yet translated)*                                           |
| 1582-2  | The Great Return from Chūgoku    | *(Not yet translated)*                                           |
| 1590    | Siege of Odawara (Alternate Win) | *(Not yet translated)*                                           |
| 1600    | Battle of Sekigahara             | 🔧 Coming Soon                                                   |
| 1614    | Siege of Osaka                   | 🔧 Coming Soon                                                   |

---

## 🧠 GPT Benefits Summary

| Feature               | GPT Capabilities                                    |
|------------------------|----------------------------------------------------|
| Strategic Reasoning    | Suggests optimal tactics based on context          |
| What-If Branching      | Generates realistic alternate historical scenarios |
| Event Narration        | Describes battles, betrayals, diplomacy in detail  |
| Adaptive Story Flow    | Adjusts plotline as your actions evolve            |
| Educational Context    | Explains historical background and consequences    |

---

## 📘 Example Play Log

- [Battle of Okehazama – Oda Nobunaga (Legacy Format)](play_logs/okehazama_oda_user001.md)

---

## 🚀 Roadmap

- ✅ All 7 major Sengoku scenarios implemented (JP)
- 🔜 English translations for all scenarios
- 🔜 Bakumatsu scenarios (Saigō, Katsu, Tokugawa)
- 🔜 Web UI or Streamlit-based GUI
- 🔜 Save/Resume system (via Markdown/JSON)

---

## 📜 License

MIT License © 2025 Shinichi Samizo  
See [LICENSE](LICENSE) for full terms.

---

## 👤 Author

**Shinichi Samizo**  
Engineer (Semiconductors & Control Systems) / Educational Framework Developer  
[GitHub](https://github.com/Samizo-AITL) / [Email](mailto:shin3t72@gmail.com)

---

Rekiden is where AI meets history. Fork it. Translate it. Build your own simulation of the past.

