Text fields
===

Text fields allow the user to input text. They can be single line, with or without scrolling, or multi-line, and can have an icon. Touching a text field places the cursor and automatically displays the keyboard. In addition to typing, text fields allow for a variety of other tasks, such as text selection (cut, copy, paste) and data lookup via auto-completion. See Patterns > Selection for text selection design.

テキストフィールドは、入力テキストをユーザに許可する。彼らは、またはスクロールせずに単一の行、または複数行であることができ、アイコンを持つことができます。テキストフィールドをタッチすると、カーソルを配置し、自動的にキーボードが表示されます。タイピングに加えて、テキストフィールドは、自動補完を介してテキスト選択（切り取り、コピー、貼り付け）、データ検索などの他のタスク、各種のを可能にする。テキスト選択設計のためのパターン>の選択を参照してください。

The type of text field determines what kind of characters are allowed inside the field and may prompt the virtual keyboard to optimize its layout for frequently used characters. Common types for which you should optimize include number, text, email address, phone number, person’s name, username, URL, street address, credit card number, PIN, and search query.

テキストフィールドのタイプは、文字の種類は、フィールド内許可され、頻繁に使用される文字にそのレイアウトを最適化するための仮想キーボードを促すことができるかを決定します。もし最適化する必要がいる一般的なタイプは数字、テキスト、電子メールアドレス、電話番号、担当者名、ユーザ名、URL、住所、クレジットカード番号、PIN、および検索クエリを含む。

### Single-line text field

#### Single-line fields

Single-line fields automatically scroll their content to the left as the text input cursor reaches the right edge of the input field.

テキスト入力カーソルが入力フィールドの右端に到達すると、単一行フィールドが自動的に左にその内容をスクロールします。

#### Light theme

Hint and input font: Roboto Regular 16sp
Tile height: 48dp
Text top and bottom padding: 16dp
Text field divider padding: 8dp

#### Dark theme

#### Light theme with icon

Hint and input font: Roboto Regular 16sp
Tile height: 48dp
Text top and bottom padding: 16dp
Text field divider padding: 8dp

#### Dark theme with icon

### Floating labels

#### Floating labels

With floating inline labels, when the user engages with the text input field, the labels move to float above the field.

ユーザーがテキスト入力フィールドに係合するとき、インラインラベルをフローティングで、ラベルはフィールドの上に浮いているように動く。

#### Light theme

Hint and input font: Roboto Regular 16sp
Label font: Roboto Regular 12sp
Tile height: 72dp
Text top and bottom padding: 16dp
Text field divider padding: 8dp

#### Dark theme

### Multi-line text field

Multi-line text fields automatically break to a new line for overflow text and scroll vertically when the cursor reaches the lower edge.

複数行のテキストフィールドは、自動的に、オーバーフローテキストの新しい行に分割し、カーソルが下縁部に到達した垂直たときにスクロール。

#### Light theme

Hint and input font: Roboto Regular 16sp
Label font: Roboto Regular 12sp
Text top and bottom padding: 16dp
Text field divider padding: 8dp

#### Dark theme

### Full-width text field

Full-width text fields are useful for more in-depth tasks.

全幅のテキストフィールドは、より綿密なタスクに便利です。

#### Single and multi-line fields

Hint and input font: Roboto Regular 16sp
Top and bottom padding for text: 20dp

### Character counter

Use a character counter in fields where a character restriction is in place.

文字制限が整備されている分野での文字カウンタを使用してください。

#### Single line with character counter

Counter text: Roboto Regular 12sp

#### Multi-line with character counter

Counter text: Roboto Regular 12sp

#### Full width with character counter

### Auto-complete text field

Use auto-complete text fields to present real-time suggestions or completions in dropdowns, so users can enter information more accurately and efficiently.

ユーザーがより正確かつ効率的に情報を入力できるように、ドロップダウン内のリアルタイム提案や補完を提示するオートコンプリートテキストフィールドを使用してください。

#### Full-width auto-complete

#### Inset auto-complete

#### Full-width inline auto-complete

#### In-line auto-complete

### Search filter

The app bar can act as a text input field. As the user types, the content underneath it is filtered and sorted.

アプリバーは、テキスト入力フィールドとして働くことができる。ユーザータイプとして、その下にコンテンツを濾過し、ソートされます。

#### Full-width text field in app bar