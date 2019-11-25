#Shader概要

######  *version :2.3.0   Update:2019-10-8*

​**Shader**中国語の名前は何ですか？**sharer**入力したVerstex（頂点）を指定の方式で入力したスタンプや色などを組み合わせて出力します。図形描画ユニットは、この出力に従って画像を画面に描画することができます。

入力したスタンプや色にシャダを加えるとマティックな素材になります。そして、私たちはMaterailを与えることができます。**レンダー**レンダリングを行う。

​**sharer**大きく二つの種類に分けられます。

​**頂点着色器(Verstex sharer)**：頂点着色器は位置、色などの頂点特性を記述するためのプログラムです。**頂点**（vertex）とは、二次元または三次元の空間の中の一つの点、例えば二次元または三次元の図形の端点または交点を指す。

​**片元着色器（Fragment sharder）**：通常は一枚ずつのメタ処理プロセスを光照射のようなプログラムを行います。スライス元は画素（画像の単位）として簡単に理解できます。