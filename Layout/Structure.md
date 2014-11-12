Structure
===

### UI regions and guidance

This section covers the high level structure of our apps ranging from mobile to desktop and contains guidance.

Note: For guidance on arranging elements in z-space to achieve the correct behavior and shadows, see the Environment and Objects in 3D space sections.

Apps come in many varieties that address very different needs. For example:

* Apps built around a single focused activity handled from a single screen (such as a calculator, a camera, and many games)
* Apps whose main purpose is to switch between different activities without deeper navigation (such as a phone dialer offering favorites, recents, and contacts)
* Apps that combine a broad set of data views with deep navigation (such as different folders for a mail app or product categories in a shopping app)

Your app's structure will depend largely on the content and tasks you want to surface for your users.

このセクションでは、モバイルからデスクトップに至るまで我々のアプリのハイレベルの構造をカバーし、指導が含まれています。

注：ガイダンスについては、正しい動作と影を達成3D空間のセクションで環境とオブジェクトを表示するには、Z空間内の要素を配置することになります。

Appsは極めて異なるニーズの取り扱った多くの製品があります。たとえば：

* 画面から取り扱われるシングルで実行されるアプリを中心に構築（電卓、カメラ、多くのゲームのような）

* より深いナビゲーションの様々な活動を切り替えることができるアプリ（お気に入り、更新ムービーを提供し、電話ダイヤラとして、連絡先）

* 深いナビゲーションを備えたデータビューの広範なセットを組み合わせるアプリ（そのようなショッピングアプリで異なるメールアプリのフォルダまたは製品カテゴリとして）

アプリの構造は、コンテンツや、あなたのユーザーのために表面化するタスクに大きく依存します。

### Toolbars

#### Starting from the top

The layout of your start screen requires special attention. This is the first screen people see after launching your app, so it should be an equally rewarding experience for new and frequent visitors alike.

Ask yourself: "What will typical users most likely want to do in my app?", and structure your start screen experience accordingly.

Put content forward. Many apps focus on the content display. Avoid navigation-only screens and instead let people get to the core experience of your app right away by making content the centerpiece of your start screen. Choose layouts that are visually engaging and appropriate for the data type and screen size.

Anchor navigation and actions. Like any toolbar, the app bar can organize important actions. Its position at the top of a screen makes it ideal for presenting navigation controls, including switching between tabs or opening the left navigation bar. If your content is searchable, include the Search action in the app bar so people can cut through the navigation hierarchy.

スタート画面のレイアウトは特別な注意が必要です。これは、人々がアプリを起動した直後に最初に表示される画面ですので、同様に新しく、頻繁な訪問者のためにも平等に期待させる必要があります。

自問してみてください：それに応じてスタート画面の経験を構造化の典型的なユーザーが最も可能性が高い私のアプリでやることになるでしょうか？

コンテンツを前方に置く多くのアプリは、コンテンツ表示に焦点を当てます。ナビゲーション画面のみを避け、代わりに人々はすぐにコンテンツスタート画面の中心とすることで、アプリのコア体験に取得しましょう。データ型と画面サイズのため、視覚的に魅力的かつ適切なレイアウトを選択してください。

アンカーナビゲーションとアクションは任意のツールバーと同様に、アプリバーが重要なアクションを整理することができます。画面上部のその位置はタブを切り替えるか、左側のナビゲーションバーを開くなど、ナビゲーションコントロールを提示するために最適です。あなたのコンテンツが検索可能である場合、人々は、ナビゲーション階層をカットすることができますので、アプリバーに検索アクションが含まれています。


Be opinionated about functionality. When your app has a large amount of content or capabilities, direct the user’s focus to the most critical aspects of your product. Highlight navigation to important destinations within the content area. Promote the most characterful action as a floating action button. De-emphasize less frequently traveled paths in your app.

機能性についての独断こと。アプリがコンテンツや機能を大量に有している場合、お使いの製品の中で最も重要な側面に、ユーザの焦点を向ける。コンテンツ領域内の重要な目的地へのハイライトナビゲーション。フローティングアクションボタンなど、ほとんどの個性アクションを推進しています。デは強調しそれほど頻繁にアプリ内のパスを旅した。

### App bar

The app bar, formerly known as the action bar in Android, is a special kind of toolbar that’s used for branding, navigation, search, and actions.

以前はAndroidの中でアクションバーとして知られているアプリのバーは、ブランディング、ナビゲーション、検索、およびアクションのために使われているツールバーの特別な種類です。

If your app has a side nav, the control to open/close the side nav is on the left side of the app bar. The control can also morph into an up arrow for page navigation. The title in the app bar reflects the current page and can be an app title, page title or a page filter.

アプリ側NAVを持っている場合、開く/閉じるのためのサイドNAVのコントロールはアプリバーの左側にあります。コントロールは、ページナビゲーションのための上向き矢印に変形することができます。アプリバーにタイトルは、現在のページを反映しており、アプリのタイトル、ページタイトルやページフィルタすることができます。

Icons on the right side of the app bar are app-related actions. The menu icon opens the overflow menu, which contains secondary actions and menu items like help, settings, and feedback.

アプリバーの右側のアイコンは、アプリ関連のアクションです。メニューアイコン、ヘルプ、設定、およびフィードバックのような2次アクションとメニュー項目が含まれているオーバーフローメニューを開きます。

#### Metrics

Default height:

Mobile Landscape: 48dp

Mobile Portrait: 56dp

Tablet/Desktop: 64dp

For extended app bars, the height is equal to the default height plus content increment(s).

デフォルトの高さ：

モバイルランドスケープ：48dp

モバイルポータル：56dp

タブレット/デスクトップ：64DP

拡張されたアプリのバーの高さは、デフォルトの高さを加えたコンテンツの増分（複数可）に等しい。

#### Menus

A menu is a temporary sheet of paper that always overlaps the App Bar, rather than behaving as an extension of the App Bar.

メニューは、常にアプリバーの延長として振る舞うよりもアプリバーと重なる紙の一時的なシートである。

### System bars

#### Status bar/window bar

On Android, the status bar contains notification icons and system icons. On Chrome, the top bar contains the window controls: minimize, full screen, and close. In a Chrome app, the top bar can disappear, and the window controls are then brought into the app bar.

Androidでは、ステータスバーには通知アイコンとシステムアイコンが含まれています。最小化、フルスクリーン、およびクローズ：クローム上で、一番上のバーは、ウィンドウコントロールが含まれています。 Chromeのアプリでは、トップバーが消えることができ、およびウィンドウコントロールは、その後、アプリバーに持ち込まれている。

Metrics:

Android status bar height: 24dp

Chrome window height: 32dp

メトリック：

Androidのステータスバーの高さ：24dp

Chromeのウィンドウの高さ：32dp

#### Color variants

By default, the color of the status or window bar is a darker tone of the app bar color. It can also reference an element in the layout or it can be translucent.

デフォルトでは、ステータスまたはウィンドウバーの色は、アプリバーの色の暗い色調です。また、レイアウトの要素を参照することも、半透明であることができます。

#### Android navigation bar

The system bar in Android houses the device navigation controls: Back, Home, and Recents. It also displays a menu for apps written for Android 2.3 or earlier.

Metrics:

Height: 48dp

アンドロイド住宅機器ナビゲーションコントロールのシステムバー: 戻る、ホーム、および更新ムービー、それはまた、アンドロイド2.3 またはそれ以前のバージョン用に書かれたアプリケーションのためのメニューが表示されます。

メトリック：

高さ：48dp

#### Color variants

By default, the color of the status or window bar is a darker tone of the app bar color. It can also reference an element in the layout or it can be translucent.

デフォルトでは、ステータスまたはウィンドウバーの色は、アプリバーの色の暗い色調です。また、レイアウトの要素を参照することも、半透明であることができます。

#### Chrome OS shelf

The shelf houses the app launcher, application icons, and system settings on Chrome OS.

Metrics:

Height: 56dp

Chrome OSの上でアプリランチャー、アプリケーションのアイコン、およびシステム設定を収容する。

メトリック：

高さ：56dp


### Side nav

If present, the left and right nav bars can be pinned for permanent display or they can float temporarily as overlays.

左右のナビゲーションバーが存在する場合、表示のために永久固定することができ、またはそれらは、オーバーレイとして一時的に浮遊する。

The content in the left nav is ideally navigation- or identity-based. The content in the right nav should be secondary to the main content on a page.

左のnav内のコンテンツは、理想的にnavigation-またはidベースです。右のnav内のコンテンツは、ページ上のメインのコンテンツへの二次的であるべきである。

#### Structure

Nav drawers that are temporary overlay the content canvas. Nav panels that are pinned sit alongside or below the content canvas.

一時的なオーバーレイコンテンツキャンバスのNAV引き出しです。横やコンテンツ·キャンバスの下に座って固定されているNAVのパネルです。

#### Metrics

Mobile: Width = screen width - app bar height

Examples:

* Nexus 4: 304dp
* Nexus 5: 288dp
* iPhone: 264dp

Desktop: Max width for the left nav is 400dp. The right nav can vary depending on content.

モバイル：幅=画面の幅 - アプリのバーの高さ

例：

* ネクサス4：304dp
* ネクサス5：288dp
* iPhone：264dp

デスクトップ：左のnavマックス幅は400dpである。右ナビゲーションは、コンテンツに依存して変化する。


### Whiteframes

Whiteframes provide a variety of layout structures using a consistent approach to surfaces, layering, and shadows.

Whiteframesは表面、レイヤー、影に一貫性のあるアプローチを使用してレイアウト構造の多様性を提供します。