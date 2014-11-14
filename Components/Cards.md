Cards
===

A card is a piece of paper that contains unique related data; for example, a photo, text, and link all about a single subject. Cards are typically an entry point to more complex and detailed information.

Cards have a constant width and variable height. The maximum height is limited to what can fit within a single view on a platform, but it can temporarily expand as needed (for example, to display a comment field).  Cards do not flip to reveal information on their back.

カードは、ユニークな関連データが含まれている一枚の紙である。例えば、すべてのシングル主題について写真、テキスト、およびリンク。カードは、一般的に、より複雑かつ詳細な情報へのエントリポイントです。

カードは、一定の幅と可変の高さを有する。最大の高さは、プラットフォーム上の単一のビュー内に収まることができるものに限定されているが、必要に応じて、一時的に（コメント欄を表示するには、たとえば）を展開することができます。カードは彼らの背中に情報を明らかにフリップはありません。

### Usage

Cards are a convenient means of displaying content composed of different types of objects. They’re also well-suited for presenting similar objects whose size or supported actions can vary considerably, like photos with captions of variable length.

カードは、異なるタイプのオブジェクトからなるコンテンツを表示する便利な手段である。彼らはまた、可変長のキャプション付きの写真のように、かなり変化することができ、その大きさやサポートされるアクション類似のオブジェクトを提示するために非常に適しています。

A card collection is a coplanar layout of cards.

カードコレクションは、カードの同一平面上のレイアウトです。

Each of these cards contains a unique data set: 
a checklist with an action, a note with an action, a note with a photo.

これらのカードはそれぞれ、一意のデータセットが含まれています：
アクションチェックリスト、アクション付きノート、写真付きノート。

Use a card layout when displaying content that:

* As a collection, comprises multiple heterogeneous data types (for example, the card collection consists of photos, movies, text, images).
* Does not require direct comparison (a user is not directly comparing images or text strings).
* Includes supporting content of highly variable length, such as comments.
* Consists of rich content or interaction, such as +1 buttons, sliders, or comments.
* Would otherwise be in a list but needs to display more than three lines of text.
* Would otherwise be in a grid list but needs to display more text to supplement the image.

コンテンツを表示するときにそのカードレイアウトを使用します。

* 収集したように、複数の異種のデータ·タイプを含む（例えば、カードコレクションは写真、動画、テキスト、画像からなる）。
* 直接比較する（ユーザが直接画像やテキスト文字列を比較していません）を必要としない。
* コメントなどの高い可変長の支持コンテンツが含まれています。
* リッチコンテンツやインタラクションのような1ボタン、スライダ、またはコメントで構成されます。
* リストにあるが、そうでなければ、以上のテキスト3行を表示する必要があるでしょう。
* そうでなければ、グリッドリストに含まれているが、画像を補完する多くのテキストを表示する必要があるでしょう。

#### Card layout guidelines

#### Typography

Body type: 14sp or 16sp
Headlines: 24sp or larger
Flat buttons: Roboto Medium, 14sp, 10sp tracking

#### Card gutters on mobile

Padding from edge of screen to card: 8dp
Gutters between cards: 8dp

#### Content padding

16dp

### Content

Card content type and quantity can vary greatly, depending on the content being expressed. Cards provide context and an entry point to more robust information and views. Don't overload cards with extraneous information or actions.

コンテンツに応じて大きく変化することができ、カードのコンテンツの種類と量は、発現される。カードは、コンテキストとより堅牢な情報·意見へのエントリポイントを提供する。余分な情報やアクションを持つカードに過負荷をかけないでください。

Place primary content at the top of the card. Use hierarchy to direct users’ attention to the most important information in the card.

カードの上部にある主なコンテンツを配置。カードの中で最も重要な情報にユーザーの注意を向けるために、階層を使用してください。

### Actions

The primary action in a card is typically the card itself.

Supplemental actions can vary from card to card in a collection, depending on the content type and expected outcome; for example, playing a movie versus opening a book. Within cards in a collection, position actions consistently.
	
カードの主なアクションは、通常、カード自体である。

補足アクションは、コンテンツの種類と期待される成果に応じて、コレクション内のカードにカードから変化することができる。例えば、本を開い対ムービーを再生する。コレクション内のカード、一貫して位置アクション内。

#### Supplemental actions

Supplemental actions within the card are explicitly called out using icons, text, and UI controls, typically placed at the bottom of the card.

UI controls placed inline with primary content can modify the view of primary content; for example, a slider to choose a day, stars to rate content, or a segmented button to select a date range.

Limit supplemental actions to two actions, in addition to an overflow menu.

カード内の補足アクションが明示的アイコン、テキストを使用して呼び出され、UIコントロールは、典型的には、カードの底部に置いた。

主なコンテンツの表示を変更することができ、一次コンテンツにインラインで配置UIコントロール。例えば、スライダーは一日を選択し、日付範囲を選択するために、コンテンツ、またはセグメント化されたボタンを評価するに主演。

オーバーフローメニューに加えて、2アクションに補足アクションを制限します。

#### Overflow menu

An overflow menu (optional) is typically placed in the upper-right corner of cards, but can be in the lower right if the placement improves content layout and legibility.

Take care not to overload an overflow menu with too many actions.

（オプション）オーバーフローメニューは、通常のカードの右上隅に配置されていますが、配置はコンテンツのレイアウトや読みやすさを向上させている場合、右下にすることができます。

あまりにも多くのアクションをオーバーフローメニューに過負荷をかけないように注意してください。

#### Considerations

Inline links within text content are strongly discouraged.

Although cards can support multiple actions, UI controls, and an overflow menu, use restraint and remember that cards are entry points to more complex and detailed information.

テキストコンテンツ内のインラインリンクが強く推奨されている。

カードは複数のアクション、UIコントロール、およびオーバーフローメニューをサポートすることができますが、拘束を使用し、カードがより複雑かつ詳細な情報へのエントリポイントであることを覚えておいてください。

### Behavior

#### Gestures

The swipe gesture on a per-card basis is supported. Card gesture behavior should be consistently implemented within a card collection.

The pick-up-and-move gesture is possible. However, consider whether it’s important for the user to be able to sort cards within the collection or if the content would be better organized with programmatic filtering/sorting.

当たりカード単位でスワイプジェスチャーがサポートされています。カードのジェスチャーの動作は一貫して、カードのコレクション内に実装されるべきである。

ピックアップ·アンド·移動ジェスチャーが可能である。しかし、コンテンツのソート/フィルタリングのプログラムとのより良い組織されるかどうユーザーがコレクション内のカードを並べ替えることができるよう、またはすることが重要だかどうかを検討します。

#### Card collection filtering, sorting, and reorganization

Card collections can be programmatically sorted or filtered by date, file size, alphabetical order, or other parameters. The first item in the collection is positioned at the top left of the collection, and the order proceeds left to right and top to bottom.

カードコレクションは、プログラムソートや日付、ファイルサイズ、アルファベット順に、または他のパラメータによってフィルタリングすることができる。コレクション内の最初の項目は、コレクションの左上に位置し、順番に進み、下へ右へ、上に任されている。

#### Scrolling

Card collections only scroll vertically. Card content that exceeds the maximum card height is truncated and does not scroll.

Cards with truncated content can be expanded, in which case the card height may exceed the maximum height of the view. In this case, the card will scroll with the card collection.

カードのコレクションは、垂直方向にのみスクロールします。最大のカードの高さが切り捨てられ超えるとスクロールしないカードの内容。

切り捨てられた内容のカードが、その場合、カードの高さは、ビューの最大高さを超えることがあり、拡大することができる。この場合、カードは、カードコレクションにスクロールする。

#### Card focus

For interfaces dependent upon sequential focus traversal for navigation (DPad, keyboard), individual cards should either have only a primary action or open a new view with the primary and supplemental actions available.

ナビゲーションのためのシーケンシャルフォーカストラバーサルに依存インタフェース（DPad、キーボード）の場合は、個々のカードのいずれかのみをプライマリアクションを持っているか、利用可能なプライマリおよび補足アクションを持つ新しいビューを開く必要があります。