Responsive interaction
===

Responsive interaction builds trust with the user and engages them. When a user interacts with an app and beautiful yet perfectly logical things happen, the user feels satisfied—even delighted.  The interaction is thoughtful and purposeful, not random, and can be gently whimsical but never distracting. It encourages deeper exploration of an app. What will happen if I touch this? And then this?

応答性の相互作用は、ユーザーとの信頼関係を構築します。ユーザーは美しく完璧に論理的で、動きが予想できるアプリと対話するとき、ユーザーは満足を感じ喜びが得られます。相互作用は決して思慮深く、ランダム、意図的、優柔、気まぐれであってはなりません、そうすると気が散ります。それはアプリのより深い探査を奨励しています。私はこれを触れた場合は、どうですか？その後は？

### User input

In material design, apps are responsive to and eager for user input:

* Touch, voice, mouse and keyboard are all first-class input methods.
* Although UI elements appear tangible, they are locked behind a layer of glass (the computer or device’s screen). Visual and motion cues help bridge that gap by immediately acknowledging input and implying direct manipulation.

Responsive interaction elevates an app from something that delivers information to the user upon request to something that communicates with the user in a tangible way.

マテリアル設計では、アプリとしてはユーザー入力のために応答性と熱望している：

* タッチ、音声、マウスとキーボードは、すべてのファーストクラスの入力方法です

* UI要素の「かたち」が見えますが、それらは画面（コンピュータまたはデバイスの画面）の層の後ろに押さえつけられています。視覚と運動の手がかりは、すぐに入力を確認し、直接操作することにより、ギャップを埋めます。

応答性の相互作用は、ある方法でユーザーと通信を何かに要求に応じて、ユーザーに情報を配信する何かからアプリを上昇させる。

### Surface reaction

Upon receiving an input event, the system provides an instantaneous visual confirmation at the point of contact: under the pad of a finger for touch, at the mic for voice, or in the appropriate field for a keyboard press. One way to express this acknowledgment is through the ink metaphor, the dynamic display surface that coats every sheet of paper.

The core visual mechanism to express this contact is the Touch Ripple. This device articulates the attack and duration of a touch event, as well as dynamic aspects, such as the amplitude of voice or the interpreted pressure of a touch.

音声用のマイクで、touch用の指のパッドの場合に、または適切なフィールドにキーボードプレス用：入力イベントを受信すると、システムは、接触点における瞬間的な視覚的な確認を提供します。この確認応答を表現する1つの方法は、インクのメタファーを介して行われ、動的な表示面を被覆紙のすべてのシート。

この接触を表現するコアの視覚メカニズムがタッチリップルです。このデバイスは、攻撃および期間タッチイベントの、ならびにこのような音声の振幅、またはタッチの解釈圧力などの動的な側面を、関節。

#### Best Practices

Input occurs at specific points: at the contact point of a finger or at the mic icon for voice. From this point, make the visual reaction radial.

指の接触点でまたは音声用のマイクのアイコンの場合：入力は、特定のポイントで発生します。この時点から、視覚的な放射状の反応を作ります。

### Material response

In addition to ink-like actions on the surface, the material itself can also react. The material can lift up when touched, indicating an active state. The user can generate new or transform existing material on touch, or directly manipulate sheets of material by dragging or flinging them.

表面上のインクのような作用に加えて、マテリアル自体にも反応することができます。触れたときマテリアルは、活性状態を示し持ち上げことができます。ユーザーは新しい生成またはtouch上で、既存のマテリアルを変換するか、直接ドラッグしたり、それらをスワイプすることにより、マテリアル・シートを操作することができます。

#### Point of origin

When new material is generated as a result of direct user interaction, surface growth motion should originate from the point of input.

新しいマテリアルは、直接のユーザ対話の結果として生成されると、表面成長モーション入力の点から発信すべきである。

#### Lift on touch

When a card or separable element is activated, the card should lift to indicate an active state.

カードまたは分離可能な要素が活性化されると、カードがアクティブ状態を示すために持ち上げなければならない。

### Radial action

All user-initiated actions have an epicenter; the place or places where their intent enters the system. Add clarity to user-initiated events by creating strong visual connections from user input, whether by fingers on a touch screen or voice through a microphone. State changes across the screen should trigger progressively as their distance to the point of contact increases, creating a ripple of action.

* Inputs have an epicenter. Touch occurs at the point of contact, voice enters through the mic icon, keyboard through the individual keys.
* Actions should visually connect to their respective input epicenter. Closer actions occur sooner than more distant ones, creating a ripple of actions (movement occurs from the distance from the epicenter).

すべてのユーザーが開始したアクションは、起点を持っています。それは意図がシステムに入り込む場合や場所。マイクを通してタッチスクリーンや音声上で指でどうか、ユーザー入力からの強い視覚的な接続を作成することによって、ユーザーが開始したイベントへの明瞭さを追加します。画面上の状態変化は、アクションのリップルを作成、接触は増加の点までの距離として次第にトリガする必要があります。

*入力は起点を持っている。タッチが接触点で発生し、音声が個々のキーを通してマイクアイコン、キーボードから入力する。
*アクションは、視覚的に、それぞれの入力に接続する必要があります。近いアクションがアクションのリップルを（動きが震央からの距離から発生する）を作成し、より遠くのものよりも早く起こる。