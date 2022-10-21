# 総合演習 課題A-3 コード群

この教材では，Pythonを使って信号処理の基礎知識の学習と音源分離実習を行います．

## 教材

教科書 ([総合演習_A-3テキスト.pdf](総合演習A-3テキスト.pdf))

## 各演習の内容・サンプルコード

### - 演習3-1
 
音声信号処理の流れを勉強します．
ここではフィルタリングの例として，周波数領域の低域通過フィルタを実装します．

- [ensyu_3-1.ipynb](ensyu_3_1.ipynb):  
   演習3-1用サンプルソースコード．

### - 演習3-2

２話者２マイクロホンで収録した音声に対してバイナリマスクによる音源分離を行います．

- [ensyu_3-2.ipynb](ensyu_3_2.ipynb):  
   演習3-2用サンプルソースコード．
   
   > 補足：
   > この演習は for ループを使って実装することができます．
   > for ループの使い方については <a href="https://github.com/YosukeSugiura/Introduction_to_Programming/tree/main/05_for" target="_blank" rel="noopener noreferrer">こちら</a> が参考になるかもしれません。

### - 演習3-3

２話者２マイクロホンで収録した音声に対してDUETによる音源分離を行います．

- [ensyu_3-3.ipynb](ensyu_3_3.ipynb):  
   演習3-3用サンプルソースコード．

### - 演習3-4

音源数を増やして，３話者２マイクロホンで収録した音声に対してDUETによる音源分離を行います．

- [ensyu_3-4.ipynb](ensyu_3_4.ipynb):  
   演習3-4用サンプルソースコード．

## 音声一覧

各音声ファイルは，ソースコードを実行するとGoogle Colabワークスペース内に自動でダウンロードされます．
音声ファイルをローカル環境にダウンロードする必要はありません．

以下に，音声ファイルについて説明を追加します．

### 演習3-1

- sound_mono.wav:  
   演習2-1用音声ファイル．モノラル音声．  

### 演習3-2

- sound_2sources.wav:  
   演習2-2，2-3用音声ファイル．２話者音源．ステレオ音声を扱う．  
   
- original_1.wav:  
   分離した際の理想音源A

- original_2.wav:  
   分離した際の理想音源B
   
### 演習3-3

- sound_2sources_duet.wav:  
   演習2-2，2-3用音声ファイル．２話者音源．ステレオ音声を扱う．  
   
- original_1.wav:  
   分離した際の理想音源A

- original_2.wav:  
   分離した際の理想音源B
   
- sound_SpeakerA.wav:  
   事前に振幅比を計算する音源A

- sound_SpeakerB.wav:  
   事前に振幅比を計算する音源B
   
### 演習3-4

- sound_3sources_duet.wav:  
   演習2-4用音声ファイル．３話者音源．ステレオ音声を扱う．  
   
- original_1.wav:  
   分離した際の理想音源A

- original_2.wav:  
   分離した際の理想音源B
   
- original_3.wav:  
   分離した際の理想音源C
   
- sound_SpeakerA.wav:  
   事前に振幅比を計算する音源A

- sound_SpeakerB.wav:  
   事前に振幅比を計算する音源B
   
- sound_SpeakerC.wav:  
   事前に振幅比を計算する音源C
