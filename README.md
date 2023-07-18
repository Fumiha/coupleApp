# medicine_reminder

# [お薬リマインダー]

## サービス概要
薬を飲み忘れの多い高齢者をもつ家族に代わりにリマインダーを送り、
手間を軽減しながら体調の共有をサポートすることで安心感を提供する、
薬のリマインド＆体調管理・共有サービスです。

（高齢者自身も利用することができるユーザーインターフェースを提供する）

## 想定されるユーザー層
*  <３０〜５０代　女性　>
* ６０代〜８０代の高齢の両親をもつ
* 両親とは別居中
* 病院の送迎等を家族で分担している
* 離れて住む高齢の両親のことが心配ではあるものの、現状同居が難しい。

## サービスコンセプト
私自身、祖母と離れて住むことになり、祖母の体調について心配しているからです。
祖母との体調共有や連絡手段があれば、とても便利だと感じています。
さらに、周囲との話の中で毎日電話で薬の連絡をしている方がいることを知り、
アプリで行うことができれば、負担が軽減されると思いました。
高齢者が一人暮らしをしていると、離れて住む家族との繋がりが薄れてしまうことがあります。
そこで、アプリを通じて体調やスケジュールを共有することで、
関心を持ち、メッセージなどのやりとりのきっかけになると良いと考えています。

## 　ユーザーが抱える課題
* <手動でのリマインドの負担>
  
定期的に両親の元を訪ねているが、その度に飲み忘れている薬を多く発見。
現在は、電話やライン等でリマインドを行っているが負担が大きい。

* <体調不安>
  
離れて住んでいるが故に、体調が分からず不安。

* <イベントの共有不足>
  
高齢者ドライバーの事故が多く、免許を返納したため、
病院や老人ホーム等、送迎が必要なイベントには、家族で分担して協力しているが、
イベントが家族で共有できてないことがある。

* 解決方法
  
アプリによる薬飲み忘れ防止のためのリマインド、カレンダー共有（送迎者登録）、体調登録→共有機能により、
ユーザーの問題の解決を目指す。

## 実装を予定している機能
### MVP
* 会員登録
* 薬の登録
* 飲む時間のリマインド
* 飲んだ後の他の家族へ報告機能　
* 健康状態の報告機能（毎日３択：良い・普通・悪い　で報告→　　　家族へ）　　　　
* メッセージ機能
* 会員登録

### その後の機能
* 病院の登録
* 通院日の登録
* カレンダー共有（病院の送り迎えなど依頼→送迎者登録）
* 非常連絡先の登録機能
* 家族への通知機能（指定期間触れていないと、家族へ緊急通知）
  
　→通知を送信する前に、ユーザーに確認のダイアログを表示する
* 各機能にオンオフ（カスタマイズ）

## 画面遷移図　（figma）
https://www.figma.com/file/Ybm4gxo3LVLyLAfkK3CbVb/%E3%81%8A%E3%81%B0%E3%81%82%E3%81%A1%E3%82%83%E3%82%93%E7%94%A8?type=design&node-id=0%3A1&mode=design&t=HXxmLC0Gjpi3KaO9-1



