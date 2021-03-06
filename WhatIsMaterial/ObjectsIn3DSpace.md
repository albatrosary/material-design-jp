Objects in 3D space
===

### _三次元空間に存在するオブジェクト_

There are parallels between organizing objects in the physical world and arranging objects in space in material design. 
In the physical world, objects can be stacked or affixed to one another, but cannot pass through one another. 
The objects cast shadows and reflect light.


現実世界とマテリアルデザインのオブジェクトは共通の類似点が存在します。

現実世界では、オブジェクトを固めたり、積み重ねる事ができ、そのときに同じ空間を占めるような重なり方は起こりません。

オブジェクトは光を当てると影を描画し、光を反射します。



These qualities apply to objects in material design and help create a spatial model that can be consistently applied across apps in ways that are familiar to users.

こういった特徴は、マテリアルデザインに存在するオブジェクトすべてに当てはまり、空間を意識させるモデルを作るのに役立ちます。
そしてそれは、ユーザーに親しみのある方法で、常にアプリケーション全体に適用する事が出来ます。

---

### Elevation

#### Elevation
#### _Elevation(エレベーション)(高度)_


Elevation is the relative position of an object along its parent’s z-axis. Elevation is the relative value between parent and child objects.

Elevationは親となる存在からZ軸方向に向けての相対位置です。

Elevationは親子間オブジェクトの相対距離です。

Elevation is measured in the same units as the x and y axes, typically in density independent pixels (dps). Since material has a standard 1dp thickness, all elevation distances are measured from one top surface to another top surface.

Elevationは一般的にx軸やy軸同じように、端末に依存しないピクセル (dps)単位で計測されます。

materialは、必ず1dpの厚さを有しています、そして、すべてのElevation計測は、オブジェクトの上面から別オブジェクトの上面までの距離で行います。

<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7U05IYmxGcW1WcVU/whatismaterial_3d_elevation1.png" width="500"/>

#### Resting elevation
#### _静止高度_

All material objects have a resting elevation, whether the object is a small component or a sheet that spans the entire display.

すべてのmaterialオブジェクトは通常状態でのelevationを持っています。
オブジェクトは、小さなコンポーネント、またはディスプレイ全体にまたがるシートをさします。

<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7WWF2M2pDSDJ6M3c/whatismaterial_3d_elevation2.png" width="500" />

---

In the static state, the resting elevation for an object does not change. It is constant throughout an app. If an object changes elevation, it should return to its resting elevation as soon as possible.

静的な状態では、オブジェクトの標準elevationは変更されません。

その値はアプリケーション全体で一定です。

もし、そのオブジェクトのelevationが変更された場合、それは出来るだけ早くその標準elevationの高さに戻す必要があります。

<img src="http://material-design.storage.googleapis.com/publish/v_1/quantumexternal/0Bx4BSt6jniD7UFFxc1NmZmNxY0U/whatismaterial_3d_elevation3.png" width="500" />

---

The resting elevation for a given component type is consistent across apps throughout a platform. However, that same component type may have different resting elevations from platform to platform depending on the depth of the environment (e.g., TV has a greater depth than mobile or desktop).

指定されたコンポーネント毎の静止座標はプラットフォーム全体を通して同じです。

しかし、同じコンポーネントでも、奥行きの深さに応じて他のプラットフォームとは異なる静止座標を持っている可能性があります。

（例：テレビは、モバイルやデスクトップよりも深さを表現できます。）

<img src="http://material-design.storage.googleapis.com/publish/v_2/material_ext_publish/0Bx4BSt6jniD7VlNUdW5seTJVaTQ/whatismaterial_3d_elevation4.png" width="500" />

---

#### Responsive elevation and dynamic elevation offsets
### _反応高度と振る舞いを表現する高度_

Certain component types have responsive elevation, which means they change their elevation in response to user input or system events. Different component states (e.g., normal, focused, pressed) may result in varying elevation changes, which are consistently implemented using dynamic elevation offsets.

特定のコンポーネントはユーザーの入力またはシステムイベントに応じて、高度(elevation)を変更するための振る舞いを持ちます。

様々なコンポーネントの状態(例：通常時、注目してほしい時、押下された時..等)に応じて反応を返し、振る舞いを表現する高度(elevation)の変更を行います。

Dynamic elevation offsets are relative to the resting state of the component, and act as the goal or target elevation for the component to move towards for a given component state. 

They also ensure that elevation changes for a given action are consistent across a component type. For example, all components that lift on press have the same elevation change, relative to their current/resting elevation.

これらは、特定のアクションに基づいたElevationの変化が、コンポーネント毎に統一されていることに留意しておいてください。

例えば、押す/離すなどをしたとき、同一種のコンポーネントは静止/現在のElevationを基準として、同じElevationの変更が発生します。


Once the input event is completed or cancelled, the component will return to its resting elevation.

入力イベントが完了するかまたは取り消されると、コンポーネントはその静止標高に戻ります。


<img src="http://material-design.storage.googleapis.com/publish/v_2/material_ext_publish/0Bx4BSt6jniD7Q1N0RzZFcVhSWXM/whatismaterial_3d_elevation5.png" width="500" />

#### Functional shadows
#### _機能的な影_

Shadows provide several important visual cues about the arrangement of objects in space. Shadows are the only visual affordance indicating the amount of separation between surfaces. The elevation of an object determines the visual appearance of its shadow.

影は、空間内のオブジェクトの位置に関するいくつかの重要な見た目の印象を与えます。
つまり影が、表面から浮き上がる表現を視覚的に伝えるアフォーダンスになります。
オブジェクトのElevationが影の見た目を決定します。

Without a shadow, there is nothing to indicate that the floating action button is a separate surface from the background surfaces.

影が無い場合、フローティングアクションボタンは、背景から独立した存在であることを示せません。

Crisp shadows indicate both the floating action button and the app bar are separate surfaces very close to the background surface.

鮮明な影は、フローティングアクションボタンとアプリケーションバーの両方が背景に凄い近い位置に浮いている、独立した存在である事を示せます。

Softer, larger shadows indicate the floating action button is at a higher elevation than the app bar.

淡く大きな影は、フローティングアクションボタンがアプリケーションバーよりかなり高い位置にある事を示せます。


In motion, shadows also provide cues about an object’s direction of movement. This is another useful tool to indicate whether the distance between surfaces is increasing or decreasing.

「動き」では、影の振る舞いがオブジェクトの動きについての視覚的手がかりを提供します。
これは底面から離れてる、または近づいているかどうかを示すための重要な機能です。

Without a shadow to indicate elevation, it’s unclear whether this circle is scaling at the same elevation, or simply increasing its elevation.

影がElevationの変化を見せなければ、この丸いオブジェクトが同じ高さに居るように見せます。もしくは、その高が変化しているかが不明な状態です。

The shadow grows softer and larger as the object’s elevation increases and grows crisper and smaller as the elevation decreases.

影はオブジェクトのElevationが高いほど柔らかくて大きくなるります、対してElevationが低くなると、鮮明にかつ小さくなります。

In this case, the consistent shadow helps the user understand that the object is changing shape as opposed to changing elevation.

このような機能は、ユーザーに対して、高さが変わっているのではなく、オブジェクトのサイズが変更されている等の変化を知らせるのに役立ちます。

### Object relationships
### _オブジェクトの関係性_


How you organize objects in an app determines how objects or collections of objects move in relation to one another. Objects can move independently of each other, or their movement can be constrained to, and dependent upon, their container. Containers and the objects they contain have a parent-child relationship. Every object has a single parent, and may or may not have one or more children.

プリケーション全体を通してオブジェクトやその集合が、どのように関連してどのように動くかは、オブジェクトのグループ単位で決まります。

オブジェクトは互いに独立して動く事ができますが、振る舞いはコンテナの中でルールづけられ、コンテナに依存します。

コンテナオブジェクトは親子関係をもちます。

そして、すべてのオブジェクトは一つの親を持つか、また一つ以上の子供を持っている場合があります


Children inherit transformation properties from their parent, such as position, rotation, scale, and elevation. For example, in the case of a scrolling card collection where all cards move together, the cards are siblings and they are all children of the card collection container that handles the scrolling movement.

子供となるオブジェクトは位置や回転、拡大や高さなどの振る舞いを親から継承します。

たとえば、すべてのカードが一緒に移動する「カード一覧」の場合、「カード」同士が兄弟となり、そのカードは「カード一覧コンテナ」の子供になります。

The hierarchy of parents and children determines how objects and groups of objects interact with one another. For example, child objects have minimal z-axis separation from their parent; other objects do not get inserted between parents and children.

親子の関係は、オブジェクトとオブジェクトのグループが互いにどのように振る舞うかをルールづけます。

例えば、子供は親からの最低限のz軸の間隔を持ちます。
また、この親子関係の間に、あらたなオブジェクトは入り込めません。

<img src="http://material-design.storage.googleapis.com/publish/v_2/material_ext_publish/0Bx4BSt6jniD7RDVQb2FiUExTUjQ/whatismaterial_3d_relationship1.png" width="500"/>

 * 子属性となる浮き上がったボタンは、親コンテンツがスクロールするのに合わせて同じようにスクロールします。

<img src="http://material-design.storage.googleapis.com/publish/v_2/material_ext_publish/0Bx4BSt6jniD7bUxFNWxtN2VnY2M/whatismaterial_3d_relationship2.png" width="500"/>

 * （親属性となる）フローティング状態のアクションボタンは所定の位置に残りつつ、(関連を持つ、または子属性の）カードは画面外にスクロールして行きます。
 
