Accessibility
===

A product is accessible when all people -- regardless of ability -- can navigate it, understand it, and use it to achieve their goals. A truly successful product is accessible to the widest possible audience.

それをナビゲートし、それを理解し、それぞれの目標を達成するためにそれを使用することができ、すべての人が - 能力に関係なく -時に製品がアクセス可能である。真に成功した製品はできるだけ広い聴衆にアクセス可能である。

These general guidelines are a good starting point for designers who want to learn about accessibility. Designing fully accessible products is a complex topic that requires in-depth study. For more info, visit: https://www.google.com/accessibility/building.

これらの一般的なガイドラインは、アクセシビリティについて学びたいデザイナーのための良い出発点である。完全にアクセシブルな製品を設計することは、綿密な研究を必要とする複雑なトピックです。詳細情報については：https://www.google.com/accessibility/building

To ensure that your product is usable for users with disabilities, consider how users will interact with your product using assistive technologies. Imagine using your product in the following ways:

お使いの製品が障害を持つユーザーのために使用可能であることを保証するために、ユーザーがあなたの製品が支援技術を使用して相互作用するかを検討します。次の方法で製品を使用して想像してみてください

* Without sound
* Without color
* With the high contrast mode enabled
* With the screen magnified
* With a screen reader (no visible screen)
* With voice control only
* With a combination of the above

### Navigation

#### Help users to be fast and efficient

How easy is it to navigate the page quickly and efficiently (e.g. jumping to key sections or getting back to primary navigation)? Present the most important information first. Small changes, like bringing a “create" button to the top, can make navigation much faster.

それは（例えば、キーのセクションにジャンプまたはプライマリナビゲーションに戻ること）迅速かつ効率的にページを移動する方法は簡単です？最初の最も重要な情報を提示する。小さな変化は、先頭に「作成」ボタンをもたらすように、はるかに高速にナビゲーションを行うことができます。

Make touch targets at least 48 x 48 pixels

The recommended minimum touch target size for any on-screen element is 48 x 48 (px, dp). Check how much space is between the elements of your mobile design. In most cases, it should be 8dp or more.

どの画面上の要素のために推奨される最小のタッチターゲットサイズは48×48（px、dp）である。お使いの携帯デザインの要素の間でどのくらいのスペースを確認してください。ほとんどの場合、それは8dp以上であるべきである。

#### Support mouse-free and standard gesture navigation

Are all parts of the design, including every user task and use case, keyboard-accessible on web interfaces and accessible with the basic interaction gestures on mobile devices? Blind users can’t use a mouse to explore your interface in a visual way. Instead they will use their keyboard to navigate or swipe through elements on their mobile devices. Ensure that mouseover information is also accessible to users who don’t use a mouse. Keyboard shortcuts should be consistent with platform standards.

キーボードでアクセス可能なモバイルデバイス上の基本的な相互作用のジェスチャーを使用してWebインターフェイスでアクセス可能すべてのユーザータスクとユースケースなど、設計のすべての部分は、ありますか？視覚障害者は、視覚的な方法であなたのインターフェイスを探索するために、マウスを使用することはできません。代わりに彼らは、モバイルデバイス上の要素をナビゲートまたはスワイプために彼らのキーボードを使用します。そのマウスオーバー情報もマウスを使用しないユーザーにアクセス可能であることを確認してください。キーボードショートカットは、プラットフォームの標準と整合的であるべきである。

#### Manage the focus of your user

Are you sure that your user and their focus never get lost when navigating between dropdowns, alerts and various screens? Think about how users will return to a screen after closing a dropdown window. Make sure that their focus will return to where it was before the dropdown opened.

あなたがドロップダウン、アラートや各種画面間を移動するとき、ユーザーとそのフォーカスが決して失われることはありません飽きていることを確認していますか？ユーザーがドロップダウンウィンドウを閉じた後の画面に戻ります方法を考えてみてください。彼らの焦点はドロップダウンが開かれる前にそれがあった場所に戻ることを確認してください。

### Readability

#### Ensure your app is still usable with larger font sizes

Is the text still legible when a user magnifies the screen or enlarges the font? Are the essential elements still visible, usable, and not overlapping? See it for yourself by using any of the built-in OS/Browser/App accessibility tools for zooming and viewing large fonts.

ユーザが画面を拡大またはフォントを拡大すると、テキストはまだ読みやすいですか？本質的な要素が重なった、目に見える使用可能ではなく、まだありますか？のいずれかを使用して自分自身でそれを参照してください内蔵のOS/ブラウザ/アプリケーションアクセシビリティツールの大きなフォントをズームして表示する。

#### Ensure critical text has enough contrast

In most cases, “sufficient contrast” means having a contrast ratio of 4.5:1. Enough contrast between the background and the text or critical elements allows all users, and particularly those with poor vision, to read text more easily. Smaller text needs lots of contrast, while big headings can tolerate a wider range of colors and backgrounds.

ほとんどの場合、「十分なコントラストが「4.5:1のコントラスト比を有することを意味する。背景とテキストまたは重要な要素の間に十分なコントラストが、すべてのユーザを可能にし、貧しい人々のビジョンを持つ特に、より簡単にテキストを読む。大きな見出しが色や背景の広い範囲を許容することができるしながら、小さいテキストは、コントラストの多くを必要とします。

#### Use more than just color to convey information

This is especially crucial for all color blind users. If colors in the design communicate specific information (e.g., visualizing traffic: red = high traffic, green = no traffic), it is important to offer an alternate way for the user to get the same information. In addition to using color, add other elements like shapes,  patterns, texture, or text.

これは、すべての色盲ユーザーにとって特に重要です。デザインの色は特定の情報（例えば、可視化するトラフィック：赤=高トラフィック、緑=なしトラフィック）で通信する場合は、ユーザーが同じ情報を取得するための代替方法を提供することが重要です。色を使用することに加えて、形状、パターン、テクスチャ、またはテキストのような他の要素を追加する。

#### Provide clues about spatial relationships

Is any information conveyed spatially or in the layout that wouldn't be apparent to a blind user who navigates one element at a time? Since assistive technologies don't indicate the distance between elements, provide some additional clues about how elements are related, like sharing a common heading.

すべての情報は、空間や時間に一つの要素をナビゲートする盲目のユーザには明らかではないレイアウトで搬送されていますか？支援技術が要素間の距離を示すものではありませんので、要素が共通の見出しを共有するように、どのように関連しているかについてのいくつかの追加の手がかりを提供する。

#### Give visual alternatives to sound

If you have audio elements, do you provide closed captions, a transcript, or another visual alternative? This guideline also applies to system alert sounds. Any flashing or blinking needs to be translated into a sound, and vice versa.  

あなたがオーディオの要素を持っている場合は、クローズドキャプション、トランスクリプト、または他の視覚的な代替手段を提供していますか？このガイドラインはまた、システムの警告音に適用されます。任意の点滅または点滅ニーズが、その逆の音に変換することができます。

### Guidance and feedback

#### Make interactive controls clear and discoverable

Do all interactive controls have associated text labels, tooltips, or placeholder text to indicate their purpose? Are you consistent in your terminology throughout the entire app? Provide the most relevant information first to the assistive technologies. When naming elements, make sure you're consistent in your terminology throughout your app.

すべてのインタラクティブなコントロールは、その目的を示すために、テキストラベル、ツールチップ、またはプレースホルダーテキストが関連付けられていますか？あなたは全体のアプリを通じて、あなたの用語では一貫している？支援技術に最初に最も関連性の高い情報を提供します。要素に名前を付けるとき、あなたはあなたのアプリケーション全体であなたの用語では一貫していることを確認してください。

#### Provide alternative text for images and video

Are you relying on graphical elements to convey information that isn't also provided in a written format? Do labels provide sufficient semantic context for the task (e.g., not just "download" but "download dinner menu")? Provide alternative text for all images and icons, and avoid using images of text in cases where a standard widget would work.

あなたはまた、書かれた形式で提供されていない情報を伝えるためにグラフィカルな要素に依存している？ラベルは、タスク（例えば、だけではなく、「ダウンロード」ではなく「ダウンロードディナーメニュー」）のための十分なセマンティックコンテキストを提供していますか？すべての画像やアイコン用の代替テキストを提供し、標準のウィジェットが動作する場所の場合で、テキストの画像を使用しないでください。

#### Offer guidance and help

Can the user find help quickly when they do not know what an element means? If a critical element times out, is there a way for the user to reactivate it? Include clear and easy-to-find help and provide contextual help so that the user can look up what keyboard shortcuts or gestures are available and how to access and use features.

ユーザーは要素が何を意味するのか分からないときに迅速に役立つ見つけることができますか？外の重要な要素回あれば、ユーザーはそれを再度アクティブにするための方法はありますか？インクルード明確かつ簡単に見つける助けをし、ユーザーがショートカットやジェスチャーが利用可能であり、どのようにアクセスし、利用機能にどのようなキーボード検索できるようにコンテキストヘルプを提供します。

#### Give meaning to links

Is the purpose of each link clear? Put the purpose of the link in the link text itself. Generic anchor text like “click here” does not serve this purpose. A better solution is a concrete link, like “Device settings." Some assistive technology modes make navigation more efficient by letting the user scan just the links, ignoring other content.

各リンクの目的は明確ですか？リンクテキスト自体にリンクの目的を置く。ジェネリックアンカーテキストは次のように「ここをクリック」この目的を果たすません。よりよい解決策のような具体的なリンクであり、「デバイス設定。"いくつかの支援技術モードが他のコンテンツを無視して、ユーザーのスキャンにだけリンクさせることにより、ナビゲーションをより効率的にする。