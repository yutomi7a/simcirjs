---
title: 九テク論理回路サポートサイト
author: 富田 裕
date: 2020/6/6
---

## はじめに
2020年九州テクノカレッジ・ハイテク情報科向けの科目『論理回路』に関する資料等を提供するサイトです.

## 授業資料
2/12の後半以降の資料のみ公開予定です.

- スライド
    - [補助スライド](https://yutomi7a.github.io/simcirjs/self_dual_slides.html)
    - [2月12日後半](https://www.dropbox.com/s/ytqq2k5z9hd8hz6/200212b.pdf)
    - [2月19日前半](https://www.dropbox.com/s/wlshuvalvedbh1g/200219a.pdf)
    - [2月19日後半](https://www.dropbox.com/s/hhxwycld0x0le4d/200219b.pdf)
    - [2月26日前半](https://www.dropbox.com/s/xhxd60qtwg6scqz/200226a.pdf)
    - [2月26日後半](https://www.dropbox.com/s/l8wjvgq8q0cp929/200226b.pdf)
    - [3月18日前半](https://www.dropbox.com/s/6pynw7l3zv57wuk/200318a.pdf)
    - [3月18日後半](https://www.dropbox.com/s/4zeuhecav2szhpg/200318b.pdf)
    - [3月25日前半](https://www.dropbox.com/s/dplk8qh541ehj2g/200325a.pdf)
    - [3月25日後半](https://www.dropbox.com/s/4bpfvpm9ouuyno5/200325b.pdf)
    - [5月27日(6月1日)前半](https://yutomi7a.github.io/simcirjs/200527a/#/) [pdf版はこちら](https://www.dropbox.com/s/n4joa7jv2x5p580/200527a.pdf?dl=0)
    - [5月27日(6月1日)後半](https://yutomi7a.github.io/simcirjs/200527b/#/) [pdf版はこちら](https://www.dropbox.com/s/lmg2ypsgxicsg2t/200527b.pdf?dl=0)
    - [6月3日](https://yutomi7a.github.io/simcirjs/200603_slides.html) 
  
- 課題(メールなどで提出)
    - [5月27日(6月1日)](https://www.dropbox.com/s/mjr5fztlr8dr4ci/200527qa.pdf?dl=0)
      * 提出先: yutomi7a@じーめーる.com (じーめーるをgmailに書き換え) またはLINEアカウント
      * 解答した用紙はカメラやスキャナで撮影し, 画像ファイルにして提出してください
        - ノートやレポート用紙に書き写してもOK
        - 可能ならpdfファイルのまま書き込み後提出してもOK
    - 6月3日:
  1. 次の論理関数をカルノー図を用いて簡単化し最小積和形を求めよ.
    $$
    \begin{align}F_1 &= A\,B+A\,C+A\,\overline{B}\,C+\overline{A}\,B\,\overline{C}\\
    F_2 &= W\,X\,Y\,Z+\overline{W}\,\overline{X}+X\,\overline{Y}\,Z\end{align}
    $$

  2. $F_2$の解答をAND, OR, NOT素子だけを使って実現してみよ(3入力のAND,OR素子を使っても構わない).
     - 前回と同様メールまたはLINEアカウントから画像またはpdfファイルを提出すること.
     - 締め切り: 6/15 23:59まで(以降の提出は減点)


### JavaScript教材 

- [デジタル回路[JavaScript版]](http://home.a00.itscom.net/hatada/_toc/dc.html#dc2sim)
  - デジタル回路の基礎を学べるサイト.
  - 残念ながらJK-FFやD-FFなどがうまく動いていません(2020年5月現在).
- [SimcirJS(forked)](sandbox.html)
  - 自分で回路を組んで動作を確認できるJavaScriptプログラム.
  - こちらでforkし, OSC(クロックパルスを入力するデバイス)の周波数を見やすいように調整しました.
  - 残念ながら多くのスマートフォンでは操作に制限があります.

### 参考文献(五十音順)

おすすめの教科書ではありませんが, 特に参考にしているものだけを取り上げます. また，無料で閲覧可能なWeb資料もあります. 

(#) 岩出秀平『[明快解説・箇条書式　ディジタル回路](http://muisuri.my.coocan.jp/electro.html)』
(#) グッドステイン, R.L.『ブール代数』赤攝也訳, 培風館, 1971.
(#) 坂井　修一『[論理回路基礎](https://ocw.u-tokyo.ac.jp/course_11273/)』東京大学OCW, 2005
(#) 細井勉『[情報科学のための論理数学](https://www.nippyo.co.jp/shop/book/1291.html)』
(#) 宮崎佳典 新谷誠 中谷広正『[理工系のための離散数学](http://www.tokyo-tosho.co.jp/books/ISBN978-4-489-02152-7.html)』
(#) 湯田春雄 堀端孝俊『[しっかり学べる 基礎ディジタル回路](https://www.morikita.co.jp/books/book/1864)』
(#) Posthoff, Christian., Steinbach, Bernd., *[Logic Functions and Equations](https://www.springer.com/jp/book/9783030024192)*

## 講師について

普段は回路と無縁な研究をしています.

<a href="https://www.researchgate.net/profile/Yu_Tomita3">Yu Tomita on ResearchGate</a>

[researchmap](https://researchmap.jp/yu_tomita)

Copyright (c) 2020 Yu Tomita

Licensed under the MIT license:
  [http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)