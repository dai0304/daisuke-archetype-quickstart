daisuke-archetype-quickstart
============================

都元ダイスケの都元ダイスケによる都元ダイスケのための Maven Java Project ひな形生成の為のarchetype。

What is this?
-------------

各種Eclipseの設定ファイルも含む、Javaプロジェクトのひな形を生成するためのApache Maven用archetypeです。

- pomに汎用的なライブラリを自動設定します。(Google guava / slf4j等)
- Eclipseコンパイラやコードフォーマッタ等の設定を都元流に自動設定します。
- eclipse-cs (Checkstyle) や Findbugs の設定も都元流に自動設定します。


How to use?
-----------

- [Maven release repository](http://maven.xet.jp/release/)
- [Maven snapshot repository](http://maven.xet.jp/snapshot/)

    mvn3 archetype:generate \
        -DarchetypeRepository=http://maven.xet.jp/release \
        -DarchetypeGroupId=jp.xet.archetype \
        -DarchetypeArtifactId=daisuke-archetype-quickstart \
        -DarchetypeVersion=1.4 $*


License
-------

Copyright (C) 2010-2011 [Daisuke Miyamoto](http://d.hatena.ne.jp/daisuke-m/).

Distributed under the Apache License v2.0.  See the file LICENSE.txt.


