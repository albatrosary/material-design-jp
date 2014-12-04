Authentic motion
===

Perceiving an object’s tangible form helps us understand how to manipulate it. Observing an object’s motion tells us whether it is light or heavy, flexible or rigid, small or large. Motion in the world of material design is not only beautiful, it builds meaning about the spatial relationships, functionality, and intention of the system.

物体の具体的な形を認識する事で、私たちはそれをどう動かせばいいか理解できます。

物体の運動を観察する事は、軽い/重さ、柔らかい/固い、小さい/大きいかを知る事ができます。

マテリアルデザインの世界での振る舞いは、美しいだけではなく、空間的特性があり、機能的であり、システム的な意味を作り出します。


### Mass and weight

Physical objects have mass and move only when forces are applied to them. Consequently, objects can’t start or stop instantaneously. Animation with abrupt starts and stops or rapid changes in direction appears unnatural and can be an unexpected and unpleasant disruption for the user.

物理的なオブジェクトは、質量があり、なんらかの力が作用したときのみ移動します。

そういった場合には、オブジェクトは急な移動開始や停止はできません。

突発的な移動開始や停止、または劇的な変化を行うようなアニメーションは不自然であり、ユーザーはそれが予想外であるために混乱し、不快な印象として残ります。


A critical aspect of motion for material design is to retain the feeling of physicality without sacrificing elegance, simplicity, beauty, and the magic of a seamless user experience.

マテリアルデザインの動きで重要な部分は、優雅さ、シンプルさ、美しさ、そして、連続した魔法のようなユーザ体験を犠牲にする事無く、一体感を維持し続ける事にあります。

 * **関連情報**  
[Curved Motionを使う  
アニメーションを行う場合のタイミング曲線と、Curved Motionパターンの定義です](http://developer.android.com/training/material/animations.html#CurvedMotion)


#### Best practices (ベストプラクティス)

Accelerate objects swiftly and decelerate them slowly to avoid abrupt changes in velocity.

勢い良くオブジェクトを加速させ、ゆるやかに減速して行きます、つまり速度の急激な変化は避けなければなりません。

 * [良い例：素早い加速と緩やかな減速が、自然かつ快適な体験を提供する。](http://material-design.storage.googleapis.com/publish/v_2/material_ext_publish/0B2wX4iIvu8L6SERxSXVhMVpsd1E/animation-authenticmotion-massandweight-ex1_xhdpi.webm)

---

An abrupt change in velocity at both the beginning and end of the animation curve means the object instantaneously starts and stops, which is unrealistic.

アニメーション曲線の最初と最後で瞬発的な起動と停止を行うような振る舞いは、非現実的です。

 * [悪い例：変化の無い直線運動は、機械的な感じです。](http://material-design.storage.googleapis.com/publish/v_2/material_ext_publish/0B2wX4iIvu8L6c0wwY2FPSVdnYlk/animation-authenticmotion-massandweight-ex2_xhdpi.webm)

#### Special cases: Entering and exiting frame

When an object enters the frame, ensure that it's moving at its peak velocity. This behavior emulates natural movement. A person entering the frame of vision does not begin walking at the edge of the frame, but before it. Similarly, when an object exits the frame, maintain the object’s velocity, rather than slowing it down as it exits the frame. The user’s attention is drawn to an object slowly entering and exiting the frame. In most cases, that isn’t your desired effect.  

オブジェクトがフレームに入るとき、それは最大速で動いています。

この動作は自然な動きを模倣しています。

視界内に存在する人は、視界の端から移動を開始しますが、其れより前には見えていません。

オブジェクトがフレームアウトするときも同じく、減速をせず、速度を維持し続けます。

オブジェクトがゆっくり入ると、ユーザーの注意はそのオブジェクトの終了が期待されます。

殆どの場合はそれは、あなたが意図しない効果を演出してしまいます。

[良い例：入るときと出るときに最大速度になる。ボールが入り、最高速度のまま、スムーズにフレームアウトします。](http://material-design.storage.googleapis.com/publish/v_2/material_ext_publish/0B2wX4iIvu8L6ckdKbll4b2RvRnM/animation-authenticmotion-massandweight-ex3_do_xhdpi.webm)

[悪い例：入るときや出るときに加速をやめないでください。速度の不必要な変化はユーザーの気をそらしてしまいます。](http://material-design.storage.googleapis.com/publish/v_2/material_ext_publish/0B2wX4iIvu8L6TnJvREpCZy1nMUU/animation-authenticmotion-massandweight-ex4_dont_xhdpi.webm)

#### Making Adjustments

Not all objects move the same way. Lighter/smaller objects may accelerate or decelerate faster because they have less mass and require less force to do so. Larger/heavier objects may need more time to reach peak speed and come to rest. Think about how this applies to the various UI elements in your app and consider how their motion should be represented.

すべてのオブジェクトが全く同じ動きをする事はありません。

軽く小さなオブジェクトは質量が少なく、小さな力で素早い加速を行えます。

重く大きなオブジェクトは質量が多く、加速してしまうと、その運動を維持し、止める為には多くの時間が必要となる場合があります。

これはあなたのアプリケーションで様々なUI要素に適用することができます。
オブジェクトの動きがどのように表現されるかは検討する事が必要です。


