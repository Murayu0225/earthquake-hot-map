# 地震ホットマップ
**注意** : *このサービスは、現在制作中のものであり、利用することはできません。ファイルに関しても制作中であるため、アップロードしてません。*
# サービス内容
- 地震が起こった際、連絡がとれなくなっても相手の電話番号と生年月日が一致すれば(相手側の登録が必須) 相手の位置情報を確認できるサービスです。
- サービスがダウンすることのないよう柔軟なサーバー増強を行えるバックグラウンド等を利用します。
- 国内サーバーでは、地震発生時にサーバーを利用できなくなる可能性があるため、海外拠点サーバーを利用する予定です。
# システム概要
- 利用するフレームワーク
  - Vue.js(軽量なフレームワークであるため)
  - その他、未定
- バックグラウンド
  - GCP(サーバーに負荷がかかっても自動的に増強が可能であるため。AWSは、利用したことがないので良さそうであれば、考えます。)
- マップサービス
  - Google Map API(その他のサービスに関しては、良さそうなものがあれば考えます。)
  - その他、未定
# Issues · Pull Requests に関して
いつでも受け付けています。こんな機能があった方が便利だというのがあれば、是非、Issuesに投稿してください。
**基本的に、IssueのないPull Requestは、受け付けることができません。** Issueを投稿してからPull Requestを行ってください。
# 貢献の仕方
当サイトでは、上記のようにいつでも貢献でき、オープンソースであることが強みです。是非、IssueやPull Requestを送信してください。
また、*official-approved*のラベルがついたIssueは、どなたでもPull Requestの提出が可能です。行っていただける場合には、投稿されたIssueにて行うことがわかる内容を記入してください。(他の方との同時進行防止)Pull Requestが進行中である場合には、**[WIP]** やドラフトにしてわかるようにしてください。Issueにて行っていただける内容を記入してから1週間以内にPull Requestの作成が確認できない場合、他の方に行っていただきます。
yarnやnpmを利用してローカルで利用することも可能ですが、Google Map APIなどのAPIに関しては`secrets.`となっています。ご自身の環境において利用する場合には、.env内に設定することによって利用することが可能です。
自身で設定したAPIにおいて費用が発生した場合、こちらは、対応できかねます。
## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

# ライセンス
[MIT ライセンス](LICENSE)を利用。
