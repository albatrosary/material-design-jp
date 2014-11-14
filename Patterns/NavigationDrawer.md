Navigation drawer
===

The navigation drawer is a common pattern found in Google apps.  The navigation drawer slides in from the left. It follows the keylines and metrics for lists.

ナビゲーションドロワーは、Googleアプリで見られる一般的なパターンです。ナビゲーションドロワーが左サイドからスライドします。それはリストのkeylinesとメトリックに従います。

#### Typography

Roboto Medium, 14sp, #FFFFFF
Roboto Regular, 14sp, #FFFFFF
List item: Roboto Medium, 14sp, 87% #000000
Subheader: Roboto Medium, 14sp, 54% #000000. Aligns to the 16dp keyline.

#### Vertical keylines and horizontal margins

Vertical keylines for icons are at 16dp from the left and right edges of the side nav and are 54% #000000.

Content associated with an icon or avatar aligns 72dp from the left edge of the side nav.

The width of the side nav is equal to the width of the screen minus the height of the action bar, or in this case 56dp from the right edge of the screen.

Use 16dp horizontal margins on mobile.

アイコンの垂直keylinesは、サイドNAVの左右の端から16dpにあると54％の＃000000です。

アイコンやアバターに関連付けられたコンテンツは、サイドNAVの左端から72dpを揃えます。

サイドナビゲーションの幅は、画面の幅を引いた画面の右端からアクションバーの高さ、またはこの場合56dp内に等しい。

モバイル上16dp水平マージンを使用してください。


#### Vertical spacing

1. 24dp
2. 56dp
3. 8dp
4. 48dp

Add 8dp padding at the top and bottom of every list grouping. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

すべてのリストのグループ化の上部と下部に8dpパディングを追加します。サブヘッダーが独自のパディングが含まれているため、一つの例外は、サブヘッダーでリストの最上位に位置する。

#### Elevation

The nav drawer spans the full height of the screen and the drawer is behind the status bar.

NAVの引き出しには、画面の全高にまたがり、引き出しは、ステータスバーの背後にある。

#### Selection state

After a list item is selected, that item becomes the app’s primary color or #000000 100% to clearly indicate selection. The touch ripple also becomes a highlight, to further indicate selection.

If this color the touch ripple/highlight doesn’t provide enough contrast with your primary color, use a darker tint of the primary color.

リスト項目が選択された後、その項目は明らかに選択を示すために、アプリの原色や＃000000 100パーセントになります。タッチリップルもさらなる選択を示すために、ハイライトになります。

この色は、タッチリップル/ハイライトがあなたの原色との十分なコントラストを提供していない場合は、原色の暗い色合いを使用しています。

#### Dividers

All dividers in the nav drawer are full-bleed inside the panel. There is also an 8dp padding above and below the divider.

NAVの引き出しの中のすべての仕切りは、フルブリードパネルの内側にある。 8dpパディングの上と分周器の下にもあります。

#### Scrolling

The navigation drawer can scroll like any normal view would.

ナビゲーションドロワーはあろう任意の通常のビューのようにスクロールすることができます。

#### Settings and support

Settings and support are located at the bottom of the scrolling list, in-line with the rest of the list content.

If the list of content in the navigation drawer is very long, the two options can be pinned to the bottom of the navigation drawer on a surface with a higher elevation. This surface is present only while at the top of the list; any other scroll position will immediately result in dismissing the surface and placing the options at the end of the list, in-line with the rest of the list content. The navigation drawer retains its scroll position when closed and reopened.

設定とサポートは、リストの内容の残りの部分とインラインで、スクロールリストの一番下に配置されています。

ナビゲーションドロワーのコンテンツのリストが非常に長い場合、2つのオプションは、より高い高度を有する表面上のナビゲーションパネルの下部に固定することができる。この表面は、一方で、リストの一番上に存在する。他のスクロール位置はすぐに表面を却下し、リストの内容の残りの部分とインラインで、リストの最後にオプションを置くことになります。閉じて再度開くとき、ナビゲーションドロワーは、そのスクロール位置を保持します。

If the list doesn’t scroll, the settings and support items will appear at the end of the list and are not pinned.

リストがスクロールしない場合は、設定やサポートアイテムは、リストの最後に表示され、ピン留めされていません。


