# 4dsv_viewer_mac

4次元ストリートビューのバレットタイム可視化のビューア

**これはmac用です**

## 初めて使用する場合

このディレクトリまで移動して以下のコマンドを実行
```
chmod a+x 4dsv_viewer_mac.app/Contents/MacOS/*

xattr -d com.apple.quarantine 4dsv_viewer_mac.app
```

## 実行方法

4dsv_viewer_mac.appを実行

ファイル選択ウィンドウでコンフィグファイルを選択すると動画ファイルが開く

## 操作方法

キーボードで操作可能

```
A：視線を左方向に回転
D：視線を右方向に回転
W：視線を上方向に回転
S：視線を下方向に回転
Q：視線を反時計回りに回転
E：視線を時計回りに回転

            Space：動画を再生・停止
            Enter：動画を1フレーム進める
BackSpace, Delete：動画を1フレーム戻す

      I：曲線の前方に移動
Shift+I：曲線の後方に移動
      J：次の曲線に移動
Shift+J：前の曲線に移動
      K：次の可視化手法に変更
Shift+K：前の可視化手法に変更
```
マウス操作でカメラの回転が可能

スライドバーで動画のフレーム移動が可能
