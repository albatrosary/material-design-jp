List controls
===

List controls are icons that appear to the left or right of the list text. They indicate the state of a list item, information about a list item, or serve as an action related to the list item. Leave-behinds are list controls, which are revealed only upon swipe.

リストコントロールは、リスト、テキストの左または右に表示されるアイコンです。彼らは、リスト項目についてのリスト項目の状態、情報を示す、またはリスト項目に関連するアクションとしての役割を果たす。去る-尻だけスワイプ時に明らかにされているリストコントロールです。

### Usage

List controls fall under four categories:

* State
* Primary action (including text strings)
* Secondary action
* Secondary info

リストコントロールは、4つのカテゴリの下に分類されます。

* 状態
* プライマリアクション（テキスト文字列を含む）
* セカンダリアクション
* 二次情報

Distinguishing elements of list tiles need to be on the left for Left-to-Right interfaces, and vice versa. States and primary actions are placed on the left side of a list tile. Text within a list item should be considered part of the primary action target.

リストタイルの際立った要素は、その逆の左から右のインターフェイスのための左側にあり、かつ必要があります。米国プライマリアクションがリストタイルの左側に配置されている。リスト項目内のテキストは、プライマリアクション·ターゲットの一部と考えるべきである。

Don’t place two icons or actions next to one another, such as a checkbox next to an avatar.

そのような次のアバターにチェックボックスとして互いに隣接し、への2つのアイコンやアクションを置かないでください。

If the primary action of the list item is navigational, don’t use an icon. The list item itself and its context should be sufficient to communicate the destination.

リスト項目の主なアクションが航行の場合は、アイコンを使用しないでください。リスト項目自体とそのコンテキストが先を伝えるのに十分であるべきである。

Secondary actions and Info should be placed on the right side of the title. Secondary actions are always a separate target from the primary action, as users increasingly expect every icon to trigger an action.

2次アクションとInfoは、タイトルの右側に配置する必要があります。ユーザーはますます、すべてのアイコンがアクションをトリガする期待どおりの二次アクションは、常にプライマリアクションとは別の標的である。

### Types of list controls

#### Checkbox

A checkbox can either be a primary action or a secondary action.

Type: primary action/state

Desktop checkboxes should appear only on hover and focus. 

チェックボックスは、プライマリアクションまたはセカンダリアクションすることができます。

タイプ：プライマリアクション/状態

デスクトップのチェックボックスのみをホバーとフォーカスに表示されます。

Type: secondary action

Separate target

When controlling a family of variables, consider using switches instead.

タイプ：セカンダリアクション

別々のターゲット

変数のファミリーを制御する場合、代わりにスイッチを使用することを検討してください。

#### Switch

Type: secondary action

Separate target

タイプ：セカンダリアクション

別々のターゲット

#### Reorder 

Type: secondary action

Usually a separate target, depending on which mode list it is in.

Allows dragging of the list item to other locations within the list. It usually appears in list editing mode.

タイプ：セカンダリアクション

通常、どのモードリストに応じて、それが別々のターゲットです。

リスト内の他の場所にリスト項目のドラッグを可能にする。これは通常、リスト編集モードで表示されます。

#### Expand/collapse

Type: secondary action

Separate target

Expands and collapses a list view vertically to show and hide details of existing list items.

タイプ：セカンダリアクション

別々のターゲット

拡大し、垂直方向に表示し、既存のリストアイテムの詳細を非表示にするには、リストビューを縮小します。

#### Leave-behinds

Type: Other

A leave-behind is an informative hint as to what swiping a list item away will do to that item. The leave-behind can transform into an action.

Swiping on a list item from either direction will reveal an icon indicating the action. After swiping, the action appears as a text button centered within the space of the list item.

タイプ：その他

リーブビハインドは、その項目に行います離れてリスト項目をスワイプものとして有益ヒントです。リーブビハインドを行動に変換することができます。

どちらの方向からリスト項目をスワイプすると、アクションを示すアイコンを明らかにする。スワイプした後、アクションはリスト項目のスペース内の中央にテキストボタンとして表示されます。


### Types of menu controls

A menu is a special type of list. In menus, use controls that are appropriate for dropdown menus, overflow menus, and so on. Don’t use these controls in regular lists. Use the regular list controls instead.

メニューはリストの特殊なタイプです。メニューでは、ようにドロップダウンメニュー、オーバーフローメニュー、およびに適切なコントロールを使用します。正規のリストにこれらのコントロールを使用しないでください。定期的なリストではなく、コントロールを使用。

#### Check

Type: state

Not a separate target.

Menus only. Indicates that the list item has been selected. The selection is done through a different control.

タイプ：状態

ていない独立したターゲット。

メニューのみ。リスト項目が選択されていることを示します。選択は、異なる制御を介して行われます。

#### Inline information

Type: secondary info

Not a separate target.

Menus only. Inline information is a small snippet of text related to the line title that can provide information or a tip, like a keyboard shortcut. It cannot be truncated.

タイプ：二次情報

ていない独立したターゲット。

メニューのみ。インライン情報は、キーボードショートカットのような情報やヒントを提供することができるラインのタイトルに関連したテキストの小さなスニペットです。これは、切り捨てられることはできません。

#### Nested menu indicator

Type: primary action

Not a separate target.

Menus only. The glyph indicates that a secondary menu will fly out upon hover, focus, and/or selection.

タイプ：プライマリアクション

ていない独立したターゲット。

メニューのみ。グリフは、二次メニューがホバー、フォーカス、および/または選択時に飛び出すことを示しています。