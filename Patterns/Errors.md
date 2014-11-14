Errors
===

Errors are instances where an app fails to complete what is expected. Errors happen when:

* The app does not understand user input.
* The system or app fails.
* A user intends to run incompatible operations concurrently.

アプリが期待されているものを完了するために失敗した場合にエラーが生成されます。エラーが発生するとき：

* このアプリは、ユーザー入力を理解していない
* システムやアプリが失敗
* ユーザーは同時に、互換性のないオペレーションを実行している

Try to prevent errors through good design. Make your app understand the user, rather than making the user have to understand the app. When an error occurs, communicate clearly about what is happening and how a user can quickly resolve it. Save and preserve as much state as possible, especially when the user has input content.

良いデザインを通してエラーを防止するようにしてください。アプリを理解しなければならないようなアプリを作るよりも、ユーザーが理解でいるようなものにしてください。エラーが発生した場合、何が起きたのかをユーザーがすぐに解決できてい内容を通知します。ユーザは、入力内容を持つ場合は特に保存してできるだけ多くの状態を保存します。

As with all feedback, prioritize which messages are most important, communicate through content states to avoid extraneous elements on screen, and be consistent with screen placements within and across form factors.

すべてのフィードバックと同様に、最も重要であるメッセージの優先順位付け、画面上の余分な要素を回避するために、コンテンツの状態を介して通信し、かつ内およびフォームファクタ全体で画面の配置と一致している。

### User input errors

Give context for user input errors to help users fix them. Politely let users know as soon as possible that they have made an error that they need to correct. Don’t let them submit a long form before telling them they made an error. Disable a form submission button if errors are detected. If the error can only be found after the user has submitted a form, be clear about what went wrong and what the user specifically needs to do to fix it.

ユーザーがそれらを修正手助けするためのユーザ入力エラーのコンテキストを与えます。丁寧に、ユーザーは、できるだけ早く、修正する必要があるエラーを通知します。アプリがエラーが発生したことを通知する前に長いフォームを送信させてはいけません。エラーが検出された場合、フォームの送信ボタンを無効にします。ユーザーがフォームを送信した後にエラーが唯一見つけることができる場合には、明確に何が悪かったのかということとユーザーがそれを修正するために行えることが必要となります。

#### Text field input  

Helper text may appear at any time before, during, or after user interaction. Error text should not appear before user interaction with the field. Helper text may transform into error text if the user inputs incorrect text.  

ヘルパーテキストは前、間、任意の時点で表示され、ユーザとの対話の後に表示しることができます。エラーテキストは、フィールドとのユーザ対話の前に表示されません。ヘルパーテキストは、ユーザの入力が正しくない場合、エラー·テキストとして変換することができる。

Do not slow down users with too much text on screen. Not every text field needs helper and/or error text.

画面上であまりにも多くのテキストを表示するために遅くならないようにします。必ずしもすべてのテキストフィールドがヘルパーおよび/またはエラーテキストを必要としません。

If the text field can have an error below it, it should have an additional 16dps of padding below it to account for the error field.

テキストフィールドがその下のエラーを持つことができる場合は、エラーフィールドを説明するために、下にパディングの追加 16dps を持つ必要があります。

#### Light

Error font is Roboto Regular 12sp
Hint and helper text is #000000 with 38% alpha

エラーフォントはRoboto Regular 12sp である
ヒントとヘルパーテキストは38％アルファと＃000000である

#### Dark

Error font is Roboto Regular 12sp
Hint and helper text is #FFFFFF with 30% alpha

エラーフォントは Roboto Regular 12sp である
ヒントとヘルパーテキストは30％アルファと＃FFFFFFである

#### Helper and error text

#### Error with floating text label

Text field input - Over/under character or word count

テキストフィールドの入力 - オーバー/下の文字や単語のカウント

Counter may be displayed before, during, and after user interaction with the field. Consider not displaying the counter until the user is approaching the limit. Counter fields should have additional 16dps of padding below it.

カウンタは、前、間、表示され、フィールドとのユーザインタラクションの後ことができます。ユーザーが限界に近づいているまで、カウンタを表示しないことを検討してください。カウンタ·フィールドは、その下のパディングの追加16dpsを持つ必要があります。

Counter font is Roboto Regular 12sp

カウンタ·フォントは Roboto Regular 12sp です

#### Single line with character counter

#### Multi line with character counter

#### Incompatible values

Incompatible value errors should be displayed during or after user interaction with the text field that triggers the error.

互換性のない値エラーが中またはエラーをトリガーするテキストフィールドとのユーザインタラクションの後に表示されるはずです。

If two or more fields have incompatible inputs, the text field and error message below each field should indicate a fix is needed. An additional message should be added at the top of the form or screen summarizing the fixes needed and any additional explanation.

2つ以上のフィールドに互換性のない入力がある場合は、修正プログラムを示す必要があり、各フィールドの下のテキストフィールドと、エラーメッセージが必要とされます。追加のメッセージは、フォームまたは必要に応じて、画面の要約の修正と追加の説明の先頭に追加する必要があります。

#### Errors detected after attempted form submission

The form should reload with scroll position at the top of the form, where the error messages are consolidated. Error messages for individual fields may be resolved as the user works through the form.

フォームは、エラーメッセージが統合される形で、の上部にあるスクロール位置をリロードする必要があります。ユーザーがフォームを介して動作として、個々のフィールドのエラーメッセージが解決されることがあります。

#### Incomplete form

Incomplete form errors should be displayed after a user has sufficiently advanced through the form to indicate they have skipped the field. If unable to detect user progress through the form, display the error after the user has attempted to submit the form.

ユーザーは十分にフィールドをスキップしたことを示すために、フォームを通って前進した後に不完全な形のエラーが表示されるはずです。フォームを介してユーザーの進捗を検出することができた場合は、ユーザーがフォームを送信しようとした後に、エラーを表示します。

If fields in a form are left empty, the text field and error message below each field should indicate the error.

フォームのフィールドを空のままにしている場合は、各フィールドの下のテキストフィールドとエラーメッセージはエラーを示す必要があります。

#### Multiple errors in a form before submission

It is sufficient to individually label error messages as the user works through the form.

ユーザーがフォームを介して動作としては、個別のエラーメッセージにラベルを付けるのに十分です。

#### Single line list error

### App errors

App errors are failures that occur regardless of user input.

アプリエラーに関係なく、ユーザ入力の発生する障害です。

#### General app error

While an error is in progress, an app should continue to display its activity/loading indicators until the failure state is reached and the app error is displayed.

エラーの進行中に故障状態に達するとアプリケーションエラーが表示されるまで、アプリがその活動/ロードインジケータの表示に継続すべきである。

If a feature is not available, it may be represented within the UI. Not every error requires a new component to pop up.

機能が利用できない場合は、UI内に表すことができます。必ずしもすべてのエラーがポップアップする新しいコンポーネントを必要としません。

If possible, give your user an action that will help them address the error. Don’t let them get stuck.

可能な場合、ユーザーはそれらのエラーに対処するアクションを与えます。何もできない状態を作ってはいけません。

#### Sync error/failure to load

A key part of designing an app is determining how screens will present content. A subset of that is determining what each screen should do when its regular content can't be shown. Examples include:

* A screen that normally presents a list of items, but no items exist yet.
* A screen that normally shows search results, but the current search yielded zero results.
* A screen that normally shows cloud-based content, but can't right now because of an unknown error.

アプリを設計の重要な部分は、画面がコンテンツを提示する方法を決定します。それのサブセットは、その定期的なコンテンツが表示できないときに、各画面は何をすべきかを決定することです。例としては：

* 通常、項目のリストを提示しますが、アイテムがまだ存在しない画面
* 通常の検索結果を示しているが、現在の検索がゼロの結果が得られた画面
* 通常は、クラウドベースのコンテンツを示していますが、不明なエラーの画面を表示してはいけません

These types of scenarios are called empty states. Although they're not the norm, they're important to design well because users may already be disappointed from encountering something unexpected.

これらのタイプのシナリオは、空の状態と呼ばれます。規範ではないがユーザーがすでに予期しない事態に遭遇し失望する可能性があるため、うまく設計することが重要です。

When sync is down or content has failed to load, the user should be able to interact with as much of the rest of the app as possible.

同期がダウンしているか、コンテンツの読み込みに失敗した場合でも、ユーザは、可能な限り、アプリの残りの部分をできるだけ多く対話することができるはずです。

#### Connectivity

When connectivity is down, the user should be able to interact with as much of the rest of the app as possible.

接続がダウンしている場合、ユーザは、可能なアプリの残りの部分だけと相互作用することができるべきである。

If appropriate, present a link to help a user accomplish their task. Only offer links that you can actually support. For example, don't offer an option like "Try again" in cases where you can already detect that the operation will fail.

適切な場合、ユーザーが自分のタスクを達成を助けるためのリンクを提示する。唯一あなたが実際にサポートできるリンクを提供します。たとえば、あなたが既に操作が失敗することを検知することができるケースでは、「もう一度お試しください」のようなオプションを提供していません。

### Incompatible state errors

Incompatible state errors occur when users attempt to run operations that conflict, such as making a call while in airplane mode or taking a screenshot from a restricted work account. Try to avoid letting users putt themselves into these situations by clearly communicating the states they are selecting and the implications for the rest of their experience. When these errors are triggered, do not imply that they are the user’s fault.

ユーザーは、機内モードにしながら、電話をかけるか、制限された作業アカウントからのスクリーンショットを取るように、業務にその紛争を実行しようとすると、互換性のないステートエラーが発生します。ユーザーが明確に彼らの経験の残りのために、彼らが選択している状態と意味を通信することによって、このような状況に自分自身をパットせる避けるようにしてください。これらのエラーがトリガされると、それらがユーザーの障害であることを意味するものではありません。

#### General incompatibility

Be clear about why the error is occurring and where it originates.  

Example:

* Screenshots and premium features are not allowed while in a restricted mode.

エラーが発生して、どこでそれが発信されている理由について明確にする。

例：

* スクリーンショットとプレミアムの機能が許可されていない制限されたモードにある間。

#### Offline by choice

Consider displaying an unintrusive but persistent indicator when users are in these states.

Examples:

* Placing a call while in airplane mode
* Music availability while offline

ユーザーがこれらの状態にあるときの非介入型が、永続インジケータを表示することを検討してください。

例：

* 飛行機モード中に電話をかける
* 音楽可用性しばらくオフライン

#### Permission requested

If your app requires user permission granted before proceeding along a workflow, consider working the permission request into the app flow instead of treating it as an error.

あなたのアプリは、ワークフローに沿って進む前に付与されたユーザー権限を必要とする場合は、エラーとして扱うのではなく、アプリのフローに許可要求を使うことを考えます。

If permissions are necessary before the first run of an app, consider how they might fit into your app’s warm welcome.

Examples:

* An app’s permissions have changed.
* In-app purchases have been disabled.

権限はアプリの最初の実行前に必要であれば、彼らはあなたのアプリの温かい歓迎に収まるかもしれない方法を検討します。

例：

* アプリのアクセス権が変更されています。
* アプリ内購入は無効になっています。