Monad Transformer
------------------

### ライブラリ
* [The transformers package](https://hackage.haskell.org/package/transformers)
* [The mtl package](https://hackage.haskell.org/package/mtl)
* [The monads-tf package](http://hackage.haskell.org/package/monads-tf)

### 入門／チュートリアル
* [Maybe と IO を一緒に使いたくなったら - ryota-ka's blog](https://ryota-ka.hatenablog.com/entry/2018/05/26/193220)
* [モナドトランスフォーマーとその周辺](http://qiita.com/ruicc/items/7512c990a1835bba444a)
* [Haskell モナド変換子 超入門](http://qiita.com/7shi/items/4408b76624067c17e933)
* [モナドトランスフォーマー・ステップ・バイ・ステップ](http://bicycle1885.hatenablog.com/entry/2012/12/08/165236)
* [A Gentle Introduction to Monad Transformers](https://github.com/kqr/gists/blob/master/articles/gentle-introduction-monad-transformers.md)
* [モナモナ言うモナド変換子入門](http://hiratara.github.io/presentations/2015-03-21_monadbase_vol2.html#/)
* [モナドとモナド変換子のイメージを描いてみた](http://d.hatena.ne.jp/melpon/20111028/1319782898)
* [Monad transformers](http://taylor.fausak.me/2015/05/14/monad-transformers/)
* [入門 StateTモナド](http://qiita.com/ak1t0/items/780f6722623ec126fcdf)
* [IO (Maybe a)というタイトルでモナド変換子について学んだことを話した - #LT駆動](http://blog.eiel.info/blog/2016/07/03/ltdd-27-io-maybe/)
* [IO (Maybe String)を触ってみる](http://qiita.com/eielh/items/2f0f774914431990ec37)
* [Haskellモナドトランスフォーマー(1)](http://delihiros.hatenablog.jp/entry/2012/04/19/140557)
* [Monad transformer](https://anhduy.io/posts/2018-02-08-monad-transformer.html)
* [モナド変換子(その１: 基本） - Qiita](https://qiita.com/HirotoShioi/items/8a6107434337b30ce457)
* [モナド変換子 (その２:課題を通じてライブラリに触れてみる) - Qiita](https://qiita.com/HirotoShioi/items/ac75b97aa52f9db9c472)
* [モナド変換子 (その3: 課題の解答) - Qiita](https://qiita.com/HirotoShioi/items/6faaf8babb23bb2f3485)
* [AceHack-Practical Monad Transformers](https://sakshamsharma.com/2018/03/monadt/)

### MonadControl/MonadTransUnlift
`MonadTrans`の`lift`がモナドをモナドスタックの中で実行できるようにするのとは逆に、モナドスタックをベースとなるモナドの中で実行する仕組みを提供する。

* [Unlifting in 2 minutes](https://github.com/fpco/unliftio/tree/master/unliftio#unlifting-in-2-minutes)
* [モナドトランスフォーマーとmonad-control](http://maoe.hatenadiary.jp/entry/20111207/1323185162)
* [monad-control](https://hackage.haskell.org/package/monad-control)
* [lifted-base](https://hackage.haskell.org/package/lifted-base)
* [MonadBaseControl in Five Minutes](http://www.parsonsmatt.org/2017/11/21/monadbasecontrol_in_five_minutes.html)
* [Announcing: monad-unlift](https://www.fpcomplete.com/blog/2015/04/announcing-monad-unlift)
* [Announcing: the new unliftio library](https://www.fpcomplete.com/blog/2017/07/announcing-new-unliftio-library)
* [Understanding unliftio \| fbrs](https://fbrs.io/unliftio/)

### 圏論
* [Monad transformer](http://mbps.hatenablog.com/entry/2014/06/28/033234)
* [Adjunction からの monad transformer](http://mbps.hatenablog.com/entry/2014/11/25/220948)
* [Monad からの monad transformer](http://mbps.hatenablog.com/entry/2014/12/11/112455)
* [Proper Treatment 正當作法/blog/posts/Monad transformers](http://conway.rutgers.edu/~ccshan/wiki/blog/posts/Monad_transformers/)

### モナド準同型
* [The mmorph package](https://hackage.haskell.org/package/mmorph)
* [モナドモナド (LT没ネタ)](http://qiita.com/hiratara/items/65fcf38070def7e5a918)
* [ZuriHac 2016: Monad Homomorphisms](https://www.youtube.com/watch?v=YTaNkWjd-ac)
* [テンソル積の作り方](http://d.hatena.ne.jp/m-hiyama/20160829/1472445276)
* [テンソル積の作り方 2： 双加群の場合、小さい圏の場合](http://d.hatena.ne.jp/m-hiyama/20160830/1472527717)

### Others
* [Wrangling Monad Transformer Stacks](https://www.youtube.com/watch?v=8t8fjkISjus)
* [ContEitherT](https://iteratee.wordpress.com/2015/10/01/conteithert/)
* [Monad transformers, free monads, mtl, laws and a new approach](https://ocharles.org.uk/blog/posts/2016-01-26-transformers-free-monads-mtl-laws.html)
* [Lifts for free: making mtl typeclasses derivable](https://lexi-lambda.github.io/blog/2017/04/28/lifts-for-free-making-mtl-typeclasses-derivable/)
* [Edward Kmett - Monad Transformer Lenses](https://www.youtube.com/watch?v=Bxcz23GOJqc)
* [Enterprise Haskell Pattern: Lensed Reader](http://michaelxavier.net/posts/2016-04-03-Enterprise-Haskell-Pattern-Lensed-Reader.html)
* [The ObserverT monad transformer [check for interest]](https://gist.github.com/rampion/015fa65ac654a2947045)
* [Refactoring to a Monad Transformer Stack](https://robots.thoughtbot.com/refactoring-to-a-monad-transformer-stack)
* [list-transformer - A beginner-friendly ListT](http://www.haskellforall.com/2016/07/list-transformer-beginner-friendly-listt.html)
* [Clean Alternatives with MaybeT](http://www.parsonsmatt.org/2016/11/18/clean_alternatives_with_maybet.html)
* [John A De Goes: MTL Versus Free Deathmatch - λC 2016 - YouTube](https://www.youtube.com/watch?v=JLevNswzYh8)
* [Monad Transformer Workshop](https://begriffs.com/posts/2017-04-09-monad-tutorial-workshop.html)
* [If you’re using lift, you’re doing it wrong (probably)](http://blog.ezyang.com/2013/09/if-youre-using-lift-youre-doing-it-wrong-probably/)
* [A Tale of Two Brackets](https://www.fpcomplete.com/blog/2017/06/tale-of-two-brackets)
* [A tale of two Monads: Free vs MTL \| Front Row](http://tech.frontrowed.com/2017/09/28/benching-free/)
* [lexi-lambda/mtl-style-example](https://github.com/lexi-lambda/mtl-style-example) - A small example of using mtl style to unit test effectful code
* [Monad Transformer State - Michael Snoyman](https://www.youtube.com/watch?v=KZIN9f9rI34&feature=youtu.be)
* [モナドをラップする話](http://qiita.com/ruicc/items/175cc23f13d6004d8b3d)
* [Ether - Monad Transformers and Classes](https://int-index.github.io/ether/)
* [Monad transformers and comonad transformers](http://dlaing.org/cofun/posts/monad_transformers_and_comonad_transformers.html)
* [Haskell Application Monad](https://savanni.luminescent-dreams.com/page/haskell-app-monad)
* [Monad Transformer State - Michael Snoyman - YouTube](https://www.youtube.com/watch?v=KZIN9f9rI34&feature=youtu.be)
* [いろいろなパッケージから提供されている ListT モナド変換子の違いについて調べてみる - 無駄と文化](http://blog.mudatobunka.org/entry/2018/01/03/233314)
* [The Comonad.Reader » Monads from Comonads](http://comonad.com/reader/2011/monads-from-comonads/)
* [Transforming Transformers](http://www.parsonsmatt.org/2018/04/10/transforming_transformers.html)
* [ResourceT: A necessary evil](https://www.fpcomplete.com/blog/2018/10/resourcet-necessary-evil)
* [resource-simple](https://hackage.haskell.org/package/resource-simple)
  * [Understanding ResourceT](https://www.fpcomplete.com/blog/2017/06/understanding-resourcet)
* [RAII is better than the bracket pattern](https://www.snoyman.com/blog/2018/10/raii-better-than-bracket-pattern)
* [Monadic yak shaving](https://ivanmiljenovic.wordpress.com/2015/02/02/monadic-yak-shaving/)
* [Monatron](https://hackage.haskell.org/package/Monatron)
* [Documentation.Layers.Overview](http://hackage.haskell.org/package/layers/docs/Documentation-Layers-Overview.html)
* [Mocking Effects using Constraints and Phantom Data Kinds](https://chrispenner.ca/posts/mock-effects-with-data-kinds)
* [Tweag I/O - capability: the ReaderT pattern without boilerplate](https://www.tweag.io/posts/2018-10-04-capability.html)
* [High-Performance Functional Programming Through Effect Rotation – John A De Goes](http://degoes.net/articles/rotating-effects)
* [ReaderT パターン(翻訳) - LugendrePublic](https://scrapbox.io/LugendrePublic/ReaderT_%E3%83%91%E3%82%BF%E3%83%BC%E3%83%B3(%E7%BF%BB%E8%A8%B3))
* [Final Tagless vs Free Monad - Google スライド](https://docs.google.com/presentation/d/1VhS8ySgk2w5RoN_l_Ar_axcE4Dzf97zLw1uuzUJQbCo/edit#slide=id.g575348a5eb_0_0)
* [【Control.Monad.Trans】(1) Identityモナド - Qiita](https://qiita.com/sand/items/e88b798d8783606071c5)
* [【Control.Monad.Trans】(2) StateTモナド - Qiita](https://qiita.com/sand/items/802b8c4a8ae19f04102b)
* [【Control.Monad.Trans】(3) ExceptTモナド - Qiita](https://qiita.com/sand/items/fe3c29560136803e8b11)
* [【Control.Monad.Trans】(4) ReaderTモナド - Qiita](https://qiita.com/sand/items/93d6ba75b0c4e39ce295)
* [【Control.Monad.Trans】(5) IOモナド - Qiita](https://qiita.com/sand/items/ee3c19c191c87c32f867)

## 属性文法
* [なぜ属性文法は重要か](https://sites.google.com/site/paclearner/why_attribute_grammars_matter)
* [Attribute Grammars Fly First-Class](http://www.staff.science.uu.nl/~swier004/Publications/AttributeGrammarsFly.pdf)