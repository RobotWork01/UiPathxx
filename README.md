### 文書番号：UiPath_01
<h1>WEBサイトからデータをJsonファイル形式で取得する例</h1>

GitHub Pageはこちら 👨‍🏫 🏌️‍♀️ 🌷🌷🌷🍂🍂🍂<br/>
https://robotwork01.github.io/UiPath/UiPath_01.html

参考記事：<br/>
&nbsp;&nbsp; https://dekiru.net/article/18065/?msclkid=727e9daaceb911eca5bb719184958114
<pre>できるネット【できるUiPath】REST APIとJSONを活用して外部のWebサービスと連携させよう
 GoogleやTwitterなどの各種サービスを利用したり、
 クラウドサービスとして提供されているAIを使って
 UiPathからデータ分析をする。</pre>

<h1>e-stat API取得手順</h1>
動画： <br/>
<span>次のURLをクリックすると、GitHub APIにて動画をダウンロードます。ダウンロードされた動画をご覧ください。</span>
<p>https://github.com/RobotWork01/UiPath/raw/main/UiPath_01%E2%98%85API%E5%8F%96%E5%BE%97.mp4　<br/>
<pre>
 <a href="https://github.com/RobotWork01/UiPath/blob/main/UiPath_01%E2%98%85API%E5%8F%96%E5%BE%97.mp4">動画ファイル参照はこちら ・・・Git LFS にて、保存されています</a>
</pre>
</p>

●政府の統計情報サイト
https://www.e-stat.go.jp/
<br/>
１）次のトップページを表示する。 <br/>
　　https://www.e-stat.go.jp/ <br/>
２）ラベル名「統計 <br/>データを活用する」の「地域」アイコンをクリックする。 <br/>
３）ラベル名「都道府県・市区町村のすがた（社会・人口統計体系）」の <br/>
「都道府県データ」を選択した後に、「データ表示」アイコンをクリックする。<br/>
４）次のURLに自動的に遷移する。 <br/>
　　https://www.e-stat.go.jp/regional-statistics/ssdsview/prefectures <br/>
５）地域候補４８地域の全てを選択した後に、確定ボタンをクリックする。 <br/>
６）項目候補５６８項目の中から下記の項目を選択した後に、確定ボタンをクリックすると自動的に画面遷移する。 <br/>
<pre>
総人口（人）
総人口（男）（人）
総人口（女）（人）
日本人人口（人）
日本人人口（男）（人）
日本人人口（女）（人）
</pre>
７）次のURLへ自動的に遷移する。 <br/>
https://www.e-stat.go.jp/regional-statistics/ssdsview/prefectures  
<pre>
WEB画面上には、統計表表示タブ、グラフ表示タブ、ダウンロードボタン、APIボタンが表示される。 
APIボタンをクリックすると下記のURLが取得出来る： 
●トップページでログインした後に、マイページ表示画面にて、アプリケーションIDを取得する。 
</pre>
＜アプリケーションIDの取得＞ <br/>
<pre>
手順：必要な項目を入力した後に「発行」ボタンをクリックする。
API＋APPID（アプリケーションID）： 
手順：appId=に発行され取得したアプリケーションIDを記入して、URLを書き換える。
</pre>
<hr>
<h3>実行画面</h3><br/>

https://user-images.githubusercontent.com/105484854/168560302-a080a803-90c6-4d4a-8808-0f1359a8ecb4.mp4

# License
"RobotWork01/UiPath" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
 
