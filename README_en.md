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
  - 🎌 Bakumatsu Period (1860s) → Implemented
  - 🔮 Future Japan (Post-Reconstruction) → Implemented
- **Goal**:
  - Learn and experience historical context by interacting with AI to explore alternative paths
  - Combine strategic thinking, narrative generation, and educational utility into one framework

---

## 🏯 What is the Sengoku Period?

New to Japanese history?  
See our short introduction to understand the **chaotic and fascinating era** of warlords, alliances, betrayals, and ambition.

▶︎ [Intro to the Sengoku Period (sengoku_intro_en.md)](./docs/sengoku_intro_en.md)

---

## 📂 Directory Structure

```
Rekiden/
├─ README.md                ← Japanese top page
├─ README_en.md             ← English top page
├─ docs/
│  └─ game_spec.md          ← Game rules and structure
├─ sengoku/
│  ├─ periods/
│  │  ├─ 1561_kawanakajima_en.md
│  │  ├─ 1582-2_chugoku_ogaeshi_en.md
│  │  ├─ 1600_sekigahara_en.md
│  │  ├─ 1600_uesugi_if_en.md
│  │  └─ 1614_osaka_campaign_en.md
├─ bakumatsu/
│  └─ ryoma_if_government_en.md
├─ future/
│  └─ future_reconstruction_path_if_en.md
├─ templates/
│  └─ scenario_template.md
```

---

## 🎮 Core Features

- **Turn-Based Gameplay**: Seasonal choices (Spring/Summer/Fall/Winter) with branching outcomes
- **Character Stats**: Leadership, Martial, Intelligence, Politics, Charisma
- **Nation Stats**: Population, Troops, Economy, Fortifications, Food, etc.
- **Event System**: War, Revolts, Betrayals, Natural Disasters, Diplomacy, and more

---

## 🤖 ChatGPT Integration

Rekiden is designed to be played interactively with ChatGPT (GPT-4 or later):

- Paste any scenario `.md` file into ChatGPT
- Choose a playable character (e.g., “Uesugi Kenshin,” “Ryoma Sakamoto,” or a future leader)
- Make decisions each turn (“Attack,” “Negotiate,” “Rebuild,” etc.)
- ChatGPT dynamically generates the narrative and continues the story

> 🧠 ChatGPT acts as Game Master, Narrator, and Engine—all in one.

---

## 📘 How to Start

▶︎ [Getting Started Guide (how_to_play_en.md)](./docs/how_to_play_en.md)

---

## 📜 Available Scenarios (EN)

### 🏯 Sengoku Period
| Year | Title                            | File                                                                 |
|------|----------------------------------|----------------------------------------------------------------------|
| 1555 | The Tripartite Alliance          | [1555_sangoku_alliance_en.md](./sengoku/periods/1555_sangoku_alliance_en.md) |
| 1561 | Battle of Kawanakajima           | [1561_kawanakajima_en.md](./sengoku/periods/1561_kawanakajima_en.md) |
| 1575 | Battle of Nagashino              | [1575_nagashino_en.md](./sengoku/periods/1575_nagashino_en.md) |
| 1582 | The Great Return from Chūgoku    | [1582-2_chugoku_ogaeshi_en.md](./sengoku/periods/1582-2_chugoku_ogaeshi_en.md) |
| 1600 | Battle of Sekigahara             | [1600_sekigahara_en.md](./sengoku/periods/1600_sekigahara_en.md) |
| 1600 | Righteous Rule (If Scenario)     | [1600_uesugi_if_en.md](./sengoku/periods/1600_uesugi_if_en.md) |
| 1614 | Siege of Osaka                   | [1614_osaka_campaign_en.md](./sengoku/periods/1614_osaka_campaign_en.md) |

### 🎌 Bakumatsu
| Title | File |
|-----------------------------|------------------------------------------------------------|
| Ryoma’s Path to Reform (If) | [ryoma_if_government_en.md](./bakumatsu/ryoma_if_government_en.md) |

### 🔮 Future Japan (Post-Reconstruction)
| Title | File |
|----------------------------------------|--------------------------------------------------------------------------|
| Memory of the Trench – Rebuilding Japan (If) | [future_reconstruction_path_if_en.md](./future/future_reconstruction_path_if_en.md) |
> ⚠️ **Note**: This scenario is not part of the core Rekiden historical series.
> It is an experimental "future simulation" that builds on the Rekiden system architecture and gameplay format.
> Designed for educational use, it explores post-disaster recovery, societal decision-making, and the integration of AITL-H technologies.
> The goal is to encourage critical thinking about future policies, technological impacts, and ethical dilemmas through AI-powered simulation.

---

## 🧠 GPT Benefits Summary

| Feature              | GPT Capabilities                                               |
|----------------------|----------------------------------------------------------------|
| Strategic Reasoning  | Suggests tactics based on terrain, diplomacy, economy          |
| What-If Exploration  | Simulates alternate histories with realism                     |
| Dynamic Storytelling | Creates vivid narratives from decisions and consequences       |
| Educational Utility  | Explains historical background, context, and decision outcomes |
| Adaptable Gameplay   | Fully personalized story progression through user input        |

---

## 🧪 Sample Play Log

- [Battle of Kawanakajima – Uesugi Kenshin Play Log (ENG)](templates/1561_kawanakajima_kenshin_user001.md)

- [Battle of Kawanakajima(Fūrin Kazan Mode)– Takeda Shingen Play Log (ENG)](templates/1561_kawanakajima_furinkazan_en.md)

---

## 🚀 Roadmap

- ✅ All Sengoku core scenarios implemented (JP)
- ✅ Key scenarios translated to English
- ✅ Future scenario support (reconstruction, AI governance, disaster recovery)
- 🔜 GUI / Streamlit support
- 🔜 Save/Resume with Markdown + JSON

---

## 📜 License

MIT License © 2025 Shinichi Samizo  
See [LICENSE](./LICENSE) for full terms.

---

## 👤 Author

**Shinichi Samizo**  
Engineer (Semiconductors & Control Systems) / Historical Simulation Developer  
GitHub: [Samizo-AITL](https://github.com/Samizo-AITL)  
Email: [shin3t72@gmail.com](mailto:shin3t72@gmail.com)

---

Rekiden is where AI meets history.  
Explore it. Expand it. Evolve the future.

---
