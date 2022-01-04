# Bakery Dataset Pre-Process
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/shinichi-oto/1567-S-E-qwsa/HEAD?labpath=bakery_01.ipynb)

-----
# Introduction
- このNotebookではデータ処理に焦点を当てているので予測モデルの作成は行っていません。EDAも行っていません。

- メモリに乗りきらないデータセットの処理方法をDASK.DataFrameを使用して処理速度を上げながら効率化を図り処理する方法をNotebookとして作成しています。
- DASKライブラリは並列処理を行えるので、CPUコアをフルに使用しデータセットを処理できるので、処理速度の向上を図れます。
>[DASKライブラリ](https://docs.dask.org/en/stable/)
