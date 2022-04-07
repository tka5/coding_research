# コーディング規約について調べたこと

- [クックパッドのコーディング規約](https://github.com/cookpad/styleguide/blob/master/ruby.ja.md)
  - 主に以下の事項についての規約
    - Ruby バージョン
    - インデント
    - 空白
    - 空行
    - 文字エンコーディングとマジックコメント
    - 1行の文字数
    - 数値
    - 文字列
    - 正規表現
    - 配列
    - ハッシュ
    - 演算式
    - 代入式
    - 制御構造
    - メソッド呼び出し
    - BEGIN と END
    - モジュールとクラスの定義
    - メソッドの定義
    - 変数

- [airbnbのスタイルガイド](https://github.com/airbnb/ruby/blob/master/README.md)
  - クックパッドと大体同じ
  - 大項目だけ抜粋
    - Whitespace
    - Line Length
    - Commenting
    - Methods
    - Conditional Expressions
    - Syntax
    - Naming
    - Classes
    - Exceptions
    - Collections
    - Strings
    - Regular Expressions
    - Percent Literals
    - Rails
    - Be Consistent
    - Translation

- [シンプルでわかりやすいコードを書くためにあなたがすべきこと](http://blog.jnito.com/entry/2016/05/18/120625)
  - メソッドの複雑度を意識する
    - [saikuro](https://github.com/metricfu/Saikuro/)で計測可能
  - 技術書から手数を増やす
    - 良いコード悪いコードを知る
      - [CODE COMPLETE](https://www.amazon.co.jp/exec/obidos/ASIN/489100455X/junic05-22/)
      - [リーダブルコード](https://www.amazon.co.jp/exec/obidos/ASIN/4873115655/junic05-22/)
    - デザインパターンを知る
      - [増補改訂版Java言語で学ぶデザインパターン入門](https://www.amazon.co.jp/exec/obidos/ASIN/4797327030/junic05-22/)
    - RDBMSに関する知見を増やす
      - [SQLアンチパターン](https://www.amazon.co.jp/exec/obidos/ASIN/4873115892/junic05-22/)
      - [ビジネス環境の変化に強いデータベース設計―仕様変更なんて恐くない!](https://www.amazon.co.jp/exec/obidos/ASIN/4883374424/junic05-22/)
    - Ruby についての知見を増やす
      - [プログラミング言語 Ruby](https://www.amazon.co.jp/exec/obidos/ASIN/4873113946/junic05-22/)
      - [Effective Ruby](https://www.amazon.co.jp/exec/obidos/ASIN/B00SF6JN4K/junic05-22/)
      - [Rails3レシピブック](https://www.amazon.co.jp/exec/obidos/ASIN/B00EYXMAES/junic05-22/)
  - スタイルガイドについて
    - [ruby-style-guide](https://github.com/fortissimo1997/ruby-style-guide/blob/japanese/README.ja.md)
    - [[初心者向け] RubyやRailsでリファクタリングに使えそうなイディオムとか便利メソッドとか](https://qiita.com/jnchito/items/dedb3b889ab226933ccf)
  - テストコードとリファクタリング etc

- [綺麗なコードと汚いコード。どちらのプログラマと一緒に働きたい？](https://codeiq.jp/magazine/2014/02/5464/)
  - リンク切れていた

- [rubocopのスタイルガイド](https://github.com/rubocop/rails-style-guide/blob/master/README.adoc)

- [RSpecのガイド](https://www.betterspecs.org/)

- [肥大化したActiveRecordモデルをリファクタリングする7つの方法（翻訳）](https://techracho.bpsinc.jp/hachi8833/2021_01_07/14738)
  - ファットモデルからミックスインで展開しない
  - 切り出し方
    - Value Object, View Object, Query Object, Form Object, Decorator



