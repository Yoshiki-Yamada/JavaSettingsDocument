# C言語の開発環境設定  
## Windowsの場合  
windowsの場合は`minGW`というものがあります。まだ開発環境が整っていない人はこちらを参照して見てください。  
### MinGWのインストール  
1. こちらのリンクをクリックしてインストーラーをダウンロードする。
![image7](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image07.png "image07")  
2. ダウンロードしたインストーラーを起動して`install`をする。  
![image8](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image08.png "image08")  
3. 次にインストールをする際の設定をします。  
・`Installation Directory`（インストール先のフォルダ）  
・`User Interface Options`（ユーザーインターフェイスの設定）  
![image9](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image09.png "image09")  
4. `Continue`をクリック  
![image10](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image10.png "image10")  
5. すると`MinGW`インストールが始まります。  
![image11](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image11.png "image11")  
6. １００％になったらインストール完了です。  
![image12](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image12.png "image12")  
7. インストール先にインストールが完了していると思います。それを起動させます。  
![image13](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image13.png "image13")  
8. チェックボックスがあると思います。そこの`mingw32-base`を右クリックして`Mark for Installation`をクリック。  
![image14](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image14.png "image14")  
![image15](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image15.png "image15")  
9. 次に、２つのチェックボックスにチェックをつけます。  
・`mingw32-base`  
・`mingw32-gcc-g++`  
![image16](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image16.png "image16")  
10. 上のメニューから`Installtion`から`Apply Changes`を選択する。  
![image17](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image17.png "image17")  
11. クリックすると、`Schedule of Pending Actions`というウィンドウが出てくるので、`Apply`をクリックする。  
![image18](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image18.png "image18")  
12. クリックするとパッケージのインストールが始まります。完了したら`Close`を押して完了です。  
![image19](https://github.com/Yoshiki-Yamada/ProjectMember2019/blob/master/image19.png "image19")  
### パスを通す  
パスを通します。  
1. コントロールパネルを起動する。  
2. システムとセキュリティをクリックします。  
3. システムをクリックします。  
4. 左のシステムの詳細をクリック  
5. クリックすると、システムのプロパティが表示されるので、環境変数をクリックする。  
6. 環境変数です。システムの環境変数にあるPashを選択して編集をクリックすます。  
7. 変数値末尾に次のパスを追加してOKをクリックします。  
`;C:¥MinGW¥bin`  
8. OKをクリックします。  
9. コマンドプロンプトを起動して、次のコマンドを実行して見ましょう。  
10. `gcc --version`   
11. このように表示されているか確認して完了になります。  
