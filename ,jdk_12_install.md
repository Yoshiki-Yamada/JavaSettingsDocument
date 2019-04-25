# JDKのインストール(mac用)  
### windowsの方はこちらから設定してください。[windows用JDKインストールマニュアル](https://github.com/shikari-s/installJDK)
macの人はHomebrewを使ってインストールをしていきます。  
Xcodeをインストールしましょう。  
## xcodeのインストール（command line tools）
1. こちらからアクセス https://itunes.apple.com/jp/app/xcode/id497799835?mt=12&ign-mpt=uo%3D4
![xcode](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image06.png "image06")
2. コマンドラインデベロッパーツールをインストールする。
```xcode-select --install```をターミナルで実行。
3. インストールが完了

2. 早速JDKをインストールします。  
homebrewをインストールできたと思うので、早速つかってみましょう。  
ターミナルに`brew cask install java`と入力し実行するとインストールができる。  
`java -version`と入力して実行するとバージョンを確認できる。  
12出ない場合は`brew cask upgrade java`と入力する  
再度、`java -version`で確認してみましょう。  
- 次にC言語の開発環境設定です。  
[次へ](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/,c-pro_install.md)  
[戻る](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/,intellij_idea_install.md)  

## 補足  
homebrewを使うことで様々なソフトをインストールやバージョンを管理できます。が、サイトから直接インストールすることもできます。一応リンクをはっつけておきます。   
jdk12のインストールサイト https://www.oracle.com/technetwork/java/javase/downloads/jdk12-downloads-5295953.html  
