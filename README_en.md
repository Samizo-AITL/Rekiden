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
- ⚔️ Russo-Japanese War (1904–1905) → Implemented
- 🌏 Greater East Asia Co-Prosperity Sphere (1942–) → Implemented
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
├─ README.md ← Japanese top page
├─ README_en.md ← English top page
├─ docs/
│ └─ game_spec.md ← Game rules and structure
├─ sengoku/
│ ├─ README.md ← Sengoku overview
│ ├─ periods/
│ │ ├─ 1561_kawanakajima_en.md
│ │ ├─ 1582-2_chugoku_ogaeshi_en.md
│ │ ├─ 1600_sekigahara_en.md
│ │ ├─ 1600_uesugi_if_en.md
│ │ └─ 1614_osaka_campaign_en.md
├─ bakumatsu/
│ └─ ryoma_if_government.md
├─ 1900s/
│ └─ russo_japanese_war_if.md
├─ ww2/
│ └─ daitoa_kyouei_if.md
├─ templates/
│ └─ scenario_template.md
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
- Choose a playable faction or character (e.g., “Saigo Takamori,” “Ryoma Sakamoto,” or “Uesugi Kenshin”)
- Make decisions each turn (“Attack,” “Negotiate,” “Retreat,” etc.)
- ChatGPT generates results dynamically and advances the story

> 🧠 ChatGPT acts as Game Master, Narrator, and Engine—all in one.

---

## 📘 How to Start

▶︎ [Getting Started Guide (how_to_play_en.md)](./docs/how_to_play_en.md)

---

## 📜 Available Scenarios (EN/JPN)

### 🏯 Sengoku Period
| Year | Title | File |
|--------|------------------------------------------|--------------------------------------------------------|
| 1561 | Battle of Kawanakajima | [1561_kawanakajima_en.md](./sengoku/periods/1561_kawanakajima_en.md) |
| 1582 | The Great Return from Chūgoku | [1582-2_chugoku_ogaeshi_en.md](./sengoku/periods/1582-2_chugoku_ogaeshi_en.md) |
| 1600 | Battle of Sekigahara | [1600_sekigahara_en.md](./sengoku/periods/1600_sekigahara_en.md) |
| 1600 | Righteous Rule – Rise of Tenchijin (If) | [1600_uesugi_if_en.md](./sengoku/periods/1600_uesugi_if_en.md) |
| 1614 | Siege of Osaka | [1614_osaka_campaign_en.md](./sengoku/periods/1614_osaka_campaign_en.md) |

### 🎌 Bakumatsu
| Title | File |
|------------------|--------------------------------------------------------|
| Ryoma’s Path to Reform (If) | [ryoma_if_government_en.md](./bakumatsu/ryoma_if_government_en.md) |

### ⚔️ Russo-Japanese War
| Title | File |
|------------------|--------------------------------------------------------|
| Russo-Japanese Peace Route (If) | [russo_japanese_war_if_en.md](./1900s) |

### 🌏 Greater East Asia Co-Prosperity
| Title | File |
|------------------|--------------------------------------------------------|
| Dawn of the Sphere (If) | [daitoa_kyouei_if_en.md](./ww2) |

---

## 🧠 GPT Benefits Summary

| Feature | GPT Capabilities |
|------------------------|----------------------------------------------------|
| Strategic Reasoning | Suggests tactics based on map, allies, economy |
| What-If Branching | Generates alternate outcomes and narratives |
| Dynamic Event Narration| Describes war, diplomacy, disasters, reforms |
| Educational Context | Provides background, causes, and consequences |
| Story-Driven Gameplay | Fully adaptable progression based on choices |

---

## 🧪 Example Play Log

- [Battle of Kawanakajima – Template Log (ENG)](templates/1561_kawanakajima_template_en.md)

---

## 🚀 Roadmap

- ✅ 7+ Sengoku scenarios (JP) complete
- ✅ English support for key battles (Kawanakajima, Sekigahara, Osaka)
- ✅ New If-scenarios: Bakumatsu, Russo-Japan, Asia Sphere
- 🔜 More translations and streamlined GUI
- 🔜 Save/Resume support (Markdown + JSON)

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
Fork it. Translate it. Rewrite history.

---
