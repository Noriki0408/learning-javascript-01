# learning-javascript-01

テクノロジー（藤原）JavaScriptの練習 (1)

## Q1の回答「コメントを解除したことで、どう変化しましたか？」

【おはよう＞＞こんにちはに変わった！！】

## Q2の回答「エラーの原因は何でしょうか？（調べてみましょう）」

【存在しない変数が定義されているために起きているエラー】

## Chromeデベロッパーツール：Consoleの実行結果

```
【おはよう！
index.html:56 Live reload enabled.
VM18 on_content_end.js:54 on_content_end ==>response to loadPagePattern, href=http://127.0.0.1:5500/index.html, pattern.id=undefined
index.html:18 おはよう！
Navigated to http://127.0.0.1:5500/index.html
VM31 on_content_end.js:54 on_content_end ==>response to loadPagePattern, href=http://127.0.0.1:5500/index.html, pattern.id=undefined
index.html:52 [Intervention] Blocked attempt to show a 'beforeunload' confirmation panel for a frame that never had a user gesture since its load. https://www.chromestatus.com/feature/5082396709879808
socket.onmessage @ index.html:52
Navigated to http://127.0.0.1:5500/index.html
index.html:18 おはよう！
on_content_end.js:54 on_content_end ==>response to loadPagePattern, href=http://127.0.0.1:5500/index.html, pattern.id=undefined】
```

## ターミナルの実行結果

```
【ReferenceError: window is not defined
    at Object.<anonymous> (/Users/miyaginoriki/Documents/fujiwara/learning-javascript-01/node-main.js:1:2)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11】
```

