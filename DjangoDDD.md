大島和輝氏による「Djangoで実践ドメイン駆動設計による実装」のセッションを紹介します。

複雑化してきたアプリケーションの開発で，ドメイン駆動設計の手法を一部取り入れた例が最近出てきました。
アプリケーションの規模が増していくにつれて，MVCでの実装を続けていると，肥大化したModelやContollerが作られやすくその解決策の一つとしてDDDの手法などが話題になっています。
そこで，本セッションではDjangoでドメイン駆動開発(以下 DDD)を設計する際のやり方をDDDの用語を交えながら説明されました。

まずは，DDD及びドメインとは何か，戦略的設計と戦術的設計の違い，MVCの問題点を紹介されました。続いて，DDDの1手法であるクリーンアーキテクチャの説明とDjangoの説明を行いました。

最後に，Djangoのアプリケーション単位をサブドメインとしながら，DDDの

・ファクトリ
・ドメインサービス 
・アプリケーションサービス
・エンティティ
・バリューオブジェクト
・リポジトリ

を中心にどのように実際に設計するのかソースコードを参照しながら紹介されました。

発表の中ではソースコードを参照しながら設計されています。セッション動画も是非御覧ください。