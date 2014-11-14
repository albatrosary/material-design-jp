Tabs
===

Tabs make it easy to explore and switch between different views or functional aspects of an app or to browse categorized data sets.

タブは探検し、異なるビューやアプリの機能的側面との間で切り替えたり、分類されたデータセットを閲覧することが簡単になります。

### Usage

A tab provides the affordance for displaying grouped content. A tab label succinctly describes the tab’s associated grouping of content.

タブには、グループ化されたコンテンツを表示するためのアフォーダンスを提供しています。タブのラベルは簡潔にコンテンツのタブの関連するグループ化を説明しています。

#### Mobile tabs

#### Desktop tabs

#### When to use

Use tabs to organize content at a high level, for example, presenting different sections of a newspaper. Don’t use tabs for carousels or pagination of content. Those use cases involve viewing content, not navigating between groups of content.

For more detail about using tabs for navigating top-level views, see “Top-level view strategies” in Layout > Structure > UI Regions and Guidance.

新聞の異なるセクションを提示、例えば、ハイレベルでコンテンツを整理するには、タブを使用してください。カルーセルまたはコンテンツの改ページ用のタブを使用しないでください。これらのユースケースは、コンテンツのグループ間を移動しない、視聴コンテンツを含む。

トップレベルのビューをナビゲートするためのタブを使用する方法の詳細詳細については、[レイアウト]> [構造>のUI地域とガイダンスで「トップレベルのビュー戦略」を参照してください。

#### Tab characteristics

Tabs are presented as a single row.

Tabs should not be nested. Content in a tab should not consist of another set of tabbed content.

A set of tabs contains at minimum a pair of tabs and no more than six tabs.

Tabs control the display of content in a consistent location.

The tab corresponding to the visible content is highlighted.

Tabs are grouped together and the group of tabs is in turn connected with their content.

Keeping tabs adjacent to their content helps maintain the relationship between the two, as too great a separation can introduce ambiguity.

タブが単一の行として表示されます。

タブは入れ子にすることはありません。タブのコンテンツはタブ付きコンテンツの別のセットで構成されてはいけません。

タブのセットは、最小のタブのペアを超えない6つのタブが含まれています。

タブは一貫した場所にコンテンツの表示を制御します。

可視のコンテンツに対応するタブが強調表示されます。

タブはグループ化され、タブのグループは、彼らのコンテンツに接続された順番になります。

彼らのコンテンツに隣接するタブを保つことはあまりにも偉大なように分離が曖昧さを導入することができ、両者の関係を維持するのに役立ちます。

### Content

Content presented in tabs can vary widely, even between tabs. For example, different years within a tabbed portfolio or different types of settings.

All content within a set of tabs should be related under a larger organizing principle (for example, Settings or Directions), with each tab’s content mutually exclusive of the others'.

Tab labels should provide meaningful distinctions that logically organize associated content.

Tab labels may be icons or text and must not be truncated.

Avoid the need for cross-tab comparison of content; significant cross-tab comparison may indicate the content would benefit from a different organization or presentation.

タブで提示されるコンテンツであってもタブ間、広く変えることができる。タブ付きポートフォリオや設定の異なる種類の内、例えば、別の年。

タブのセット内のすべてのコンテンツが他人の相互に排他的な各タブのコンテンツで、より大きな組織の原則（例えば、[設定]または方向）の下で関連している必要があります。

タブのラベルは、論理的に関連するコンテンツを整理、意味のある区別を提供する必要があります。

タブのラベルは、アイコンまたはテキストであってもよく、切り捨ててはいけません。

コンテンツのクロスタブの比較の必要性を回避する。コンテンツを指示することができる重要なクロスタブの比較は別の組織やプレゼンテーションの恩恵を受ける。

### Types of tabs

Depending on the platform and the context of use, tabbed content can be presented as either fixed tabs or scrollable (swipeable) tabs.

プラットフォームや使用状況に応じて、コンテンツは、固定タブやスクロール可能（swipeable）のタブのいずれかとして提示することができるタブ付き。

#### Fixed tabs

Fixed tabs display all tabs concurrently and are best used with content that benefits from quick pivots between tabs, such as switching transportation methods for directions in Google Maps.

The maximum number of tabs is limited by the view’s width. Fixed tabs have equal width, based on the widest tab label. To navigate between fixed tabs, touch the tab or swipe the content area left or right.

固定タブは同時にすべてのタブを表示し、最善のようなGoogleマップでの方向について輸送方法を切り替えるなどのタブ間の迅速なピボット、恩恵を受けたコンテンツで使用されます。

タブの最大数は、ビューの幅によって制限されている。固定タブは最も広いタブのラベルに基づいて、同じ幅を持っている。 、固定タブ間を移動タブをタッチしたりスワイプするために、コンテンツエリアを左または右に。

#### Scrollable tabs

Scrollable tabs display a subset of tabs at any given moment, and can contain longer tab labels and a larger number of tabs. They are best used for browsing contexts in touch interfaces when users don’t need to directly compare the tab labels.

To navigate between scrollable tabs, touch the tab, swipe the tabs left or right, or swipe the content area left or right.

スクロール可能なタブは、任意の時点でのタブのサブセットを表示し、長タブラベルタブをより多く含有することができる。ユーザーが直接タブのラベルを比較する必要がないときには、最高のタッチインタフェースでの閲覧コンテキストのために使用される。

、タブをタッチし、スクロール可能なタブ間を移動スワイプするには、タブを左または右、またはコンテンツ領域を左または右にスワイプ。

### Specs

#### Fixed and full-screen width

Tab width: 1/3 of screen
Tab indicator: 2dp height
Text: 14sp Roboto Medium
Text is centered in the tab cell
Active text color: #fff or secondary color

Disabled text color: #fff 60%

#### Scrollable

Tab width: 12dp + word length + 12dp
Tab indicator: 2dp height
Text: 14sp Roboto Medium
Active text color: #fff or secondary color
Disabled text color: #fff 60%

#### Desktop/tablet

Tab width: 24dp + word length + 24dp
Tab indicator: 2dp height
Text: 14sp tablet, 13sp desktop Roboto Medium
Active text color: #fff or secondary color
Disabled text color: #fff 60%

#### Tab touch target animation