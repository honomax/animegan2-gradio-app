# animegan2-gradio-app

## プロジェクト概要
本リポジトリは、AnimeGAN2を用いて、実写の顔画像をアニメ風に変換するGradioウェブアプリになります。

## 使用環境

本プロジェクトは **Google Colab** 上での実行を想定しています。

追加で必要なライブラリがある場合は、Notebook の冒頭で次のようにインストールしてください：
```python
!pip install ライブラリ名
```

## 詳細
- [bryandlee/animegan2-pytorch ](https://github.com/bryandlee/animegan2-pytorch)の事前学習済みモデルを利用
- 複数のアニメスタイルを切り替え可能（celeba_distill、face_paint_512_v1、face_paint_512_v2、paprikaなど）

  各モデルはtorch.hub.loadのpretrained引数で切り替えて使用
- Gradioアプリで手軽にWeb上で動作できる

## 結果・出力
画像の出力画面が表示されるとGradio UI上のダウンロードボタンから保存できます。
