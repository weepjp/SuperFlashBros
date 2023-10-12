# SuperFlashBros (大乱闘フラッシュブラザーズ)

![image](https://user-images.githubusercontent.com/3696720/213860994-09499cff-ff4c-4a80-b13f-47101d758465.png)

- #[swf2js](https://swf2js.com/) Vs. #[Ruffle](https://ruffle.rs/)
- (EN) It's a hot battle (comparison) of Flash <u>"Players"</u>.
- (JA) #swf2js と #ruffle の Flash <u>Player</u> エミュレータたちの熱き比較（バトル）を繰り広げるサイト！ それが、大乱闘フラッシュブラザーズである！

# しくみ (in japanese)

- curl を使って、他サイトの swf を取得。
- 本当に swf 形式だったら、base64 にする（それ以外はエラー出す）。
- base64 を Data URI Schema にして、 #swf2js or #ruffle に 読み込ませます。
- （そのくらいの説明、英語で書けよ。。。）


# Usage

![image](https://user-images.githubusercontent.com/3696720/213863045-58e99146-1b6a-4be1-a20c-2370e432e933.png)

- Enter the URL of the desired Adobe Flash (.swf) file into the form.
- Select player #swf2js or #ruffle.
- Press FLAAASH!! button.

# Setup

- PHP 7.4 


# Links

- Website
  - [大乱闘フラッシュブラザーズ](https://weep.jp/swf/) - Operation confirmation site.
  - [GitHub オールスター！ 大乱闘フラッシュブラザーズ！](https://www.weep.blog/2022/02/13.html) - Release blog article.
- Battle(?) Players
  - [swf2js.com](https://swf2js.com/) - Player!
  - - [swf2js/swf2js: swf2js is Flash Player Runtime Engine written in pure JavaScript. ](https://github.com/swf2js/swf2js)
  - [Ruffle](https://ruffle.rs/) - Player!
  - - [ruffle-rs/ruffle: A Flash Player emulator written in Rust](https://github.com/ruffle-rs/ruffle)

# Licence

- MIT License Copyright (c) 2022-2023 weepjp
- A parody of Nintendo's Super Smash Bros (大乱闘スマッシュブラザーズ) Series.
