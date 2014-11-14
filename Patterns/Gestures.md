Gestures
===

Gestures are divided into Touch Mechanics (what your fingers do on the screen) and Touch Activities (context-specific results of specific gestures in the user interface).  A single touch mechanic (touch) may have multiple results depending on context (tap, cancel, enable/disable lights out), and a single touch activity (zoom in) may be achieved through multiple touch mechanics (pinch open, double touch, double-touch drag, etc.)

ジェスチャーは、タッチ力学（あなたの指が画面上に何をすべきか）とタッチ活動（ユーザー·インターフェース内の特定のジェスチャーのコンテキストに固有の結果）に分かれています。シングルタッチメカニック（タッチ）が（タップ、キャンセル、/無効のライトアウトイネーブル）、コンテキストに応じて複数の結果を有することができ、ワンタッチ活性（ズームイン）がオープン、ダブルタッチピンチ（複数のタッチメカニックを通じて、ダブルを達成することができる - タッチ、ドラッグ、など）

Note that Drag, Swipe, and Fling gesture activities are covered in more detail in their own section due to their highly contextual results.

そのドラッグし、スワイプをメモし、情事ジェスチャー活動は、それらの高度に文脈的な結果に自分自身のセクションで詳しく説明されています。

### Touch mechanics

Touch mechanics are what the user's fingers do on the screen.

タッチメカニックは、ユーザーの指が画面上で何をすべきかである。

#### Touch

one-finger press, lift

Example: Select

1本指プレス、リフト

例：選択

#### Double touch

one-finger press, lift, one-finger press, lift

Example: Zoom in

1本指プレス、リフト、ワンフィンガープレス、リフト

例：ズームイン

#### Drag, Swipe, or Fling

one-finger press, move, lift

Example: Dismiss, scroll, tilt, etc.

1本指を押し、移動、リフト

例：閉じ、スクロール、傾き、など

#### Long press

one-finger press, wait, lift

Example: Select an element, such as a list item

Long press is not used to display a contextual menu.

1本指プレス、待って、リフト

例：このようなリスト項目として、要素を選択

長押しは、コンテキストメニューを表示するために使用されていません。

#### Long-press drag

one-finger press, wait, move, lift

Example: Pick up and move, select multiple items

1本指プレス、待って、移動、リフト

例：ピックアップし、移動し、複数の項目を選択

#### Double-touch drag

one-finger press, lift, one-finger press, drag, lift

Example: Zoom in, zoom out

1本指プレス、リフト、1本指を押し、ドラッグ、リフト

例：ズームで、ズームアウト

#### Pinch open

two-finger press, move outwards, lift

Example: Zoom in

2本指を押して、外側に移動、リフト

例：ズームイン

#### Pinch closed

two-finger press, move inwards, lift

Example: Zoom out

2本指を押して、内側に移動し、リフト

例：ズームアウト

#### Two-finger touch

two-finger press, lift

Example: Zoom out

2本指を押し、リフト

例：ズームアウト

#### Two-finger swipe, drag, fling

two-finger press, move, lift

Example: Select multiple items, pan, tilt

2本指を押し、移動、リフト

例：複数の項目を選択して、パン、チルト

#### Two-finger long-press

two-finger press, wait, lift

Example: None; this gesture is uncommon.

二本指プレス、待って、リフト

例：なし。このジェスチャーはまれである。

#### Two-finger long-press drag

two-finger press, wait, move, lift

Example: Pick up and move

二本指プレス、待って、移動、リフト

例：ピックアップし、移動

#### Two-finger double touch

two-finger press, lift, two-finger press, lift

Example: Zoom out

二本指プレス、リフト、二本指プレス、リフト

例：ズームアウト

#### Rotate

two-finger press, simultaneously orbit both fingers around center point, lift

Example: Rotate content, such as a map

2本指のプレスは、同時に、中心点の周りの両方の指を周回、リフト

例：マップのようなコンテンツを回転

### Touch activities

Context-specific results of specific gestures in the user interface.

ユーザーインターフェイスの特定のジェスチャーのコンテキスト固有の結果。

#### Activate

Activates a screen element, like a button.

Touch mechanics: Touch

ボタンのような画面要素を、アクティブにします。

メカニックをタッチ：タッチ

#### Cancel or Escape

Cancels or escapes out of the current task, as in dialogs or menus.

Touch mechanics: Touch

取り消しまたはダイアログやメニューのように、現在のタスクの外にエスケープします。

メカニックをタッチ：タッチ

#### Enable/Disable lights out

Hides or shows a view’s chrome.

Touch mechanics: Touch

非表示にしたり、ビューのクロムを示している。

メカニックをタッチ：タッチ

#### Drag or Swipe or Fling

See the following section for distinctions between Scroll, Reveal upon scroll, Pan, Dismiss, Swipe to refresh, Edge swipe, Paging swipe, Overscroll collapse, Menu open, and Tilt.

Touch mechanics: Drag, Swipe, or Fling

エッジスワイプ、ページングスワイプ、Overscroll崩壊、メニューオープン、チルト、スワイプリフレッシュする、パン、解任、スクロールの間の区別のために、以下のセクションを参照してくださいスクロール時に公開する。

タッチ力学：ドラッグ、スワイプ、または情事

#### Data selection (when nothing is selected)

Selects a single element

Touch mechanics: Long press, two-finger touch

単一の要素を選択し、

タッチ力学：長押し、2本指のタッチ

#### Data selection (when items are already selected)

Selects additional elements while in selection mode. Can use any combination of subsequent one- or two-finger gestures.

Touch mechanics: Touch, two-finger touch

しばらく選択モードでの追加要素を選択します。その後の一次元または二本指ジェスチャーの任意の組み合わせを使用することができます。

タッチ力学：タッチ、2本指のタッチ

#### Data multi-selection drag

Reveals selection box that originates from point of gesture initiation. Height and width can be adjusted based on finger position. Final selection is based on selection box dimensions upon finger(s) lifting.

Touch mechanics: Two-finger swipe or drag, long-press drag with no items selected

ジェスチャー開始点に由来する選択ボックスを明らかにする。高さと幅は、指の位置に基づいて調整することができる。最終的な選択は、指（複数可）、昇降時に選択ボックスの寸法に基づいています。

タッチ力学：2本指スワイプまたはドラッグは、アイテムなしで長押しドラッグして選択した

#### Pick up and move

Affects the selected item or items. It can be used to:

* Rearrange data within a view
* Move an item into a container or onto a target
* Reorder items in a list or a card collection

Touch mechanics: Two-finger long-press drag, long-press drag on selected item

選択した項目に影響を与えます。それがために使用することができます：

* ビュー内のデータを並べ替え
* 容器の中に、またはターゲットにアイテムを移動
* リストやカードコレクション内の*並べ替えのアイテム

選択した項目に2本指長押し、ドラッグ、長押しドラッグ：力学をタッチ

#### Zoom in

Scales up content.

Touch mechanics:

* Double-touch
* Double-touch drag (down)
* Pinch open

コンテンツをアップスケーリングします。

メカニックをタッチ：

* ダブルタッチ
* ダブルタッチドラッグ（下）
* オープンピンチ

#### Zoom in to fit

For nested views, scales up the smallest targetable view.

Touch mechanics: Double-touch

ネストされたビューの場合は、最小の標的可能なビューをスケールアップ。

メカニックをタッチ：ダブルタッチ

#### Zoom out

Scales down content.

Touch mechanics:

* Double-touch at maximum zoom
* Double-touch drag (up)
* Pinch closed
* Two-finger touch
* Two-finger double 

コンテンツをダウンスケールします。

メカニックをタッチ：

* 最大ズームでのダブルタッチ
* ダブルタッチドラッグ（最大）
* ピンチを閉じ
* 2本指タッチ
* 2本指ダブル

#### Expand

Expands collapsed content.

Touch mechanics: Pinch open

#### Collapse

Collapses expanded content.

Touch mechanics: Pinch closed

折りたたまれたコンテンツを展開します。

メカニックをタッチ：オープンピンチ

#### Rotate

Rotates the targeted content.

Touch mechanics: Rotate

ターゲットコンテンツを回転させる。

メカニックをタッチ：回転

### Drag, swipe, or fling details

Because the activity performed by a swipe gesture can vary greatly based on context, this section describes some of the major swipe gesture patterns and their differences. Gesture velocity (from least to most) is the main distinction between Drag, Swipe, and Fling. Depending on context of use, gesture velocity can produce different results:

* Drag: Fine gesture, slower, more deliberate, controlled, typically has an on-screen target
* Swipe: Gross gesture, faster, typically has no on-screen target
* Fling: Gross gesture, no on-screen target

スワイプジェスチャによって実行されるアクティビティが大幅にコンテキストに基づいて変化する可能性があるため、このセクションでは、主要なスワイプジェスチャーパターンとその相違点をいくつか説明します。ジェスチャー速度は（少なくともから最もへ）ドラッグし、スワイプ、と情事の間の主な違いです。使用状況に応じて、ジェスチャ速度が異なる結果を生成することができる。

* ドラッグ＆：ファインジェスチャーは、遅く、より多くの、意図的な制御、一般的に画面上の目標を持つ
* スワイプ：グロスジェスチャーは、より速く、通常は無画面上の目標を持つ
* 情事：グロスジェスチャー、ない画面上のターゲット

A swipe becomes a fling based on ending velocity and whether the affected element has crossed a threshold.

スワイプは、速度を終了にして、影響を受けた要素がしきい値を超えたかどうかをもとに情事になる。

Generally, gesture velocity impacts whether the action is immediately reversible once crossing that threshold: a Drag maintains contact with the element, and reversing the gesture will drag the element back across the threshold. A fling imparts velocity and removes contact with the element while it crosses the threshold, preventing a reversal.

一般的に、アクションは一度、そのしきい値を超え、すぐに可逆ジェスチャー速度への影響であるかどうか：ドラッグエレメントとの接触を維持し、ジェスチャーを逆にすると、バックしきい値越えて要素をドラッグします。情事は、速度を付与し、それが逆転を防止、しきい値を超えるながら要素との接触を除去します。

#### Swipe Activity

#### Morphology

#### Scroll

Vertical or horizontal swipe in content body.

Scroll amount varies based on velocity of gesture: drag (slow) vs. swipe vs. fling (fast)

Generally:

- scroll directions are mutually exclusive

- applied to content at 100% scale

コンテンツ本体の垂直または水平スワイプ。

スクロール量は、ジェスチャの速度によって異なります：ドラッグ情事対スワイプ対（低速）（高速）

一般的には：

- スクロール方向が相互に排他的である

- 100％スケールでコンテンツに適用

#### Reveal upon scroll

Reversing the scroll direction in a content area can have an additional effect of immediately revealing hidden in-app elements. E.g., scrolling up in Chrome shows the Omnibox.

Dismiss in-app elements by resuming original scroll direction.

コンテンツ領域にスクロール方向を逆にすると、すぐに隠れたアプリ内の要素を明らかにすることの付加的な効果を持つことができます。例えば、Chromeでスクロールアップすると、アドレスバーが表示されます。

オリジナルのスクロール方向を再開することでアプリ内の要素を解任。

#### Pan

Omnidirectional, one or two fingers

Generally applied to:

- unbounded content (maps)

- content that is larger than the screen height or width (zoomed in web page or photo)

全方向性、1つまたは2つの指

一般的に適用される：

- 無制限のコンテンツ（マップ）

- 画面の高さまたは幅よりも大きいコンテンツは、（ウェブページや写真の拡大）

two-finger pan gesture, when transitioning from another two-finger gesture (e.g., pinch zoom or rotate) such as in Maps, will result in two-finger pan.

二本指パンジェスチャーは、そのようなマップのように、別の2本指ジェスチャーからの移行（例えば、ピンチズームや回転させる）と、2本の指でパンになります。

Two-finger pan gesture as the initiating gesture will result in tilt.

開始ジェスチャーとして二本指パンジェスチャは、チルトになります。

Drag is typically used with Pan.

ドラッグして、一般的にパンと一緒に使用されている。

Fling will maintain gesture velocity, resulting in a significant pan of the content along the direction of the fling gesture.

情事情事はジェスチャーの方向に沿った内容の大幅なパンで、その結果、ジェスチャー速度を維持します。

#### Dismiss

Originates on a swipeable element such as a list item or card.

Orthogonal to the direction of scrolling.

The gesture is typically horizontal, with symmetrical actions.

The Dismiss gesture is committed based on crossing a threshold.

そのようなリストアイテムやカードなどのswipeable要素に由来する。

スクロールの方向と直交する。

ジェスチャは、対称的なアクションで、一般的に水平である。

閉じジェスチャーは、しきい値を横切るに基づいて取り組んでいます。

#### Swipe to refresh

Available at index zero of a list, or at the content origination edge of an empty container.

Generally vertical and in a downward direction.

リストのインデックスがゼロで、または空コンテナのコンテンツ発信エッジで利用できる。

略鉛直下方向である。

#### Edge swipe

A swipe that originates outside of the screen and reveals off-screen content. Invokes out-of-context content, that is, content separate and distinct from the current view.

If no edge swipe action is defined, an Edge swipe gesture can default to a Paging swipe.

The Edge swipe gesture is committed based on crossing a threshold.

画面の外に発信し、スワイプはオフスクリーンの内容を明らかにしている。ある外のコンテキスト内容を呼び出し、現在のビューから独立した別個のコンテンツ。

全くエッジスワイプアクションが定義されていない場合、エッジスワイプジェスチャは、ページングスワイプをデフォルトにすることができます。

エッジスワイプジェスチャがしきい値を超えるに基づいて取り組んでいます。

#### Paging swipe

An on-screen, in-content swipe that reveals additional, related off-screen content.

Don’t use paging swipes when individual elements are swipeable. The gesture reveals one page/tab per paging swipe.

Paged content may be >100% zoom, in which case an in-content swipe will Pan to an edge of the content, and an additional in-content swipe will Page.

See also: Overscroll collapse

The Paging swipe gesture is committed based on crossing a threshold.

オンスクリーンは、内コンテンツの追加が明らかスワイプ、オフスクリーンのコンテンツを関連。

個々の要素がswipeableあるとき、ページングスワイプを使用しないでください。ジェスチャーは、ページングスワイプごとに1つのページ/タブを明らかにする。

ページングされたコンテンツは、インコンテンツスワイプがコンテンツのエッジにパンし、その場合、> 100％のズーム、および追加でコンテンツスワイプするページがあります。

参照：Overscroll collapse

ページングスワイプジェスチャがしきい値を超えるに基づいて取り組んでいます。

#### Overscroll collapse

Navigate up in hierarchy.

Paging swipe at the top or bottom of scrolling content to navigate to Parent content.

The Overscroll collapse gesture is committed based on crossing a threshold.

階層にまでナビゲートします。

上部またはスクロールするコンテンツの下部にページングスワイプは親コンテンツに移動します。

Overscroll崩壊ジェスチャーは、しきい値を超えるに基づいて取り組んでいます。

#### Menu open

Drag originating from a menu or picker reveals a menu. Upon lift, the highlighted menu option is selected.

Menu appears upon touch

Drag is used with Menu open.

メニューまたはピッカーから発信ドラッグして、メニューを明らかにする。リフト時には、ハイライト表示されたメニューオプションが選択されています。

メニューは、タッチ時に表示されます

ドラッグは、メニューのオープンと共に使用される。

#### Tilt

Tilts 3D content forward or backward

When transitioning from another two-finger gesture (e.g., pinch zoom or rotate) such as in Maps, will result in two-finger pan.

Drag is used with Tilt.

傾く3Dコンテンツ前方または後方

そのような地図のように別の2本指ジェスチャーからの移行（例えば、ピンチズームや回転させる）場合には、二本指パンになります。

ドラッグして、チルトで使用されます。
