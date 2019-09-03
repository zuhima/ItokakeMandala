# 糸掛け曼荼羅メーカー/Thread Handing Mandala Maker

~~(現在、編集中です...。)
(Currently editing...)~~

※I'm not good at English...Please forgive my poor English.

## 本プログラムは[こちら](https://myprogramserver.mybluemix.net/ItokakeMandala)から！/This program can be used [HERE](https://myprogramserver.mybluemix.net/ItokakeMandala)!  
※リンクが切れていたら申し訳ありません。/Sorry if the link is broken

## 追記 Postscript  
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

__1.曼荼羅のタイプを決める/Select type of mandala__ (Mandala Type)  
曼荼羅の形やパターンを選ぶことができる。  
You can select shape and pattern of the mandala.  
* prime num



## 4. 備考 Remarks
* 本プログラムは、HTML,JavaScriptで動いており、ライブラリとしてはjQuery, D3.js(いずれもCDN)を使用しています。
通信環境があるところで使用してください。  
 This program is writed by _HTML_, _JavaScript_._jQuery_ and _D3.js_(both of CDN) are used for library.You need a communication environment.

* ピンの数を多くするほど描画処理に時間がかかります。  
The more pins you set, drawing process takes time.

## 5.バージョン情報 Version information  
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
