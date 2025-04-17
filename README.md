# study_pawtner

## ■サービス概要
**どんなサービスなのかを３行で説明してください。**

Study Pawtnerは、プログラミング学習者の、特にエラーに関する学習の「記録・振り返り・共有」をサポートするサービスです。
日々の学習記録とエラー解決の軌跡を時系列で結びつけ、参考にした記事URLやAIとのやり取りを共有します。
学習が進むとかわいい犬達が遊びに来てくれます。

## ■ このサービスへの思い・作りたい理由
**このサービスの題材となるものに関してのエピソードがあれば詳しく教えてください。  このサービスを思いつくにあたって元となる思いがあれば詳しく教えてください。**

プログラミング学習をする中で、過去に遭遇したエラーが再度発生した際「あの時のエラーって何を参考にした？どうやって解決したんだっけ？」と思うのですが、
いつどの記事を参考にしたか？AIとどのようなやり取りをしたか？すぐに見つけることが出来ず苦労した経験からこのサービスを考えました。  
エラーを解決していく過程、参照した記事のURLやAIとのやり取りを日々の学習記録と結びつけて確認出来るようにすれば、解決に日数を要したエラーや自分がよく遭遇するエラーなども振り返りやすいのではと思いました。 
また、長時間一人でPCと向き合うプログラミングの作業を癒してくれる『相棒』がいたらいいなと思い、犬のキャラクターが足跡(Paw)を残して一緒に進んでくれる「Pawtner」を考えました。  
  
昨今、プログラミング学習でAIの活用について議論がされるなかで、AIを活用する人はAIとどのようなやり取りをしているか？使わないで取り組む人は何を参考にしているか？ そのような情報が共有出来る場になればと願っています。  
  


## ■ ユーザー層について
**決めたユーザー層についてどうしてその層を対象にしたのかそれぞれ理由を教えてください。**

【想定ユーザー層】  
エンジニアを目指してプログラミング学習する人  
【理由】 
自身が対象であり、経験から同じような境遇の方の役に立てればと考えました。  



## ■サービスの利用イメージ
**ユーザーがこのサービスをどのように利用できて、それによってどんな価値を得られるかを簡単に説明してください。**  

(1)学習記録の作成＆共有  
- 最小限プルダウン・チェックボックスだけで記録可能。文字入力なしでも出来る。
- エラー解決記事と時系列でリンクしており、エラーの記録を追跡できる。  
- 作成した記録は X(Twitter)やMattermostへ投稿可能。
- 投稿すると犬のエサを獲得し、使用すると犬が登場する。 

【得られる価値】  
- 記録習慣を無理なく開始/継続できる。  
- エラーの記録を追跡できる。  
- SNS投稿による仲間との接点やフィードバックがモチベーションに繋がる。  

(2)エラー解決記録 
- ツリー形式で時系列に沿ってエラーの解決に取り組んだ記録を残せる。
- 参考にしたURLを記載する欄を設定、ユーザーが参考にした記事URLやAIとのやり取りを公開出来る。
- 記録を作成すると犬のエサを獲得し、使用すると犬が登場する。

【得られる価値】  
- いつ・どのようにそのエラー解決に取り組んだか、自己学習の振り返りが出来る。
- 他のユーザーがエラー解決に何を参考にしているか、どのように取り組んでいるかを知ることが出来る。

(3)Github集計  
- クローズやコミットした件数に応じて犬のエサを獲得、使用すると犬が登場する。 

【得られる価値】  
- Github利用、学習習慣を身につけるきっかけ作り。
- エラーに遭遇した日のみ記録など、毎日記録をする訳ではない人でも使用するきっかけになる。
- 草生やしのついでくらいで緩く続けられる、ユーザーの使用継続促進。

(4)犬のキャラクター  
- 学習記録、Github利用に応じて獲得した犬のエサを使用すると登場する。
- ランダムで新しい犬種の犬が登場して仲間が増えていく。  

【得られる価値】  
- 学習モチベーション向上
- 頑張りの可視化

(5)通知機能(検討中)  
- 任意で設定した時間までに学習記録の入力がなかったら「記録を書きませんか？」と通知する。

【得られる価値】  
- 記入忘れ防止、継続の促進



## ■ ユーザーの獲得について
**想定したユーザー層に対してそれぞれどのようにサービスを届けるのか現状考えていることがあれば教えてください。**  

X(Twitter)、Mottermostへの投稿を通じてリンクやハッシュタグをから届けばと考えています。  



## ■ サービスの差別化ポイント・推しポイント
**似たようなサービスが存在する場合、そのサービスとの明確な差別化ポイントとその差別化ポイントのどこが優れているのか教えてください。**  
**独自性の強いサービスの場合、このサービスの推しとなるポイントを教えてください。**

【類似サービスとの差別化ポイントと優位性】  
Studyplus  
https://app.studyplus.jp/  
学習時間や内容を記録するアプリで、勉強の習慣化やモチベーション維持を目的としています。ソーシャル機能で他のユーザーと進捗を共有でき、特に学生(高校生・大学生)や資格試験受験者に人気。  
類似点：学習記録、外部SNS(Twitter)との直接連携  
差別化：学習全般でプログラミング学習には特化していない。SNS連携は限定的。  

habitica  
https://habitica.com/static/home  
タスク管理とRPG風のガミフィケーションを融合。学習や習慣を「クエスト」として記録し、キャラクターを育成。コミュニティ機能で仲間と協力可能。  
類似点：学習記録、キャラクター育成、チェックボックス形式でタスク管理  
差別化：学習全般でプログラミング学習に特化しておらず、SNS（X/Mattermost）連携はない。  

Notion  
https://www.notion.com/ja  
学習記録用のテンプレートで日誌を管理可能。チェックボックスやプルダウンで入力簡易化。コミュニティでテンプレート共有可能。  
類似点：学習記録のカスタマイズ・簡単入力 、外部API連携(カスタムで可能)   
差別化：学習全般でプログラミング学習に特化はしていない。キャラクター要素はない。  

【差別化ポイントと優位性】  
(1)学習記録とエラー解決記録のリンク
(2)学習記録の外部SNS連携  
コミュニティとの接点が自然に生まれ、孤独感の解消、仲間探しにつながる。  
(3)キャラクター要素  
努力の可視化、犬のキャラクターと達成の共有
(4)Github連携での緩やかな継続導線  
サービスから離れても自然に学習継続→再接続の可能性を残す。  


## ■ 機能候補
**現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないのでMVPリリース時に作っていたいもの、本リリースまでに作っていたいものをそれぞれ分けて教えてください。**

(1)学習記録  
- 日付(デフォルトToday、カレンダー選択)、学習時間(プルダウン)、学習内容(箇条書き、候補選択or記入登録)、メモ欄(任意文字入力欄)の記載
→最小限プルダウンとチェックボックス入力で作成可能  
- X(Twitter) API、Mattermost APIを使用し同じ内容を投稿出来る
- 学習記録を作成すると犬のエサを獲得する((4)キャラクター要素参照)  
**〜MVPリリースまで全て実装〜**  

(2)エラー解決記録  
- エラーについてツリー形式で記事を作成、公式リファレンス・まとめ記事・AIなど参照にしたものをタグ付けできる
- created_at, update_atに応じて学習記録とリンクする
- 記録の作成、追加に応じて犬のエサを獲得する((4)キャラクター要素参照)  
**〜MVPリリースまで〜**  
- 参考にした記事URLやAIとのやり取りを記載する欄を設定、ユーザーが参考にしたURLと参考数が閲覧可能
- 記事を他のユーザーに共有出来る
**〜本リリースまで〜**  

(3)Github集計  
**〜MVPリリースまで実装なし〜**  
- Github APIを使用し、Githubのpublicのイシューとプルリクエストの件数を集計
- クローズやコミットした件数に応じて犬のエサを獲得する((4)キャラクター要素参照)  
**〜本リリースまで〜**  

(4)キャラクター要素  
- 犬のキャラクターデザインが登場
- 学習記録、エラー解決まとめ記事、Githubプルリクエスト・コミット件数に応じて犬のエサを獲得 
- 使用することで犬が登場、使用に応じて登場するランダムに登場する犬種が増えていく  
- 犬種は図鑑で確認可能
→MVPリリースまでに5種くらいまで  
→本リリースまでに15種以上目指す  
**〜MVPリリースまで〜**  
-  ポートフォリオ検証を想定して、デモモード実装予定
(ユーザーadminでログインすると犬のエサ100個所持になるなど)  
**〜本リリースまで〜**  

(5)通知機能(検討中)  
**〜MVPリリースまで実装なし〜**  
- 任意で設定した時間までに学習記録の入力がなかったら「記録を書きませんか？」と通知する機能を追加するか検討中です
- メール通知が一番ハードルが低いですが、実装するとしたらどの通知機能を使うか含め検討中です
**〜本リリースまで〜**  

(6)ユーザー登録機能、ログイン機能  
- メールアドレス、パスワードでのユーザー登録機能
- ログイン機能  
**〜MVPリリースまでに全て実装〜**  

## ■ 機能の実装方針予定
**一般的なCRUD以外の実装予定の機能についてそれぞれどのようなイメージ(使用するAPIや)で実装する予定なのか現状考えているもので良いので教えて下さい。**

基本的にはカリキュラムで学習した言語や機能から作成する方針です。  
- Ruby on Rails
- HTMLとCSS
- Javascript

今後、就職活動で余力があればフロントだけReactなど企業が使っているものに差し替えるなどの変更は加えるかもしれません。  

【外部サービスへの投稿】  
- X(Twitter) API  
- Mottermost API  

【外部データ取得】  
- Github API  
(publicのイシュー・プルリクのクローズ・コミット件数を予定)  

※通知機能については検討中  
