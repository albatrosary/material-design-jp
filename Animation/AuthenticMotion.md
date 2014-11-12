Authentic motion
===

Perceiving an object’s tangible form helps us understand how to manipulate it. Observing an object’s motion tells us whether it is light or heavy, flexible or rigid, small or large. Motion in the world of material design is not only beautiful, it builds meaning about the spatial relationships, functionality, and intention of the system.

オブジェクトの「かたち」を知覚することは、それを操作する「やり方」を理解するのに役立ちます。オブジェクトのモーションを観察することは、光や重さ、柔らかさまたは剛性、小さいまたは大きいであるかどうかを伝えてくれます。マテリアル設計の世界での動きは美しいということだけでなく、システムの空間的な関係性、機能、および意思についての意味合いがあります。

### Mass and weight

Physical objects have mass and move only when forces are applied to them. Consequently, objects can’t start or stop instantaneously. Animation with abrupt starts and stops or rapid changes in direction appears unnatural and can be an unexpected and unpleasant disruption for the user.

物理的なオブジェクトは、質量を有し力がそれらに適用される場合にのみ移動します。その結果、オブジェクトが瞬時に動いたり停止することはできません。方向が急激に開始、停止または急激な変化とアニメーションが不自然に表示されるとユーザにとって予想外になり不快な印象になります。

A critical aspect of motion for material design is to retain the feeling of physicality without sacrificing elegance, simplicity, beauty, and the magic of a seamless user experience.

マテリアル設計のための運動の重要な側面は、優雅さ、シンプルさ、美しさ、そしてシームレスなユーザーエクスペリエンスを犠牲にすることなく、体験的な感覚を保持することです。

#### Best practices

Accelerate objects swiftly and decelerate them slowly to avoid abrupt changes in velocity.

迅速にオブジェクトを加速し、速度の急激な変化を避けるために、ゆっくりと減速します。

An abrupt change in velocity at both the beginning and end of the animation curve means the object instantaneously starts and stops, which is unrealistic.

アニメーションカーブの両端における速度の急激な変化、つかりオブジェクトが瞬時に起動や停止することは非現実的である。

#### Special cases: Entering and exiting frame

When an object enters the frame, ensure that it's moving at its peak velocity. This behavior emulates natural movement. A person entering the frame of vision does not begin walking at the edge of the frame, but before it. Similarly, when an object exits the frame, maintain the object’s velocity, rather than slowing it down as it exits the frame. The user’s attention is drawn to an object slowly entering and exiting the frame. In most cases, that isn’t your desired effect.  

オブジェクトがフレームに入るとき、それがピーク速度で動いていることを確認してください。この動作は、自然な動きをエミュレートします。ビジョンのフレームに入る場合は、フレームの端で動くのを開始しますがそれ以前にはありません。オブジェクトがフレームを出るときも同様に（むしろオブジェクトがフレームを出るときに）、減速することよりも物体の速度を維持します。ユーザの視点はオブジェクトがゆっくり入るとフレームを終了に引き寄せられます。ほとんどの場合、これらは期待するような効果ではない。

#### Making Adjustments

Not all objects move the same way. Lighter/smaller objects may accelerate or decelerate faster because they have less mass and require less force to do so. Larger/heavier objects may need more time to reach peak speed and come to rest. Think about how this applies to the various UI elements in your app and consider how their motion should be represented.

すべてのオブジェクトが同じように動くことはない。軽いく小さなオブジェクトはより少ない質量を持っており加速は、少ない力でいいので高速な減速がある。大きく重いオブジェクトは、ピーク速度に達すると速度を維持し、より多くの時間が必要になる場合があります。これは作ったアプリの中でさまざまなUI要素に適用する方法について考えさせられ、オブジェクトの動きがどう表されるべきかを検討することになります。



