# 「ゼロから学ぶPythonプログラミング」訂正

注意深く執筆したつもりですが、現時点で以下のミスや修正点が見つかっております。ご迷惑をおかけして申し訳ありません。

他に誤りや修正すべき点を見つけた方は、[GitHubのIssue](https://github.com/kaityo256/python_zero/issues)にてご指摘いただければ幸いです。

最終更新日：2021年1月22日

| ページ番号 | 誤 | 正 |
| ---  | --- | --- |
| p. 10 | 「2. 五芒星の描画」のコードの2行目 <br>`draw = ImageDraw.raw(im)` | <br> `draw = ImageDraw.raw(img)`|
| p. 66 | 12行目 <br>「8ビットが0でない」 | <br>「8ビット**目**が0でない」 |
| p. 124| 図8.3のクラスのコードのインデントが不正。 <br> ![図8.3誤](fig/fig08_3_error.jpg)| 正しいインデントは以下の通り。<br> ![図8.3正](fig/fig08_3_correct.jpg)|
| p. 124| 図8.4のメッセージが「`c = Counter()`」 <br> ![図8.4誤](fig/fig08_4_error.jpg)| 正しくは`c.count()` <br> ![図8.4正しい](fig/fig08_4_correct.jpg)|
| p. 161| 図10.7のBINARY_MULTIPLYの箱のラベルが誤っている<br> ![図10.7誤](fig/fig10_7_error.jpg) | 正しくは以下の通り。<br> ![図10.7正](fig/fig10_7_correct.jpg) |
| p. 174| 図11.6のAとCの間のコストが2 ![図11.6誤](fig/fig11_6_error.jpg) |AとCの間のコストは7 ![図11.6正](fig/fig11_6_correct.jpg)  |
| p. 174| 図11.7のAとCの間のコストが2 ![図11.7誤](fig/fig11_7_error.jpg) |AとCの間のコストは7 ![図11.6正](fig/fig11_7_correct.jpg)  |
| p. 188| 「random.randint」から2行目<br>「これは6面サイコロを10回ふることを」| <br>「これは6面サイコロを**5**回ふることを」
