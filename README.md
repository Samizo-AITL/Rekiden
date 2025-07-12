# 🏯 Rekiden（歴伝）– ChatGPT連携・歴史シミュレーションゲームフレームワーク

**Rekiden（歴伝）** は、日本史の転換点をテーマにしたテキストベースの歴史シミュレーションゲームです。  
👉 ChatGPTとの対話を通じて、歴史の「if」を体験しながら遊べる新感覚フレームワークです。

---

## 🎯 プロジェクト概要

- **ジャンル**：歴史シミュレーション／ストラテジー（対話型）
- **形式**：Markdownで管理されたターン制シナリオ（選択肢ベース）
- **目的**：
  - 歴史的状況を再現し、異なる選択肢によって「ifの歴史」を体験できる教材／ゲームフレームワーク
  - 教育・戦略思考・物語生成を融合した実践型学習・創作支援ツール

---

## 🗂 実装状況（2025年7月現在）

- 🏯 戦国時代（1555–1615）→ 主要シナリオ6本以上を実装、一部英訳済
- 🎌 幕末（1860年代）→ 龍馬ifルートを実装、他は構想中
- 🔮 未来編（災害復興後）→ AITL-H技術導入型のifルートを試作済

---

## 🧭 戦国時代をプレイしよう！

| 年号 | タイトル | シナリオリンク |
|----------|--------------------------|------------------------------------------------------------------|
| 1555年 | 三国同盟 | [1555_sangoku_alliance.md](./sengoku/periods/1555_sangoku_alliance.md) |
| 1561年 | 川中島の戦い | [1561_kawanakajima.md](./sengoku/periods/1561_kawanakajima.md) |
| 1575年 | 長篠の戦い | [1575_nagashino.md](./sengoku/periods/1575_nagashino.md) |
| 1582年 | 本能寺と中国大返し | [1582-2_chugoku_ogaeshi.md](./sengoku/periods/1582-2_chugoku_ogaeshi.md) |
| 1600年 | 義の天下（上杉if） | [1600_uesugi_if.md](./sengoku/periods/1600_uesugi_if.md) |
| 1614年 | 大坂の陣（真田丸） | [1614_osaka_campaign.md](./sengoku/periods/1614_osaka_campaign.md) |

---

## 📚 幕末・未来編シナリオ（教育的if展開）

### 🎌 幕末
| タイトル | ファイル |
|-----------------------------|------------------------------------------------------------|
| 龍馬if・薩長同盟・大政奉還 | [ryoma_if_government.md](./bakumatsu/ryoma_if_government.md) |

### 🔮 未来編（ポジティブ未来・災害復興）
| タイトル | ファイル |
|--------------------------------|---------------------------------------------------------------|
| 再建の道 – AITL-Hと共に（if） | [future_reconstruction_path_if.md](./future/future_reconstruction_path_if.md) |

---

## 🎮 プレイ方法（ChatGPTとの対話型）

1. シナリオ `.md` ファイルを ChatGPT に貼り付ける
2. プレイヤー（例：上杉謙信、坂本龍馬）を指定する
3. ターンごとに「攻撃」「交渉」「内政」などの選択を入力
4. ChatGPTが状況を進行し、分岐・物語を自動生成する

> ChatGPTが**ゲームマスター・ナレーター・エンジン**を全て兼ねます。

---

## 📘 はじめての方へ

▶︎ [how_to_play.md](./docs/how_to_play.md)：遊び方のガイド

---

## 🧪 プレイログ例（テンプレート）

- [川中島の戦い（上杉謙信）](./templates/1561_kawanakajima_user001.md)
- [義の天下（上杉景勝）](./templates/1600_uesugi_if_user001.md)
- [大坂の陣（豊臣秀頼）](./templates/1614_osaka_campaign_user001.md)

---

## 🚀 今後の展開

- 🔜 幕末・未来編の分岐追加・GUI対応（Streamlit予定）
- 🔜 保存機能（Markdown/JSON形式）
- 🔜 教育活用スライド・授業テンプレートの展開

---

## 📜 ライセンス

MIT License © 2025 Shinichi Samizo  
詳細は [LICENSE](./LICENSE) を参照。

---

## 👤 制作・運営

- 三溝 真一（Shinichi Samizo）  
- 半導体・制御系エンジニア／教育教材開発者  
- GitHub: [Samizo-AITL](https://github.com/Samizo-AITL)  
- Email: [shin3t72@gmail.com](mailto:shin3t72@gmail.com)
