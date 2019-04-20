# JDKのインストール(mac用)  
### windowsの方はこちらから設定してください。[windows用JDKインストールマニュアル](https://github.com/shikari-s/installJDK)
macの人はHomebrewというパッケージマネージャーがあり、かなり優秀なので、これを使ってみましょう。
その前に、Xcodeをインストールしましょう。
## xcodeのインストール（command line tools）
1. こちらからアクセス https://itunes.apple.com/jp/app/xcode/id497799835?mt=12&ign-mpt=uo%3D4
![xcode](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image06.png "image06")
2. コマンドラインデベロッパーツールをインストールする。
```xcode-select --install```をターミナルで実行。
3. インストールが完了
## Homebrweのインストール
1. まず、Homebrewをインストールします。こちらにアクセスしてターミナルにコマンドをコピーペーストしてください。
![image05](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image05.png "image05")
すると、Homebrewのインストールが始まります。時間がかかる場合もあります。
- 途中でエンターの入力やmacのpassの入力を求められることがあります。
```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

（中略）

Press RETURN to continue or any other key to abort
==>

(中略)

Password:

(中略)

==> Installation successful!

==> Homebrew has enabled anonymous aggregate user behaviour analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics.html

==> Next steps:
- Run `brew help` to get started
- Further documentation:
    https://docs.brew.sh
  ```

2. インストールが完了したら早速JDKをインストールします。  
ターミナルに`brew cask install java`と入力し実行するとインストールができる。  
`java -version`と入力して実行するとバージョンを確認できる。  
12出ない場合は`brew cask upgrade java`と入力する  
再度、`java -version`で確認してみましょう。  
- ここまでで環境設定は終了です。
