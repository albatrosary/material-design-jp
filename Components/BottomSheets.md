Bottom sheets
===

One way to present a set of actions to a user is with a bottom sheet, a sheet of paper that slides up from the bottom edge of the screen. Bottom sheets offer flexibility in the display of clear and simple actions that do not need explanation.

ユーザに一連のアクションを提示する一つの方法は、底部シートは、画面の下端から上を摺動する紙のシートである。ボトムシートは説明を必要としない、明確でシンプルなアクションの表示における柔軟性を提供します。

### Usage

Bottom sheets are especially suitable when three or more actions are displayed to the user and when the actions do not require a description. If there are two or fewer actions or detailed description is required, consider using a menu or dialog instead.

Bottom sheets can be list-style or grid-style. Grid layouts increase visual disambiguation.

You can use bottom sheets to show actions related to other apps or to allow entry points to other apps (via the app icon).

アクションの記述を必要としないときに三つ以上のアクションがユーザに表示されたときに下部シートが特に適している。そこに2つ以下のアクションですか詳細な説明が必要な場合は、メニューを使用して、またはその代わりにダイアログを検討してください。

ボトムシートは、リストスタイルまたはグリッドスタイルがあります。グリッドレイアウトは、視覚的な曖昧さ回避を増加させる。

あなたは他のアプリに関連するアクションを表示したり、他のアプリに（アプリのアイコンを介して）エントリポイントを許可するように底のシートを使用することができます。

### Content

In a standard list-style bottom sheet, each action should have a text description and a left-aligned icon. When necessary, use separators to logically group actions. Also use subheaders or titles to give context to the choices.
A scrollable grid-style bottom sheet can contain icons for standard share actions.

標準リストスタイルのボトムシートでは、各アクションは、テキスト記述と左揃えのアイコンを持っている必要があります。必要な場合には、論理的にグループ化アクションに区切り文字を使用しています。また、選択肢にコンテキストを与えるためにサブヘッダーまたはタイトルを使用。
スクロール可能なグリッドスタイルのボトムシートは標準の共有アクションのアイコンを含めることができます。

### Behavior

When a bottom sheet is displayed, it should animate upwards from the bottom edge of the screen. The previous content dims to give the user context for where they just were and the modal nature of the choice. Tapping on the dimmed area dismisses the sheet, as does swiping down on the sheet.

If the sheet contains more actions that can fit in the initial display, the sheet is scrollable. Scrolling should also pull up the sheet container and eventually cover the entire screen.

When the action sheet covers the entire screen, add a dismiss button to the header, on the left side of the title.

ボトムシートが表示されたら、それは画面の下端から上方にアニメーション化する必要があります。以前の内容は、彼らがちょうどあった場所のためのユーザコンテキストおよび選択のモーダルな性質を与えるために暗く。シートを下にスワイプする場合と同様に淡色エリアをタップすると、シートを閉じる。

シートは初期表示に収まる以上のアクションが含まれている場合は、シートがスクロール可能である。スクロールもシートコンテナを引き上げ、最終的に画面全体をカバーする必要があります。

アクションシートが画面全体をカバーする場合は、タイトルの左側に、ヘッダに却下ボタンを追加します。

### Specs

The following font, color specs and redlines are provided for mobile apps.
Font and color:

* Text: Roboto Regular 16sp,  #000 87%
* Title (optional): Roboto Regular 16sp, #000 54%
* Default bottom sheet background fill: #FFF
* Overlay shield fill: #000 20%

次のフォント、色の仕様と朱書きは、モバイルアプリのために設けられている。
フォントと色：

* テキスト：Roboto正規16sp、＃000 87％
* タイトル（オプション）：Roboto Regular 16sp、＃000 54％
* デフォルトボトムシートの背景の塗りつぶし：#FFF
* オーバーレイシールドフィル：＃000 20％