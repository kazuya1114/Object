# オブジェクト指向デザインパターン

## 1. SoC(処理の分離)
![クライアントサーバシステム](クライアントサーバシステム.png)
<br></br>

## 2. メリット
<P>①プログラムの鵜飼い回しができる</p>
<p>②改修の際、修正するものとしないものを分離できる</p>
<p>例：デザインパターンを利用したシステムと処理が同じでUIだけが違うシステムを新規で作成する</p>
<p>この時、UIに相当するプレゼンテーション層以外のロジックを使いまわしできる</p>
<p>また、修正を行うファイルの分離もプレゼンテーション層のみに分離できている(この場合、改修ではないが)</p>
<br></br>

## 3. クライアントサーバシステムの概念を元にしたデザインパターン
- ドメイン駆動設計(DDD)
- MVC(Model View Controller)
- MVVM(Model View ViewModel> etc...
