# electron-nsen-player

Electronで作ったNsen( http://live.nicovideo.jp/watch/nsen/vocaloid )を見る何かです。

* 常に最前面で表示されます。
* サイズを変更できます。
  * ウィンドウサイズを変更し、必要に応じてwebview部分をピンチしてズームしてください。
* ウィンドウバーがありません。

## 使い方

* `git clone git@github.com:keisei1092/electron-nsen-viewer.git`
* https://github.com/atom/electron/blob/master/docs/tutorial/using-pepper-flash-plugin.md を参考にFlash Player再生できるようにしてください(投げ槍ですまん
* `npm start`
* webviewはすごく下の方にあるので、まず透明な部分を一度クリックした後<kbd>↓</kbd>でwebviewがいるところまでスクロールしてください
* 全画面webviewが覆うぐらいまで移動したら、2本指でNsenの画面でウィンドウを覆うまでスクロール(ズームまたはズームアウト)してください
* 必要に応じてウィンドウのサイズを大きくして、webview部は2本指ズームで大きくしてください

以下clone元のelectron-quick-startのREADME.md残しておきます

**Clone and run for a quick way to see an Electron in action.**

This is a minimal Electron application based on the [Quick Start Guide](http://electron.atom.io/docs/latest/tutorial/quick-start) within the Electron documentation.

A basic Electron application needs just these files:

- `index.html` - A web page to render.
- `main.js` - Starts the app and creates a browser window to render HTML.
- `package.json` - Points to the app's main file and lists its details and dependencies.

You can learn more about each of these components within the [Quick Start Guide](http://electron.atom.io/docs/latest/tutorial/quick-start).

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/atom/electron-quick-start
# Go into the repository
cd electron-quick-start
# Install dependencies and run the app
npm install && npm start
```

Learn more about Electron and its API in the [documentation](http://electron.atom.io/docs/latest).

#### License [CC0 (Public Domain)](LICENSE.md)
