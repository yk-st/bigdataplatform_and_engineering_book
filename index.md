---
layout: default
title: エンジニアのためのデータ分析基盤入門
description: エンジニアのためのデータ分析基盤入門のサポートページです
site_url: https://yk-st.github.io/bigdataplatform_and_engineering_book/
---
   
<h1 id="-">エンジニアのためのデータ分析基盤入門</h1>
<p>本リポジトリは、技術評論社から出版された以下の書籍 のWeb補足情報を提供するためのものです。書籍に関する「正誤表」や関連情報をまとめています。</p>
<p align="center"><img src="title.png" width="350" height="450"></p>
<p>ISBNが発行されたら追記予定です。</p>
<h1 id="-">本書の構成</h1>
<p>各章のハイライトです。</p>
<ul>
<li><p>1章
ビッグデータの世界や歴史や今、これからについて紹介する章です。
ビッグデータ世界の概略がわかります。</p>
</li>
<li><p>2章
データ基盤を管理する「データエンジニアリング」を想定して、職責やナレッジを含めた基礎知識を概説します。
データエンジニアリングでカバーすべき範囲は多岐にわたるため、まず大まかにデータ基盤全体を把握していきます。</p>
</li>
<li><p>3章
データ基盤を構築/管理する上で大切なポイントである「セルフサービス」「SSoT」という考え方を中心に<br>知恵を創出しやすいデータ基盤に求められる役割や考え方、方法論について解説します。</p>
</li>
<li><p>4章
データ基盤を4つの層に分割し、それぞれの層で登場する技術スタックを紹介します。
単純な技術の羅列とならないようにユーザが知恵の創出に集中するためのベースとなる特定の技術スタックを取り上げて特徴や用途を紹介することで
多々あるビッグデータの技術の中から技術選択で迷わないようにしていきます。</p>
</li>
<li><p>5章
データを管理するためのメタデータを紹介します。
「データの定義をいちいちSQLで調べている」「データが見つけづらい」「データが活用されない」メタデータを通したユーザの悩みを解決する章です。</p>
</li>
<li><p>6章
データマートを作成し利用綺麗に整形することも大事ですが、
単純な作成方法だけにとどまらず、ユーザがデータマートを自由に素早く反復して作成できるようにすることが重要です。
データ利用の一つの障壁となる人とのコミュニケーションをシンプルにするための方法について紹介する章です。</p>
</li>
<li><p>7章
データの状態を常にモニタリングすることで、データの精度を高めるデータ品質管理について紹介します。
間違えたデータで意思決定をしないように、データの品質を継続的に測定し、データの設計書を残し継続的に知恵を創出できるデータ基盤を作り上げます。</p>
</li>
<li><p>8章
データ基盤開発の方向を見失わないようにするためのKPI管理とKPI管理対象項目について紹介していきます。
なんとなくでデータ基盤を管理、運用する状況から脱する際に役に立つ実際のデータ基盤で運用されている項目を紹介します。</p>
</li>
<li><p>Appendix
ビッグデータに関する要素はリレーショナルデータベースの技術要素と通ずるものがあります。
そのため1章からの解説をよりわかりやすくするために、リレーショナルデータベースの基本要素を解説する付録です。</p>
</li>
</ul>
<h1 id="-">正誤表</h1>
<p>正誤表へのリンクです。<br><a href="errors.md">正誤表</a></p>
<h1 id="-">動作環境</h1>
<p>本書を作成時に利用した筆者の動作の確認環境は以下です。</p>
<ul>
<li>M1 Max MacBook Pro(2021)</li>
<li>Java 11(openjdk 11.0.12)</li>
<li>Spark 3.2.0</li>
<li>Python 3.8</li>
<li>Docker Desktop(4.3.1 (72247))</li>
<li>Ubuntu 18.10 (Cosmic Cuttlefish)</li>
</ul>
<h1 id="-">著者について</h1>
<p>普段はデータを活用する企画業務に従事<br>ビッグデータのシステム構築から活用までアドバイザリーをやっています。</p>
<ul>
<li>Twitter：<a href="https://twitter.com/yuki_saito_en">@yuki_saito_en</a></li>
<li>LinkedIn: <a href="https://www.linkedin.com/in/yuki-saito-40872b217/">https://www.linkedin.com/in/yuki-saito-40872b217/</a></li>
<li>Note: <a href="https://note.com/yukinkoyuki">https://note.com/yukinkoyuki</a></li>
<li>MENTA(アドバイザリー):<a href="https://menta.work/member/dashboard">https://menta.work/member/dashboard</a></li>
<li>Udemy(オンライン講師): <a href="https://www.udemy.com/user/yuki-saito-7/">https://www.udemy.com/user/yuki-saito-7/</a></li>
</ul>
<h1 id="-">本書内で紹介している書籍など</h1>
<p>ここではビッグデータ関連書籍として、書籍内で紹介している書籍やおすすめの書籍について紹介します。</p>
<ul>
<li><a href="https://amzn.to/3nQ90ts">Spark: The Definitive Guide: Big Data Processing Made Simple (English Edition)</a></li>
<li><a href="https://amzn.to/3nNMcdU">Kafka: The Definitive Guide (English Edition)</a></li>
<li><a href="https://amzn.to/3tQh69g">データ指向アプリケーションデザイン ―信頼性、拡張性、保守性の高い分散システム設計の原理</a></li>
</ul>
<h1 id="-">その他補助になると考えられるもの</h1>
<p>本書で頻繁に出てくるSpark(Pyspark)やKafka、メタデータストア、ストリーミングをコード中心に駆け回ってみる講座たちです。<br>コードはGithubに公開していますので更に理解を深めるためにご利用ください。</p>
<ol>
<li><a href="https://www.udemy.com/course/python-spark-pyspark/?referralCode=E67BF8B61F65866794EB">「データサイエンスのための前処理入門PythonとSparkで学ぶビッグデータエンジニアリング(PySpark) 速習講座」</a></li>
</ol>
<p>Gitリポジトリ<br><a href="https://github.com/yk-st/pyspark_batch">https://github.com/yk-st/pyspark_batch</a></p>
<ol>
<li><a href="https://www.udemy.com/course/draft/4367192/?referralCode=AB48AD18D10E55DCB0E5">「【PythonとSparkで始めるデータマネジメント入門】 ビッグデータレイクのための統合メタデータ管理入門」</a></li>
</ol>
<p>Gitリポジトリ<br><a href="https://github.com/yk-st/pyspark_datamanagement_metadata">https://github.com/yk-st/pyspark_datamanagement_metadata</a></p>
<ol>
<li><a href="https://www.udemy.com/course/python-spark-streaming/?referralCode=F5E3B429A5C47468BDAD">「【データサイエンスのためのストリーミング前処理入門　PythonとSparkで始めるビッグデータストリーミング処理入門」</a></li>
</ol>
<p>Gitリポジトリ<br><a href="https://github.com/yk-st/pyspark_streaming">https://github.com/yk-st/pyspark_streaming</a></p>
<ol>
<li><a href="https://www.udemy.com/course/draft/4415660/?referralCode=EF89D5D240FB483AF4A1">「超速入門!【データサイエンスへの最初の一歩】PythonとSparkで学ぶデータ分析のための前処理と分散処理 一気見講座」</a></li>
</ol>
<p>Gitリポジトリ<br><a href="https://github.com/yk-st/pyspark_super_crush_course">https://github.com/yk-st/pyspark_super_crush_course</a></p>
