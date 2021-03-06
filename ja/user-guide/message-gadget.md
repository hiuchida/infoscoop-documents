# メッセージ

メッセージガジェットのコントロールとその操作について説明します。

![メッセージガジェット][message_gadget_jp]

<table>
    <thead>
        <tr>
            <th>番号</th><th>名前</th><th>説明</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>(1)</td>
            <td>タイトル</td>
            <td>
                <p>
                    ガジェットのタイトルです。<br>
                    リンクが張られている場合、クリックすると当該サイトのコンテンツを表示します。
                </p>
            </td>
        </tr>
        <tr>
            <td>(2)</td>
            <td>ヘッダアイコン</td>
            <td>
                <p>
                    メッセージの各機能を実行するコントロール。<br>
                    各アイコンの説明は後述の表を参照。
                </p>
            </td>
        </tr>
        <tr>
            <td>(3)</td>
            <td>公開メッセージ</td>
            <td>
                <p>
                    クリックすると公開メッセージ入力フォームを表示します。<br>
                    <img src="images/widget/message-gadget-2.jpg" alt="公開メッセージフォーム">
                </p>
            </td>
        </tr>
        <tr>
            <td>(4)</td>
            <td>システムグループ</td>
            <td>
                <p>
                    <ul>
                        <li>
                            受信メッセージ<br>
                            <img src="../../images/feed_add.gif" alt="RSSリーダー追加アイコン">アイコンをクリックすると、自身宛てのメッセージを表示するRSSリーダーが追加されます。
                        </li>
                        <li>
                            送信メッセージ<br>
                            <img src="../../images/feed_add.gif" alt="RSSリーダー追加アイコン">アイコンをクリックすると、自身が送信した公開メッセージ、メッセージを表示するRSSリーダーが追加されます。
                        </li>
                        <li>
                            お知らせ<br>
                            <img src="../../images/feed_add.gif" alt="RSSリーダー追加アイコン">アイコンをクリックすると、お知らせ送信されたメッセージを表示するRSSリーダーが追加されます。<br>
                            <img src="../../images/email_edit.gif" alt="メッセージ編集アイコン">アイコンをクリックすると、全ユーザー宛てのメッセージを送信するフォームが表示されます。<br>
                            このアイコンは、システム設定で許可されていない場合は表示されません。<br>
                            <img src="images/widget/message-gadget-3.jpg" alt="お知らせフォーム">
                        </li>
                        <li>
                            全ユーザーの公開メッセージ<br>
                            <img src="../../images/feed_add.gif" alt="RSSリーダー追加アイコン">アイコンをクリックすると、全ユーザーの公開メッセージおよび自身宛てのメッセージを表示するRSSリーダーが追加されます。
                        </li>
                    </ul>
                </p>
            </td>
        </tr>
        <tr>
            <td>(5)</td>
            <td>ユーザーグループヘッダ</td>
            <td>
                <p>
                    ユーザーグループ名称が表示されます。<br>
                    グループ名称右の<img src="../../images/feed_add.gif" alt="RSSリーダー追加アイコン">アイコンをクリックすると、ユーザーグループに所属する全てのユーザーの送信した公開メッセージおよび自身宛てのメッセージを表示するRSSリーダーが追加されます。<br>
                    <img src="../../images/email_edit.gif" alt="メッセージ編集アイコン">アイコンをクリックすると、ユーザーグループに所属する全てのメンバー宛てのメッセージを送信するフォームが表示されます。<br>
                    <img src="images/widget/message-gadget-4.jpg" alt="グループメッセージフォーム">
                </p>
            </td>
        </tr>
        <tr>
            <td>(6)</td>
            <td>ユーザーグループ</td>
            <td>
                <p>
                    作成したユーザーグループに所属するユーザーの一覧が表示されます。<br>
                    ユーザー名右の<img src="../../images/feed_add.gif" alt="RSSリーダー追加アイコン">アイコンをクリックすると、対象ユーザーの送信した公開メッセージおよび自身宛てのメッセージを表示するRSSリーダーが追加されます。<br>
                    <img src="../../images/email_edit.gif" alt="メッセージ編集アイコン">アイコンをクリックすると、対象ユーザー宛てのメッセージを送信するフォームが表示されます。
                </p>
            </td>
        </tr>
    </tbody>
</table>


## ヘッダアイコンの説明

<table>
    <thead>
        <tr>
            <th>アイコン</th><th>名前</th><th>説明</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><img src="../../images/refresh.gif" alt="更新アイコン"></td>
            <td>更新</td>
            <td>
                <p>
                    新着メッセージのチェックを行います。<br>
                    通常はガジェットの自動更新間隔(システム設定: デフォルト10分)でチェックが行われます。手動でチェックを行いたい場合はこのアイコンをクリックします。
                </p>
            </td>
        </tr>
        <tr>
            <td><img src="../../images/minimize.gif" alt="最小化アイコン"></td>
            <td>最小化</td>
            <td>
                <p>ガジェットを最小化します。最小化されているガジェットは、このアイコンが[元に戻す]アイコン<img src="../../images/restore.gif" alt-"元に戻すアイコン">に切り替わるので、これをクリックすることで元のサイズに戻ります。</p>
            </td>
        </tr>
        <tr>
            <td><img src="../../images/restore.gif" alt="元に戻すアイコン"></td>
            <td>元に戻す</td>
            <td>
                <p>最小化されているガジェットを元に戻します。</p>
            </td>
        </tr>
        <tr>
            <td><img src="../../images/maximize.gif" alt="最大化アイコン"></td>
            <td>最大化</td>
            <td>
                <p>ガジェットを最大化します。最大化されたメッセージガジェットの説明は後述を参照してください。</p>
            </td>
        </tr>
        <tr>
            <td><img src="../../images/show_hidden_icons.gif" alt="ガジェットメニュー表示アイコン"></td>
            <td>メニューを開く</td>
            <td>
                <p>ガジェットのメニューを開きます。</p>
            </td>
        </tr>
    </tbody>
</table>


## メニューの説明

メニューを開くアイコン![ガジェットメニュー表示アイコン][Gadget Menu icon]をクリックすると、ガジェットのメニューが開きます。

<table>
    <thead>
        <tr>
            <th>アイコン</th><th>名前</th><th>説明</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><img src="../../images/access.gif"/></td>
            <td>グループ編集</td>
            <td>グループ編集ウィンドウを表示します。グループ編集ウィンドウの説明は後述を参照してください。</td>
        </tr>
        <tr>
            <td><img src="../../images/trash.gif"/></td>
            <td>削除</td>
            <td>パーソナライズエリアからガジェットが削除されます。</td>
        </tr>
    </tbody>
</table>


## メッセージガジェットの最大化

ガジェットヘッダの最大化アイコンをクリックすると、最大化されたメッセージガジェットを表示します。

![最大化されたメッセージガジェット][message_gadget_maximize_jp]

<table>
    <thead>
        <tr>
            <th>番号</th><th>名前</th><th>説明</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>(1)</td>
            <td>ヘッダアイコン</td>
            <td>
                <p>
                    最大化されたメッセージガジェットの機能を実行するコントロール。<br>
                    各アイコンの説明は後述の表を参照。
                </p>
            </td>
        </tr>
        <tr>
            <td>(2)</td>
            <td>公開メッセージ</td>
            <td>
                <p>クリックすると公開メッセージ入力フォームを表示します。</p>
            </td>
        </tr>
        <tr>
            <td>(3)</td>
            <td>システムグループ</td>
            <td>
                <p>
                    <ul>
                        <li>
                            受信メッセージ<br>
                            クリックすると、メッセージ表示ペインに自身宛てのメッセージが表示されます。
                        </li>
                        <li>
                            送信メッセージ<br>
                            クリックすると、メッセージ表示ペインに自身が送信したメッセージ(公開メッセージを含む)が表示されます。
                        </li>
                        <li>
                            お知らせ<br>
                            クリックすると、メッセージ表示ペインにお知らせ送信されたメッセージが表示されます。
                        </li>
                        <li>
                            全ユーザーの公開メッセージ<br>
                            クリックすると、メッセージ表示ペインに全ユーザーの公開メッセージおよび自身宛てのメッセージが表示されます。
                        </li>
                    </ul>
                </p>
            </td>
        </tr>
        <tr>
            <td>(4)</td>
            <td>ユーザーグループヘッダ</td>
            <td>
                <p>
                    ユーザーグループ名称が表示されます。<br>
                    ユーザーグループ名称をクリックすると、メッセージ表示ペインにそのユーザーグループに所属する全てのユーザーの送信した公開メッセージおよび自身宛てのメッセージが表示されます。<br>
                    <img src="../../images/email_edit.gif" alt="メッセージ編集アイコン">アイコンをクリックすると、ユーザーグループに所属する全てのメンバー宛てのメッセージを送信するフォームが表示されます。
                </p>
            </td>
        </tr>
        <tr>
            <td>(5)</td>
            <td>ユーザーグループ</td>
            <td>
                <p>
                    作成したユーザーグループに所属するユーザーの一覧が表示されます。<br>
                    ユーザー名称をクリックすると、メッセージ表示ペインに対象ユーザーの送信した公開メッセージおよび自身宛てのメッセージが表示されます。<br>
                    <img src="../../images/email_edit.gif" alt="メッセージ編集アイコン">アイコンをクリックすると、対象ユーザー宛てのメッセージを送信するフォームが表示されます。
                </p>
            </td>
        </tr>
        <tr>
            <td>(6)</td>
            <td>メッセージ表示ペイン</td>
            <td>
                <p>
                    選択されたメッセージの一覧が表示されます。<br>
                    <img src="images/widget/message-gadget-6.jpg" alt="メッセージ一覧"><br>
                    <ul>
                        <li>
                            ユーザー名称<br>
                            クリックすると、⑤のユーザー名称クリック時と同様の動作をします。
                        </li>
                        <li>
                            返信する<br>
                            クリックすると、メッセージ発信者宛てのメッセージを送信するフォームが表示されます。
                        </li>
                    </ul>
                </p>
            </td>
        </tr>
    </tbody>
</table>


## 最大化時のヘッダアイコンの説明

<table>
    <thead>
        <tr>
            <th>アイコン</th><th>名前</th><th>説明</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><img src="../../images/refresh.png" alt="更新アイコン"></td>
            <td>更新</td>
            <td>
                <p>
                    新着メッセージのチェックを行います。<br>
                    通常はガジェットの自動更新間隔(システム設定: デフォルト10分)でチェックが行われます。手動でチェックを行いたい場合はこのアイコンをクリックします。
                </p>
            </td>
        </tr>
        <tr>
            <td><img src="../../images/access.gif" alt="グループ編集アイコン"></td>
            <td>グループ編集</td>
            <td>
                <p>グループ編集ウィンドウを表示します。グループ編集ウィンドウの説明は後述を参照してください。</p>
            </td>
        </tr>
        <tr>
            <td><img src="../../images/restore.gif" alt="元に戻すアイコン"></td>
            <td>元に戻す</td>
            <td>
                <p>最大化されているガジェットを元に戻します。</p>
            </td>
        </tr>
    </tbody>
</table>


## グループ編集ウィンドウ

システム管理者がユーザー検索設定を行っている場合、ユーザーを検索して自身の作成したグループに追加することができます。

![グループ編集ウィンドウ(ユーザー検索有り)][message_gadget_groupmodal_search_jp]

システム管理者がユーザー検索設定を行っていない場合、以下のような画面が表示され、ユーザーIDを指定して自身の作成したグループに追加することができます。

![グループ編集ウィンドウ(ユーザー検索無し)][message_gadget_nosearch]

<table>
    <thead>
        <tr>
            <th>番号</th><th>名前</th><th>説明</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>(1)</td>
            <td>グループタブ</td>
            <td>
                <p>
                    登録したグループの名称が表示されます。<br>
                    <img src="../../images/edit.gif" alt="名称変更アイコン">をクリックすると、グループ名称の変更を行うことができます。<br>
                    <img src="../../images/x.gif" alt="タブ削除アイコン">アイコンをクリックすると、グループを削除します。
                </p>
            </td>
        </tr>
        <tr>
            <td>(2)</td>
            <td>グループ追加</td>
            <td>
                <p>クリックすると、グループを追加登録することができます。</p>
            </td>
        </tr>
        <tr>
            <td>(3)</td>
            <td>ユーザー表示ペイン</td>
            <td>
                <p>
                    グループに所属しているユーザー情報が以下のフォーマットで表示されます。<br>
                    <code>[ユーザー名称]([ユーザーID]) [メールアドレス] [組織名]</code><br>
                    <img src="../../images/trash.gif" alt="削除アイコン">アイコンをクリックすると、グループからユーザーを削除します。
                </p>
            </td>
        </tr>
        <tr>
            <td>(4)</td>
            <td>検索フォーム</td>
            <td>
                <p>
                    ユーザー名、メールアドレス、所属組織を条件にしてグループに追加するユーザーを検索することができます。<br>
                    条件を入力し、検索ボタンをクリックすると入力条件で中間一致検索を行い、以下のように検索結果が表示されます。<br>
                    <img src="images/widget/message-gadget-9.jpg" alt="ユーザー検索フォーム"><br>
                    検索結果のユーザー名左のチェックボックスにチェックを入れ、ユーザー追加ボタンをクリックすることで選択中のグループにユーザーを追加することができます。
                </p>
            </td>
        </tr>
        <tr>
            <td>(5)</td>
            <td>閉じる</td>
            <td>
                <p>グループ編集ウィンドウを閉じます。</p>
            </td>
        </tr>
        <tr>
            <td>(6)</td>
            <td>ユーザー追加フォーム</td>
            <td>
                <p>ユーザーIDを入力してユーザー追加ボタンをクリックすると、選択中のグループにユーザーを追加することができます。</p>
            </td>
        </tr>
    </tbody>
</table>


## 新着メッセージチェック

ガジェットの自動更新間隔(システム設定: デフォルト10分)によりメッセージガジェットが更新された、または![更新アイコン][Refresh icon]アイコンによる手動更新が行われた場合、infoScoopのヘッダに通知メッセージが表示されます。  
ただし、若干のタイムラグがある場合があります。

![新着メッセージ通知][message_gadget_notice_jp]

通知「新着メッセージが届いています。」をクリックすると、メッセージガジェットが最大化状態で表示されます。


[message_gadget_jp]: images/widget/message-gadget-1.jpg "メッセージガジェット"
[message_gadget_maximize_jp]: images/widget/message-gadget-5.jpg "最大化されたメッセージガジェット"
[message_gadget_groupmodal_search_jp]: images/widget/message-gadget-7.jpg "グループ編集モーダル(ユーザー検索有り)"
[message_gadget_nosearch]: images/widget/message-gadget-8.png "グループ編集モーダル(ユーザー検索無し)"
[message_gadget_notice_jp]: images/widget/message-gadget-10.jpg "新着メッセージ通知"
[Gadget Menu icon]: ../../images/show_hidden_icons.gif
[Refresh icon]: ../../images/refresh.gif "更新アイコン"
