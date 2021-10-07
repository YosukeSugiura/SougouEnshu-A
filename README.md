# 総合演習 課題A-2 コード群

この教材では，信号処理の基礎知識の学習とPythonを使って信号処理実習を行います．

## 教材

教科書 ([総合演習_A-2テキスト.pdf](https://github.com/YosukeSugiura/SougouEnshu-A/blob/master/%E7%B7%8F%E5%90%88%E6%BC%94%E7%BF%92_%E8%AA%B2%E9%A1%8CA-2%E3%83%86%E3%82%AD%E3%82%B9%E3%83%88.pdf))

## 各課題の内容

### - 課題2-1
 
音声信号処理の流れを勉強します．
ここではフィルタリングの例として，周波数領域の低域通過フィルタを実装します．

- [kadai_2-1.ipynb](https://github.com/YosukeSugiura/SougouEnshu-A/blob/master/kadai_2_1.ipynb):  
   課題2-1用サンプルソースコード．

### - 課題2-2

２話者２マイクロホンで収録した音声に対してバイナリマスクによる音源分離を行います．

- [kadai_2-2.ipynb](https://github.com/YosukeSugiura/SougouEnshu-A/blob/master/kadai_2_2.ipynb):  
   課題2-2用サンプルソースコード．

### - 課題2-3

２話者２マイクロホンで収録した音声に対してDUETによる音源分離を行います．

- [kadai_2-3.ipynb](https://github.com/YosukeSugiura/SougouEnshu-A/blob/master/kadai_2_3.ipynb):  
   課題2-3用サンプルソースコード．

### - 課題2-4

音源数を増やして，３話者２マイクロホンで収録した音声に対してDUETによる音源分離を行います．

- [kadai_2-4.ipynb](https://github.com/YosukeSugiura/SougouEnshu-A/blob/master/kadai_2_4.ipynb):  
   課題2-4用サンプルソースコード．

## 音声一覧

各音声ファイルは，ソースコードを実行すると自動でGoogle Colabワークスペース内にダウンロードします．

### 課題2-1

- sound_mono.wav:  
   課題2-1用音声ファイル．モノラル音声．  

### 課題2-2

- sound_2sources.wav:  
   課題2-2，2-3用音声ファイル．２話者音源．ステレオ音声を扱う．  
   
- original_1.wav:  
   分離した際の理想音源A

- original_2.wav:  
   分離した際の理想音源B
   
### 課題2-3

- sound_2sources.wav:  
   課題2-2，2-3用音声ファイル．２話者音源．ステレオ音声を扱う．  
   
- original_1.wav:  
   分離した際の理想音源A

- original_2.wav:  
   分離した際の理想音源B
   
- sound_SpeakerA.wav:  
   事前に振幅比を計算する音源A

- sound_SpeakerB.wav:  
   事前に振幅比を計算する音源B
   
### 課題2-4

- sound_3sources.wav:  
   課題2-4用音声ファイル．３話者音源．ステレオ音声を扱う．  
   
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
