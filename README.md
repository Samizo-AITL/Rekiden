# 🏯 Rekiden（歴伝）– ChatGPT連携・歴史シミュレーションゲームフレームワーク

**Rekiden（歴伝）** は、日本史の転換点をテーマにしたテキストベースの歴史シミュレーションゲームです。
👉 ChatGPTとの対話を通じて、歴史の「if」を体験しながら遊べる新感覚フレームワークです。

プレイヤーは戦国大名や幕末志士、近代国家の指導者となり、外交・戦術・内政・交渉を選択し、GPTがその結果を進行・描写します。

---

## 🎮 まずはここから：戦国時代をプレイしよう！

Rekidenの中核は**戦国時代**シナリオです。
信長・謙信・秀吉・家康などになりきって、外交・合戦・登用・裏切りを戦略的に選びましょう。

| 年号 | タイトル | シナリオリンク |
|----------|--------------------------|------------------------------------------------------------------|
| 1555年 | 三国同盟 | [1555_sangoku_alliance.md](./sengoku/periods/1555_sangoku_alliance.md) |
| 1561年 | 川中島の戦い | [1561_kawanakajima.md](./sengoku/periods/1561_kawanakajima.md) |
| 1575年 | 長篠の戦い | [1575_nagashino.md](./sengoku/periods/1575_nagashino.md) |
| 1582年 | 本能寺と中国大返し | [1582-2_chugoku_ogaeshi.md](./sengoku/periods/1582-2_chugoku_ogaeshi.md) |
| 1600年 | 義の天下（上杉if） | [1600_uesugi_if.md](./sengoku/periods/1600_uesugi_if.md) |
| 1614年 | 大坂の陣（真田丸） | [1614_osaka_campaign.md](./sengoku/periods/1614_osaka_campaign.md) |

> 💬 例：「1561年の川中島で上杉謙信を選んでプレイします」とGPTに伝えるだけで即スタート！

---

## 📚 拡張対応：幕末・日露戦争・大東亜共栄圏（ifルート中心）

以下は「if歴史展開」をテーマとした教育的シナリオ群です：

| 時代 | テーマ | シナリオ例 |
|------------|--------------------------------|------------------------------------|
| 🎌 幕末 | 龍馬if・薩長同盟・大政奉還 | [ryoma_if_government.md](./bakumatsu/ryoma_if_government.md) |
| ⚔️ 日露戦争 | ポーツマス講和／朝鮮中立構想 | [russo_japanese_war_if.md](./1900s/russo_japanese_war_if.md) |
| 🌏 昭和前期 | 大東亜共栄圏の連携ルート | [daitoa_kyouei_if.md](./ww2/daitoa_kyouei_if.md) |

---

## 🎯 プロジェクト概要

- **ジャンル**：歴史シミュレーション／ストラテジー（対話型）
- **形式**：Markdownで管理されたターン制シナリオ（選択肢ベース）
- **目的**：
- 歴史的状況を再現し、異なる選択肢によって「ifの歴史」を体験できる教材／ゲームフレームワーク
- 教育・戦略思考・物語生成を融合した実践型学習・創作支援ツール

---

## 🧠 Rekidenの特徴

| 項目 | 特徴内容 |
|------------------|----------|
| ターン制進行 | 春夏秋冬の4ターン制。戦争・内政・外交・登用などを毎ターン選択 |
| if歴史分岐 | ChatGPTが状況に応じて分岐を生成。歴史を仮想的に変える体験が可能 |
| GPT進行役 | GPTがゲームマスターとなり、イベント・結果・会話をナラティブ描写 |
| 教材連携 | 歴史教育や討論教材として使用可能（問い／背景／比較視点付き） |
| 対話型UI対応 | 今後GUI・保存機能との統合を予定（Streamlit・JSON連携など） |

---

## 📘 遊び方ガイド（はじめての方へ）

ChatGPTでのプレイ方法、貼り付け例、進行手順などは以下を参照：

▶︎ [how_to_play.md](./docs/how_to_play.md)

---

## 🧪 実際のプレイ例

- [川中島の戦い（上杉謙信）](./templates/1561_kawanakajima_user001.md)
- [義の天下（上杉景勝）](./templates/1600_uesugi_if_user001.md)
- [大坂の陣（豊臣秀頼）](./templates/1614_osaka_campaign_user001.md)

---

## 🚀 今後の展開

- ✅ 戦国時代：全7シナリオ実装済
- 🔜 幕末〜近代：外交・戦争・政略によるifルート強化
- 🖥 GUIビューア（Webベースの進行・保存）
- 📚 教材スライド・授業導入支援パック
- 🤖 ChatGPT自動戦略生成の全自動化

---

## 📜 ライセンス

MIT License © 2025 Shinichi Samizo
詳細は [LICENSE](./LICENSE) を参照。

---

## 👤 制作・運営

三溝 真一（Shinichi Samizo）
半導体・制御系エンジニア、教育教材開発者
GitHub: [Samizo-AITL](https://github.com/Samizo-AITL)
Email: [shin3t72@gmail.com](mailto:shin3t72@gmail.com)
