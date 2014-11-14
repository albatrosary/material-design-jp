Dialogs
===

Dialogs inform users about critical information, require users to make decisions, or encapsulate multiple tasks within a discrete process. Use dialogs sparingly because they are interruptive in nature—their sudden appearance forces users to stop their current task and refocus on the dialog content. Not every choice, setting, or detail warrants such interruption and prominence.

Alternatives to dialogs include simple menus or inline expansion within the current content area. Both approaches present information or options while maintaining the current context and are less disruptive.

ダイアログは、重要な情報をユーザーに通知し意思決定を行う、または個別プロセス内で複数のタスクをカプセル化するために、ユーザーが必要になります。彼らは彼らの現在のタスクを停止し、ダイアログコンテンツに再び集中することが自然に彼らの突然の出現が強制的にユーザーが割込であるため、控えめにダイアログを使用してください。必ずしもすべての選択肢、設定、または詳細ワラントなどの中断やプロミネンス。

ダイアログに選択肢はシンプルなメニューや現在のコンテンツ領域内のインライン展開が含まれています。どちらも、現在の情報または現在のコンテキストを維持し、あまり破壊的である一方、オプションに近づく。

### Content

Dialog content can vary widely, but typically consists of text and/or UI control elements and is focused on a specific task or process, such as confirming item deletion or choosing a setting.

Use inline expansion within the content area of dialogs to disclose additional information or content such as advanced options. Avoid opening additional dialogs from within a dialog.

Full-screen dialogs may open additional dialogs, such as pickers, because their design accommodates additional layers of material without significantly increasing the perceived z-depth of the app or increasing visual noise.

Avoid creating dialogs with scrolling content, particularly alerts. Instead, consider alternate containers or layouts that are optimized for reading or interacting with significant amounts of content.

ダイアログの内容は大きく異なるが、通常は、テキストおよび/またはUIコントロールの要素で構成され、そのようなアイテムの削除を確認するか、設定を選択として、特定のタスクやプロセスに焦点を当てていることができます。

そのような高度なオプションなどの追加情報やコンテンツを開示するダイアログのコンテンツ領域内にインライン展開を使用してください。ダイアログ内から追加のダイアログを開くことは避けてください。

彼らのデザインは大幅にアプリの知覚Z深度を増やすか、視覚的なノイズを増大させることなく、材料の追加の層を収容しているため、フルスクリーンのダイアログは、そのようなピッカーなどの追加ダイアログを開くことがあります。

スクロールのコンテンツ、特にアラートのダイアログの作成は避けてください。その代わりに、読書やコンテンツ、かなりの量と対話するために最適化されている代替容器やレイアウトを検討してください。

### Behavior

Dialogs are separate from the underlying parent material and do not scroll with the parent material.

Certain types of dialog content naturally needs to scroll, such as a long list of ringtones. In these cases, make it obvious that content scrolls by displaying scroll bars by default.

Dialogs should never be obscured by other elements or appear only partially on screen. Dialogs always retain focus until they have been affirmed or dismissed or a required action has been taken, such as choosing a setting.

ダイアログには、基礎となる母材とは別であり、母材でスクロールしません。

ダイアログ特定のタイプのコンテンツは、当然そのような着信音の長いリストとして、スクロールする必要があります。これらの場合には、それは明らかデフォルトでスクロールバーを表示することにより、コンテンツをスクロールさせること。

ダイアログには、他の要素によって隠さない、または画面上に部分的にしか表示されないでください。彼らが肯定または却下または必要なアクションはこのような設定を選択するように、撮影されたされるまで、ダイアログは常にフォーカスを保持している。


### Alerts

Alerts inform the user about a situation or action that requires their confirmation or acknowledgement before proceeding. They differ slightly in appearance based upon the severity and impact of the message conveyed.

Alerts are interruptive and urgent, and prevent users from proceeding until they make a decision.

Disambiguation: In contrast to Alerts, Snackbars present optional but important information or actions and usually appear after an action. For example, use an alert to confirm discarding a draft. Use a snackbar to present an undo action, because the action is optional and the user can continue with their primary task without taking action.

アラートは、先に進む前に、それらの確認や承認を必要とする状況や処理についてユーザーに通知します。彼らは、重症度と伝えたメッセージの影響に基づいて、外観が若干異なります。

アラートは中断的かつ緊急であり、彼らが決定を下すまで、先に進むからユーザーを防ぐ。

曖昧さ回避：コントラストアラートには、本オプションですが、重要な情報やアクションをスナックバー、通常はアクションの後に現れる。例えば、ドラフトを破棄確認するアラートを使用しています。アクションはオプションであり、ユーザーがアクションを取ることなく、それらの主なタスクを続行することができますので、元に戻すアクションを提示するスナックバーを使用してください。

#### Alerts without title bars

Most alerts don't need titles. Usually the decision doesn't have a severe impact and can be summed up succinctly in a sentence or two. The content area should either ask a question (such as "Delete this conversation?") or make a clear statement whose relationship to the action buttons is obvious.

ほとんどのアラートはタイトルを必要としません。通常決定は深刻な影響を持っていないと文または2で簡潔に要約することができます。コンテンツ領域のいずれか（例えば、「この会話を削除しますか？」のような）質問をするか、その関係のアクションボタンには自明である明確な文を作る必要があります。

#### Alerts with title bars

Use alerts with title bars sparingly. They are appropriate only for high-risk situations, such as potential loss of data or connectivity, or extra charges.

If a title is required, use a clear question or statement along with some additional explanation in the content area. For example, "Erase USB storage?"

Avoid apologies and ambiguous statements or questions. For example, “Warning!” or “Are you sure?”

A user should be able to skip the content completely and still have a clear idea of what choices are available based on the title and the text of the action buttons.

控えめにタイトルバーとアラートを使用してください。彼らはそのようなデータや接続、または追加料金の潜在的な損失などの高リスク状況、に適しています。

タイトルが必要な場合は、コンテンツ領域でのいくつかの追加の説明と一緒に明確な質問や文を使用します。例えば、「USBストレージを消去？」

謝罪とあいまいな文や質問を避けてください。たとえば、「警告！」や「必ずあなたをか？ "

ユーザーは完全にコンテンツをスキップして、まだ選択肢はタイトルとアクションボタンのテキストに基づいて利用可能であるかの明確なアイデアを持っていることができるはずです。

### Simple menus

Simple menus are used in list views on tablet and mobile devices to display the options for a specific list item. Simple menus immediately commit choices upon selection. See Components > Menus > Simple Menus for more details about simple menus.

Disambiguation: In contrast to simple menus, simple dialogs can present additional detail related to the options available for a list item or provide navigational or orthogonal actions related to the primary task. Although they can display the same content, simple menus are preferred over simple dialogs because simple menus are less disruptive to the user’s current context.

シンプルなメニューは、特定のリストアイテムのオプションを表示するには、タブレットとモバイルデバイス上のリストビューで使用されている。シンプルなメニューは、直ちに選択時の選択肢をコミットします。シンプルなメニューの詳細については、部品>メニュー>シンプルなメニューを参照してください。

曖昧さ回避：シンプルなメニューとは対照的に、単純なダイアログがリストアイテムに使用可能なオプションに関連する追加の詳細情報を提示したり、プライマリタスクに関連のナビゲーションまたは直交アクションを提供することができます。それらが同じコンテンツを表示することができますが、単純なメニューは、ユーザの現在のコンテキストにあまり破壊的であるため、単純なメニューが簡単なダイアログがより好ましい。

### Simple dialogs

Simple dialogs can present additional detail related to the options available for a list item or provide navigational or orthogonal actions related to the primary task. For example, simple dialogs can display avatars, icons, or clarifying subtext, or they can enable users to add an account that’s not currently listed as an option.

Choosing an option immediately commits the option and closes the menu.

Touching outside of the dialog, or pressing Back, cancels the action and closes the dialog.

Simple dialogs are more interruptive than simple menus and should be used sparingly.

シンプルなダイアログがリストアイテムに使用可能なオプションに関連する追加の詳細情報を提示したり、プライマリタスクに関連のナビゲーションまたは直交アクションを提供することができます。例えば、単純なダイアログがアバター、アイコン、または明確言外の意味を表示することができ、またはそれらは、現在、オプションとして表示されていないアカウントを追加するために、ユーザーを有効にすることができます。

オプションを選択すると、すぐにオプションをコミットして、メニューを閉じます。

ダイアログの外に触れるか、または戻るを押し、アクションをキャンセルし、ダイアログを閉じます。

シンプルなダイアログが単純なメニューよりも中断的であり、慎重に使用する必要があります。

Simple dialogs do not have explicit buttons that accept or cancel the operation.

A simple dialog appears centered vertically and horizontally in the screen.

The distance between the edges of the screen and the edges of the dialog is minimum 40dp on the left and right, and minimum 24dp on the top and bottom.

The distance between the edge of the dialog and content is 24dp.

シンプルなダイアログが受け入れるか操作をキャンセル明示ボタンを持っていません。

簡単なダイアログが画面に上下左右の中央に表示されます。

画面の端と、ダイアログのエッジ間の距離は、上部と下部の左右、および最小24dp最小40dpある。

ダイアログのエッジとコンテンツの間の距離は24dpである。

### Confirmation dialogs

Confirmation dialogs require users to explicitly confirm their choice before the option is committed. For example, users can listen to multiple ringtones, but only upon touching OK is the final selection committed.

Touching Cancel in a confirmation dialog, or pressing Back, cancels the action, discards any changes, and closes the dialog.

Touching outside of a confirmation dialog will not perform any action; the user must explicitly confirm or cancel to dismiss the confirmation dialog.

確認のダイアログがオプションがコミットされる前に、明示的に彼らの選択を確認するようユーザーに要求。たとえば、ユーザーは複数の着信音を聞くことができるが、唯一、OKに触れる際にコミットし、最終的な選択がある。

確認ダイアログで[キャンセル触る、または戻るを押し、アクションをキャンセルすべての変更を破棄し、ダイアログを閉じます。

任意のアクションを実行しません確認ダイアログの外に触れる。ユーザーが明示的に確認するか、確認ダイアログを閉じキャンセルする必要があります。

Confirmation dialogs can use layouts other than lists, for example a date picker, but they are still focused on specifying a single value (picking the date, but not picking the time & date).

確認のダイアログが例日付ピッカーのために、リスト以外のレイアウトを使用することができますが、彼らはまだ、単一の値を指定する（日付ピッキングが、時間＆日付をピッキングしない）に焦点を当てている。

Confirmation dialogs provide both an explicit confirmation button and explicit Cancel button. The explicit Cancel button clarifies that leaving the confirmation dialog will discard changes, for example, by touching Cancel or pressing Back.

Confirmation dialogs should avoid launching additional simple dialogs or simple menus. The additional layers of material can increase the app’s perceived z-depth, and add unnecessary visual complexity.

If additional simple dialogs or simple menus are needed to complete the task or process, consider using a full-screen dialog instead of a confirmation dialog.

確認ダイアログは、明示的な確認ボタンと明示両方がキャンセルボタンを提供する。キャンセル明示的なボタンは確認ダイアログを離れることはキャンセルに触れるか、戻る押すことによって、例えば、変更を破棄することを明確にしている。

確認のダイアログが追加のシンプルなダイアログや簡単なメニューを起動することは避けてください。材料の追加の層は、アプリの認知Z深度を増加させ、不要な視覚的な複雑さを追加することができます。

追加のシンプルなダイアログまたは単純なメニューがタスクやプロセスを完了するために必要とされる場合は、フルスクリーンのダイアログの代わりに、確認ダイアログを使用することを検討。


### Full-screen dialogs

Mobile only: Because of limited real estate on mobile devices, content that may appear as a dialog in other form factors (tablet, desktop, etc.) may be more appropriately presented in a full-screen dialog.
Full-screen dialogs can be used to group a set of tasks forming a complex operation that requires an explicit confirmation or action, such as save or create, before changes are committed or discarded, for example, creating a calendar entry.

Full-screen dialogs enable complex layouts, minimize the appearance of stacked sheets of material (dialogs above dialogs) and thus an increase in the app’s perceived z-depth. They enable individual tasks to launch simple menus or simple dialogs as part of the complex operation.

モバイルのみ：モバイルデバイス上の制限、不動産、他のフォームファクタ（タブレット、デスクトップなど）の中でダイアログとして表示されることがあり、コンテンツのため、より適切に全画面のダイアログで提示することができる。
フルスクリーンダイアログがカレンダーエントリを作成し、グループへの変更は、たとえば、コミットまたは廃棄される前に、そのような保存や作成などの明示的な確認またはアクションを必要とする複雑なオペレーションを形成する一連のタスクを使用することができます。

フルスクリーンのダイアログは（ダイアログ上記のダイアログ）、従って、アプリの認知Z深度の増加を材料の積載されたシートの外観を最小限に抑えるため、複雑なレイアウトを可能にする。彼らは、複雑な操作の一部として、簡単なメニューや簡単なダイアログを起動するための個々のタスクを有効にしてください。

Consider using a full-screen dialog when the content or process meets any of the following criteria:

* The dialog’s content includes components like pickers or form fields requiring IME input
* When changes are not saved in real time
* When there is no draft capability in the app
* When performing batch operations or queuing changes prior to submitting them

コンテンツやプロセスは、以下の基準のいずれかを満たしているフルスクリーンダイアログを使用して検討してください。

* ダイアログの内容は、IME入力を必要とするピッカー、またはフォームフィールドのようなコンポーネントが含まれています
* 変更はリアルタイムに保存されません
* 全くドラフト機能がアプリで存在しない場合
* それらを提出する前に、バッチ操作を実行したり、変更をキューイング

In the example to the right, the full-screen dialog supports a simple dialog used to pick dates. No modifications and selections made in the full-screen dialog are saved until Save is touched. Touching the X will discard all changes and exit the full-screen dialog.

右の例では、フルスクリーンのダイアログは、日付を選択するために使用する簡単なダイアログをサポートしています。保存がタッチするまでフルスクリーン]ダイアログで行われた無修正と選択は保存されません。 Xに触れると、すべての変更を破棄し、全画面ダイアログを終了します。

In full-screen dialogs, the confirmation and dismissive actions are at the top of the screen.

The confirmation action is at the top right of the screen and uses descriptive and accurate words, such as “save”, “send”, “add”, “share”, “update”, or “create”.

Don’t use vague actions such as “done” or “ok” or “close” for the confirmation action. They are too similar in meaning to the X and non-specific in their result.

全画面のダイアログでは、確認と否定のアクションは、画面の上部に表示されます。

確認動作は、画面の右上にあり、そのような「作成」、「追加」、「送信」、「共有」を「保存」「更新」、または記述的かつ正確な言葉を使用しています。

そのような「済」または「OK」または「クローズ」の確認アクションと漠然としたアクションを使用しないでください。彼らの結果でXおよび非特異的に意味すぎる類似している。

The confirmation action is disabled until all mandatory criteria in the dialog are met.

The discard action, an X at the top left of the screen, closes the full-screen dialog and discards any changes. The Back button is equivalent to the discard acti.

If the user has made any changes, they are prompted to confirm the discard action.

If no changes have been made, touching the X or Back immediately closes the dialog and no discard confirmation is required.

ダイアログ内のすべての必須基準が満たされるまで確認動作は無効になっています。

廃棄アクションは、画面の左側上部のXは、フルスクリーンのダイアログを閉じ、すべての変更を破棄します。 [戻る]ボタンは、廃棄ACTIに相当します。

ユーザーが任意の変更を行った場合、それらは廃棄アクションを確認するプロンプトが表示されます。

変更が行われていない場合は、Xに触れるか、バックはすぐに、ダイアログを閉じ、全く廃棄の確認は必要ありません。

The X differs from an Up arrow, which is used when the view’s state is constantly being saved or when apps have draft or autosave capabilities. For example, an Up arrow is used in Settings because all changes are committed immediately. In these cases, the Back button navigation and action match the Up arrow functionality, and there are no explicit confirmation or cancel actions.

Xは、ビューの状態を常時保存またはされているときに使用されている上矢印とは異なりアプリはドラフトまたは自動保存機能を持っているとき。すべての変更が即座にコミットされているので、例えば、上矢印は、[設定]で使用されます。これらのケースでは、戻るボタンナビゲーションとアクションが上矢印の機能と一致し、かつ明示的な確認はありませんまたはアクションをキャンセルします。

### Specs

Dialogs contain an optional title, content, and actions.

The optional title briefly describes the type of choice being made. Titles should always be displayed in their entirety and should be used only when necessary. Titles can be used to clarify the decision being made. For example, a title may indicate what part of a process the dialog relates to or by identifying what will be affected by the decision, such as a setting.

Dialog content can vary widely, but typically consists of text and/or UI control elements and is focused on a specific task or process, such as confirming item deletion or choosing a setting.

When needed, actions acknowledge, affirm, or dismiss the particular choice or process presented by the dialog content.

ダイアログは、オプションのタイトル、内容、およびアクションが含まれています。

オプションのタイトルは、簡単に好みのタイプが行われて説明します。タイトルは常に、それらの全体が表示されるべきであり、必要な場合にのみ使用すべきである。タイトルが行われて決定を明確にするために使用することができる。例えば、タイトルはダイアログがまたはそのような設定として、意思決定によって影響されるかを識別することにより、関連するプロセスのどの部分を示してもよい。

ダイアログの内容は大きく異なるが、通常は、テキストおよび/またはUIコントロールの要素で構成され、そのようなアイテムの削除を確認するか、設定を選択として、特定のタスクやプロセスに焦点を当てていることができます。

必要なときに、アクションが認める、断言、またはダイアログの内容によって提示された特定の選択またはプロセスを解任。

#### A note on accessibility

To ensure usability for people with disabilities, make sure that your buttons have a minimum height of 36dp, but that the touchable target has a minimum height of 48dp.

The default color of all dialog action text is the application’s theme accent color. Always make sure the action text color uses a sufficient contrast ratio to meet accessibility guidelines. Change the default text color as needed to create a sufficient contrast ratio.

障害を持つ人々のための使いやすさを確保するために、あなたのボタンが36dpの最小の高さがあることを確認したが、触れることができるターゲットは48dpの最小の高さを持っていること。

すべてのダイアログアクションテキストのデフォルトの色は、アプリケーションのテーマアクセントカラーです。常にアクションのテキストの色は、アクセシビリティのガイドラインを満たすのに十分なコントラスト比を使用していることを確認してください。十分なコントラスト比を作成するために、必要に応じて、デフォルトのテキストの色を変更します。

Dialogs present a focused and limited set of actions, which are generally affirmative or dismissive.

Affirmative actions are placed on the right side and continue the process. Affirmative actions may be destructive, like Delete or Remove.

Dismissive actions are placed directly to the left of affirmative actions and return the user to the originating screen or step in the process.

Dismissive and affirmative action text can be Cancel/OK or can be more specific active verbs or verb phrases that indicate the outcome of the decision.

ダイアログは、一般的に肯定的または否定的なアクションの集中的かつ限定されたセットを提示します。

肯定的なアクションが右側に配置され、プロセスを継続している。削除するか削除するような肯定的な行動は、破壊的かもしれません。

否定的行動は肯定的アクションの左に直接配置し、プロセスに起因する画面やステップにユーザーを戻している。

否定と肯定的なアクションのテキストは、OK/キャンセルすることができ、または意思決定の結果を示す、より具体的なアクティブ動詞または動詞句であることができる。

#### Button width and padding guidelines

#### Side-by-side buttons

Side-by-side buttons are recommended when the text of each label does not exceed the maximum button width, such as the commonly used OK/Cancel buttons.

Use the following formula to calculate maximum button width for a given dialog:

The maximum width for buttons in a dialog = (Dialog width - 16dp - 16dp - 8dp) / 2

For example:

The maximum width for buttons in a 280dp wide dialog = (280dp - 16dp - 16dp - 8dp) / 2 = 120dp

各ラベルのテキストは最大ボタンの幅を超えない場合、サイドバイサイドのボタンが推奨され、一般的にOKを使用されるような/ボタンをキャンセルします。

指定されたダイアログの最大ボタンの幅を計算するには、次の式を使用します。

（ - 16dp - 16dp - 8DPダイアログ幅）/2=ダイアログ内のボタンの最大幅

たとえば：

280dp広いダイアログ=内のボタンの最大幅（280dp - 16dp - 16dp - 8DP）/2=120dp


#### Stacked full-width buttons

When text labels exceed the maximum button width, use stacked buttons to accommodate the text. Affirmative actions are stacked above dismissive actions

テキストラベルが最大ボタンの幅を超えたときに、テキストに対応するために、積み重ねられたボタンを使用します。肯定アクションは否定的アクションの上に積層されている