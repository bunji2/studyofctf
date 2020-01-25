# 挑戦状！

問題ファイル：[問題ファイル](https://github.com/bunji2/studyofctf/raw/master/problems.7z)

SHA256 digest = 21b3529f4d5d10a8f7143c8036d9a0f1340fd4c1b8ade2ea897aaa7a311f9038

7zip で暗号化されています。解凍パスワードは SLACK の方に載ってます。

## problem3_kakutake

このまま実行しても何もおきません。
どうにかして正しいフラグをセットして "That's flag" を表示させて下さい。

フラグのフォーマット：flag{%s}

ヒント：movzx→cmp→je の繰り返しに注目

## problem4_kakutake

実行して標準入力に正しいフラグを入力して "That's flag" を表示させて下さい。

フラグのフォーマット：flag{%s}

ヒント：入力された文字列を変換している。call に注目。

## 動作環境

多分、x86_64 の Linux 環境ならば動くのではないかと。。。

## ビルド環境

CentOS7 (x86_x64)
GCC 4.8.5
