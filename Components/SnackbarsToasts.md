Snackbars & toasts
===

Snackbars provide lightweight feedback about an operation. They show a brief message at the bottom of the screen on mobile and lower left on desktop. Snackbars appear above all other elements on screen. Snackbars can contain an action.

スナックバーは、操作に関する軽量フィードバックを提供する。彼らは、デスクトップ上のモバイルと左下の画面の一番下に簡単なメッセージを示しています。スナックバーは、画面上の他のすべての要素の上に表示されます。スナックバーは、アクションを含めることができます。

They automatically disappear after a timeout or after user interaction elsewhere on the screen, particularly after interactions that summon a new surface or activity. Snackbars can be swiped off screen. They do not block input on the screens on which they appear. Show only one snackbar on screen at a time.

彼らは、自動的に、特に新しい表面または活性を召喚相互作用した後に、タイムアウト後または他の場所、画面上のユーザーとの対話の後に消える。スナックバーは、画面をオフにスワイプすることができます。彼らは、それらが現れる上の画面で入力をブロックしない。一度に画面上に一つだけスナックバーを表示します。

Android also provides a capsule-shaped toast, primarily used for system messaging. Toasts are similar to snackbars but do not contain actions and cannot be swiped off screen.

Androidはまた、主にシステムメッセージングに使用カプセル型トーストを提供します。トーストスナックバーに似ていますがアクションを含んでいないし、画面をオフにスワイプすることはできません。

### Usage

#### Very short text strings

Snackbars should generally only be tall enough to accommodate one string, and the string should be directly related to the operation performed. They cannot contain icons or action icons. Actions are in the form of text.

スナックバーは、一般的に1つの文字列のみを収容するのに十分な高であるべきであり、文字列が実行された操作に直接関連する必要があります。彼らは、アイコンやアクションのアイコンを含めることはできません。アクションは、テキストの形である。

#### Transient

For usability, snackbars should not contain the only way to access a core use case. They should not be persistent or stack, as they are above other elements on screen.

ユーザビリティの場合は、スナックバーは、コアのユースケースにアクセスする唯一の方法を含むべきではありません。彼らは永続的であるか、彼らは画面上の他の要素の上にあるように、積み重ねてはならない。

#### 0-1 actions, not dismiss or cancel

If an action is present, comply with dialog spacing and affordance rules. For two or more actions, use a dialog, not a snackbar, even when one of the actions is a dismiss action. If the action described in the snackbar is important enough to block the use of the screen, it should be a dialog.

アクションが存在する場合、ダイアログ間隔とアフォーダンス規則に従う。のいずれかのアクションがアクションを却下するときに2つ以上のアクションについては、さえ、ダイアログではなく、スナックバーを使用します。スナックバーで説明アクションがスクリーンの使用を阻止するのに十分重要である場合には、ダイアログであるべきである。

#### Don’t block the floating action button

Move your floating action button vertically to accommodate the snackbar height.

スナックバーの高さに対応するために、垂直方向にあなたのフローティングアクションボタンを移動します。

### Specs

#### Mobile snackbar

* Single-line snackbar height: 48dp
* Multi-line snackbar height: 80dp
* Text: Roboto Regular 14sp
* Action button: Roboto Medium 14sp, all-caps text
* Default background fill: #323232 100%

#### Tablet/desktop snackbar

* Single-line snackbar height: 48dp tall
* Minimum width: 288dp
* Maximum width:  568dp
* 2dp rounded corner
* Text: Roboto Regular 14sp
* Action button: Roboto Medium 14sp, all-caps text
* Default background fill: #323232 100%  

#### Android toast

Developers can create custom toasts or custom screen placements for them. If making a custom toast, you are strongly encouraged to adhere to the snackbar style provided above.

開発者は、彼らのためのカスタム乾杯またはカスタム画面配置を作成することができます。カスタムトーストを作る場合は、強く上で提供スナックバースタイルに付着することが奨励される。