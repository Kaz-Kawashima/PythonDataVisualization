# PythonDataVisualization
A Comparison of Python Data Visualization Libraries

このリポジトリでは Python の データ可視化ライブラリを比較します。調査対象のライブラリは下記のとおりです。

- データフレームライブラリ
  - `Pandas`
  - `Polars`
- 高水準作図ライブラリ
  - `seaborn` `seaborn.object`
  - `plotly express`
  - `altair`
  - `plotnine`
  - `HvPlot`
- 低水準作図ライブラリ
  - `matplotlib`
  - `plotly`
  - `bokeh`
  - `holoview`

データフレームのライブラリとして `Pandas` と `Polars` を試していますが、メジャーなデータ可視化ライブラリはどちらにも対応しているケースが多いようです。

## 動的グラフ

下記のライブラリは javascript を利用して動的グラフを生成します。github上では実行結果が確認できないので、html ファイルを確認してみて下さい。一部のライブラリはオフラインの html 出力もうまく行かないので（なんらかのおまじないが必要）その場合は jupyter notebook を実行してみて下さい。

- 高水準作図ライブラリ
  - `plotly express`
  - `altair`
  - `HvPlot`
- 低水準作図ライブラリ
  - `plotly`
  - `bokeh`
  - `holoview`

## Line Plot

厚労省の COVID-19 感染者数データをもとに、日別の新規感染者数を折れ線グラフを描画してみます

![Line Plot Altair](/figs/LinePlotAltair.png)

## Bar Plot

厚労省の COVID-19 感染者数データをもとに、累積の感染者数を棒グラフを描画してみます

![Bar Plot Plotly](/figs/BarPlotPlotly.png)

##  Facet Plot

タイタニックデータから、船室/性別 による生存/死亡 の棒グラフを描画してみます

![Facet Plot Seaborn](/figs/FacetPlotsSeaborn.png)

## Box Like Plot

Scikit Learn に付属しているダイヤモンドデータから、箱ひげ図やバイオリンプロットを描画してみます

![Box Plot plotnine](/figs/BoxPlotPlotnine.png)

