# 男子全員の責任 — 制作資料

## 辞書的定義

マンガ企画『男子全員の責任』の企画・世界観・人物・シナリオ・打ち合わせ資料を整理するためのリポジトリです。現時点では文書の構成仕様と雛形が中心です。

## 用語としての用例

「作品のテーマを01_conceptへ、登場人物の設定を03_charactersへ整理する」のように、制作資料の置き場所を統一する用途で使います。作品名からあらすじや主張を推測せず、内容は各資料で確定させます。

## 思想的背景

[構成仕様](doc/spec.md) は、企画、設定、キャラクター、各話、打ち合わせを分ける設計です。別の種類の情報を混在させず、参照先を明確にして制作を進められる形にします。具体的な作品テーマや作者の思想は、雛形があることだけから確定できません。

## 技術的背景・構成

[manga-docs/](manga-docs/) 以下のMarkdown文書で管理します。アプリや画像生成コードを提供するリポジトリではありません。

- [01_concept/](manga-docs/01_concept/): ログライン・テーマ
- [02_world/](manga-docs/02_world/): 用語・作中年表・舞台
- [03_characters/](manga-docs/03_characters/): 人物設定
- [04_scripts/](manga-docs/04_scripts/): 各話のシナリオ
- [05_meetings/](manga-docs/05_meetings/): 打ち合わせ・アイデア

## 歴史的背景

[2026年3月12日の構成仕様追加](https://github.com/masa-san-jp/Manga-Danshi-Zen-in-No-Sekinin/commit/711fd55c8b2beebbac1511aa288546f917ada0c2) を受け、[PR #1](https://github.com/masa-san-jp/Manga-Danshi-Zen-in-No-Sekinin/pull/1) で manga-docs の雛形を追加しました。これは制作管理用の構成を整えた履歴であり、作品の刊行履歴ではありません。作中の history.md と実際の開発履歴も区別します。

## 展開

構成仕様を入口として各ファイルの内容を充実させていくための土台です。現在の [manga-docs/README.md](manga-docs/README.md) はプレースホルダーです。ディレクトリや話数ファイルの存在を、その作品・エピソードの完成や公開と解釈しないでください。
