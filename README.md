# test_calculator_202604

<img src="https://evofan.github.io/test_calculator_202604/screenshot/1.png" width="50%">  



reference  

**HTML+CSS+JSで電卓を作ってみた※ウェブカツブログ記事参照**  
[https://qiita.com/bumpfuji10/items/2b9470667530f67696ca](https://qiita.com/bumpfuji10/items/2b9470667530f67696ca)  

**【JavaScript】ローカルストレージに配列を保存しよう！基本的な使い方を解説【localStorage】**  
[https://yurupro.cloud/3107/](https://yurupro.cloud/3107/)  
>arrayをシリアル化～ローカルストレージに保存

**howler.js - JavaScript audio library for the modern web**  
[https://howlerjs.com/](https://howlerjs.com/)  

**JavaScriptで配列内の値を昇順・降順に並び替える方法**  
[https://zenn.dev/tk4/articles/0dcfdd76b862202b217c](https://zenn.dev/tk4/articles/0dcfdd76b862202b217c)

**プラッシュ画面とアイコン | Capacitorドキュメンテーション**  
[https://capacitorjs.jp/docs/guides/splash-screens-and-icons](https://capacitorjs.jp/docs/guides/splash-screens-and-icons)  
<img src="https://evofan.github.io/test_calculator_202604/screenshot/2.png" width="50%">  
>npx capacitor-assets generate
  
**change app icon?(Gemini in Android Studio)**  
アプリのアイコンを変更するには、目的に応じていくつかの方法があります。 
  
方法1：アセットスタジオを使用する（推奨）  
Android Studioでアイコンを変更する最良の方法は、必要なサイズとフォーマットを自動的に生成するイメージアセットスタジオを使用することです。  
1.  
プロジェクトビューでresフォルダを右クリックします。  
2.  
[新規] > [イメージアセット]を選択します。  
3.  
[アイコンタイプ]ドロップダウンで、[ランチャーアイコン（アダプティブとレガシー）]を選択します。  
4.  
ソース画像（高解像度のPNGまたはSVGなど）を選択します。  
5.  
[次へ]をクリックし、[完了]をクリックします。これにより、既存のic_launcherファイルが上書きされます。  
  
方法2：プロジェクト内の既存ファイルを使用する   
res/ディレクトリにアイコンファイル（icon-512.webpなど）がいくつかあることに気づきました。これらのファイルを使用する場合は、以下の手順に従ってください。 
1.  
これらのファイルを適切なmipmapフォルダに移動してください（例：icon-48.webpをmipmap-mdpi/ic_launcher.webpに移動）。    
2.  
すべてのファイル名がic_launcher.webpになっていることを確認してください（AndroidManifest.xmlと一致する限り、任意の名前でも構いません）。  
  
現在の状態  
現在、アプリは以下のように設定されています。  
• アイコン：@mipmap/ic_launcher  
• 丸型アイコン：@mipmap/ic_launcher_round  
アイコンとして設定したい特定の画像ファイルがある場合は、そのファイルの場所をお知らせください。  
<img src="https://evofan.github.io/test_calculator_202604/screenshot/3.png" width="50%">  
<img src="https://evofan.github.io/test_calculator_202604/screenshot/4.png" width="50%">  




