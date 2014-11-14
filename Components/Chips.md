Chips
===

Chips are small blocks that represent a complex entity, such as a calendar event or contact. They can contain a photo, short title string (truncated if necessary), and other brief information. Chips are easily manipulated through drag and drop. Touching them invokes the full entity view in a card or full screen view or invokes a menu of options related to that chip’s entity.

Animations invoking and invoked from chips should resize the chip material between entity views for element persistence.

チップは、カレンダー事象又は接触のような複雑なエンティティを表す小さなブロックである。彼らは写真、（必要に応じて切り捨て）短いタイトル文字列、およびその他の簡単な情報を含めることができます。チップは、簡単にドラッグアンドドロップを介して操作されている。それらに触れると、カードまたはフルスクリーンビューで完全なエンティティのビューを起動するか、そのチップのエンティティに関連するオプションのメニューを呼び出します。

チップから呼び出し、呼び出されたアニメーションは、要素の永続性のためにエンティティビュー間のチップ材のサイズを変更する必要があります。

### Contact chips

Contact chips represent people for whom the user has contact information. They are invoked and inserted into a text field (usually the To field) when the user starts typing a contact’s name, sees the contact’s addresses, and selects the correct one. Contact chips can be added directly to a text field from a menu of contacts.

Contact chips confirm that the user will be sending their message to the correct person, and are space and operationally efficient.

接触チップは、ユーザーが連絡先情報を持って誰のために人を表しています。彼らは呼び出され、テキストフィールド（通常はフィールドにするには）ユーザーが連絡先の名前を入力する開始したときに、連絡先のアドレスを見て、正しいものを選択して挿入されている。接触チップは、接点のメニューからテキストフィールドに直接添加することができる。

接触チップは、ユーザーが正しい人に自分のメッセージを送信されることを確認し、スペースや運用上効率的である。

#### Closed contact chip

* The contact name text is Roboto Regular 14sp.
* Upon focus, the chip rises. When pressed, it expands to shows alternative addresses for the contact.
* Open contact chip

* 連絡先の名前のテキストはRoboto正規14spです。
* フォーカス時には、チップは上昇する。このボタンを押すと、それは連絡先のショーの代替アドレスに展開されます。
* オープン接触チップ

#### Contact name text:  Roboto Regular 16sp

* Address text: Roboto Regular 14sp
* On press, the contact chip closes automatically.
* By default, the top field is activated and focused.

* Addressテキスト：Roboto定期14sp
* プレスでは、接触チップが自動的に閉じます。
* デフォルトでは、トップフィールドが活性化され集中している。