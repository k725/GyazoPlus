GyazoPlus
---------

GyazoWin+の改造版です。

------------------

What is this
-------------

[GyazoWin](http://nothing.sh/blog/archives/44)の改造版の、[GyazoWin+](http://d.hatena.ne.jp/nvsofts/20090321/1237619040)の改造版の、[GyazoWin+(最新のソースにマージ版)](http://exe.tyo.ro/2012/02/gyazowingyazowin.html)の改造版です。

GyazoWinやGyazoWin+では ``~\AppData\Roaming\Gyazo`` 配下に ``id.txt`` を生成しますが、  
GyazoPlusでは ``GyazoPlus.ini`` でIDを管理します。

これにより、USBフラッシュドライブ等で簡単にGyazoPlusを持ち運ぶことが可能です。

Setting
-------

``GyazoPlus.ini`` を編集してください。  
基本は ``misc/readme_gyazowinp.txt`` 内に書いてある説明と殆ど変わりませんが、  
設定値の ``yes``, ``no`` が ``true``, ``false`` になっています。

``upload_id`` という項目が増えていますが、これはサーバで自動的に生成されます。(基本的に触らなくて平気です)  
なお、Gyazo公式リポジトリに存在している ``upload.cgi`` は自動的にIDを生成します。

``upload_port`` はアップロードする際に使用します。  
通常は80を指定し、httpsを使用する際に443にすれば問題ありません。  
また、80, 443番以外のポートに対しても指定が可能です。

LICENSE
-------

ライセンスはフォーク元に準じます。  
GyazoWinやGyazoWin+のReadmeは ``misc`` フォルダに存在しています。

[Creative Commons Attribution-Noncommercial 2.1 Japan](http://creativecommons.org/licenses/by-nc/2.1/jp/)