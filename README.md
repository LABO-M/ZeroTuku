# ZeroTuku
ゼロから始めるDeepLearningのソースコード

## ゼロつく無印のコード
Chapter"章番号"_Zero_"作成者名".ipynb　で作成

## utilsディレクトリの説明
utilsディレクトリは，自作関数やモジュールをまとめたディレクトリになります．

.pyファイルを使いたいときは，utilsディレクトリの中にあるもの使用してください．

.pyファイルを追加したい場合は，utilsディレクトリに追加し，以下の様に呼び出してください．
```python
from utils.hogehoge import *
```

### .pyの説明
function.py : 活性化関数と損失関数をまとめたファイル

gradient.py : 学習のための勾配を計算するためのファイル

mnist.py : MNISTデータセットを入手するためののファイル

optimizer.py : 学習の効率化を行うためのファイル

im2col.py : 畳み込み層，プーリング層を実装するために入力の変換をするファイル

layers.py : ゼロつく無印で用いる全結合層，畳み込み層，プーリング層

trainer.py : ニューラルネットの訓練をするためのファイル

