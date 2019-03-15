G Suite with Watson
============================================
GoogleのG Suite（Gmail、フォーム、スプレッドシート、GAS等）とIBM Watson™を組み合わせた業務支援ツールのテンプレート集です。メールやフォーム、RSS等からスプレッドシート上に蓄積したデータを、Watsonへの学習や、Watsonを活用した処理に利用できます。

[](![img](https://github.com/softbank-developer/docs/blob/master/images/watson_gsuite_logo.png?raw=true))

テンプレートはデータ収集元と、利用Watson APIにより分かれます。各テンプレートには次のコンポーネントが含まれます。

- データの収集と動作設定用Googleスプレッドシート  
- IBM Watson™と連携してデータを処理するためのGASスクリプト  
	現在、Watson APIはNatural Language Classifier（NLC）のみに対応しています。


## 各テンプレート概要
- ### chat
	- GAS上で稼働する問い合わせ対応を行うWEBアプリケーションからのデータを収集・処理
	- Natural Language Classifierを利用した分類
- ### form
	- Google フォームからのデータを収集・処理
	- Natural Language Classifierを利用した分類
- ### gmail
	- Gmailからのデータを収集・処理
	- Natural Language Classifierを利用した分類
- ### rss
	- RSSからのデータを収集・処理
	- Natural Language Classifierを利用した分類
- ### spreadsheet
	- Googleスプレッドシートで収集されるデータを処理
	- Natural Language Classifierを利用した分類


## 環境構築
各テンプレートは、Googleドライブ上で、スプレッドシートの形で公開されています。各スプレッドシートには、対応するGASスクリプトも内包されています。導入のための最も簡単な方法は、このGoogle Drive上で公開されているスプレッドシートをコピーする方法です。各スプレッドシートのリンクは下を参照してください。

なんらかの理由で上記の方法が取れない場合は、手動で環境を構築するための手順も用意しています。具体的な手順について
は下のリンク先よりご確認ください。
- ### chat
	- [Googleドライブから環境をコピー](https://docs.google.com/spreadsheets/d/1pUk2PrEO56QuyUnYiJgutjx5OTuPYmDh4JtLRnngbg0)
	- [手動で環境構築](https://github.com/softbank-developer/gsuite_with_watson/tree/master/chat)
- ### form
	- [Googleドライブから環境をコピー](https://docs.google.com/spreadsheets/d/1_ZK3d38NN984_1Z2QhwLHyuE2yT2gh4LefmQpn8W_kE)
	- [手動で環境構築](https://github.com/softbank-developer/gsuite_with_watson/tree/master/form)
- ### gmail
	- [Googleドライブから環境をコピー](https://docs.google.com/spreadsheets/d/18KObxlbLQL5W-ENQOWKr_cDB4EGV52KpybjMAIKfEYo)
	- [手動で環境構築](https://github.com/softbank-developer/gsuite_with_watson/tree/master/gmail)
- ### rss
	- [Googleドライブから環境をコピー](https://docs.google.com/spreadsheets/d/1MiOHGjc6o8vW3i0MZ7liiEgctxWPtJKgxVQaLEVXjM8)
	- [手動で環境構築](https://github.com/softbank-developer/gsuite_with_watson/tree/master/rss)
- ### spreadsheet
	- [Googleドライブから環境をコピー](https://docs.google.com/spreadsheets/d/1-Ikcm89xwDVj9P_sJFF34Dl6MoLWx-wgw-Siq_Tl6mE)
	- [手動で環境構築](https://github.com/softbank-developer/gsuite_with_watson/tree/master/spreadsheet)

より、詳細なドキュメントは下記のリンクよりご確認ください。  
https://softbank-developer.github.io/docs/


## ライセンス
[MIT](https://github.com/softbank-developer/gsuite_with_watson/blob/master/LICENSE)
