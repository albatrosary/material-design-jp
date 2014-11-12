Bidirectionality
===

A well-designed app supports bidirectionality, which means that it can be localized easily for language scripts that are written and read from right-to-left (RTL) or left-to-right (LTR). RTL scripts include Arabic, Hebrew, and Persian.

うまく設計されたアプリは、それが読み書き右から左（RTL）から、または左から右（LTR）されている言語スクリプトのために簡単にローカライズできることを意味し、双方向性をサポートしています。 RTLスクリプトはアラビア語、ヘブライ語、ペルシャ語が含まれる。

Bidirectionality affects not only text but also layout and iconography.

双方向性のみならず、テキストだけでなく、レイアウトや図像に影響を与えます。

### UI mirroring overview

The main difference between RTL and LTR interfaces is the direction of time. For speakers of languages that use RTL scripts, time moves from right to left. These users expect the UI to flow from right to left to accurately reflect the direction of time.

RTLとLTRインターフェース間の主な違いは、時間方向である。 RTLスクリプトを使用する言語の話者のために、時間が右から左に移動します。これらのユーザーは、UIは正確に時間方向を反映するために、右から左に流れるように期待しています。

Mirroring—changing the UI from LTR to RTL or vice-versa—includes both the layout of the app and graphical elements.
An RTL layout is the mirror image of the LTR layout. Icons are to the right of text fields. The navigation buttons are in reverse order, with the back button on the right side.

RTL以降にLTRからUIをミラーリング変化のアプリとグラフィカル要素のレイアウトの両方をその逆-含まれています。
RTLレイアウトはLTRレイアウトの鏡像である。アイコンがテキストフィールドの右側にある。ナビゲーションボタンは、右側の[戻る]ボタンで、逆の順序である。

Icons that hint at a specific direction, like the speaker icon, are mirrored. Other icons, such as a camera and a check mark, remain unmirrored intentionally.

特定の方向をほのめかすアイコンは、スピーカーのアイコンのように、ミラーリングされます。カメラやチェックマークのような他のアイコンは、意図的にミラー化されていないままである。

### RTL mirroring guidelines

Follow these guidelines for mirroring text, layout, and iconography to support right-to-left UIs.

The guiding principle for RTL interfaces is that time moves from right to left. Forward points to the left, backwards points to the right.

The most important icons for mirroring are back and forward buttons.

UIを左右からサポートするために、テキスト、レイアウト、および図像をミラーリングするため、以下のガイドラインに従ってください。

RTLインターフェイス用の指導原理は、右から左にその時間に移動している。左のフォワード·ポイント、右に後方ポイント。

ミラーリングのための最も重要なアイコンが後方と前方のボタンです。

#### When to mirror

Back and forward navigational buttons are reversed.

戻ると前方ナビゲーションボタンが逆になっている。

An icon that shows forward movement should be mirrored.

前方への移動を示しているアイコンがミラーリングされるべきである。

Other things are more subtle. For example, a icon that represents a setting uses a slash through the icon to indicate the off state. In an LTR interface, the slash goes from top left to bottom right. In an RTL interface, the slash goes from top right to bottom left.

他のものはより微妙である。たとえば、設定を表すアイコンはオフ状態を示すために、アイコンを通してスラッシュを使用しています。 LTRインターフェイスでは、スラッシュが左上から右下に行く。 RTLインターフェイスでは、スラッシュが左下に右上から行く。

A volume icon with a slider at its right side should be mirrored. The slider should progress RTL, and the sound waves should emerge from the right.

その右側にあるスライダーで音量アイコンがミラーリングされるべきである。スライダーは、RTLを進めるべきであり、音の波が右から出てくるはずです。

Icons of people, heads, or faces should typically mirror, especially if they appear close to text. This is so the people face forward, towards the text, instead of backward, shying away from the text.

人、頭、または顔のアイコンは、典型的にはそれらをテキストに近い表示されている場合は特に、ミラーリングする必要があります。人々はテキストに向かって、前向きので、これは離れてテキストから尻込み、代わりに後方です。

This can sometimes be very subtle, as with an angled or slightly turned face, or a grouping of faces.

これは時々、傾斜、またはわずかになった顔、または顔のグループ分けと同じように、非常に微妙なことができます。

Sometimes, both the horizontal and circular direction of time are implied in an icon. For example, the redo and undo buttons in Google Docs have both a horizontal direction and a circular direction.

時には、時間の両方の水平および円周方向は、アイコンに暗示されている。たとえば、REDOログとは、Googleドキュメント内のボタンは、水平方向と円周方向の両方を持って元に戻す。

In LTR, these point to the same direction in both circular and horizontal representations of time. In RTL, choose whether to show circular or horizontal direction.

LTRでは、時間の円形と水平の表現の両方で同じ方向にこれらのポイント。 RTLで、円形または水平方向を表示するかどうかを選択。

Icons that contain representations of text need careful mirroring.

Text is right-aligned in RTL. If there is a paragraph indent at the beginning of a paragraph, an unfinished line at the end of the paragraph, or a ragged right side, the icons need to be mirrored.

テキストの表現が含まれているアイコンは、慎重なミラーリングを必要としています。

テキストは右揃えRTLである。段落、段落、または不揃い右側の終わりに、未完成の行の先頭の段落インデントがある場合は、アイコンがミラーリングされる必要がある。

#### When not to mirror

While the linear representation of time is mirrored in RTL, the circular direction of time is not. Clocks still turn clockwise for RTL languages. A clock icon or a circular refresh or progress indicator with an arrow pointing clockwise should not be mirrored.

時間の線形表現はRTLでミラーリングされている間、時間の円形向きではありません。クロックは依然としてRTL言語用時計回りに回します。時計アイコンや矢印を時計回りの円形リフレッシュまたは進行インジケータがミラーリングされるべきではない。

Some icons refer to physical objects that are not mirrored in the right-to-left world.

For example, physical keyboards look the same everywhere in the world, so they should not be mirrored.

一部のアイコンは、右から左への世界に反映されていない物理オブジェクトを参照してください。

例えば、物理的なキーボードは、世界でもどこでも同じに見えるので、彼らはミラー化するべきではありません。

Certain icons might seem directional but they actually represent holding an object with one’s right hand.

For example, the search icon typically has its handle at the bottom right side, because the majority of users are right-handed.

The majority of users in RTL-writing countries are also right-handed, so such icons should not be mirrored.

特定のアイコンが、方向性に思えるかもしれないが、彼らは実際に自分の右手を持つオブジェクトを保持して表す。

大多数のユーザーが右利きであるため、例えば、検索アイコンは、典型的には、右下のハンドルを有している。

RTL-書き込みの国におけるユーザーの大半も、右利きなので、そのようなアイコンがミラー化されるべきではない。

Media playback buttons and the progress indicator are not mirrored. The LTR direction of these elements represents the direction of the tape, not the direction of time.


メディア再生ボタンとプログレスインジケータがミラーリングされていない。これらの要素のLTR方向がテープの方向ではなく、時間方向を表す。

### Other localization considerations

While considering bidirectionality in app design, think also about other factors for localized apps.

アプリのデザインの双方向性を考慮しながら、ローカライズされたアプリケーションのための、他の要因についても考える。

Because text in graphical elements will always require localization, try to convey concepts in ways that don’t use text.

グラフィック要素内のテキストは常にローカライズが必要になりますので、テキストを使用しない方法で概念を伝えるようにしてください。

Numbers are also text. Icons containing numbers must be localized for languages that use different numerals. For example, Bengali, Marathi, Nepali, and most Arabic locales use different forms of numbers. An icon containing these numerals would have to be redrawn to accommodate their shape.

数字もテキストです。数字を含んだアイコンは異なる数字を使用する言語にローカライズされている必要があります。たとえば、ベンガル語、マラーティー語、ネパール語、およびアラビア語のほとんどのロケールは、数値の異なる形式を使用しています。これらの数字を含んでいるアイコンは、その形状に対応するために再描画しなければならないであろう。

Context matters; mirroring may be needed even for LTR locales. For example, if one is editing an RTL paragraph inside an English document in an English UI in Google Docs, the buttons for numbered and bulleted lists, and indent and unindent should be mirrored to suit RTL even though the primary UI direction is LTR.

コンテキスト事項；ミラーリングはあっても、LTRロケールのために必要とされるかもしれない。一つはGoogleドキュメントで英語UIの英語文書内のRTL段落を編集している場合は、番号付き箇条書きリスト、インデントやインデント解除用のボタンは、プライマリUI方向がLTRであっても、RTLに合わせてミラーリングする必要があります。