# Ubuntu の GUI 操作

> オペレーティング・システム Ubuntu の
  グラフィカル・ユーザ・インタフェース（GUI）に慣れるようにします．


## タスク 0: プレゼンテーション・スライド

[プレゼンテーション・スライド](../../_downloads/slides/ROS-I%20Basic%20Developers%20Training%20-%20Session%200.pdf) の PDF ファイルがこのトレーニングには添付されています．


## タスク 1: Ubuntu デスクトップに慣れる

ログイン画面でパスワード入力欄に
`rosindustrial` を入力して
Enter キーを押してください．
ログインできた場合には
次のような画面が見えているはずです．

![](../../_static/ubuntu_desktop.png)

デスクトップ上のいくつかの項目について見ていきます．

![](../../_static/ubuntu_desktop_details.png)

1. 画面の右上にある歯車アイコンは，
   ユーザのログアウトやコンピュータのシャットダウン，
   システム設定へのアクセスなどを行うための
   メニューを表示します．
1. 左側のバーには，
   実行中の「お気に入り」アプリケーションや
   接続された USB ドライブなどが表示されます．
1. 最上部のアイコンは，
   全てのアプリケーションとファイルにアクセスするために使用されます．
   これについては後で詳しく見ていきます．
   1. 続くアイコンは，
      現在実行中のアプリケーションか
      「ピン留め」されているアプリケーションです．（後で詳述）
   1. USB ドライブのようなリムーバブル・ドライブは
      アプリケーションのアイコンの後にあります．
   1. ランチャーバーがあまりにも多くになった場合，
      クリックして上下にドラッグすると
      非表示のアプリケーションを見ることができます．
   1. ランチャーのアイコンを再編成するには
      「飛び出す」までアイコンをクリックしたままにして
      目的の場所に移動します．


## タスク 2: アプリケーションを開く・調べる

ランチャーのファイリング・キャビネットの形をしたアイコンをクリックします．
ウィンドウが表示され，デスクトップは次のようになります．

![](../../_static/ubuntu_folder_browser.png)

注記事項:

1. 通常は 閉じる・最小化・最大化 のボタンが
   ウィンドウのタイトルバーの左側にあります．
1. ウィンドウのメニューは，
   画面の上部にあるメニューバーに表示されます．
   これは Mac の場合と同じです．
   ただしメニューはメニューバーの上に
   マウスを置いたときのみ表示されます．
1. フォルダアイコンの左右に三角形があることに注目してください．
   左の三角はこのアプリケーションで
   いくつのウィンドウが開いているかを示し，
   右は現在どのアプリケーションが最前面にあるか，
   または「フォーカスがある」ことを示しています．
   アプリケーションが開いているときにアイコンをクリックすると，
   次の2つのうちのいずれかが実行されます．
   * 開いているウィンドウが1つだけの場合，
     そのウィンドウにフォーカスが移ります．
   * 複数のウィンドウが開いている場合は，
     2回目のクリックをすると，
     すべてのウィンドウが最前面に表示されるため，
     どのウィンドウを表示するかを選択できます．
     （下図参照）
     ![](../../_static/ubuntu_inspect.png)


## タスク 3: アプリケーションを開始する・ランチャーバーへのピン留め

ランチャーボタン（左上）をクリックし，
検索ボックスに「 gedit 」と入力します．
「Text Editor」アプリケーション
（これがまさに gedit です）が表示されます．
（下図参照）

![](../../_static/ubuntu_start_application.png)

アプリケーションをクリックします．
テキストエディタのウィンドウが画面に表示されて
テキストエディタ・アイコンが左側のランチャーバーに表示されます．
（下記参照）

![](../../_static/ubuntu_application_pin.png)

1. ランチャーアイコンを右クリックして
   "Lock to Launcher" を選択してください．
1. gedit ウィンドウを閉じてください．
   閉じてもランチャーアイコンがまだ残っているはずです．
1. gedit ランチャーアイコンをクリックしてください．
   新しい gedit ウィンドウが表示されるはずです．