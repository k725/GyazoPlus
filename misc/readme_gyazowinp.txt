gyazoiwnp by tyoro

NVさんのgyazowin+の拡張をtnjの最新ソースに適用したものです。
ライセンスはgyazowin+に準拠します。

以下、gyazowin+の添付readmeままです。

2012 02/08
------------------

gyazowin+ v1.00 by NV
gyazowin by tnj(http://nothing.sh/blog/archives/44)

<概要>
tnj氏のgyazowinの改造版です。
アップロード先を指定できるので、gyazo以外にもアップロードが可能です。
また、確認メッセージの表示機能などが追加されています。

<ファイル構成>
gyazowin+.exe	- 本体
gyazowin+.ini	- 設定ファイル
readme.txt	- このファイル

<インストール>
適当なフォルダに本体と設定ファイルをコピーすれば使えます。

<アンインストール>
コピーしたファイルを削除するだけです。
レジストリは使用していません。

<設定ファイルについて>
INI形式です。[gyazowin+] セクション内にすべての設定を記述します。

upload_server=アップロード先サーバ
アップロード先のサーバを設定します。
ドメイン名[:ポート] の形で指定します。
初期設定: gyazo.com

upload_path=アップロード先パス
アップロード先のCGIへのパスを指定します。
必ず最初には/を付けてください。
初期設定: /upload.cgi

use_ssl=(yes/no)
SSLを使用するかを指定します。
初期設定: no

ssl_check_cert=(yes/no)
SSLを使用するとき、サーバ証明書のチェックを行うかを指定します。
初期設定: yes

use_auth=(yes/no)
Basic認証を使用するか指定します。
初期設定: no

auth_id=ID
Basic認証を行うときに使用するIDを指定します。
初期設定: (空白)

auth_pw=パスワード
Basic認証を行うときに使用するパスワードを指定します。
初期設定: (空白)

up_dialog=(yes/no)
アップロード時に確認ダイアログを表示するかを指定します。
初期設定: yes

copy_url=(yes/no)
画像URLをクリップボードにコピーするかを指定します。
初期設定: yes

copy_dialog=(yes/no)
クリップボードへコピー時にダイアログを表示するかを指定します。
初期設定: yes

open_browser=(yes/no)
画像を既定のブラウザで表示するかを指定します。
初期設定: no

<ライセンス>
Creative Commons Attribution-Noncommercial 2.1 Japan とします。
原作: tnj氏
改造: NV