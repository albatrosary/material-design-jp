Buttons
===

A button consists of text and/or an image that clearly communicates what action will occur when the user touches it.  There are three types of main buttons:

* Floating action button: a circular button made of paper that lifts and emits ink reactions on press.
* Raised button: a typically rectangular button made of paper that lifts and emits ink reactions on press.
* Flat button: a button made of ink that emits ink reactions on press but does not lift.
* In addition, fully saturated icons in your design generally always denote affordances.

Buttons should be designed in accordance with your app’s color theme.

ボタンは、テキストおよび/または明確にユーザーがそれに触れたときにアクションが発生するどのような通信を行う画像で構成されています。メインボタンは次の3種類があります。

* フローティングアクションボタン：持ち上げ、プレス上のインク反応を発する紙で作られた円形のボタン。
* 隆起ボタン：持ち上げ、印刷機上でインキ反応を放出する紙製の一般的に長方形のボタンを押します。
* フラットボタン：上のインク反応を発するが、持ち上げていないインクで作られたボタンを押します。
* また、完全に一般的に常にアフォーダンスを表し、デザインのアイコンを飽和。

ボタンはアプリのカラーテーマに合わせて設計されなければならない。

### Usage

#### Choosing button style

Choosing a button style depends on the primacy of the button, the number of containers on screen, and the overall layout of the screen.

First, look at the button’s function: is it important and ubiquitous enough to be a floating action button?

Next, choose raised or flat dimensionality depending on the container it will be in and how many z-space layers you have on screen. There should not be layers upon layers upon layers of objects on the screen.

Finally, look at your specific layout. You should primarily use one type of button per container. Only mix button types when you have a good reason to, such as emphasizing an important function.

ボタンのスタイルを選択すると、ボタン、画面上の容器の数、画面の全体的なレイアウトの優位性に依存します。

まず、ボタンの機能を見て：それは、フローティングアクションボタンにすることが重要と十分に遍在する？

次に、上昇またはフラット次元は、それが中でどのように多くのz空間層あなたが画面上に持っているであろうコンテナに応じて選択します。画面上のオブジェクトのレイヤーの際に各層の際に層があってはならない。

最後に、特定のレイアウトを見てください。あなたは主にコンテナあたりのボタンの1つのタイプを使用する必要があります。あなたがそのような重要な機能を強調などに十分な理由を持っている場合にのみ、ボタンの種類を混在させる。

#### Buttons in dialogs

Use ink buttons on dialogs to prevent too many layers of dimension.

次元のあまりに多くの層を防止するために、ダイアログ上のインクボタンを使用します。

#### Buttons inline

Choose raised or flat buttons depending on your specific layout. Make sure to allow enough padding around flat buttons so the user can easily find them.

あなたの特定のレイアウトに応じて上昇またはフラットボタンを選択してください。ユーザーが簡単に見つけられるように平らなボタンの周りに十分なパディングを許可することを確認してください。

#### Persistent footer buttons

If your app requires actions to be persistent and readily available to the user, first consider using the floating action button.

If a floating action button isn’t quite right, but the button still needs to be easy to access, consider persistent footer buttons.

あなたのアプリは、永続的な、ユーザが容易に利用できるようにするための措置を必要とする場合、第1の浮遊アクションボタンを使用することを検討してください。

フローティングアクションボタンが非常に適切ではないですが、ボタンがまだアクセスしやすいように必要がある場合は、永続的なフッターのボタンを検討してください。


### Flat & raised buttons

#### Raised buttons

Raised buttons emphasize functions that would otherwise get lost on a busy or wide space. They add dimension to mostly flat layouts.

隆起したボタンは、他の方法でビジーまたは広い空間で迷子になるだろうな機能を強調している。彼らは主にフラットなレイアウトに次元を追加。

#### Flat buttons

Use flat buttons for contexts such as toolbars and dialogs to avoid gratuitous layering.

無償階層化を避けるために、そのようなツールバーやダイアログなどのコンテキストのフラットボタンを使用します。

#### Flat and raised button states

Button states for mocks:

* Raised buttons behave like a piece of material resting on another sheet – they lift and color on press.
* Flat buttons remain flush to the sheet and fill with color on press.

モックのためのボタンの状態：

*隆起ボタンは、別のシート上の材料休息の一片のように振る舞う - 彼らは持ち上げ、プレス上の色。
*フラットボタンはシートにそろえたままを押し上の色でいっぱい。

Ink travels between buttons as they come into focus. Focused state animations emanate between the normal and pressed state.

When representing button states in mocks, use graphic rings to represent the animation. Note that focused states will be in animation and that these images do not represent what the focused state should look like in implementation.

彼らが焦点に来るように、インクには、ボタンの間を移動する。焦点を当てた状態アニメーションは正常と押された状態との間で出てくる。

モックでボタンの状態を表すときに、アニメーションを表現するために、グラフィックのリングを使用しています。集中状態がアニメーションであることをこれらの画像が合焦状態が実装にどのように見えるかを表すものではないことに注意してください。

#### Flat Light/Light theme

Minimum width: 88dp
Height: 36dp
Hover: 20% #999999
Pressed: 40% #999999
Disabled text: 26% #000000

#### Flat Dark/Dark theme

Minimum width: 88dp
Height: 36dp
Hover: 15% #CCCCCC
Pressed: 25% #CCCCCC
Disabled text: 30% #FFFFFF

#### Raised Light/Light theme

Minimum width: 88dp 
Height: 36dp 
Disabled text: 26% #000000
Disabled button: 12% #000000

#### Raised Dark/Dark theme

Minimum width: 88dp 
Height: 36dp 
Normal color: 500 
Hover color: 600 
Pressed color: 700 
Disabled text: 30% #FFFFFF 
Disabled button: 12% #FFFFFF

#### A note on accessibility

To ensure usability for people with disabilities, make sure that your buttons have a height of 36dp, but that the touchable target has a minimum height of 48dp.

障害を持つ人々のための使いやすさを確保するために、あなたのボタンが36dpの高さがあることを確認したが、触れることができるターゲットは48dpの最小の高さを持っていること。

#### Buttons in motion

### Floating action button

#### Floating action button

Floating action buttons are used for a special type of promoted action. They are distinguished by a circled icon floating above the UI and have special motion behaviors related to morphing, launching, and the transferring anchor point.

Floating action buttons come in two sizes: the default, which should be used in most cases, and the mini, which should only be used to create visual continuity with other elements on the screen.

フローティングアクションボタンが促進作用の特殊なタイプのために使用される。彼らは、モーフィングの起動、および転送するアンカーポイントに関連した特別な運動行動をUI上に浮かんで丸で囲んだアイコンで区別し、持っています。

ほとんどの場合に使用すべきデフォルト、およびのみ、画面上の他の要素との視覚的な連続を作成するために使用されるべきであるミニ、：フローティングアクションボタンが2サイズ入って来る。

#### Associated content

Not every screen needs a floating action button. A floating action button should represent the primary action in an application. In the screen on the left, the primary action is to touch images in a gallery, so no button is needed. On the right, the primary action is to add files.

必ずしもすべての画面には、フローティングアクションボタンを必要とします。フローティングアクションボタンは、アプリケーション内のプライマリアクションを表している必要があります。左の画面では、プライマリアクションは、ギャラリー内の画像をタッチするので、[いいえ]ボタンは必要ありません。右側には、プライマリアクションは、ファイルを追加することです。

Try to use only one floating action button per screen, as it should represent only the most common action and is prominent on the screen.

それが唯一の最も一般的なアクションを表現し、画面上で顕著であるべきであるように、画面ごとに一つだけのフローティングアクションボタンを使用してみてください。

Don’t use floating action buttons in dialogs. Use a flat button.

ダイアログでアクションボタンをフローティングで使用しないでください。平らなボタンを使用します。

Don’t attach a floating action button to a side drawer; it could distract a user from the task they want to accomplish. Side drawers are for navigation.

サイドの引き出しにフローティングアクションボタンを接続しないでください。それは彼らが達成したいタスクからユーザーをそらすことができます。サイドの引き出しは、ナビゲーションのためのものです。

Don’t associate floating action buttons with pulldown menus.

プルダウンメニューでアクションボタンを浮動関連付けないでください。

#### Related actions

Put overflow actions in the overflow menu in toolbars, not in floating action buttons.

しないアクションボタンをフローティングに、ツールバーにオーバーフローメニューのオーバーフローアクションを置く。

If the hallmark of the app is adding file types, a floating action button can morph into related actions after it is first touched.

アプリの最大の特徴は、ファイルタイプを追加している場合は、それが最初にタッチした後に、フローティングアクションボタンは、関連するアクションに変形することができます。

However, if a set of actions that appear after touching a floating action button are unrelated to the button and are not a natural extension of it, then place the actions into an overflow menu.

フローティングアクションボタンをタッチした後に表示されるアクションのセットがボタンとは無関係であり、それの自然な拡張でない場合は、その後オーバーフローメニューにアクションを配置します。

If a floating action button morphs into a toolbar, that toolbar should contain related actions. In this example, the button lets the user select the media type to add.

フローティングアクションボタンがツールバーにモーフィングする場合、そのツールバーは関連のアクションを含める必要があります。この例では、ボタンは、ユーザがメディアタイプを追加するために選択できる。

Don’t morph floating action buttons into a toolbar that contains unrelated or confusing actions.

無関係または紛らわしい行動を含むツールバーにアクションボタンを浮動モーフィングしないでください。

A floating action button can contain a list of contacts.

フローティングアクションボタンは、連絡先のリストを含めることができます。

The list of contacts shouldn’t contain unrelated actions.

連絡先のリストは無関係のアクションを含めることはできません。

#### Qualities

Make floating action buttons positive actions like Create, Favorite, Share, Navigate, and Explore.

アクションボタンを作成し、お気に入り、共有、ナビゲート、および情報などの積極的な行動を浮動してください。

In general, avoid using floating action buttons for destructive actions like Archive or Trash; nonspecific actions; alerts or errors; limited tasks like cutting text; or controls that should be in a toolbar, like volume control or changing a font color. Floating action buttons don’t contain app bar icons or status bar info like notifications. Don’t layer badges or other elements over a floating action button.

一般的には、アーカイブやゴミ箱のような破壊的な行動のためのアクションボタンをフローティング使用は避けてください。非特異的なアクション。警告やエラー。テキストをカットするような限定されたタスク。またはコントロールは、ボリュームコントロールやフォントの色を変えるように、ツールバーにあるべきであること。フローティングアクションボタンがアプリバーアイコンや通知などのステータスバーの情報が含まれていません。フローティングアクションボタンの上にバッジまたはその他の要素を重ねないでください。

Use the circle-shaped icon consistently to enforce the primary action pattern across apps.

アプリ全体の主要行動パターンを強制するために一貫して円形のアイコンを使用します。

Don’t make floating action buttons bounce.

アクションボタンバウンスフローティングにしないでください。

#### Placement

A floating action button can be placed according to the keyline spacing rules or attached to an extended app bar. If floating action button is placed at the base of a list, the content should have enough padding at the bottom so the button does not block content in last row.

フローティングアクションボタンは、拡張アプリバーにキーライン間隔の規則に従って配置または取り付けることができる。フローティングアクションボタンがリストの基部に配置されている場合、ボタンは、最後の行のコンテンツをブロックしないように、コンテンツが下部に十分なパディングを持っている必要があります。

A floating action button can attach to a footer or to an extended sheet.

フローティングアクションボタンは、フッターにまたは拡張シートに添付することができます。

A floating action button shouldn’t float in a random location. Take care when attaching floating action buttons to a toolbar, where it might overlap with or cover other touch targets.

フローティングアクションボタンは、ランダムな位置に浮かぶべきではありません。それはと重複または他のタッチのターゲットをカバーするかもしれないツールバー、フローティングアクションボタンを取り付けるときは注意してください。


A floating action button can attach to an extended app bar.

フローティングアクションボタンは、拡張アプリバーに取り付けることができます。

A floating action button can be attached to a toolbar or structural element within a sheet (as long as it’s not blocking other elements).

（それは他の要素をブロックしていない限り、）浮動アクションボタンは、シート内のツールバーまたは構造要素に取り付けることができる。

A floating action button can be attached to the edge of a sheet.

フローティングアクションボタンは、シートの端部に取り付けることができる。

Don’t have more than one floating action button per screen.

画面ごとに複数のフローティングアクションボタンがありません。

Don’t place floating action buttons inside a drawer or attached to a drawer.

引き出しの内側にアクションボタンをフローティングや引き出しに取り付けるに置かないでください。

Don’t associate floating action buttons with every element on a screen.

画面上のすべての要素とアクションボタンを浮動関連付けないでください。

Don’t block floating action buttons with snackbars or toasts.

スナックバーや乾杯でアクションボタンを浮動ふさがないでください。

### Other buttons

#### Icon toggles

Icons are appropriate for app bars, toolbars, action buttons or as toggles.

Icon toggles can display bounded or unbounded ink press ripples beyond their touch target bounds. For more information, see Surface Reaction.

アイコンはアプリのバー、ツールバー、アクションボタンまたはトグルとして適切である。

アイコンのトグルは、タッチ対象の境界を越えて有界または非有界インクプレス波紋を表示することができます。詳細については、表面反応を参照してください。

#### Mobile dropdown buttons

#### Pulldown button

A pulldown button controls the state of a value. There may be two to many states. The button displays the current state and a down arrow icon. When a user interacts with the button, a menu flies out adjacent to and typically below the button with all of the state options.

States may be represented within the pulldown menu as a list of strings, a palette, icons, or many other display options. Pressing one state changes the displayed state of the button.

The pulldown shown here is the generic pulldown button with a list menu. Scrolling within the pulldown should behave like scrolling within menus.

プルダウンボタンは値の状態を制御します。多くの州に2があるかもしれません。ボタンは、現在の状態と下向きの矢印アイコンが表示されます。ユーザーがボタンと対話するとき、メニューには、通常の状態オプションのすべてを持つボタンの下に隣接して飛び出す。

国は、文字列のリスト、パレット、アイコン、または他の多くの表示オプションとしてプルダウンメニュー内で表現することもできる。一方の状態を押すと、ボタンの表示状態を変更します。

ここに示されているプルダウンリストメニューを持つ汎用プルダウンボタンです。プルダウン内スクロールは、メニュー内のスクロールのように振る舞うべきです。

#### Generic overflow pulldown button

This button is a pulldown button that does not have a displayed state but has an arrow or a generic menu button. When the button is pressed, the menu flies out. Pressing an option on the menu generally navigates to further settings for that option.

このボタンは、表示された状態を持っていますが、矢印または汎用メニューボタンを持っていないプルダウンボタンです。ボタンを押すと、メニューが飛び出す。メニューのオプションを押すと、一般的には、そのオプションの追加設定にナビゲートします。

#### Segmented pulldown button

A segmented pulldown has two sections: the current state and the dropdown arrow icon. Pressing the current state will cause that state’s action to fire within the screen. Pressing the dropdown arrow will display all the state options. Selecting one will change the displayed state.

現在の状態と、ドロップダウン矢印アイコン：セグメント化されたプルダウンには2つのセクションがあります。現在の状態を押すと、その状態のアクションが画面内に発射する原因となります。ドロップダウンの矢印を押すと、すべての状態のオプションが表示されます。 1を選択すると、表示された状態を変更します。

#### Editable segmented pulldown button

This button has a segmented pulldown, where the displayed state is text editable, such as a font size picker. Pressing the current state causes both that state’s action to fire and makes the displayed state editable. Pressing the arrow displays all the state options.

このボタンは、表示された状態は、フォントサイズピッカーとして、テキストが編集可能なセグメント化されたプルダウンを、持っています。現在の状態を押すと、発射するその状態のアクションの両方を引き起こし、表示された状態が編集可能になります。矢印が表示されすべての状態のオプションを押す。

#### Desktop dropdowns

Desktop app bar specs