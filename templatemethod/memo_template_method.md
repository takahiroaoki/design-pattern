# Template Method

似たクラスを複数作成する必要があるとき、それらの共通部分や骨組みを抽象クラスで設計する。
インターフェースではなく抽象クラスを使うのは、インターフェースでは具体的な関数の実装ができないから。
サブクラスで変更されたくないメソッドには抽象クラスのなかでfinal修飾子を付与しておく。


抽象クラスをより具体的に実装すれば、サブクラスでの記述が楽になる一方で自由度は下がり、抽象クラスの記述をほとんどしなければ、サブクラスの自由度が増す一方で、記述量の増加や、サブクラス間で重複する記述も書かなければいけなくなる。
一般にこのせめぎあいにマニュアルはなく、プログラムの設計者に委ねられている。