# スクリプト群の説明

## nltk-word-tokenize

NLTK の nltk.word_tokenize を使用し英文のトークン化を行う。
入力には fileinput を使用しているため標準出力とファイル入力のどちらでも動作する。

## make-vocabulary

トークン化された文から使用されている語彙を頻度順に出力する。
文は標準入力から与える。上位n語を取り出す場合は引数にnを与える。
