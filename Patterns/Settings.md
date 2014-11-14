Settings
===

### Settings

Application settings allow users to indicate their preferences for how the app should behave. They grant the user a genuine sense of control and can be useful in avoiding repeated interruptions with the same question.

アプリケーションの設定は、ユーザーがアプリがどのように振る舞うべきかのために自分の好みを示すことができます。彼らはユーザーにコントロールの本物感を付与し、同じ質問を繰り返さ中断を回避するのに役立ちます。

#### Accessing settings

Settings are given low prominence in the UI because they’re not frequently needed by users. When your app uses settings:

* The action for accessing Settings should always be simply labelled as “Settings”.
* If the current screen supports a side nav drawer, place a menu item for Settings in the drawer, below all other items except Help & Feedback.
* Otherwise, if there is a toolbar on the current screen, place a menu item for Settings in the toolbar’s action overflow, below all other items except Help & Feedback.

頻繁にユーザが必要としていないので、設定がUIに低い隆起を与えられている。ときにアプリが設定を使用します：

* アクセス設定のアクションは常に、単に「設定」と表示されるべきである。
* 現在の画面は、サイドのnavドロワーをサポートしている場合、ヘルプ＆フィードバック除く他のすべての項目の下に、引き出しの中に設定するためのメニュー項目を配置。
* 現在の画面上のツールバーがある場合、そうでない場合は、ヘルプ＆フィードバック除く他のすべての項目の下に、ツールバーのアクションオーバーフローに設定するためのメニュー項目を配置。

#### Using settings appropriately

When users visit Settings—however infrequently—they’ll hold this screen to the same expectations as the rest of their experience. It should be well-organized and predictable. Don’t overwhelm the user with too many options.

ユーザーが訪問したときに設定し、しかしまれに経験の他の部分と同じ期待にこの画面を保持します。それはよく組織と予測可能でなければなりません。あまりにも多くのオプションを持つユーザーを圧倒しないでください。

Avoid the urge to “just make it a setting”. For each control you’re considering adding to Settings, make sure it’s appropriate by asking the following questions:

* Is this actually a user preference? Information and actions are not user preferences.
If not, don’t make it a setting. If it’s static information about the app (e.g. version number, terms of service, open source licenses), organize it into a Help screen.
If it’s an action (e.g. refresh, change account), find an appropriate place for it within the main flow of your app.
* Is this infrequently changed by users? Would users feel burdened by taking multiple actions to access this control each time?
If not, don’t make it a setting. Make the control more readily available, possibly via a toolbar or action overflow.
* Would fewer than 20% of users change the value of this control? 
If not, don’t make it a setting.

「ちょうどそれの設定にする」ための衝動を避けてください。 設定への追加を検討している各コントロールのためには、以下の質問をすることによって、適切だことを確認してください。

* これは、ユーザの嗜好に実際ありますか？情報とアクションは、ユーザーの好みではありません。
そうでなければ、設定しないでください。それは静的なアプリに関する情報（例えばバージョン番号、サービスの観点から、オープンソースのライセンスは）なら、ヘルプ画面にそれを整理する。
それは、アクション（例えばリフレッシュ、変更アカウントが）なら、あなたのアプリの主な流れの中、それに適した場所を見つける。
* これは、まれに、ユーザーによって変更されていますか？ユーザーがこのコントロールたびにアクセスするために複数のアクションを取ることによって負担を感じるだろうか？
そうでなければ、設定しないでください。おそらくツールバーまたはアクション·オーバーフローを経由して、制御がより容易に利用できるようにします。
* 利用者の20％未満では、このコントロールの値を変更しますか？
そうでなければ、設定しないでください。

These same questions should be applied to both new and existing settings. For existing settings, you may have to think more about the last question: If the setting were removed, would it cause harm to the minority who would no longer be able to change it? If so, then maintaining it as a setting is appropriate.

これらの同じ質問は、新規および既存の設定に適用されるべきである。設定が削除された場合、それはもはやそれを変更することはできないであろう少数派に害を引き起こす：既存の設定では、最後の質問についてもっと考える必要がある？設定が適切であるようにそうであれば、それを維持する。

#### Grouping settings

When you have many settings, turn one long list into multiple shorter lists by clustering the settings. Your strategy for arranging them will depend on the total number of settings in the Settings panel in your app.

あなたは多くの設定を持っている場合、設定をクラスタリングすることにより、複数の短いリストに一つの長いリストを向ける。それらを配置するためのあなたの戦略は、あなたのアプリケーションでの設定パネルの設定の合計数に依存します。

#### Seven or fewer

Don’t group at all.

全すべてのグループはありません。

#### Nine to 10

Try grouping related settings under 1 or 2 section dividers. If you have any "singletons" (settings that don't relate to any other settings and can't be grouped under your section dividers), treat them as follows:

* If they include some of your most important settings, list them at the top without a section divider.
* Otherwise, list them at the bottom with a section divider called "Other", in order of importance.

1または2のセクションの仕切りの下に関連した設定をグループ化してみます。あなたは、（他の設定に関係していないとあなたのセクションの仕切りの下にグループ化することができない設定）あらゆる「シングルトン"を持っている場合は、次のように扱う。

* 彼らはあなたの最も重要な設定のいくつかを含む場合は、そのセクションデバイダなしのトップでそれらを一覧表示します。
* それ以外の場合は、重要度順に「その他」というセクション·デバイダ、底でそれらを一覧表示します。

#### 11 to 15

Same advice as above, but try two to four section dividers. Look for "doubles": two settings that relate to one another, but not to any other settings. Try to combine them into one setting. For example, you might be able to redesign two related checkbox settings into one multiple choice setting.

上記と同じアドバイスが、二から四節仕切りをしてみてください。他の設定には、2つの相互に関連の設定ではなく、「ダブルス」を探してください。一つの設定にそれらを組み合わせるようにしてください。たとえば、1複数の選択肢の設定に二つの関連のチェックボックス設定を再設計することができるかもしれません。

#### 16 or more

If you have any instances of four or more related settings, group them under a subscreen. Apply the guidance above to each subscreen.

あなたは、従属の下に4つ以上の関連する設定、グループ、それらを任意のインスタンスがある場合。各サブ画面に上記のガイダンスを適用します。


#### Choosing defaults

Users will expect the initial value for each setting to be sensible. The following questions can help inform your decisions:

* Which choice would most users be likely to choose on their own if there were no default?
* Which choice is the most neutral or middle-of-the-road?
* Which choice is the least risky, controversial, or over-the-top?
* Which choice uses the least amount of battery or mobile data?
* Which choice most respects the user’s attention, and only interrupts when it is important?

ユーザーが賢明であると設定するごとに、初期値を期待します。あなたの決定を知らせることができ、次の質問：

* デフォルトがない場合どの選択肢ほとんどのユーザは自分自身で選択する可能性が高いでしょうか？
* ほとんど中性または中道のはどの選択肢です？
* どちらの選択である以上、危険な物議を醸す、またはオーバーザトップ？
* どの選択がバッテリーやモバイルデータの最小量を使用しています？
* そのほとんどの選択は、ユーザの注意を尊重し、それが重要な場合にのみ割り込み？