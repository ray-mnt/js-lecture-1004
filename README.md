# テクノロジー（藤原） 10/4課題

- テキストエディタ（Visual Studio Codeなど）でREADME.mdを開きます
- 下の欄（` ``` `で挟まれている部分）に、ChromeデベロッパーツールのConsoleで実行したログを丸ごとコピー＆ペーストしてください
```

var str = "Hello";
undefined
var num = 123
undefined
var flag = ture;
VM36:1 Uncaught ReferenceError: ture is not defined
    at <anonymous>:1:12
(anonymous) @ VM36:1
var flag = true;
undefined
var prefList = ["北海道","青森","岩手","宮城","秋田"]
undefined
console.log(prefList[0]);
VM69:1 北海道
undefined
console.log(prefList[3]);
VM73:1 宮城
undefined
var prefHash["kanto"]);
VM79:1 Uncaught SyntaxError: Unexpected token [
var prefHash = {"kanto":"関東地方","kinki":"近畿地方","chugoku":"中国地方","shikoku":"四国地方"};
undefined
console.log(prefHash ["kanto"]);
VM120:1 関東地方
undefined
console.log(prefHash.kanto);
VM140:1 関東地方
undefined
console.log(prefHash ["kinki"]);
VM143:1 近畿地方
undefined
console.log(prefHash.kinki);
VM166:1 近畿地方
undefined
console.log(prefHash.test);
VM187:1 undefined
undefined
var preHash1 = ("kanto":"関東地方",
VM191:1 Uncaught SyntaxError: Unexpected token :
var preHash1 = ("kanto":"関東地方","chubu":"中部地方"};
VM193:1 Uncaught SyntaxError: Unexpected token :
var prefHash1 = ("kanto":"関東地方","chubu":"中部地方"};
VM194:1 Uncaught SyntaxError: Unexpected token :
var prefHash = {"kanto":"関東地方","kinki":"近畿地方","chugoku":"中国地方","shikoku":"四国地方"};
undefined
var prefHash1 = ("kanto":"関東地方","chubu":"中部地方"};
VM198:1 Uncaught SyntaxError: Unexpected token :
var prefHash = {"kanto":"関東地方","kinki":"近畿地方","chubu":"中部地方","chugoku":"中国地方","shikoku":"四国地方"};
undefined
var prefHash1 = ("kanto":"関東地方","chubu":"中部地方"};
VM203:1 Uncaught SyntaxError: Unexpected token :
var prefHash1 = {"kanto":"関東地方","chubu":"中部地方"};
undefined
var prefHash1 = {kanto:"関東地方",chubu:"中部地方"};
undefined
var prefHash1 = {"kanto":"関東地方","chubu":"中部地方"};
undefined
var prefHash2 = {kanto:"関東地方",chubu:"中部地方"};
undefined
var prefHash3 ={};
undefined
prefHash3["kanto"] = "関東地方";
"関東地方"
prefHash3["chubu"] = "中部地方";
"中部地方"
var prefHash4 = {};
undefined
prefHash4.kanto = "関東地方"
"関東地方"
prefHash4.chubu = "中部地方"
"中部地方"

```

## 例（下記の書き方をまねてください）

```
console.log('hello')
VM31:1 hello
undefined
```
