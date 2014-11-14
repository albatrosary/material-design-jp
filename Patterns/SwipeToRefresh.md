Swipe to refresh
===

### Swipe to refresh

#### Updating content

There are two methods for updating content in an app. The preferred method is to automatically update content using sync. Syncing is a process by which an app periodically and automatically keeps its content seamlessly up to date, so users always have the freshest content. Syncing is preferred because it doesn’t require user action, and users have the confidence that they’re always looking at the most recent content.

アプリ内のコンテンツを更新するための2つの方法があります。好ましい方法は、自動的に同期を使用してコンテンツを更新することである。同期は、ユーザーが常に最新のコンテンツを持っているので、アプリは定期的かつ自動的に、シームレスに最新の内容を保持するプロセスです。それはユーザーのアクションを必要としないため、同期が好ましく、ユーザーは常に最新のコンテンツを見ていることを自信を持っている。

The other method for updating content is to use a manual refresh. Refresh requires users to initiate content updates via an action or a swipe to refresh gesture. Refresh can be used to supplement syncing, for example, when checking for new mail in a Gmail account, or updated notifications in Google+. An explicit refresh action enables users to refresh content while maintaining their current scroll position.

コンテンツを更新するための他の方法は、手動でリフレッシュを使用することです。リフレッシュはアクションやジェスチャーをリフレッシュするスワイプを介してコンテンツの更新を開始するために、ユーザーが必要となります。リフレッシュは、例えば、同期を補足するために使用することができ、Gmailアカウントの新しいメール、またはGoogle+の中で更新された通知のためにチェックするとき。明示的なリフレッシュ動作は、彼らの現在のスクロール位置を維持しながら、コンテンツを更新することを可能にします。

#### Swipe to refresh

Swipe to refresh is a swipe gesture available at the beginning of lists, grid lists, and card collections where the most recent content appears (Index 0). Typically, this gesture is available at the top of content collections, but it can also be at the bottom (for example, in chat applications). It’s best to utilize this gesture with dynamic content that has frequent updates and that emits from a consistent location, where users have a high probability of seeing new content after initiating the gesture.

リフレッシュするスワイプリスト、グリッド、リスト、および最新のコンテンツが表示され、カードのコレクション（インデックス0）の開始時に利用可能なスワイプジェスチャです。典型的には、このジェスチャーは、コンテンツコレクションの上部に利用可能であるが、それはまた、（チャット·アプリケーションなどで）一番下にあることができる。これは、頻繁に更新があり、動的コンテンツを含む、このジェスチャーを利用するのがベストです、それは、ユーザーがジェスチャーを開始した後、新しいコンテンツを見ての高い確率を持って一貫性のある場所から放出する。

Be aware that changes may not be immediately obvious to users when the swipe to refresh gesture is used in applications and views that can change significantly or are completely replaced upon refresh. For example, the refresh may non-sequentially delete, reorder, modify, and insert items or only change off-screen items.

ジェスチャーをリフレッシュするスワイプを大幅に変更することができ、または完全リフレッシュの際に交換されているアプリケーションとビューで使用される場合の変更はユーザーにすぐに明らかではないことに注意してください。例えば、リフレッシュは、非順次、削除、並べ替え、変更、およびアイテムを挿入するかだけをオフスクリーンの項目を変更することがあります。

#### Refresh indicator positioning and behavior

The refresh indicator resting position is always centered horizontally relative to the refreshing content.

リフレッシュインジケータ静止位置は常に爽やかコンテンツに対して水平方向にセンタリングされている。

The refresh indicator resting position is always located near the top of the refreshing content.

The y-axis resting position of the refresh indicator can be adjusted so that its location is visually harmonious with the underlying layout. For example, the indicator may fall on a material edge or grid line, but it should always be near the top of the refreshing content.

リフレッシュインジケータ休ん位置は常にさわやかコンテンツの上部付近に位置しています。

その位置は、基礎となるレイアウトで視覚的に調和しているように、リフレッシュ·インジケータのy軸の静止位置を調整することができる。例えば、インジケータは材料エッジまたはグリッドライン上に落ちるかもしれないが、それは常に爽やかコンテンツの上部付近でなければなりません。

The refresh indicator remains visible until the refresh activity completes and any new content is visible, or the user navigates away from the refreshing content.

The refresh indicator appears only in conjunction with a refresh gesture or action. Sync does not display a refresh indicator.

リフレッシュアクティビティが完了し、新しいコンテンツが表示されている、またはユーザーが離れてさわやかなコンテンツから移動するまでリフレッシュインジケータが表示されたまま。

リフレッシュインジケータのみリフレッシュジェスチャーやアクションと連動して表示されます。 Syncはリフレッシュインジケータを表示しません。

#### Refresh indicator transitions

When another surface is positioned in z-space above the material containing the refreshing content, the refresh indicator translates from underneath the surface and is clipped until it is fully visible.

When the material containing the refreshing content is positioned in z-space either above every other surface or seamed with a coplanar surface, the refresh indicator scales up in size as it translates.

When a content refresh is initiated via an action in the app bar or overflow menu, the refresh indicator scales up in its final resting position.

別の表面はさわやかなコンテンツを含む材料上記のz空間に配置されたとき、リフレッシュインジケータは、表面の下から変換し、それが完全に表示されるまでクリップされます。

さわやかなコンテンツを含む材料をz空間内のいずれかの他のすべての面の上方に位置する、または同一面で継ぎ合わされているときに変換するように、リフレッシュ·インジケータのサイズがスケールアップ。

コンテンツリフレッシュがアプリバーまたはオーバーフローメニューの作用を介して開始されると、リフレッシュインジケータはその最終的な静止位置にスケールアップ。

#### Implementation details

As the refresh indicator translates and/or scales into view, the circular spinner fades in while rotating.

To ensure users intentionally initiate a refresh using the swipe to refresh gesture, the refresh indicator must pass a threshold before the app will begin to refresh. This threshold is indicated through a number of cues: the circular spinner reaches 100% opacity, the rotation of the circular spinner slows down, and the rate of translation of the refresh indicator slows down.

Completing the gesture at any point after passing the threshold will initiate the refresh action.

Reversing the gesture past the threshold will cancel the initiation of the refresh action.

リフレッシュインジケーターが翻訳し、および/またはビューにスケールとして、円形スピナーは回転しながらフェードイン。

アプリがリフレッシュするために開始されます前に、ユーザーが意図的にジェスチャーをリフレッシュするためにスワイプを使ってリフレッシュを開始することを確認するために、リフレッシュインジケータがしきい値を渡す必要があります。このしきい値はキューの数まで表示されます：円形スピナーは円形スピナーの回転が遅くなり、100％の不透明度に達し、リフレッシュインジケータの翻訳速度は遅くなります。

しきい値を通過した後の任意の時点でのジェスチャーを完了すると、リフレッシュ動作を開始します。

しきい値を超えてジェスチャーを逆にすると、リフレッシュ動作の開始をキャンセルさせていただきます。