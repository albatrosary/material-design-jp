Switches
===

Switches allow the user to select options. There are three kinds: checkboxes, radio buttons, and on/off switches.

*Note: The graphic rings shown in the following examples represent animation and do not represent what buttons should look like in implementation.

スイッチは、ユーザがオプションを選択できるようにする。そこに三種類ある：チェックボックス、ラジオボタン、およびオン/オフスイッチオン。

*注：次の例に示すグラフィックリングがアニメーションを表し、実装でどのように見えるかのボタン表すものではありません。

### Checkbox

Checkboxes allow the user to select multiple options from a set.

If you have multiple on/off options appearing in a list, checkboxes are a good way to preserve space.

If you have a single on/off option, avoid using a checkbox and use an on/off switch instead.

Checkboxes use animation to communicate focused and pressed states.

チェックボックスは、ユーザーがセットから複数のオプションを選択することができます。

あなたがリストに表示されるオン/オフのオプションに複数のを持っている場合は、チェックボックスが容量を節約するための良い方法です。

あなたが/オフオプションのシングルを持っている場合は、チェックボックスの使用は避け、代わりにオン/オフスイッチを使用しています。

チェックボックスは集中して押された状態を通信するためにアニメーションを使用。

#### Light

On: Swatch 500, Alpha 100%
Off: #000000, Alpha 54%
Disabled: #000000, Alpha 26%

#### Dark

On: Swatch 500, Alpha 100%
Off: #FFFFFF, Alpha 70%
Disabled: #FFFFFF, Alpha 30%

### Radio button

Radio buttons allow the user to select one option from a set. Use radio buttons for exclusive selection if you think that the user needs to see all available options side-by-side.

Otherwise, consider a pulldown, which uses less space than displaying all options.

Radio buttons use animation to communicate focused and pressed states.

ラジオボタンは、ユーザがセットから1つのオプションを選択できるようにする。あなたは、ユーザーが使用可能なすべてのオプションをサイドバイサイドを見る必要があると思われる場合の排他的な選択のためのラジオボタンを使用してください。

それ以外の場合は、すべてのオプションを表示する場合に比べ、少ないスペースを使用してプルダウンを、検討してください。

ラジオボタンは集中して押された状態を通信するためにアニメーションを使用。

#### Light

On: Swatch 500, Alpha 100%
Off: #000000, Alpha 54%
Disabled: #000000, Alpha 26%

#### Dark

On: Swatch 500, Alpha 100%
Off: #FFFFFF, Alpha 70%
Disabled: #FFFFFF, Alpha 30%


### Switch

On/off switches toggle the state of a single settings option. The option that the switch controls, as well as the state it’s in, should be made clear from the corresponding inline label. Switches take on the same visual properties of the radio button.

Switches use animation to communicate focused and pressed states.

The on/off slide toggle with the words “on” and “off” baked within the asset is deprecated. Use the switch shown here instead.

ON / OFFスイッチは、単一の設定オプションの状態を切り替えます。スイッチのコントロールだけでなく、それは中の状態が、対応するインラインラベルから明確にすべきオプション。スイッチは、ラジオボタンの同じ視覚特性を帯びる。

スイッチは、集中して押された状態を通信するためにアニメーションを使用。

アセット内焼き言葉「オン」と「オフ」を持つオン/オフスライドトグルが廃止されました。代わりに、ここに示されているスイッチを使用します。

#### Light

Thumb On: Swatch 500, Alpha 100%
Track On: Swatch 500, Alpha 50%

Thumb Off: Grey 50, #FAFAFA, Alpha 100%
Track Off: #000000, Alpha 26%

Thumb Disabled: Grey 400, #BDBDBD, Alpha 100%
Track Disabled: #000000, Alpha 12%

#### Dark

Thumb On: Swatch 200, Alpha 100%
Track On: Swatch 200, Alpha 50%

Thumb Off: Grey 400, #BDBDBD, Alpha 100%
Track Off: #FFFFFF, Alpha 30%

Thumb Disabled: Grey 800, #424242, Alpha 100%Track Disabled: #FFFFFF, Alpha 10%

Use the outer radial reaction only on form factors that favor finger touch, where interaction may obstruct the element completely. For desktop usage with a mouse, you do not need this extra indication.

唯一の相互作用が完全に要素を遮ることが指のタッチを、好むフォームファクタ上の外側の半径方向の反応を使用してください。マウスでデスクトップの使用状況では、この余分な表示をする必要はありません。