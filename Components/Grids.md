Grids
===

Grid lists are an alternative to standard list views. Grid lists are distinct from grids used for layouts and other visual presentations.

グリッドリストは、標準のリストビューに代わるものである。グリッドリストは、レイアウトやその他の視覚的なプレゼンテーションのために使用されるグリッドとは区別される。

### Usage

A grid list is best suited to presenting a homogenous data type, typically images, and is optimized for visual comprehension and differentiating between like data types.

グリッドリストは、均質なデータタイプ、一般的に画像を提示するに最適な、および視覚理解等のデータタイプを区別するために最適化されている。

A grid list is a continuous element consisting of tessellated, regular subdivisions called cells that contain tiles.

Cells are arrayed vertically and horizontally within the grid.

Tiles hold content and can span one or more cells vertically or horizontally.

グリッドリストは、タイルを含むセルと呼ばれるテセレーション、定期的なサブディビジョンからなる連続要素です。

細胞は、グリッド内の垂直方向及び水平方向に配列されている。

タイルは、コンテンツを保持し、垂直方向または水平方向に1つまたは複数のセルをまたがることができる。

If the text in tiles needs to be prominent enough to distinguish between primary content pieces, consider using a different container, like a list or cards, optimized for displaying text and facilitating reading comprehension.

Lists: Optimized for reading comprehension, particularly when comparing a set of data containing multiple data types.

Cards: Used for content with inconsistent formatting, such as photos with captions of variable length, or data sets with heterogeneous content, such as a mixed collection of photos and videos and books.

タイル内のテキストは、一次コンテンツピースを区別するのに十分顕著にする必要がある場合、テキストを表示し、読解を容易にするために最適化されたリストやカードのように、別のコンテナを使用することを検討してください。

リスト：複数のデータ型を含むデータセットを比較する場合は特に、読解するために最適化された。

カード：一貫性のない書式付きコンテンツに使用、など写真や動画、書籍の混合収集のような異種コンテンツを含む可変長のキャプション、またはデータセットとの写真など。

### Content

#### Content in tiles

Tile content consists of primary content and secondary content. Primary content is the main differentiating element, typically an image. Secondary content can be an action or text.

Provide a default image for tiles that lack an image for primary content.

タイルコンテンツが主要コンテンツと二次コンテンツで構成されています。主要コンテンツは、メイン微分要素、典型的には、画像である。二次コンテンツは、アクションまたはテキストとすることができる。

主要なコンテンツのための画像が欠けてタイルのデフォルトの画像を提供。

#### Actions in tiles

Actions on both primary and secondary content—such as play, zoom in, delete, or select—are immediate and typically do not result in a submenu of options (action overflow) within the grid list.

Actions can open a subsequent view, such as a card.

上のアクション、削除、ズームイン、または、コンテンツなどの遊びなどのプライマリとセカンダリの両方-選択している即時、通常グリッドリスト内のオプション（アクション·オーバーフロー）のサブメニューをもたらさない。

アクションには、そのようなカードとして、後続のビューを開くことができます。

#### Primary actions

* Fill the entire tile and therefore are not represented via icons or text.
* Are consistent throughout tiles in a specific grid. For example, the primary action for all tiles in a single grid could be to view details for an image.

* 全体のタイルを埋めるため、アイコンやテキストを経由して表現されていない。
* 特定のグリッド内のタイル全体で一貫している。例えば、単一のグリッド内のすべてのタイルを1次アクションは、画像の詳細を表示する可能性があります。

#### Secondary actions or content

* Are represented in tiles with icons or text.
* Are consistent throughout tiles in a specific grid.
* Are placed in a consistent location within the tiles of a specific grid, but that consistent location may vary between grids (at corners or edges). For example, all titles in a grid could be located at the bottom left corner.

* アイコンやテキストを持つタイルで表されます。
* 特定のグリッド内のタイル全体で一貫している。
* 特定のグリッドのタイル内で一貫場所に配置されているが、その一貫性のある場所は、（コーナーやエッジに）グリッド間で異なる場合があります。例えば、グリッド内のすべてのタイトルは、左下隅に配置することができる。

### Behavior

#### Scrolling

Grids typically scroll only vertically.

Horizontally scrolling grids are discouraged because the scrolling interferes with typical reading patterns, affecting comprehension.

Cut off grid tiles to communicate the scroll direction for content overflow.

グリッドは通常、垂直方向にのみスクロールします。

スクロールが理解に影響を与え、典型的な読書パターンに干渉するため、水平方向のスクロールグリッドは落胆している。

コンテンツオーバーフロー用のスクロール方向を伝えるために、グリッドタイルを切り取ります。

#### Gestures

Per-tile swipe actions are not permitted. Pick-up-and-move actions are discouraged.

タイルごとのスワイプアクションは許可されていません。ピックアップ·アンド·ムーブアクションが落胆している。

#### Tile filtering and sorting

Content in a grid list can be programmatically filtered or sorted by date, file size, alphabetical order, or other parameters.

The first item in the grid is positioned at the top left of the grid, and the order proceeds left to right and top to bottom.

グリッドリストの内容は、プログラムでフィルタリングや日付、ファイルサイズ、アルファベット順、または他のパラメータによって並べ替えることができます。

グリッド内の最初の項目は、グリッドの左上に位置し、順番に進み、下へ右へ、上に任されている。

#### Dimensions and resizing

Resizing a grid list causes the tiles to re-sort as horizontal space becomes available. Tiles do not scale to fill available horizontal space.

A grid list does not transform into a list when horizontal space contracts. Grid lists and lists are separate structures for emphasizing different data types. Grid lists prioritize images over text and lists prioritize text over images.

タイルをグリッドリストを引き起こすサイズを変更すると、再ソートするよう水平方向のスペースが利用可能になる。タイルは、使用可能な水平方向のスペースを埋めるためにスケーリングしない。

グリッドリストは、リストするとき、水平スペース契約に変身していません。グリッドリストとリストは、異なるデータ·タイプを強調するための別個の構造体である。グリッドリストは、テキストの上に画像を優先順位を付け、リストは画像の上に文字列に優先順位を付ける。

### Specs

#### Grid list header/footers

#### Single-line header/footer

Height: 48dp
Text padding: 16dp
Default font size: 16sp
Secondary action is flush right to the footer.

#### Two-line header/footer

Height: 68dp
Text padding: 16dp
Default font size for each line: 16sp/12sp or 14sp/14sp

#### Image-only grid list

Grid padding: 4dp

Tiles in grid lists can span multiple columns.

Carefully consider whether secondary text is needed in grid lists that use multi-column tiles, as larger tiles can develop significant empty space.

グリッドリストのタイルは、複数の列にまたがることができます。

慎重に二次テキストがより大きなタイルがかなりの空きスペースを開発することができますように、複数列のタイルを使用したグリッドリストで必要かどうかを検討してください。

#### Single-line grid list

#### Text only

Height: 48dp
Text padding: 16dp
Default font size: 16sp
Grid padding: 4dp or 1dp

#### Text with icon

Height: 48dp
Text padding: 16dp
Default font size: 16sp
Grid padding: 4dp or 1dp

The secondary action can be flush right or flush left within the footer or header.

二次アクションはフッターまたはヘッダー内のフラッシュ右または左揃えにすることができます。

#### Two-line grid list

#### Text only

Height: 68dp
Text padding: 16dp
Default font size for each line:16sp/12sp or 14sp/14sp
Grid padding: 4dp or 1dp

#### Text with icon

Height: 68dp
Text padding: 16dp
Default font size for each line: 16sp/12sp or 14sp/14sp

The secondary action can be flush right or flush left within the footer or header.

二次アクションはフッターまたはヘッダー内のフラッシュ右または左揃えにすることができます。

Grid padding: 4dp or 1dp