Principles
===

Material design uses fundamental tools that have come from the world of print design, like baseline grids and a common set of structural grids that work across various pages. The layout is designed to scale across different screen sizes and will help facilitate UI development and ultimately help you create scalable apps.

マテリアル設計は、ベースライングリッドと様々なページにまたがって機能する構造グリッドの共通セットのように、プリントデザインの世界から来た基本的なツールを使用しています。レイアウトは全体で異なる画面サイズを拡張できるように設計されており、UI開発を容易にするのに役立ちますし、最終的にスケーラブルアプリを作成するのに役立ちます。

The layout guidelines also encourage apps to have a consistent look and feel by using the same visual elements, structural grids, and general spacing rules across platforms and screen sizes. Structural and visual consistency creates an environment for the user that is recognizable across products, which provides users with a high level of familiarity and comfort.

レイアウトのガイドラインにも一貫性のある外観を持ち、同じ視覚的要素、構造グリッド、プラットフォームや画面サイズ全体で一般的なスペーシングルール使用して感じるようにアプリを奨励します。構造的および視覚的な一貫性は、親しみやすさと快適さの高レベルをユーザーに提供し、認識全体での製品であるユーザーのための環境を作成します。

Before delving into layout details, consider the rules of how the material behaves and how it is crafted.

レイアウトの詳細に掘り下げる前に、マテリアルがどのように動作し、それがどのように細工されている方法のルールを検討してください。

### Paper craft

In material design, every pixel drawn by an application resides on a sheet of paper. Paper has a flat background color and can be sized to serve a variety of purposes. A typical layout is composed of multiple sheets of paper.

マテリアル設計では、アプリケーションによって描画のすべてのピクセルは、紙のシート上に存在します。紙は、フラットな背景色を有し、様々な目的を果たすようなサイズにすることができる。典型的なレイアウトは、複数の用紙で構成されています。

The system may draw pixels for elements such as status or system bars, which don’t reside on paper. It’s helpful to think of such system elements as being printed on the back side of the display’s glass, on a surface that is separate from the app content beneath it.

このシステムは、紙の上に存在しない状況やシステムのバー、などの要素のピクセルを引いてもよい。それは、その下にアプリのコンテンツとは別の面には、ディスプレイのガラスの裏面に印刷されているものとして、このようなシステム要素を考えると便利です。

#### Arranging paper

Seams are created when two sheets of paper share the full length of a common edge. Sheets joined by a seam generally move together.

紙の2枚の共通のエッジの全長を共有する場合の継ぎ目が生成されます。シームによって接合されたシートは、一般的に一緒に移動します。

Steps are created when two sheets of paper overlap. Sheets that have different z-positions typically move independently of each other.

手順は、紙の重なりのとき2枚作成されます。異なるz軸の位置を有するシートは、典型的には互いに独立して移動します。

#### Paper toolbars

A toolbar is a strip of paper used to present actions. The actions cluster on either side of the toolbar. Navigation actions, such as a drawer menu icon or an up arrow, appear at the left, while contextual actions appear at the right.

ツールバーには、アクションを提示するために使用される紙のストリップである。アクションは、ツールバーのいずれかの側にクラスタ化します。文脈アクションが右に表示されながら、そのような引き出しメニューアイコンまたは上矢印などのナビゲーションアクションは、左側に表示されます。

The left and right actions in a toolbar are never split by another sheet of paper. However, a toolbar can constrain its width to less than the full length of its paper.

ツールバーの左右のアクションは、他の用紙で分割されることはありません。しかし、ツールバーは、その紙の全長未満にその幅を制限することができます。

Toolbars frequently form a step above another sheet of paper that displays the content that the toolbar’s actions relate to. As that sheet of paper scrolls beneath the toolbar, the toolbar clips it at the point of entry, preventing it from passing through to the opposite side.

ツールバーは、頻繁に、ツールバーのアクションはに関連するコンテンツを表示する紙の別のシート上のステップを形成する。ツールバーの下に紙の巻物のシートとしては、エントリーの時点で、ツールバーのクリップには、反対側へ通過するのを防止する。

A toolbar can also be initially presented as seamed with a second sheet of paper, but then lift to form a step. This variant of clipping is called waterfall.

ツールバーは、2枚目の用紙を継ぎとしても、最初に提示されるが、ステップを形成するために持ち上げることができる。クリッピングのこの亜種は、滝と呼ばれています。

Alternately, the toolbar can maintain its seam, pushing off the screen as the two sheets of paper move together.

代わりに、ツールバーは二枚の紙が一緒に移動すると、画面をオフにプッシュする、その継ぎ目を維持することができる。

Finally, the second sheet can cover the toolbar as it moves.

最後に、それが動くように、第2のシートは、ツールバーをカバーすることができます。

Toolbars have a standard height, 56 dp on mobile and 64 dp on desktop, but they can be taller. When taller, the actions can be pinned to either the top or the bottom of the toolbar.

ツールバーは、標準的な高さが、携帯電話で 56dpと、デスクトップ上の 64dp を持っているが、それらは高さを高くすることができます。ときは高くアクションはトップまたはツールバーの一番下のどちらかに固定することができます。

Toolbars can change height dynamically once they become pinned. When resizing, they snap incrementally.

ピンになったら、ツールバーは動的に高さを変更することができます。サイズを変更する場合、段階的にスナップします。

#### Floating actions

A floating action is a circular sheet of paper separate from a toolbar.

A floating action represents a single promoted action. A floating action can straddle a step if it relates to the content of the paper creating that step.

フローティング·アクションは、ツールバーとは別の紙の円形シートである。

フローティングアクションは、単一の昇格アクションを表します。それはそのステップを作成する論文の内容に関連する場合、フローティングアクションはステップをまたぐことができます。

A floating action can straddle a seam if it relates to the content of both of the papers creating that seam.

Never introduce a decorative seam merely to provide an anchoring point for an action.

それがその継ぎ目を作成する論文の両方の内容に関連する場合、フローティングアクションは継ぎ目をまたぐことができます。

決して行動のためのアンカーポイントを提供するために、単に装飾的な縫い目を導入しない。


