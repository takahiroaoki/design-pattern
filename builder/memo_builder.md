# Builderパターン

Directorインスタンスは、自分が操作しているインスタンスがTextBuilderインスタンスなのかHTMLBuilderインスタンスなのかは具体的には知らないが、Builderであることだけを知っていれば扱うことができる。
このようにどのクラスがどのクラスのメソッドを知っているかを意識していれば、コードの修正の際にどこを修正すれば良いのかがわかりやすい。


逆に、Builderクラスのようなインターフェースや抽象クラスを積極的に活用することで、修正しやすいコードを書くことができる。設計者には将来どんな機能が加わるかを意識して設計することが求められる。