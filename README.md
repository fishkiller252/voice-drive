## voice-drive

声援駆動開発サポート

```html   
<input type="image" width="150" height="300" src="images/fran.jpg" value="Check" onclick="praise()">
```
src/imagesの中に画像をセットしてください。
src="images/xxx.jpg"などに編集

```js
var voice = new Audio("音声ファイルのあるURL");

function praise() {
  voice.play()
};
```

 パッケージ化

#### Windows
electron-packager . ディレクトリ名 --platform=win32 --electron-version=1.4.5 --icon=./--------.ico
#### OSX
electron-packager . ディレクトリ名 --platform=darwin --electron-version=1.4.5 --icon=./--------.icns
#### Linux
electron-packager . ディレクトリ名 --platform=linux --electron-version=1.4.5 --icon=./----------.png
