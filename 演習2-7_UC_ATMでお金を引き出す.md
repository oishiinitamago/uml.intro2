## 演習2-7
ATMで「お金を引き出す」ユースケース

###　ユースケース図
ATMで「お金を引き出す」

### 概略
概略 銀行のATMを利用して、自分の口座からキャッシュカードで必要なお金を引き出します。
### アクター 
利用者
### 事前条件 
アクターが口座とキャッシュカードを持っていること。
### 事後条件 
アクターの口座から指定された金額が引き出されること。

## 基本フロー

1. 利用者がATMにキャッシュカードを入れるとこのユースケースが始まる
2. 引き出しボタンを押す
3. 引き出したい金額を入力する
4. 引出し者の情報を入力する
5. 引き出したい金額を残高から引く
6. 引き出されたお金を受け取る

## 代替フロー
A-1.：引出しを実行する前であればいつでも、引出しを中止することができる
1. システムは引出しの中止を確認する
2. 引出しシステムは中止
E-１：引き出したい金額が残高にない
1. 引出しシステムは引出しを中止する
E-２：引出し者の情報が不足している
1. 引出しシステムは引出し者の情報を再入力するか、引出しを中止する
E-３：引出しに失敗する
1. 引出しシステムはユースケースを終了する


### ユースケース名 ATMで「お金を引き出す」
***【基本シナリオ】***
1. 引き出しボタンを押す
2. 引き出したい金額を入力する
3. 引出し者の情報を入力する
4. 引き出したい金額を残高から引く
5. 引き出されたお金を受け取る

***【例外シナリオ】***
