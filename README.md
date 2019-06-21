# learning-javascript-01

テクノロジー（藤原）JavaScriptの練習 (1)

## Q1の回答「コメントを解除したことで、どう変化しましたか？」

【こんにちはというポップアップが表示された】

## Q2の回答「エラーの原因は何でしょうか？（調べてみましょう）」

【windowはNodeJsで定義されてないから】

## Chromeデベロッパーツール：Consoleの実行結果

```
【console.log ('hello')
breadcrumbs.js:58 hello
undefined
const preflist = ["北海道", "青森"]
undefined
preflist[0]
"北海道"
preflist[1]
"青森"
document.body
<body class=​"c-blogs a-show notePage">​…​</body>​
console.log
ƒ log() { [native code] }】
```

## ターミナルの実行結果

```
【
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/urasouma/Documents/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
】
```

