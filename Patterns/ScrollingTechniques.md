Scrolling techniques
===

### Scrolling

#### Based on blocks

When designing scrolling behavior, it is helpful to think in blocks. This is just a mental model and won’t be represented with any visual affordance.

These are the main four blocks for app bars that help with the scrolling structure:

* Status bar: 24dp
* Navigation bar: 56dp on mobile and 64dp on tablet and desktop.
* Tab bar/search bar: 48dp
* Flexible space: space to accommodate a desired aspect ratio for images or extended app bars.

スクロール動作を設計するとき、それはブロック単位で考えると便利です。これはちょうどメンタルモデルであり、任意の視覚的なアフォーダンスで表現されることはありません。

これらには、スクロール構造に役立つアプリ·バーのための主要な4ブロックです。

* ステータスバー：24dp
* ナビゲーションバー：タブレットとデスクトップ上のモバイルと64dp上の56dp
* タブバー/検索バー：48dp
* 柔軟なスペース：スペースは画像または拡張アプリバーの所望のアスペクト比に対応する

### Standard app bar

The standard app bar height is 56dp on mobile and 64dp on larger screen sizes. There are two options when it comes to scrolling.

1. The app bar can scroll off screen with the content and come back when the user reverse- scrolls.
2. The app bar can stay fixed at the top and let the content scroll under it.

標準アプリのバーの高さは、より大きな画面サイズでモバイルおよび64dp上56dpである。それは、スクロールするために来るとき2つのオプションがあります。

1. アプリのバーがコンテンツで画面をオフにスクロールしたときに、ユーザーリバースにスクロールを戻って来ることができる。
2. アプリバーが上部に固定され、その下にコンテンツのスクロールをさせたままにすることができます。

#### Tabs

The standard app bar can be extended to include tabs or a search box. Using the blocks as a mental model is helpful when determining the scrolling behavior. In this case, you have two options:

1. The navigation bar scrolls off and the tab bar stays anchored at the top.
2. The app bars stays in place and the content scrolls under it.

標準アプリバーはタブや検索ボックスを含むように拡張することができる。スクロール動作を決定する際にメンタルモデルとしてのブロックを使用すると便利です。この場合は、次の2つのオプションがあります。

1. オフナビゲーションバーのスクロールとタブ·バーが上部に固定されたまま。
2. アプリバーは、場所とその下のコンテンツがスクロールに留まる。

#### Flexible space

The app bar is flexible and can be extended to accommodate larger typography or images. To extend the app bar, add a flexible space block.

1. The flexible space shrinks until only the navigation bar is left. The title should also shrink into place to become a 20sp title in the navigation bar. When scrolling all the way back, the flexible space and the title grow into place again.
2. The whole app bar scrolls off. When the user reverse-scrolls, the navigation bar returns anchored to the top. When scrolling all the way back, the flexible space and the title grow into place again.

アプリバーは柔軟性があり、より大きなタイポグラフィや画像に対応するように拡張することができる。アプリバーを拡張するために、柔軟な空間ブロックを追加します。

1. 唯一のナビゲーションバーが残るまで柔軟なスペースが縮小します。タイトルはまた、ナビゲーションバーの20SPのタイトルになるために、所定の位置に縮小する必要があります。背中のすべての方法をスクロールするときは、柔軟性のあるスペースとタイトルが再び定位置に成長する。
2. 全体のアプリバーのスクロールオフ。ユーザーが-スクロールを逆にすると、ナビゲーションバーに戻り、トップに係留。背中のすべての方法をスクロールするときは、柔軟性のあるスペースとタイトルが再び定位置に成長する。

#### Flexible space with image

To use images in the app bar, you can use flexible space to accommodate the desired aspect ratio. In this example, the aspect ratio is 4:3. When scrolling, the content pushes up the image so that the flexible space shrinks. The last 20% of the image’s flexible space is tinted with the primary color for the app.

アプリバーに画像を使用するには、所望のアスペクト比に対応するために柔軟なスペースを使用することができます。 この例では、アスペクト比は4:3である。スクロール時に柔軟空間が縮小するように、コンテンツが画像を押し上げる。画像の柔軟なスペースの最後の20％はアプリケーションのための主要な色で着色される。