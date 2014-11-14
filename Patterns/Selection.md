Selection
===

A long-press (a touch or mousedown that’s held in the same position for a moment) is the global gesture to select data. On touch devices, a two-finger touch may also be used to trigger selection.

長押し（一瞬同じ位置に保持さのタッチやマウスダウン）は、データを選択するためのグローバルなジェスチャーです。タッチデバイスに、二本指タッチはまた、選択をトリガするために使用することができる。

Using checkboxes (or custom analogs) to initiate selection is an explicit anti-pattern for mobile. For desktop, checkboxes may be used, with the following guidelines:

* Avoid persistently displaying checkboxes as part of each item.
* When hovering on an item, display a single checkbox for that item.
* After an item has been selected, display checkboxes for all remaining items in that set.

選択を開始するためのチェックボックス（またはカスタム類縁体）を使用すると、モバイル用の明示的なアンチパターンである。デスクトップの場合は、チェックボックスには、次のガイドラインを使用することができる：

* 持続的に各項目の一部としてチェックボックスを表示しないようにしてください。
* アイテムにホバリングする場合、その項目のチェックボックスが1つ表示します。
* 項目が選択された後、そのセット内の残りのすべての項目の表示のチェックボックス。

The use of checkboxes in contexts such as task lists or checklists where checking an item indicates completion, rather than selection, is entirely appropriate.

項目をチェックすることなく、選択ではなく、完了したことを示すようなタスクリストやチェックリストなどのコンテキストでのチェックボックスの使用は、完全に適切である。

### Item selection

Support for multi-selection is strongly recommended for list and grid containers. However, this is not required if the only actions available are valid for a single selection (like a list of phone numbers, where calling is the only action), or if the context is strongly biased toward direct, single-item manipulation (like moving icons on Android’s home screen.)

複数選択のサポートが強く、リストとグリッドコンテナに推奨されます。利用可能な唯一のアクションは、またはコンテキストが強く、直接、単一アイテムの操作に向けて付勢されている場合（呼び出しにのみアクションです電話番号のリスト、など）単一選択のために有効である場合は、これが動くように（必須ではありませんAndroidのホーム画面上のアイコン。）

Both long-press and two-finger touch may be extended by a drag gesture to select multiple items when initiating selection. Other items between the beginning and end points of the drag will be included in the selection. On desktop, a simple drag originating outside the bounds of all items may also be used to initiate multi-selection (for example, beginning a drag in the left margin of a list, and extending down and to the right to select items from that list.)

長押しや二本指タッチの両方が選択を開始する際に複数の項目を選択するドラッグジェスチャにより延長することができる。ドラッグの開始と終了点の間の他の項目は、選択に含まれます。デスクトップ上で、すべてのアイテムの境界の外部から発信簡単なドラッグはまた、リストの左余白にドラッグを開始すると、ダウンして拡張し、そのリストから項目を選択して右へ、例えば（マルチ選択を開始するために用いることができる。）

Once an initial selection is made, it can be altered through a number of user actions:

* Touch on an unselected item to select it, or on a selected item to unselect it.
* Shift+touch/click on an item to extend selection to that item and all items between it and the original selection.

最初の選択が行われると、それは、ユーザアクションの数によって変更することができる。

* 選択されていない項目をタッチして選択状態にし、または選択した項目でそれを解除する。
* Shiftキー+タッチ/その項目とそれと元の選択の間のすべてのアイテムに選択範囲を拡張するために項目をクリックします。

### Text selection

Text selection is indicated by highlighting the bounds of the selected text.

On mobile platforms, a selection handle is added to both the beginning and end of the selection. Standard actions related to the text appear in a dropdown menu ideally positioned immediately above, but not overlapping, the selection.

テキスト選択は、選択したテキストの境界を強調することによって示されます。

モバイルプラットフォームでは、選択ハンドルが始まりと選択範囲の最後の両方に追加されます。テキストに関連する標準のアクションは、理想的には、すぐ上に配置ドロップダウンメニューに表示されますが、選択、重複していない。

Text selection is effectively a single-select context, as the selection must be one contiguous block. However, the bounds of the selection may be altered following selection through a number of user actions:

* Dragging during the initial selection to expand the selection
* Dragging on either of the selection handles to expand or reduce the selection
* Touching (or clicking) repeatedly within the selection to expand it (single word > paragraph > all)
* Keyboard shortcuts
* Shift+Left/Right Arrow for character-by-character
* Shift+Up/Down Arrow for line-by-line
* Ctrl/Command+A to select all

選択が1の連続したブロックでなければなりませんようにテキストの選択は、効果的に単一選択コンテキストです。しかし、選択の境界はユーザアクションの数を通じて、次の選択を変更することができる：

* 選択範囲を拡張する最初の選択時にドラッグする
* 選択範囲のいずれかにドラッグする展開または選択範囲を減らすためにハンドル
* 繰り返し選択範囲内に触れる（またはクリック）して展開します（単一の語>パラグラフ>すべて）
* キーボードショートカット
* 文字ずつのためには、Shift +左/右矢印
* ライン·バイ·ラインのためのには Shift +上向き/下向き矢印
* Ctrl /コマンド+ A はすべてを選択する

#### Text selection handles

#### Text Selection - Light Theme

#### Text Selection - Dark Theme

Dropdown menus for Cut, Copy, Paste, and More appear above the selection area. When the user selects More, the dropdown will collapse toward the icon and the overflow menu items will grow, centered from the icon area. The font for menu text is Roboto Medium 14 sp, all in capital letters.

ドロップダウン切り取り、コピー、貼り付け用のメニュー、および詳細は、選択領域の上に表示されます。ユーザーがより選択すると、ドロップダウンアイコンに向かって崩壊するとオーバーフローメニュー項目がアイコン領域から中心に、成長します。メニューテキストのフォントはすべて大文字で、Roboto Medium 14spである。