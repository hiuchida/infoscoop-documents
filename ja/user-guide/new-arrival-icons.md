# 新着アイコン

RSSリーダー、お知らせは、表示された記事に新着を示す太陽マークが表示されます。

![太陽マークの表示][The latest mark]

新着記事に表示される太陽マークは二種類あります。

* 初めて表示された記事に表示される、点滅する太陽マーク。
* 比較的最近に表示された記事に表示される、回転しない太陽マーク。

回転しない太陽マークが表示される記事の条件は、

* 全体設定のfreshDays日以内の日付をもつ記事であること
* 前回ログオフした時間より新しい日付をもつ記事であること

のどちらか(あるいは両方)を満たした記事に太陽マークが表示されます。

回転する太陽マークが表示される条件は、上記の回転しない太陽マークが表示される条件を満たした上で、

* 前回取得した最初の記事(RSS内の並びで最初に書かれた記事)の日付よりも新しい日付をもつ記事

である必要があります。


## 新着を全て表示アイコンについて

RSSリーダーに新着記事が含まれる場合、RSSリーダーを最小化するとヘッダのタイトル右側に太陽マークと新着記事数が表示されます。

RSSリーダー最小化時の記事数は、新着記事数/全記事数の順で表示されます。

![RSSリーダー最小化時の表示][Display of article count when the RSS Reader is minimized]

表示された[新着を全て表示]アイコンをクリックするとRSSリーダーが新着を全て表示する状態になり、ガジェットの高さが新着件数に応じて調整されます。

**注意** RSSリーダー内の記事が日時順でソートされていなかった場合には全ての新着記事を表示する事は出来ません。

![全ての新着記事][All new arrival articles]


[The latest mark]: images/etc/new-arrival-icons-1.png "太陽マークの表示"
[Display of article count when the RSS Reader is minimized]: images/etc/new-arrival-icons-2.png "RSSリーダー最小化時の表示"
[All new arrival articles]: images/etc/new-arrival-icons-3.png "全ての新着記事"
