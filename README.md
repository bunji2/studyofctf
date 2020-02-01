# 挑戦状！

問題ファイル：[problems2_win.7z](https://github.com/bunji2/studyofctf/raw/master/problems2_win.7z) (Win x86_64 版)

SHA256 digest = efd105640cd18ddce4ee3f27f615050feb18819e75cf50e621e7c0ca2d2b47f4

問題ファイル：[problems2.7z](https://github.com/bunji2/studyofctf/raw/master/problems2.7z) (Linux x86_64 版)

SHA256 digest = 529826190f5473188299d3047f30853228b5f7aec82c17627ebab9623a0dbe66


~旧問題ファイル：problems.7z (Linux x86_64 版)~

~SHA256 digest = 21b3529f4d5d10a8f7143c8036d9a0f1340fd4c1b8ade2ea897aaa7a311f9038~

7zip で暗号化されています。解凍パスワードは SLACK の方に載ってます。

problems.7z は一部環境で正常に動作しないようなので problems2.7z もしくは problems2_win.7z をお使い下さい。

## problem3_kakutake

このまま実行しても何もおきません。
どうにかして正しいフラグをセットして "That's flag" を表示させて下さい。

フラグのフォーマット：flag{%s}

ヒント：movzx→cmp→je の繰り返しに注目

→[解](answer_problem3.md)

## problem4_kakutake

実行して標準入力に正しいフラグを入力して "That's flag" を表示させて下さい。

フラグのフォーマット：flag{%s}

ヒント：入力された文字列を変換している。call に注目。

→[解](answer_problem4.md)

## 動作環境

多分、x86_64 の Linux 環境か Windows 環境ならば動くのではないかと。。。

## ビルド環境

CentOS7 (x86_x64)
GCC 4.8.5

Windows7 Pro SP1 (x86_64)
Msys2/Mingw64
