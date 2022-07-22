# mixjuice-getNewDate-api
## https://mixjuice-get-date.herokuapp.com/
## https://fukuno.jig.jp/app/IchigoJam/#10%20%3F%22MJ%20GETS%20mixjuice-get-date.herokuapp.com%22%0A
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/MixJuice?src=hash&amp;ref_src=twsrc%5Etfw">#MixJuice</a> で現在の日時を取得するapiを作りました。<a href="https://t.co/XizMOAcweP">https://t.co/XizMOAcweP</a><br><br>シンプルですが色んなことができそうです。 <a href="https://twitter.com/hashtag/IchigoJam?src=hash&amp;ref_src=twsrc%5Etfw">#IchigoJam</a> でのIoT制作などにお役立てください。<br><br>▼src on GitHub▼<a href="https://t.co/7Yi6lf6pYI">https://t.co/7Yi6lf6pYI</a> <a href="https://t.co/mQXTFVVrwD">pic.twitter.com/mQXTFVVrwD</a></p>&mdash; 初代 *Hana道場【師範】 (@shoichi1031da) <a href="https://twitter.com/shoichi1031da/status/1550497997494321152?ref_src=twsrc%5Etfw">July 22, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

以下のコマンドをIchigoJam（MixJuice）もしくはIchigoJam web（仮想MixJuice）で実行してください。

?"MJ GETS mixjuice-get-date.herokuapp.com/"

### IchigoJamの配列に下記の日時データが格納されます。
<ul>
<li>[0]:年</li>
<li>[1]:月</li>
<li>[2]:日</li>
<li>[3]:時</li>
<li>[4]:分</li>
<li>[5]:秒</li>
</ul>

### 配列の開始番号はデフォルトで0番ですが、URLのパラメーターに「i=開始番号」を追記することができます。

例）i=50の場合

?"MJ GETS mixjuice-get-date.herokuapp.com/?i=50"

<ul>
<li>[50]:年</li>
<li>[51]:月</li>
<li>[52]:日</li>
<li>[53]:時</li>
<li>[54]:分</li>
<li>[55]:秒</li>
</ul>
