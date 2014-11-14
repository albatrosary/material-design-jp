Menus
===

Menus allow users to take an action by selecting from a list of choices revealed upon opening a temporary, new sheet of material.

メニューは、ユーザーが、材料の一時的な、新しいシートを開くと明らかにした選択肢のリストから選択して行動を起こすことができます。


### Usage

A menu is a temporary piece of material emitted from a button, an action, a pointer, or another control that contains at least two menu items.

Each menu item is a discrete option or action that can affect the app, the view, or selected elements within a view.

Menus should not be used as a primary method for navigation within an app.

メニューは、ボタン、アクション、ポインタ、または少なくとも2つのメニュー項目が含まれている別のコントロールから放出される物質の一時的な作品です。

各メニュー項目は、ビュー内のアプリ、ビュー、または選択された要素に影響を与えることができる個別のオプションまたはアクションです。

メニューはアプリ内ナビゲーションのための主要な方法として使用すべきではありません。

The label of an emitting button or control concisely and accurately reflects the menu items contained within the menu. Menu bars typically use single words as labels, like “file”, “format”, “edit”, and “view”, while other contexts may have more verbose labels.

Menus display a consistent set of menu items, each of which may be enabled or disabled based on the current state of the application.

発光ボタンまたはコントロールのラベルは、簡潔かつ正確に、メニュー内に含まれるメニュー項目を反映している。他のコンテキストではより詳細なラベルを持っているかもしれないメニューバーは、一般的に、「ファイル」、「フォーマット」、「編集」、および「ビュー」などのラベルなどの単語を使用します。

メニューは、有効またはアプリケーションの現在の状態に基づいて無効になる場合があり、それぞれがメニュー項目、一貫性のあるセットを表示。

Contextual menus dynamically change their available and enabled menu items based on the current state of the application.

Generally, remove menu items that are irrelevant to the current context, and disable menu items which are relevant but need certain conditions to be met (for example, Copy becomes enabled when text is selected).

Certain application states may result in a contextual menu containing only a single menu item. For example, when highlighting text on a web page, Android reveals only Copy, since users cannot cut or paste text.

コンテキストメニューを動的にアプリケーションの現在の状態に基づいて利用可能であり、有効なメニュー項目を変更する。

一般的には、（コピー、テキストが選択されたときに有効になり、たとえば）現在のコンテキストとは無関係であるメニュー項目を削除し、関連しているが、満たすべき特定の条件を必要とするメニュー項目を無効にします。

特定のアプリケーションの状態は、単一のメニュー項目を含むコンテクストメニューになることがあります。 Webページ上のテキストを強調表示するときに例えば、Androidは、ユーザーがカットまたはテキストを貼り付けることができないので、唯一のコピーを明らかにする。

Reposition menus vertically and horizontally based on their proximity to screen edges.

垂直方向と水平方向のエッジをスクリーニングするための彼らの近接性に基づいてメニューを再配置します。

If the height of a menu prevents all menu items from being displayed, the menu can scroll internally. One example is when viewing a menu on a phone in landscape orientation.

メニューの高さが表示されてからすべてのメニュー項目を防止する場合は、メニューが内部的にスクロールできます。横向きに電話でメニューを表示するときに一例である。

A menu can also cascade.

メニューもカスケード接続することができます。

These animations show scrolling and cascading menus in action.

これらのアニメーションは、スクロールや、アクションのメニューをカスケード表示します。

### Menu items

Each menu item is limited to a single line of text that describes the action it will perform when selected.

The text is generally a single word or short phrase, but it can include icons and helper text, like keyboard shortcuts, as well as controls like checkmarks to indicate multiple selected items or states. See also List controls.

Menus with static content should have the most frequently used menu items placed at the top of the menu.

Menus with dynamic content may have other behavior, such as placing previously used fonts at the top of the menu. The order can change based on user actions.

Menu items can reveal nested submenus. Try to limit nesting to one level deep, as it can be difficult to navigate multiple nested submenus.

各メニュー項目が選択されたとき、それが実行するアクションを説明するテキストの単一行に制限されています。

テキストは、一般に、単一の単語または短いフレーズですが、それは、複数の選択したアイテムまたは状態を示すためにチェックマークのようなアイコンやヘルパーテキスト、キーボードショートカットなど、並びにコントロールを含めることができます。コントロールの一覧を表示も参照してください。

静的コンテンツを持つメニューは、メニューの一番上に置かれ、最も頻繁に使用されるメニュー項目を持っている必要があります。

動的コンテンツを持つメニューは、メニューの一番上に、以前に使用されているフォントを配置するように、他の動作をする場合があります。順序は、ユーザのアクションに基づいて変更することができます。

メニュー項目は、ネストされたサブメニューを明らかにすることができます。それは複数のネストされたサブメニューをナビゲートすることは困難として、1レベルの深さまで入れ子に制限してください。

Displaying actions as disabled, rather than removing them, lets the user know they exist under the right conditions.

For example, Redo is disabled when there is nothing to redo. Cut and Copy are disabled until content is selected.

削除するのではなく、彼らは適切な条件の下に存在を知って、ユーザーをすることができます無効のアクションを表示します。

やり直すものがないとき、たとえば、やり直しが無効になっています。カットして、コンテンツが選択されるまでのコピーは無効になります。

### Behavior

Menus appear above all other in-app UI elements.

Dismiss a menu by tapping outside of the menu, or by tapping the emitting button (if visible).

Generally, selecting a menu item will also dismiss the menu. An exception is when a menu allows for multiple items to be chosen, for example, by using checkmarks.

メニューは、他のすべてのアプリ内のUI要素の上に表示されます。

発光ボタン（可視の場合）をタップして、メニューの外側をタップしてメニューを閉じます。

一般的には、メニュー項目を選択すると、メニューを解任いたします。複数の項目がチェックマークを使用することによって、例えば、選択されなければためのメニューが許す場合は例外である。

Menus are positioned over their emitting elements such that the currently selected menu item appears on top of the emitting element.

メニューは、現在選択されているメニュー項目が発光素子の上部に表示されるように、それらの発光素子の上に配置されている。

Do not display a duplicate of the selected menu item.

選択したメニュー項目の複製を表示しません。

Positioning the menu below the emitting element separates it from its context.

発光素子の下にメニューを配置すると、その文脈からそれを分離します。

### Simple Menus

Simple menus are used in list views on tablet and mobile devices to display the options for a specific list item.

Disambiguation: In contrast to simple menus, simple dialogs can present additional detail related to the options available for a list item or provide navigational or orthogonal actions related to the primary task. Although they can display the same content, simple menus are preferred over simple dialogs because simple menus are less disruptive to the user’s current context.

シンプルなメニューは、特定のリストアイテムのオプションを表示するには、タブレットとモバイルデバイス上のリストビューで使用されている。

曖昧さ回避：シンプルなメニューとは対照的に、単純なダイアログがリストアイテムに使用可能なオプションに関連する追加の詳細情報を提示したり、プライマリタスクに関連のナビゲーションまたは直交アクションを提供することができます。それらが同じコンテンツを表示することができますが、単純なメニューは、ユーザの現在のコンテキストにあまり破壊的であるため、単純なメニューが簡単なダイアログがより好ましい。

Use simple menus in lists to display the options for a specific list item.

Choosing an option immediately commits the option and closes the menu.

Touching outside of the menu, or pressing Back, cancels the action and closes the menu

特定のリストアイテムのオプションを表示するには、リストに簡単なメニューを使用します。

オプションを選択すると、すぐにオプションをコミットして、メニューを閉じます。

メニューの外に触れ、または戻るを押し、アクションをキャンセルし、メニューを閉じます

When opened, simple menus attempt to vertically align the currently selected menu item with the list item.

開いたときに、簡単なメニューの試みは縦にリスト項目と現在選択されているメニュー項目を整列させる。

When close to a screen edge, simple menus reposition their vertical alignment so that all menu items are completely visible.

画面の端に近い、シンプルなメニューは、そのように、垂直方向の配置位置を変更すると、すべてのメニュー項目が完全に表示されます。

Do not arbitrarily position the first menu item over the list item.

任意のリスト項目の上に最初のメニュー項目を配置しないでください。

Simple menus appear over their emitting element, not below.

シンプルなメニューはありません下記、彼らの発光素子の上に表示されます。

Menu width varies depending on string length.

Simple menus always maintain a 16dp margin (phone) or 24dp margin (tablet) to the left and right edges of the screen.

メニューの幅は、文字列の長さに依存して変化する。

シンプルなメニューは、常に画面の左右の端に16dpマージン（電話）または24dpマージン（タブレット）を維持する。

Menus show a persistent scroll bar when content is scrollable.

コンテンツがスクロール可能であるときのメニューは、永続的なスクロールバーを表示します。

Don’t duplicate the selected menu item

選択したメニュー項目を複製しないでください

Simple menus are always aligned with the start of the list item text and do not reposition horizontally based on touch location.

シンプルなメニューは常にリスト項目のテキストの開始と整合されており、タッチ位置に基づいて、水平位置を変更しないでください。


### Specs

Specs are provided for various sizes and types of menus and for different platforms.

仕様は、様々なサイズやメニューの種類の異なるプラットフォームのために提供される。

#### Mobile

#### Various widths

#### Cascading menu

#### Cascading redlines