# AoyamaType


インストール方法：
pip install git+https://github.com/37021463/aoyamatype.git
以上のコマンドを実行してください。

最初にURL:https://kwanseio365-my.sharepoint.com/:f:/g/personal/ijv85378_nuc_kwansei_ac_jp/ElNx956B6chEppmidaLVxm4BUMw0mT9WP4NU0cGyJH1hDA?e=uCca4V からdata.zipをダウンロードしてください。

次にaoyamatype -d [PATH] PATHはダウンロードしたdata.zipのものとし、コマンドを入力してください。

エラー：
pip install git+https://github.com/37021463/aoyamatype.git
が実行できない場合は以下のURLから自分のPCにあったgitをダウンロードしてください。
https://git-scm.com/

インストール時に
[WARNING: The script aoyamatype.exe is installed in 'C:\Users\AppData\...\Python311\Scripts' which is not on PATH.
Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.]
このような警告文が表示される場合はPythonのScriptがインストールされるディレクトリが環境変数PATHに含まれていません。
環境変数PATHに警告文で表示されたPATHを追加してください。
Unix系OSでは、~/.local/binをPATHに追加します。

aoyamatype -d [PATH]が実行できない場合は以下の点をもう一度確認してください・
・ダウンロードしたdataフォルダがzip形式になっているか
・PATHが本当にdata.zipのものになっているか
