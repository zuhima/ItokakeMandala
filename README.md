# 糸掛け曼荼羅メーカー/Thread Handing Mandala Maker

~~(現在、編集中です...。)
(Currently editing...)~~

※I'm not good at English...Please forgive my poor English.

## 本プログラムは[こちら](https://myprogramserver.mybluemix.net/ItokakeMandala)から！/This program can be used [HERE](https://myprogramserver.mybluemix.net/ItokakeMandala)!  
※リンクが切れていたら申し訳ありません。/Sorry if the link is broken

## 追記 Postscript  
　__2019.9.14__　バージョン情報にver0.2.2を追加。使い方に追記。  
　__2019.9.4__　バージョン情報にver0.2.1を追加。使い方に追記。  
　__2019.9.3__　バージョン情報にver0.2.0を追加。使い方を編集。  
　__2019.9.1__　バージョン情報にver0.1.2を追加。使い方に追記。備考に追記。  
　__2019.8.30__　バージョン情報にver0.1.1を追加。使い方に追記。  
　__2019.8.25__　バージョン情報にver0.1.0を追加。使い方に追記。ブラウザ上で動かせるようにリンクを追加。  
　__2019.8.24__　バージョン情報にver0.0.3を追加。  
　__2019.8.16__　バージョン情報にver0.0.2を追加。

## 1.概要 Overview
　糸掛け曼荼羅というストリングアートがあるが、本プログラムではそれを画面上で作成することができる。  
 "Itokake Mandala" is a kind of string art.This program can draw it.

![mandala](https://image.jimcdn.com/app/cms/image/transf/dimension=320x10000:format=jpg/path/s02f156111babe491/image/i6fef9adb67f9fe73/version/1526972599/%E7%B3%B8%E3%81%8B%E3%81%91%E6%9B%BC%E8%8D%BC%E7%BE%85.jpg)


[糸掛け曼荼羅とは？](https://www.itomandala.com/%E7%B3%B8%E3%81%8B%E3%81%91%E6%9B%BC%E8%8D%BC%E7%BE%85%E3%81%A8%E3%81%AF/)  
[What's "_Thread handing mandala_"?](https://www.itomandala.com/%E7%B3%B8%E3%81%8B%E3%81%91%E6%9B%BC%E8%8D%BC%E7%BE%85%E3%81%A8%E3%81%AF/)

## 2.デモ　DEMO  
Ver0.1.0  
<img src="https://raw.github.com/wiki/zuhima/ItokakeMandala/gif/demo_ver0.1.0_basic.gif" width="500px">  


## 3.使い方　Usage
__ファイルを落としてこなくても使えるようにしました__ => [こちら](https://myprogramserver.mybluemix.net/ItokakeMandala)から  
__You can use this program without downloading files.__ => [HERE](https://myprogramserver.mybluemix.net/ItokakeMandala)!  
※リンクが切れていたら申し訳ありません。/Sorry if the link is broken...  

__1.描画範囲の設定/Set drawing size__ (Drawing Size)  
数値を入力することで曼荼羅の描画範囲を設定することができる。  
If you input numeric, drawing size of Mandala is set.

__2.線のサイズを決める/Set line size__ (Line size)  
基本的には1pxで問題ない。必要に応じて値を変えればいい。  
Basically there is no problem with 1px.Change the value as needed.

__3.ピンの数を決める/Set number of pins__ (Pin Count)  
半角数字を入力して、ピンの数を決める。  
Set number of pins by inputting single-byte alphanumeric characters.

__4.曼荼羅のタイプを決める/Select type of mandala__ (Mandala Type)  
曼荼羅のタイプやパターンはここで変えることができる。  
Type and pattern of mandala can be changed.

* prime num  
ある素数だけ飛ばした位置のピンに糸をかけることで出来上がるパターン。選んでくる素数によって模様が変わる。prime numを選択するとすぐ下にチェックボックスが出現する。1つ1つは素数を表している。  
A pattern created by threading a pin at a position where a certain prime number has been skipped.Pattern is changed by prime numbers you slect.If you select _prime num_, checkboxes appear just below.

* flower  
花模様の曼荼羅を描画する。選択するとUIが変化し、petal,step1,step2の入力欄が現れる。いずれも数値を入力する。  
The mandala of flower pattern is drawn.If you select _flower_, UI changes and input fields of _petal_, _step1_, _step2_ arpear.Each input field input numeric.
  - petal：花びらの枚数 / Number of petal
  - step1：線の始点の移動ペース / Move pace of line's start point
  - step2：線の終点の移動ペース / Move pace of line's end point

__5.配色を決める/Select color type__ (Color Type)  
曼荼羅の配色を設定することができる。  
You can set color of mandala.
* mono  
指定色のみで描画する。monoを選んだのち、すぐ下に色の入力欄が出現する。  
Draw by only one color you set.After selecting _mono_, a color inout field appears jaust below.

* gradation  
こちらで用意したグラデーションパターンで描画する。2パターンあるので、どちらか選ぶ。  
Draw by gradation pattern prepared. There are two pattern, choose either.

* random  
Createボタンを押すたびに色をランダムで変える。  
Change the color randomly each time you press the _Create_ button.

__6.アニメーション設定/Set animation type__ (Animation)  
描画の際の演出を設定することができる。
* none  
演出なしで描画する。  
Not animation.

* magic circle  
各ピンから一斉に線を引く。  
Draw a line from each pin at once.

__7.Createボタンを押す/Push *Create* button__ (Create)  
1 ~ 5の設定を行ったうえでCreateボタンを押すことで曼荼羅が描画される。  
The mandala is drawn by pushing the _Create_ button after setting 1 ~ 5.



## 4. 備考 Remarks
* 本プログラムは、HTML,JavaScriptで動いており、ライブラリとしてはjQuery, D3.js(いずれもCDN)を使用しています。
通信環境があるところで使用してください。  
 This program is writed by _HTML_, _JavaScript_._jQuery_ and _D3.js_(both of CDN) are used for library.You need a communication environment.

* ピンの数を多くするほど描画処理に時間がかかります。  
The more pins you set, drawing process takes time.

## 5.バージョン情報 Version information  
* __Ver0.2.2__ (2019.9.14)  
描画範囲の設定機能の追加。花模様曼荼羅の描画タイプ(単色,ノンアニメーション)を追加。  
Added function that drawing size set.And added mandala of flower pattren.(only mono color, non animation)

* __Ver0.2.1__ (2019.9.4)  
アニメーションモードの「magic circle」を追加。  
Added animation mode "_magic circle_".

* __Ver0.2.0__ (2019.9.3)  
今後の機能追加のために、プログラムを改修。一部UIの追加。機能としての変更点はなし。  
Refurbishmented program for adding function, and added part of UI.No functional changes.

* __Ver0.1.2__ (2019.9.1)  
ランダム配色モードを追加。プログラムの軽微な修正。
Added random color mode and fixed code.

* __Ver0.1.1__ (2019.8.30)  
グラデーションモードを追加。(2モード)  
The gradation mode is added.(2modes)　

* __Ver0.1.0__ (2019.8.25)  
線の色を変えられるように変更。単色のみ。  
The color of lines can be changed.Only monochromatic mode.

* __Ver0.0.3__ (2019.8.24)  
チェックボックスを最初からチェック状態にしておく。  
Prime number checkboxes are checked from beginnig.

* __Ver0.0.2__ (2019.8.16)  
UI周りのタグを"p"を"div"に変更。GitHubのブランチテストも兼ねて。  
Change tag around UI from "p" to "div". Also serves as branch test for GitHub.

* __Ver0.0.1__ (2019.8.12)  
　円形の一般的な曼荼羅の描画。線の太さの変更。素数パターンの変更。  
　Circular general mandala drawing.You can chenge the line thickness and prime number checkboxes.

## 6.今後の実装予定 Future implementation schedule  
* 線の色付け(~グラデーション、ランダム~、カスタム) / Line coloring(~gradation,random,~custom)  
* UI周りの改良 / UI improvements  
* 角型曼荼羅の実装 / Implementation of square mandala  
* 素数パターン以外の曼荼羅描画(~花~,鳥...) / Drawing mandara other than prime numbers(~flower~, bird...)  
* アニメーション設定 / Animation settings  
　　　　　　　　　　　　　　　　...etc

## 7.著者 Author  
__zuhima__ => [github](https://github.com/zuhima), [twitter](https://twitter.com/hmjnzsm0922/)  
　最近(2019/8~)プログラムの公開みたいなことを始めました。よかったらフォローしてください、よろしくお願いします。  
 Recentry, I started to publish my program.Please follow me.

## 8.ライセンス LICENCE  
MIT

## 9.最後に Comment
　ここまで読んでいただきありがとうございました。プログラムの公開をするのはこれが初めてで、ここで書く内容からMarkdownの記法まで細かく調べながら、
 このREADMEを書いています。読みにくいところや分かりにくいところがあったら申し訳ございません。また、無理のないペースでこのツールのバージョンアップを行ったり、
 別のツールを作成してみたりするつもりなので、よろしくお願いします。  
