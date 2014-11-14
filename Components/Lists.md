Lists
===

Lists present multiple line items in a vertical arrangement as a single continuous element.

リストは、単一の連続要素として垂直配置で複数の行項目を提示する。

### Usage

A list consists of a single continuous column of tessellated sub-divisions of equal width called rows that function as containers for tiles.

Tiles hold content, and can vary in height within a list.

リストには、タイルのコンテナとして機能する同じ幅と呼ばれる行のモザイク式サブディビジョンの単一の連続列で構成されています。

タイルはコンテンツを保持し、リスト内の高さを変えることができる。

Lists are best suited to presenting a homogeneous data type or sets of data types, such as images and text, optimized for reading comprehension with the goal of differentiating between like data types or qualities within a single data type.

If more than three lines of text need to be shown in list tiles, use cards instead.

If the primary distinguishing content consists of images, use a grid list.

リストは、最高の均質なデータ型または単一のデータタイプ内のようなデータ·タイプまたは品質を区別することを目的として読解するために最適化された画像やテキストなどのデータ型のセットを提示することに適している。

以上のテキスト3行リストタイルに示される必要がある場合は、代わりにカードを使用する。

主な特徴的なコンテンツが画像で構成されている場合は、グリッド·リストを使用します。

#### Tile content

List tiles present collections of related content in a consistent format, using hierarchy to enhance readability by prioritizing a consistent type or set of content. For example, in an email app, an inbox list emphasizes an avatar and text snippet over a time stamp. This helps users more easily find the most important information within the collection of content.

リストには、一貫性のあるタイプに優先順位を付けることにより、可読性を高めるため、またはコンテンツのセットに階層を使用して、一貫性のある形式で、関連コンテンツの存在コレクションをタイル。たとえば、電子メールアプリで、受信トレイのリストがタイムスタンプ上のアバターとテキストスニペットを強調している。これにより、ユーザーはより簡単にコンテンツの集合内で最も重要な情報を見つけることができます。

List tiles can contain up to three lines of text, and the amount of text can vary between tiles within the same list. To display more than three lines of text, use a card.

Bias the most distinguishing content in a tile towards the left of the tile. In tiles with mutli-line content, place the most distinguishing content in the first line.

一覧タイルは、テキストの3つまでの行を含むことができ、テキストの量は、同じリスト内のタイルの間で変化し得る。以上のテキスト3行を表示するには、カードを使用してください。

バイアスタイルの左側に向かってタイルの中で最も特徴的なコンテンツ。 mutliラインコンテンツを含むタイルでは、最初の行の中で最も特徴的なコンテンツを配置。


### Content

#### Tile actions

The majority of space on a list tile should be dedicated to the primary action.

Because actions are not distinguishing elements of list tiles, place supplemental actions on the right side of the tile.

Primary and supplemental actions, such as play, zoom in, delete, and select, are immediate and typically do not have a submenu of options (action overflow) within the list.

Actions can open a subsequent view, such as a card.

リストタイル上のスペースの大部分は基本アクション専用にする必要があります。

アクションリストタイルの要素を区別していないので、タイルの右側の補足アクションを置く。

そのような遊びのような一次および補足のアクションは、リスト内のオプション（アクション·オーバーフロー）のサブメニューを持っていない一般的に、ズームイン、削除、および選択し、即時であり、。

アクションには、そのようなカードとして、後続のビューを開くことができます。

#### Primary actions:

* Fill the entire tile, and therefore are not represented via icons, text, etc.
* Are consistent throughout tiles in a specific list. For example, the primary action for all tiles in a single list of music would be to play a song, or in a list of emails, to open to read an email.

* 全体のタイルを埋めるため、アイコン、テキストなどを経由して表現されていない
* 特定のリスト内のタイル全体で一貫している。例えば、音楽の単一のリスト内のすべてのタイルを1次アクションは、電子メールを読むために開くために、歌、または電子メールのリスト内をプレイすることであろう。

#### Supplemental actions:

* Are represented in tiles with icons, secondary text, etc.
* Are functionally consistent throughout tiles in a specific list, for example, an icon that indicates whether someone is online.
* Are placed in a consistent location within the tiles of a specific list.

* アイコン、二次テキスト、とタイルで表現される
* 例えば、特定のリストに誰かがオンラインであるかどうかを示すアイコンがタイル全体で機能的に一貫している。
* 特定のリストのタイル内の一貫性のある場所に配置されます。

Avoid creating visual noise by repeatedly using supplemental actions in tiles, for example, by displaying a share action in every tile. Toggles, such as stars or pins, are exceptions because they provide meaningful information by displaying state.

繰り返しタイル内の共有アクションを表示することによって、例えば、タイルで補足アクションを使って、視覚的なノイズを作成しないようにしてください。彼らが状態を表示することにより、意味のある情報を提供するため、そのような星やピンなどのトグルは、例外です。

### Behavior

#### Scrolling

Lists scroll only vertically.

リストは垂直方向にのみスクロールします。

#### Gestures

Per-tile swipe actions should be consistent within lists.

Where appropriate, tiles can be moved between a list and a drop target (for example, moving a file into a folder) and picked up and manually reordered within a list.

タイルごとのスワイプアクションはリスト内で一貫している必要があります。

適切な場合には、タイルは、リスト内で並べ替えを手動で（フォルダにファイルを移動する、など）のリストとドロップターゲットとの間を移動し、ピックアップとすることができます。

#### Tile filtering and sorting

List tiles can be programmatically sorted or filtered by date, file size, alphabetical order, or other parameters.

一覧タイルは、プログラムソートや日付、ファイルサイズ、アルファベット順に、または他のパラメータによってフィルタリングすることができる。


### Specs

In a single-line list, each tile contains a single line of text. The amount of text can vary between tiles within the same list.

単一行のリストで、各タイルは、1行のテキストが含まれています。テキストの量は、同じリスト内のタイルの間で変化し得る。

In a two-line list, each tile contains a maximum of two lines of text. The amount of text can vary between tiles within the same list.

2行のリストで、各タイルは、2行のテキストの最大が含まれています。テキストの量は、同じリスト内のタイルの間で変化し得る。

In a three-line list, each tile contains a maximum of three lines of text.

The amount of text can vary between tiles within the same list.

3行のリストで、各タイルは、3行のテキストの最大が含まれています。

テキストの量は、同じリスト内のタイルの間で変化し得る。

#### Single-line list

#### Text only

Font: Roboto Regular 16sp
Tile height: 48dp
Text padding, top: 16dp
Text padding, bottom: 20dp

Bottom padding is measured from the baseline.

Add 8dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

底のパディングは、ベースラインから測定される。

リストの上部と下部に8DPパディングを追加します。サブヘッダーが独自のパディングが含まれているため、一つの例外は、サブヘッダーでリストの最上位に位置する。

#### Icon with text

Font: Roboto Regular 16sp
Tile height: 56dp
Icon padding, left: 16dp
Text padding, left: 72dp
Text padding, top: 16dp
Text padding, bottom: 20dp

Bottom padding is measured from the baseline.

Add 8dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

底のパディングは、ベースラインから測定される。

リストの上部と下部に8dpパディングを追加します。サブヘッダーが独自のパディングが含まれているため、一つの例外は、サブヘッダーでリストの最上位に位置する。

#### Avatar with text

Font: Roboto Regular 16sp
Tile height: 56dp
Left avatar padding: 16dp
Text padding, left: 72dp
Text padding, top: 20dp
Text padding, bottom: 24dp

Bottom padding is measured from the baseline.

Add 8dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

底のパディングは、ベースラインから測定される。

リストの上部と下部に8DPパディングを追加します。サブヘッダーが独自のパディングが含まれているため、一つの例外は、サブヘッダーでリストの最上位に位置する。

#### Avatar with text and icon

Font: Roboto Regular 16sp
Tile height: 48dp
Left avatar padding: 16dp
Text padding, left: 72dp
Text padding, top: 20dp
Text padding, bottom: 24dp

Bottom padding is measured from the baseline.

底のパディングは、ベースラインから測定される。

Right icon padding: 16dp

Add 8dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

リストの上部と下部に8DPパディングを追加します。サブヘッダーが独自のパディングが含まれているため、一つの例外は、サブヘッダーでリストの最上位に位置する。


#### Two-line list

#### Text only

Primary text font: Roboto Regular 16sp
Secondary text font: Roboto Regular 14sp
Tile height: 72dp
Text padding, left: 16dp
Text padding, top and bottom: 20dp

Bottom padding is measured from the baseline.

Add 8dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

底のパディングは、ベースラインから測定される。

リストの上部と下部に8DPパディングを追加します。サブヘッダーが独自のパディングが含まれているため、一つの例外は、サブヘッダーでリストの最上位に位置する。

#### Icon with text

Primary text font: Roboto Regular 16sp
Secondary text font: Roboto Regular 14sp
Tile height: 72dp
Left icon padding: 16dp
Text padding, left: 72dp
Text padding, top and bottom: 20dp

Bottom padding is measured from the baseline.

Add 8dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

底のパディングは、ベースラインから測定される。

リストの上部と下部に8DPパディングを追加します。サブヘッダーが独自のパディングが含まれているため、一つの例外は、サブヘッダーでリストの最上位に位置する。

#### Avatar with text

Primary text font: Roboto Regular 16sp
Secondary text font: Roboto Regular 14sp
Tile height: 72dp
Left avatar padding: 16dp
Text padding, left: 72dp
Text padding, top and bottom: 20dp

Bottom padding is measured from the baseline.

Center-align icon with text area.

Add 8dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

底のパディングは、ベースラインから測定される。

テキスト領域と中央揃えアイコン。

リストの上部と下部に8DPパディングを追加します。サブヘッダーが独自のパディングが含まれているため、一つの例外は、サブヘッダーでリストの最上位に位置する。

#### Avatar with text and icon

Primary text font: Roboto Regular 16sp
Secondary text font: Roboto Regular 14sp
Tile height: 72dp
Left avatar padding: 16dp
Text padding, left: 72dp
Text padding, top and bottom: 20dp

Bottom padding is measured from the baseline.

底のパディングは、ベースラインから測定される。

Right icon padding: 16dp

Add 8dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

#### Three-line list

#### Text only

Primary text font: Roboto Regular 16sp

Secondary text font: Roboto Regular 14sp
Tile height: 88dp
Text padding, left: 16dp
Text padding, top: 16dp
Text padding, bottom: 20dp

Bottom padding is measured from the baseline.

Add 8dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

底のパディングは、ベースラインから測定される。

リストの上部と下部に8DPパディングを追加します。サブヘッダーが独自のパディングが含まれているため、一つの例外は、サブヘッダーでリストの最上位に位置する。

#### Icon with text

Primary text font: Roboto Regular 16sp
Secondary text font: Roboto Regular 14sp
Tile height: 88dp
Left icon padding: 16dp
Text left padding: 72dp
Text padding, top: 16dp
Text padding, bottom: 20dp

Bottom padding is measured from the baseline.

Top-align icon with primary text.

Add 8dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

底のパディングは、ベースラインから測定される。

プライマリテキストを持つトップ整列アイコン。

リストの上部と下部に8DPパディングを追加します。サブヘッダーが独自のパディングが含まれているため、一つの例外は、サブヘッダーでリストの最上位に位置する。

#### Avatar with text

Primary text font: Roboto Regular 16sp
Secondary text font: Roboto Regular 14sp
Tile height: 88dp
Left avatar padding: 16dp
Left text padding: 72dp
Text padding, top: 16dp
Text padding, bottom: 20dp

Bottom padding is measured from the baseline.

Top-align avatar with primary text.

Add 8dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

底のパディングは、ベースラインから測定される。

プライマリテキストを持つトップアラインアバター。

リストの上部と下部に8DPパディングを追加します。サブヘッダーが独自のパディングが含まれているため、一つの例外は、サブヘッダーでリストの最上位に位置する。

#### Avatar with text and icon

Primary text font: Roboto Regular 16sp
Secondary text font: Roboto Regular 14sp
Tile height: 88dp
Left avatar padding: 16dp
Text left padding: 72dp
Text padding, top: 16dp
Text padding, bottom: 20dp

Bottom padding is measured from the baseline.

Right icon padding: 16dp

Top-align avatar and icon with primary text.

Add 8dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

トップアラインアバターとプライマリテキストとアイコン。

リストの上部と下部に8DPパディングを追加します。サブヘッダーが独自のパディングが含まれているため、一つの例外は、サブヘッダーでリストの最上位に位置する。

リストの上部と下部に8DPパディングを追加します。サブヘッダーが独自のパディングが含まれているため、一つの例外は、サブヘッダーでリストの最上位に位置する。