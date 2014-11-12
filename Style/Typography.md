Typography
===

### Roboto and Noto

Since the Ice Cream Sandwich release, Roboto has been the standard typeface on Android. Since Froyo, Noto has been the standard typeface on Android for all languages not covered by Roboto. Noto is also the standard typeface for all languages on Chrome OS.

To support all languages worldwide, Google recommends using Roboto for languages that use the Latin, Greek, and Cyrillic scripts and Noto for all other languages.

「Ice Cream Sandwich」のリリース以来、Robotoは、Android上の標準書体となっています。「Froyo」以来、「Noto」はRobotoでカバーされていないすべての言語のためにAndroid上の標準書体となっています。NotoはまたChrome OS上のすべての言語のための標準的な書体です。

世界中のすべての言語をサポートするために、Googleは他のラテン語、ギリシャ語、キリル文字などすべての言語でNotoを使用する言語のためのRobotoを使用することをお勧めします。

Roboto has been refined extensively to work across the wider set of supported platforms. It is slightly wider and rounder, giving it greater clarity and making it more optimistic.

Robotoは、サポートされているプラットフォームの広いセットにわたって動作するように広範囲に洗練されています。より明確に与えて楽観的に作り、わずかに広い領域で殆どの場所で利用可能です。

Noto’s vertical metrics are compatible with Roboto.

NotoのバーチャルメトリックはRobotoと互換性があります。

#### Language coverage

Roboto supports languages that use the Latin, Greek, and Cyrillic scripts, such as English, French, Greek, and Russian. In addition, Roboto has been extended to completely cover all Latin, Greek, and Cyrillic characters as defined in Unicode 7.0. The number of supported characters has doubled from previous releases, from about 2000 to about 4000 characters.

Noto covers all major living languages languages, including English, Greek, Russian, Arabic, Hebrew, Chinese, Japanese, and Korean (CJK), Hindi, Bengali, Georgian, Armenian, Thai, Lao, Khmer, and many others.

Robotoはラテン語、ギリシャ語、およびそのような英語、フランス語、ギリシャ語、ロシア語などのキリル文字のスクリプトを、使用する言語をサポートしています。また、Robotoは、Unicode7.0で定義されているように完全にすべてのラテン語、ギリシャ語、およびキリル文字をカバーするために拡張されました。サポートされている文字の数は約4000文字に約2000から、以前のリリースにくらべ倍増しています。

Notoは、英語、ギリシャ語、ロシア語、アラビア語、ヘブライ語、中国語、日本語、韓国語（CJK）、ヒンディー語、ベンガル語、グルジア語、アルメニア語、タイ語、ラオス語、クメール語、および他の多くを含むすべての主要な生活言語言語をカバーしています。

#### Font weights

Roboto has six weights: Thin, Light, Regular, Medium, Bold, and Black.

Robotoは6つの重みを持っています：薄型、軽量、レギュラー、ミディアム、ボールド、ブラック

Noto Sans CJK has seven weights: Thin, Light, DemiLight, Regular, Medium, Bold, and Black. The weight of Noto Sans CJK Regular is the same as Roboto Regular.

Note（日中韓）は7つの重みを持っています：シン、太字レギュラーライト、DemiLight、ミディアム、およびブラック：能登なきは7の重みを持っています。Robotoレギュラーと同じです。

Noto fonts for Thai, Devanagari, and all other major living languages have Regular and Bold weights.

Notoフォントはタイ語、デーヴァナーガリー、および他のすべての主要な生活言語で通常のものと太字を持っています。

#### Hinted fonts

Hints are the instructions embedded in a font on how to modify (distort) a glyph to look better on low-resolution displays. As a tradeoff, a hinted font consumes more space than the unhinted version.

Both Roboto and Noto have hinted and unhinted versions. Google recommends:

Use the unhinted versions on Android and on Mac OS X, which doesn’t implement hints.
Use hinted fonts on Chrome OS, Windows, and Linux.

ヒントは、低解像度のディスプレイ上でよく見えるように（歪ま）グリフを変更する方法についてフォントで埋め込まれた命令です。トレードオフとして、ぼかしたフォントがunhintedバージョンよりも多くのスペースを消費します。

RobotoとNotoの両方が示唆したunhintedバージョンです。 Googleが推奨しています。

Android上とヒントを実装していないMac OS Xでは、上のunhintedバージョンを使用してください。
使用はクロームのOS、Windows、およびLinux上でのフォントを示唆しました。

#### Font Stack

For both Android and web properties, the font stack should specify Roboto, Noto, and then sans-serif.

### Standard styles

Typographic guidelines are provided for three categories of language scripts:

* English and English-like: Latin (except Vietnamese), Greek, Cyrillic, Hebrew, Armenian and Georgian
* Tall: Language scripts that require extra line height to accommodate larger glyphs. Includes South and Southeast Asian and Middle-Eastern languages, like Arabic, Hindi, Telugu, Thai, Vietnamese.
* Dense: Language scripts that require extra line height to accommodate larger glyphs but have different metrics from tall scripts. Includes Chinese, Japanese, and Korean.

表記上のガイドラインは、言語スクリプトの三つのカテゴリーのために提供されています。

* 英語と英語に似た：ラテン語、ギリシャ語、キリル語、ヘブライ語、アルメニアとグルジア語（ベトナム語を除く）
* トール：余分な行の高さを必要とする言語のスクリプトは、より大きなグリフ文字：アラビア語、ヒンディー語、テルグ語、タイ語、ベトナム語などの南および東南アジアおよび中東の言語が含まれています。
* Dense：大きなグリフを収容するために余分な行の高さが必要ですが、背の高いスクリプトから異なるメトリックを持つ言語スクリプト。中国語、日本語、韓国語が含まれています。

#### Typographic scale & basic styles

Too many type sizes and styles at once can wreck any layout. A typographic scale has a limited set of type sizes that work well together along with the layout grid. The basic set of styles are based on a typographic scale of 12, 14, 16, 20 and 34.

一度にあまりにも多くの型のサイズとスタイルは、どのレイアウトを破壊することができます。タイポグラフィスケールはレイアウトグリッドに沿って一緒にうまく動作型のサイズの制限されたセットを持っています。スタイルの基本的なセットは、12、14、16、20及び34の印刷上のスケールに基づいています。

English-like: These sizes and styles are chosen to balance content density and reading comfort under typical usage conditions. Type sizes are specified with sp (scaleable pixels) to enable large type modes for accessibility.

英語っぽい：これらのサイズとスタイルは、一般的な使用条件の下でコンテンツ密度や読書の快適さのバランスをとるように選択される。型のサイズは、アクセシビリティのための大型のモードを有効にするには、SP（スケーラブルピクセル）で指定されています。

Tall:

* Weight: Use Regular weight, as Medium weight is unavailable in Noto. In addition, Google recommends avoiding Bold weight, based on feedback from native speakers that Bold is too heavy.

* Font size: For Title through Caption styles, font size is 1 px larger than that specified for English. For styles larger than Title, the English type size is suitable.

トール：

* 重さ：ミディアム重量はNotoでは使用できないように、通常の太さを使用してください。また、Googleは太字が重すぎるネイティブスピーカーからのフィードバックに基づいて、太字重量を回避することをお勧めします。

* フォントサイズ：キャプションのスタイルを通じてタイトルについては、フォントサイズが英語に指定された値よりも1 px 大きい。タイトルよりも大きなスタイルの場合、英語の型のサイズが適しています。

Dense:

* Weight: Since Noto CJK has seven weights that match Roboto, use the same weight settings as English.
* Font size: For Title through Caption styles, the font size is 1 px larger than that specified for English. For styles larger than Title, the English type size is suitable.

Dense:

* 重量：Noto CJK はRobotoと一致する7の重みを持っているので、英語と同じ重さ設定を使用します。
* フォントサイズ：キャプションのスタイルを通じてタイトルについては、フォントサイズが英語に指定された値よりも1 pc 大きい。タイトルよりも大きなスタイルの場合、英語の型のサイズが適しています。


English and English-like: Across form factors, text that appears in the app bar should use the Title style, Medium 20sp.

英語と英語っぽい：フォームファクタ、タイトルのスタイル、ミディアム20SPを使用する必要があり、アプリバーに表示されるテキストアクロスです。

There are certain scenarios where the larger Subhead style should be used instead of the smaller Body style. Some of those instances include when information is presented as small snippets or when titles are paired with lines of Body-styled text.

大きな小見出しのスタイルではなく、より小さなボディスタイルを使用する必要があり、特定のシナリオがあります。情報は、小さなスニペットとして提示したとき、またはそれらのインスタンスのようなものがありタイトルはボディスタイルのテキストの行とペアにされたときです。

Button style (Medium 14sp, all caps) is used for all buttons, whether they are ink or material.

ボタンのスタイル（ミディアム14sp、すべて大文字）は、それらがインクや材料であるかどうか、すべてのボタンに使用されます。

#### Basic colors & color contrast

Of course, text that is the same color as the background is hard to read. Text with too much contrast can dazzle and also be hard to read. This is especially true of light-colored text against dark backgrounds.

Text should maintain a minimum contrast ratio of at least 4.5:1 (calculated based on luminance values) for legibility. A ratio of 7:1 is preferred.

These color combinations also consider contrast ratios for users with an atypical color response.

背景が読みづらいように当然のことながら、同じ色のテキストである。あまりにも多くのコントラストのテキストは眩まし、また読みにくくなります。これは、暗い背景に明るい色のテキストの特に当てはまります。

読みやすさのために（輝度値に基づいて計算）1：テキストは、少なくとも4.5の最小コントラスト比を維持しなければならない。 7：1の比が好ましい。

これらの色の組み合わせは、また、非定型色応答を持つユーザーのためのコントラスト比を考慮してください。

#### Large type and dynamic type

For the best user experience, use dynamic type instead of relying only on smaller type sizes or allowing truncation of larger-size text.

Large type applied correctly can make apps more interesting, differentiate layouts, and help users to decode content quickly.

Dynamic type enables large type when the length of the text in a layout is unknown. Dynamic sizes are selected from a typographic scale based on available space and letter size estimates.

最高のユーザーエクスペリエンスのために、代わりに小さい型のサイズのみに依存またはより大きなサイズのテキストの切り捨てを可能にする動的な型を使用します。

アプリをより面白くするレイアウトを差別化し、ユーザーが迅速にコンテンツをデコードするために助けることができる正しく適用大型タイプです。

レイアウト内のテキストの長さが不明な場合に、ダイナミック型は大型タイプが有効になります。ダイナミックなサイズは、利用可能なスペースとレターサイズの推定値に基づいてタイポグラフィックのスケールから選択されます。


#### Line height

To achieve proper readability and appropriate pacing, line heights have been determined based on each style’s individual size and weight. Line wrapping only applies to Body, Subhead, Headline, and the smaller Display styles. All other styles should exist as single lines.

適切な読みやすさと、適切なペーシングを達成するために、行の高さは、各スタイルの個々の大きさ及び重量を基準にして決定されている。行の折り返しは、ボディ、小見出し、見出し、小さい表示スタイルに適用されます。他のすべてのスタイルは、単一のラインとして存在している必要があります。

English and English-like: see image.

英語と英語のような：画像を参照してください。

Tall:
Line height is 0.1 em larger for Body 1 and Subhead 1. In English and English-like scripts, a gap between lines is an obvious straight white space. In the tall group of scripts, this gap is not sufficient. For Body 1 and Subhead 1, which have a relatively small line height in English, the lack of space is obvious. Therefore, the gap needs to be increased to ensure a line gap that is visually similar to English-like scripts.
Very small line heights for Title and larger styles are adjusted to avoid clipping between characters with low descenders in one line and character with tall ascenders in the next line.

トール：
行の高さが0.1英語と英語に似たスクリプトで本体1と小見出し1. EMが大きく、ライン間のギャップが明らかストレートホワイトスペースである。スクリプトの背の高い群では、このギャップは十分ではない。英語で比較的小さな行の高さを有している本体1と小見出し1、については、スペースの不足が明らかである。したがって、ギャップは英語のようなスクリプトと視覚的に類似しているラインのギャップを確実にするために大きくする必要がある。
タイトルと大きなスタイルの非常に小さなラインの高さは次の行では背の高いアセンダと1行と文字で低いディセンダーと文字の間にクリッピングを回避するために調整されている。

Dense:
Line height is 0.1 em larger for all styles. CJK ideographic characters use the entire em box, while English mostly uses a portion of the em box—often the lower portion below the x-height. Therefore, the actual gap between lines is smaller for CJK when the same line height is set. To achieve the same design intention as English for CJK, the line height needs to be larger than in English.

Dense：
行の高さは、すべてのスタイルのために0.1 EM大きい。英語はほとんどのx高さ以下のEMボックス-しばしば下部の一部を使用しながら、日中韓表意文字は、全体のemボックスを使用します。同じ行の高さが設定されている場合、したがって、ライン間の実際のギャップは、CJKのために小さい。英語はCJKのため、行の高さは、英語の場合よりも大きくする必要があるのと同じ設計意図を達成する。

#### Line breaking rules/hyphenation

#### Characters and line length

Consider this advice on readability and line length from the Baymard Institute:

“You should have around 60 characters per line if you want a good reading experience. Having the right amount of characters on each line is key to the readability of your text.”

"Too wide – if a line of text is too long the user’s eye will have a hard time focusing on the text. This is because the length makes it difficult to get an idea of where the line starts and ends. Furthermore it can be difficult to continue from the correct line in large blocks of text.”

"Too narrow – if a line is too short the eye will have to travel back too often, breaking the reader’s rhythm. Too short lines also tend to stress people, making them begin on the next line before finishing the current one (hence skipping potentially important words).”

Source: “Readability: the Optimal Line Length,”

Baymard研究所の読みやすさとラインの長さに、このアドバイスを考えてみます。

あなたは良い読書体験をしたい場合は、「あなたは行あたり60文字の周りに持っている必要があります。各ライン上の文字の適切な量を持つことは、あなたのテキストの読みやすさの鍵となります。」

"あまりにも広い - 。テキストの行は、ユーザの目がテキストに焦点を当てた苦労を持つことになりますが長すぎる場合、これは長さは、それが困難なラインが始まる位置と終了位置のアイデアを得るためになっているので、さらにそれが困難な場合があります。テキストの大きなブロック内の正しい行から続行します。」

"あまりにも狭いが - 。ラインが短すぎるの目はあまりにも短い線はまたそれ故に、（現在のものを仕上げ、潜在的にスキップする前に、それらが次の行に始まること、人々を強調する傾向がある読者のリズムを壊し、あまりにも頻繁に戻って移動する必要があります重要な単語）。」

出典：“Readability: the Optimal Line Length,”

#### Tracking and kerning