# ブラウザのマイクから音声を拾ってibm watsonのspeech to textをnodjsで利用する

socketや音声ファイルの扱いについて分からなかったのでryojiysd氏のコードを利用させて頂きました。(https://github.com/ryojiysd/node-audio-stream)

speech to textでstream mode を利用するとライブオーディオでリアルタイムに文字起こし出来るらしいがドキュメント見てもわからなかったので
音声ファイルを作成してspeech  to textへ渡す形にした。

面倒くさくてdbは使ってないためsubmitなどの処理はdom操作でそれっぽくしてるだけ。

起動
```
node app.js
```
