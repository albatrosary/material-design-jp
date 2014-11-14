Progress & activity
===

Make loading content in your app as delightful and painless as possible by minimizing the amount of visual change a user sees before they can view and interact with content. Each operation should only be represented by one activity indicator—for example, one refresh operation should not display both a refresh bar and an activity circle.

彼らは閲覧やコンテンツと対話することができます前に、ユーザーが見ている視覚的な変化量を最小限に抑えることによって、できるだけ楽しいかつ無痛としてあなたのアプリでコンテンツのロードを行います。各操作は一つだけ活動の指標たとえばによって表されるべきで、1回のリフレッシュ動作がリフレッシュバーと活動サークルの両方を表示すべきではありません。

### Types of indicators

For operations where the percentage of the operation completed can be ascertained, use a determinate indicator. They give users a quick sense of how long an operation will take.

For operations where the user is asked to wait a moment while something finishes, and it’s not necessary to expose what's happening behind the scenes and how long it will take, use an indeterminate indicator.

There are two types of indicators: linear and circular. You can use either one for determinate and indeterminate operations.

完了した操作の割合が確認できる操作については、確定的インジケータを使用しています。彼らは、ユーザーの操作に要する時間の迅速な感覚を与える。

何かが終了し、それがかかりますシーンやどのくらいの背後に何が起こっているのか公開する必要はありませんしながら、ユーザーが瞬間を待つように要求される操作については、不確定なインジケータを使用しています。

線形と円形：指標の2種類があります。あなたは確定と不確定操作のためのいずれかを使用することができます。

#### Linear

A linear progress indicator should always fill from 0% to 100% and never move backwards to a lower value. If multiple operations are happening in sequence, use the progress indicator to represent the delay as a whole. This way, when the bar reaches 100%, it doesn't return back to 0%.

Linear bars should appear and disappear on the edge of a header or sheet.

リニア進捗インジケータが常に0％から100％まで記入し、低い値に後方に移動することはありません。複数の操作が連続して起こっている場合は、全体としての遅延を表すために進行状況インジケータを使用しています。バーが100％に達すると、この方法は、それが0％に戻って戻らない。

リニアバーが表示され、ヘッダまたはシートの端に消えるはずです。

### Behavior