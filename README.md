# GIS Day in 東京 2022 Eコース「GeoPandasを用いた地理情報プログラミング入門」リポジトリ

* 東京都立大学 都市環境学部 地理環境学科 中山大地
* 2022年11月26日 東京都立大学 南大沢キャンパス
* このテキストのURL [https://github.com/bokutachi256/gisday2022](https://github.com/bokutachi256/gisday2022)
* Google ColaboratoryのURL [https://colab.research.google.com/](https://colab.research.google.com/)

# 使用データ
* 国土数値情報
  * 鉄道時系列データ（令和3年版）
    * [`https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N05-v2_0.html`](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N05-v2_0.html)
    * `utf8` フォルダ内の`N05-21_RailroadSection2.geojson`と`N05-21_Station2.geojson`を使用．
  * 公共施設（平成18年版）
    * [`https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-P02-v4_0.html`](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-P02-v4_0.html)
    * 全都道府県のファイルを結合して使用．
  * 行政区域（平成28年）
    * [`https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N03-v3_1.html`](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N03-v3_1.html)
    * 平成28年の全国データ（`N03-22_220101`）を使用．
* e-Stat
  * 市区町村別ごとの総人口と年齢3区分データ（2015年度）
    * [`https://www.e-stat.go.jp/regional-statistics/ssdsview/municipality`](https://www.e-stat.go.jp/regional-statistics/ssdsview/municipality)
    * 全市区町村の総人口（A1101）と年齢3区分（A13）を使用

# 実習用データの準備とGoogle Driveの設定
1. [共有データフォルダ（https://drive.google.com/drive/folders/1a3xEnnfz1J6yQ2AMNqM3MqniVs-P_3pi?usp=share_link）](https://drive.google.com/drive/folders/1a3xEnnfz1J6yQ2AMNqM3MqniVs-P_3pi?usp=share_link)にアクセスします．
1. 右上のログインボタンを押してGoogle Driveにログインします．<img width="1015" alt="screenshot" src="https://user-images.githubusercontent.com/12523507/204067502-43dd8455-b41d-43ed-93f6-3318376e0583.png">

2. 左側の「共有アイテム」を押し，共有アイテムの「gisday2022」を右クリックして「ドライブへのショートカットを追加」を選びます．
3. 「マイドライブ」を選んで「ショートカットを追加」ボタンを押します．
4. 左側の「マイドライブ」押してマイドライブを表示すると，「gisday2022」フォルダが追加されています．
5. 左上の「新規」ボタンを押して「新しいフォルダ」を選びます．
6. フォルダ名を「gisday2022_export」にします．
7. これでGoogle Driveの設定は完了です．
