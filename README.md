# Word-calculator

# Overview
英単語の足し算・引き算を電卓感覚で楽しめます。

# Description
自然言語処理Word2Vecの魅力の一つとして、単語のベクトル化による単語の足し算・引き算があります。  
当アプリは、英単語の足し算・引き算が自由にでき、Word2Vecの魅力を体感できます。

# Folders and Files
┏ model_etc …  
┃　┣ word2disvec.txt … 各単語の分散表現  
┃　┣ id2word.json … 辞書（key:ID、value:単語）  
┃　┣ word2id.json … 辞書（key:単語、value:ID）  
┃　┗ weights.txt … 各単語の重み行列  
┣ word2vec_text8.ipynb … Word2Vecモデル（Skip-gram）の作成プログラム  
┣ word_calculator.ipynb … 英単語の足し算・引き算用プログラム（メイン）  
┗ words_list.xlsx … 単語とIDの一覧（メインアプリで入力するのは ID）  

# Capture
![demo_word_calculator](https://user-images.githubusercontent.com/39453720/46589494-14cb7600-cae5-11e8-95b2-d9010a0b81a3.gif)
