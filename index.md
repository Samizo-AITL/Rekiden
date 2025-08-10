---
title: Rekiden
---

<style>
html,body{height:100%; margin:0;}
body{
  background-image:url('{{ site.baseurl }}/assets/images/washi.PNG');
  background-size:cover;
  background-position:center;
  background-attachment:fixed;
}

/* Minimaのヘッダー・フッター・白枠などを消す */
.site-header, .site-footer, .site-title {
  display: none !important; /* ←ヘッダー消す */
}
.page-content, .wrapper, .page, .post, .post-list,
.site-nav, .site-nav .page-link {
  background: transparent !important;
  box-shadow: none !important;
  border: none !important;
}

/* ▼ A) 完全に背景だけ（読みやすさ補助なし） */
.main{
  max-width:980px; margin:2rem auto; padding:0;
  background: transparent;
}

/* ▼ B) 少しだけ白地を入れて可読性UP（Aを無視して使いたい方だけON）
.main{
  max-width:980px; margin:2rem auto; padding:1.5rem;
  background: rgba(255,255,255,.55);
  border-radius: 8px;
  backdrop-filter: blur(1px);
}
*/
</style>

<div class="main" markdown="1">

# Rekiden
# 🏯🌍 **Rekiden – 戦国とWW2を体験する歴史ifシミュレーション**

**Rekiden** は、日本の **戦国時代** と **第二次世界大戦** をテーマにした、ChatGPT連携型の  
**歴史ifシナリオ教材／戦略シミュレーションフレームワーク**です。  
あなたは **武将・国家指導者・科学者**として、歴史の転換点に立ち、対話によって「ifの選択」を行い、  
その先の世界を追体験します。

---

🏠 [**English Version is here**](./README_en.md)  
→ Experience **Rekiden** in English

---

## 🎮 **遊び方（ChatGPTと対話）**

1. `.md` シナリオファイルを **ChatGPT** に貼り付ける  
2. **プレイヤーキャラを指定**（例：上杉謙信、山本五十六など）  
3. **ターンごとに選択肢を入力**（例：交渉／進軍／研究）  
4. **ChatGPT** が **物語・状況・結末を生成・進行**

> ChatGPT は **ナレーター・ゲームマスター・エンジン**を兼ねて進行します。

---

## 🏯 **戦国時代シナリオ (1555–1614)**

### ⚔️ **時代別シナリオ一覧**

| 年号 | 陣営 / 主人物 | タイトル | リンク |
|---|---|---|---|
| 1555年 | 今川義元・武田信玄・北条氏康 | 三国同盟 | [1555_sangoku_alliance.md](./sengoku/periods/1555_sangoku_alliance.md) |
| 1561年 | 武田信玄 vs 上杉謙信 | 川中島の戦い | [1561_kawanakajima.md](./sengoku/periods/1561_kawanakajima.md) |
| 1575年 | 織田信長・徳川家康 vs 武田勝頼 | 長篠の戦い | [1575_nagashino.md](./sengoku/periods/1575_nagashino.md) |
| 1582年 | 明智光秀 vs 羽柴秀吉 | 本能寺と中国大返し | [1582-2_chugoku_ogaeshi.md](./sengoku/periods/1582-2_chugoku_ogaeshi.md) |
| 1600年 | 上杉景勝（if） vs 徳川家康 | 義の天下（上杉 if） | [1600_uesugi_if.md](./sengoku/periods/1600_uesugi_if.md) |
| 1614年 | 真田幸村・豊臣秀頼 vs 徳川秀忠 | 大坂の陣（真田丸） | [1614_osaka_campaign.md](./sengoku/periods/1614_osaka_campaign.md) |

📘 **海外プレイヤー向け背景解説：**  
[**Sengoku Introduction in English**](./docs/sengoku_intro_en.md)

---

## 🌍 **第二次世界大戦シナリオ (1939–1945)**  
**連合国** 🇬🇧 🇺🇸 🇫🇷 vs. **枢軸国** 🇩🇪 🇮🇹 🇯🇵

### 🎮 **プレイアブル・シナリオ一覧**

| 年代 | 国家 | プレイヤー | タイトル | リンク |
|---|---|---|---|---|
| 1941年 | 🇯🇵 日本 | 山本五十六 | 真珠湾とミッドウェーの海軍戦略 | [yamamoto_navy.md](./ww2/japan/yamamoto_navy.md) |
| 1941年 | 🇺🇸 米国 | ルーズベルト | 総力戦と国際同盟の決断 | [roosevelt_strategy.md](./ww2/usa/roosevelt_strategy.md) |
| 1945年 | 🇺🇸 米国 | オッペンハイマー | 原爆開発と科学倫理の葛藤 | [oppenheimer_ethics.md](./ww2/usa/oppenheimer_ethics.md) |
| 1942年 | 🇺🇸 米国 | マッカーサー | 太平洋戦線・フィリピン奪還作戦 | [macarthur_pacific.md](./ww2/usa/macarthur_pacific.md) |
| 1939年 | 🇩🇪 独 | ヒトラー | ポーランド侵攻と外交の岐路 | [hitler_politics.md](./ww2/germany/hitler_politics.md) |

📖 [**第二次世界大戦 時代背景（日本語）**](./ww2/ww2_overview.md)

---

### 🐉 [**諸葛亮と赤壁の戦い** — *The Sleeping Dragon Awakens (AD 208)*](./three_kingdoms/red_cliffs_en.md)

---

## 📘 **関連ガイド・素材**
- [**how_to_play.md**](./docs/how_to_play.md)  
- [**templates/**](./templates/)

---

## 👤 **作成者情報 / Author**

**三溝 真一（Shinichi Samizo）**  

半導体×制御×AI×歴史　統合クリエイター

📬 **連絡先**  
- ✉️ [shin3t72@gmail.com](mailto:shin3t72@gmail.com)  
- 🐦 [https://x.com/shin3t72](https://x.com/shin3t72)  
- 💻 [https://samizo-aitl.github.io/](https://samizo-aitl.github.io/)

---

## 📜 **ライセンス**
MIT License © 2025 Shinichi Samizo — see [LICENSE](./LICENSE)

---

## 💬 **ご意見・フィードバック募集**

**Rekiden プロジェクト**では、皆さまからの  
**ご意見・ご提案・改善案**を歓迎しています。

- 「教材としての使い方」  
- 「戦略の表現方法」  
- 「他時代への応用」 など

ぜひお気軽にお寄せください。

👉 [**ディスカッションはこちら（GitHub Discussions）**](https://github.com/Samizo-AITL/Rekiden/discussions)

あなたの知見が、この教材をより深く豊かにします。

---

## 🖼️ **上杉謙信 - 川中島の戦い（1561年）**

![上杉謙信 川中島の戦い](./Uesugi_Kenshin_Kawanakajima_1561.png)

若き謙信が馬上から突撃する姿を描いた**リアルな油彩風イメージ**。  
**Rekiden教材の導入ヴィジュアル**として使用可能です。

</div>
