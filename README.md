# ARCard Template

[AR.js](https://github.com/jeromeetienne/AR.js) と
[A-Frame](https://github.com/aframevr/aframe/) を用いて作成した AR 名刺。

## 見方

<img src="https://github.com/5ebec/arcard/blob/master/src/assets/marker/marker.png" width="320">

この画像は QR コード兼マーカーとなっています。スマホ等で QR コードを読み取ると
AR 名刺が見られる Web ページの URL が表示されるので
、[サポートされているブラウザ](https://github.com/jeromeetienne/AR.js/#browser-support)※
で開き、カメラの使用を許可していただくと AR 名刺を見ることが出来ます。

#### ※ 現時点で把握できている追加の情報です

- iOS 版 Chrome は Webcam error が出て動作しない。
- iOS12 では `設定 > Safari > Camera & Microphone Access` を ON にしないと
  Webcam error が出て動作しない。
- iOS の省電力モードでは Safari であってもエンティティが表示されないことがある。

## LICENSE

[MIT](LICENSE)
