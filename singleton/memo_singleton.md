# Singletonパターン

Singleton.javaやTripleton.javaのフィールドで、自分自身のインスタンスを用いているのは、無限ループにはならない。
というのもstatic修飾子を用いていることで、これはインスタンスフィールドではなくクラスフィールドとなっているから。
その証拠に、このフィールドにthis.(fieldName)でアクセスしようとしてもエラーが出る。これは、それぞれのインスタンスはこのフィールドを持っていないことを表している。