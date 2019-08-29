# 糸掛け曼荼羅メーカー/Thread Handing Mandala Maker

~~(現在、編集中です...。)
(Currently editing...)~~

※I'm not good at English...Please forgive my poor English.

## 本プログラムは[こちら](https://myprogramserver.mybluemix.net/ItokakeMandala)から！/This program can be used [HERE](https://myprogramserver.mybluemix.net/ItokakeMandala)!  
※リンクが切れていたら申し訳ありません。/Sorry if the link is broken

## 追記 Postscript  
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
ファイルを落としてこなくても使えるようにしました => [こちら](https://myprogramserver.mybluemix.net/ItokakeMandala)から  
You can use this program without downloading files. => [HERE](https://myprogramserver.mybluemix.net/ItokakeMandala)!  
※リンクが切れていたら申し訳ありません。/Sorry if the link is broken...  

基本的な使い方は以下0.~3.の通り。  
Basic usage is as follows 0-3.

__0. 線の太さを決める / Set line thickness (Line size)__  
　デフォルトでは1pxで描画される。ピンの数を多くするのであれば、より細い線で描画したほうがきれいにできる。太くしても雰囲気が変わるので試してみるとよい。  
 Default line thickness is 1px.If you increase the number of pins, the thinner the line, the better.  
 If you chenge the thickness of the line, The atmosphere of the mandala changes.Try it.

__1. ピンの数を決める / Set number of pins (Pin Count)__  
　円上に並べるピンの個数を入力する。ピンの数は4個以上で受け付ける。  
 Input the number of pins arranged on circle.You have to enter 4 or more.

__2. 素数のチェックボックスにチェックを入れる / Check the prime number checkbox (Prime Number Selection)__  
　Pin Countを入力するとPrime Number Selection欄にチェックボックスが現れる。チェックボックス1つ1つが素数を表している。
左から2,3,5...と続き最大はPin Countで入力した数未満の素数である。ここで選ぶ素数のパターンによって模様が変わってくる。  
If you enter the number of pins, checkboxes appear.Each checkbox represents a prime number.
The check boxes are 2,3,5 ... from the left, and the maximum is a prime number less than the number entered.Pattern changes depending on the prime number you choose.

__3. Create!ボタンを押す / Push a _Create!_ button (Create!)__  
　チェックボックスにチェックを入れると無効化されていたCreate!ボタンが有効になる。これを押すことで曼荼羅が描画される。  
 If you check checkboxes, disabled _create!_ button is enabled.This button press to draw Mandala.

(ピンの数や素数パターンを変更した際にCreate!ボタンが無効化されたままになっているときは、素数のチェックボックスをいじると有効化になります。)  
(If the button remains disabled, touch the prime number checkbox.)

__線の色を変える / Change color of lines(Color Type)__  
　Color Typeのラジオボタンで配色のモードを変えられます。
* mono  
　選択すると色を入力できるようになる。色を指定してcreateボタンを押すことで反映される。色の名前出ない文字列が入力された場合は黒色になる。  
 If you select _mono_ in radio buttons, you can input color name.After input color name, reflected by pressing the _create!_ button.Enter a non-color name to turn black.

* gradation  
　選択するとラジオボタンが表示される。どちらかのタイプを選択し_create!_ ボタンを押すことでグラデーションがかかった曼荼羅が描画される。  
If you select _gradation_ in radio buttons, you can select two type by radio buttons that appear newly.After selecting _gradation type_ radio button, mandala is drawn a gradient mandala by pushing _create!_ button.

## 4. 備考 Remarks
　本プログラムは、HTML,JavaScriptで動いており、ライブラリとしてはjQuery, D3.js(いずれもCDN)を使用しています。
通信環境があるところで使用してください。  
 This program is writed by _HTML_, _JavaScript_._jQuery_ and _D3.js_(both of CDN) are used for library.You need a communication environment.

## 5.バージョン情報 Version information  
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
* 線の色付け(グラデーション、カスタム) / Line coloring(gradation,custom)  
* UI周りの改良 / UI improvements  
* 角型曼荼羅の実装 / Implementation of square mandala  
* 素数パターン以外の曼荼羅描画(花,鳥...) / Drawing mandara other than prime numbers(flower, bird...)  
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
