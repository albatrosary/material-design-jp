Search
===

### In-app search

When an app supports large amounts of information, users expect to be able to quickly locate particular content by searching.

アプリは大量の情報をサポートしている場合、ユーザーが迅速に検索することによって、特定のコンテンツを見つけることができることを期待。

In its most basic form, a search involves:

* Opening a search text field
* Entering and submitting a query
* Displaying a set of search results

その最も基本的な形態では、検索が含まれます。

* 検索テキストフィールドを開く
* 入力とクエリを送信
* 組の検索結果を表示する

However, the search experience can be made significantly more gratifying by including some enhancements:

* Enabling voice search
* Providing historical search suggestions based on recent user queries, even before a query has been started
* Offering auto-completed search suggestions that match actual results in your application data

ただし、検索経験はいくつかの拡張機能を含めることによって、著しくより満足することができます：

* 有効にする音声検索
* クエリが開始された前であっても、最近のユーザーのクエリに基づいて、歴史的な検索候補を提供する
* あなたのアプリケーションデータに実際の結果と一致して、自動完成検索候補を提供

There are two major patterns for in-app search: persistent search and expandable search.

持続的検索および拡張可能な検索：アプリ内の検索のための2つの主要なパターンがあります。

#### Persistent search

Persistent search is appropriate when search is the primary focus of your app. The search text field is presented within an inset search box, ready to receive focus. The user also can touch the microphone action to initiate a voice search.

検索はアプリの主な焦点であるとき、永続検索は適切である。検索テキストフィールドがフォーカスを受け取る準備ができて、インセットの検索ボックス内で提示されている。また、ユーザは、音声検索を開始するためのマイクアクションに触れることができる。

When in focus, the search field expands to present historical search suggestions. If needed, the onscreen keyboard will also appear. Choosing any of the suggestions submits the search. Touching the up arrow releases the focus from search, dismissing suggestions and the onscreen keyboard.

ピントが合っているときは、検索フィールドには、歴史的な検索候補を提示するように拡張。必要に応じて、オンスクリーンキーボードも表示されます。提案のいずれかを選択すると、検索を提出する。上矢印リリース検索からフォーカス、解雇提案や画面上のキーボードに触れる。

As the user enters a query, the search suggestions shift to auto-completion. As the user types, the suggestions are filtered and sorted. Choosing a suggestion or pressing the return key submits the search.

The X action in the search box clears the query.

When displaying search results, the search box remains visible, but is not focused by default. The onscreen keyboard is dismissed so more results can be shown.

Search results are formatted as cards to match the inset appearance of the search box and to accommodate different types of results.

ユーザがクエリに入ると、検索候補は、自動補完に移行。ユーザーの種類としては、提案を濾過し、ソートされています。提案を選択するか、リターンキーを押すと、検索を提出する。

検索ボックスに、Xアクションクエリをクリアします。

検索結果を表示すると、検索ボックスが表示されたままが、デフォルトではフォーカスされていない。より多くの結果が表示できるように画面上のキーボードは却下されている。

カードは、検索ボックスの挿入の外観と一致するように、結果の異なる種類に対応するために、検索結果がフォーマットされている。

#### Expandable search

Expandable search is appropriate when search is not the primary focus of your app.

Instead of displaying a search text box, a search action, denoted by the magnifying glass icon, is presented within a toolbar.

Touching the search icon causes the toolbar to transform, clearing other content and displaying a search text field. If voice search is supported, the microphone icon also appears.

The search text field automatically receives focus, and, if needed, the onscreen keyboard will appear. Historical search suggestions can be shown beneath the toolbar. Choosing any of the suggestions submits the query.

Touching the up arrow closes search and restores the original presentation of the toolbar.

検索はアプリの主な焦点でない場合に拡張可能な検索は適切である。

代わりに虫眼鏡のアイコンで示される検索テキストボックス、検索アクションを、表示するので、ツールバーの中に提示されている。

検索アイコンをタッチすると、変換するためのツールバー、他のコンテンツをクリアして、検索テキストフィールドを表示します。音声検索がサポートされている場合は、マイクのアイコンも表示されます。

検索テキストフィールドが自動的にフォーカスを受け取った、と必要に応じて、オンスクリーンキーボードが表示されます。歴史的な検索候補は、ツールバーの下に表示することができます。提案のいずれかを選択すると、クエリを送信する。

上矢印をタッチすると、検索を終了し、ツールバーの元のプレゼンテーションを復元します。

As the user enters a query, the search suggestions shift to auto-completion. As the user types, the suggestions are filtered and sorted. Choosing a suggestion or pressing the return key submits the search.

The X action in the search field clears the query.

When displaying search results, the search version of the toolbar remains visible, but is not focused by default. The onscreen keyboard is dismissed so more results can be shown.

Search results, like the suggestions from the previous steps, appear in the main body of the page beneath the toolbar.

ユーザがクエリに入ると、検索候補は、自動補完に移行。ユーザーの種類としては、提案を濾過し、ソートされています。提案を選択するか、リターンキーを押すと、検索を提出する。

検索フィールドのXアクションクエリをクリアします。

検索結果を表示するときは、ツールバーの検索バージョンが表示されたままが、デフォルトではフォーカスされていない。より多くの結果が表示できるように画面上のキーボードは却下されている。

検索結果は、前のステップからの提案のように、ツールバーの下にあるページの本体に表示されます。