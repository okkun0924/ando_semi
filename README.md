# 安藤ゼミ PythonDataScienceHandbook 3.12.7 (グループ１)
## 該当範囲　
<https://jakevdp.github.io/PythonDataScienceHandbook/03.11-working-with-time-series.html>

## 各種関数の補足
### eval() 
<https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.eval.html?highlight=eval#pandas.eval>
>The eval() function in Pandas uses string expressions to efficiently compute operations using DataFrames. For example, consider the following DataFrames

### dropna(), describe()
dropna:欠損値(nan)を落とす引数指定で色々できる
describe:統計量の表示
### resample()
時系列データをより高い・低い頻度でサンプリングし直す。アップサンプリング(短い周期)とダウンサンプリング(長い周期)がある。
ここではリサンプリングした値にsum()メソッドを使って和の値を返している。
need to convert RangeIndex into DateTimeIndex for using resample() fanc.
<https://note.nkmk.me/python-pandas-time-series-resample-asfreq/>
<https://stackoverflow.com/questions/48248239/pandas-how-to-convert-rangeindex-into-datetimeindex>
<https://note.nkmk.me/python-pandas-time-series-datetimeindex/>
### rolling()
窓関数の適用。
元のデータ点ごとに指定範囲の統計量を算出するのがrolling()で、指定範囲ごとにデータを集約するのがresample()。
<https://note.nkmk.me/python-pandas-rolling/>
<https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.rolling.html>
### groupby()
同じ値を持つデータをまとめて、それぞれの塊に対して共通の操作を行いたい時に使う。
<https://qiita.com/propella/items/a9a32b878c77222630ae>
### where()
`numpy.where(condition[, x, y])`
>Return elements, either from x or y, depending on condition.
If only condition is given, return condition.nonzero().
<https://note.nkmk.me/python-numpy-where/>
### subplotについて、ix,loc,ilocの違い
<http://ailaby.com/lox_iloc_ix/>
dfのcolumnとrowを指定する方法
## グループメンバー
okkun0924 YosukeHoshi takumaosada

### 教科書の画像
![p.203](https://user-images.githubusercontent.com/29570642/58529286-3bc1ee00-8215-11e9-8af2-2c4fccc7f8eb.JPG)
![p.204](https://user-images.githubusercontent.com/29570642/58529287-3bc1ee00-8215-11e9-80d0-5fdeff02da85.JPG)
![p.205](https://user-images.githubusercontent.com/29570642/58529288-3bc1ee00-8215-11e9-879f-6f31c32d4924.JPG)
![p.206](https://user-images.githubusercontent.com/29570642/58529289-3c5a8480-8215-11e9-9c97-59fbba4ff254.JPG)
![p.207](https://user-images.githubusercontent.com/29570642/58529290-3c5a8480-8215-11e9-8602-0dfe234aa663.JPG)
![p.208](https://user-images.githubusercontent.com/29570642/58529291-3c5a8480-8215-11e9-95fb-edf11aa65adc.JPG)
![p.209](https://user-images.githubusercontent.com/29570642/58529292-3c5a8480-8215-11e9-8c34-194aeed6c364.JPG)


## グループメンバー
okkun0924 YosukeHoshi takumaosada
