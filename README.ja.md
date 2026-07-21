<p align="center">
  <a href="README.md">English</a> |
  <a href="README.zh-CN.md">简体中文</a> |
  <strong>日本語</strong>
</p>

# Entwined Quills

> *エラリー・クイーン生誕120周年記念ファンジン*  
> 中国のエラリー・クイーン愛好家による記念プロジェクトです。

---

## このプロジェクトについて

**Entwined Quills** は、**エラリー・クイーン生誕120周年**を記念して制作された特別プロジェクトです。

より多くの読者に手に取って楽しんでいただけるよう、私たちが自主制作したデジタル版を公開しています。

他言語への翻訳も歓迎しています。翻訳してくださる方は、ぜひ Pull Request で成果をご投稿ください。

## プロモーション素材

### ポスター

![プロモーションポスター](promotional-poster.jpg)

### プロモーション動画

https://github.com/user-attachments/assets/2a72cb93-78a5-4cc7-863a-19984768d463

## 収録内容

本ファンジンは、小説、評論、翻訳、Q&A資料、参考年表を一冊にまとめたものです。

### 第1巻

中国のエラリー・クイーン愛好家が執筆した7篇のトリビュート小説。

### 第2巻

- 中国の愛好家によるエラリー・クイーン評論
- 日本およびアメリカの評論の中国語訳
- Q&Aセクション

### 特別資料

ファンジンの巻末には、次の3つの年表を収録しています。

1. 作者たちの創作活動の年表
2. 作品の刊行年月日をまとめた年表
3. エラリー・クイーンとドルリー・レーンが解決した事件の推定年代順年表

これらの年表は、多数の資料を参照して作成しました。

## イラスト

ファンジンには、エラリー・クイーン作品の名場面を描いた18点のイラストを収録しています。

## タイトルの由来

ファンジンのタイトルには、**「Entwined Quills」**を選びました。

- 略称が **EQ** となり、Ellery Queen を直接示していること
- 表紙の書名に配された **Q**
- 絡み合う羽根のイメージが、二人の作家、協働、創作を象徴していること

タイトル決定後、EQが愛した言葉遊びのように、**「Entwined Quills」**の文字を並べ替えると次の言葉になることに気づき、私たちは喜びました。

> **Queen still wind**

中国語タイトルは **缱绻之翎**  
ピンイン：**Qiǎnquǎn Zhī Líng**

この中国語タイトルは、古典的で優雅な響きと文学的な趣を込めて選ばれました。

## 読者の皆さまへ

本ファンジンをお読みになった方からのご感想をお待ちしています。長文のレビューでも短いコメントでも、心より歓迎いたします。

- [Issues](https://github.com/FugeCantabile/Entwined-Quills/issues) へのご投稿を歓迎します
- 外部サイトでレビューを公開された場合は、そのリンクも Issue でぜひお知らせください

皆さまのご感想を楽しみにしています。

### コメント Issue の投稿方法

GitHub CLI を使用する場合：

```bash
# 1. 必要に応じてリポジトリを Fork または clone する
git clone https://github.com/FugeCantabile/Entwined-Quills.git
cd Entwined-Quills

# 2. GitHub CLI にログインする
gh auth login

# 3. 短いコメントや長文レビューを Issue として投稿する
gh issue create \
  --title "My reading notes on Entwined Quills" \
  --body "I have finished reading the fanzine. Here are my comments..."
```

外部サイトのレビューへのリンクを共有する場合：

```bash
gh issue create \
  --title "Review link: [your review title]" \
  --body "I published my review here: https://example.com/your-review"
```

## 翻訳でのご協力

**このプロジェクトの翻訳に関心をお持ちの方からのご協力を、心より歓迎いたします。**

特に次の翻訳を歓迎しています。

- 英語訳
- 日本語訳
- その他の言語への翻訳

このリポジトリは、主として公開済みのデジタル版そのものを保管するためのものです。翻訳は原版を置き換えず、追加ファイルとしてご投稿ください。

### 翻訳の Pull Request を投稿する方法

翻訳にご協力いただく場合は、次の手順を推奨します。

```bash
# 1. GitHub 上でリポジトリを Fork し、自分の Fork を clone する
git clone https://github.com/YOUR_USERNAME/Entwined-Quills.git
cd Entwined-Quills

# 2. 元のリポジトリを upstream として追加する
git remote add upstream https://github.com/FugeCantabile/Entwined-Quills.git

# 3. 翻訳用ブランチを作成する
git checkout -b translation/en-readme

# 4. 翻訳ファイルを追加する
# 例：
# README.en.md

# 5. 変更をステージし、コミットする
git add README.en.md
git commit -m "Add English translation of README"

# 6. ブランチを自分の Fork に push する
git push origin translation/en-readme

# 7. GitHub CLI で Pull Request を作成する
gh pr create \
  --repo FugeCantabile/Entwined-Quills \
  --base main \
  --head YOUR_USERNAME:translation/en-readme \
  --title "Add English translation of README" \
  --body "This PR adds an English translation of README.md."
```

GitHub CLI を使用しない場合も、同じ Git の手順を行った後、GitHub のウェブ画面から Pull Request を作成できます。

ご投稿いただいた内容は、できる限り速やかに確認し、更新いたします。

## ライセンス

本プロジェクトは、[CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) ライセンスのもとで提供されています。

- **表示（BY）：** 原著作者を適切に表示する必要があります
- **非営利（NC）：** 本資料を営利目的で使用することはできません
- **継承（SA）：** 本資料を改変、変形、または加工した場合、同じライセンスのもとでその成果を頒布する必要があります

---

**Entwined Quills = Queen still wind**
