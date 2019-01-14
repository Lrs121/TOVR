![DL Count](https://img.shields.io/github/downloads/turtle-insect/TOVR/total.svg)

# 寄付
<a href="https://www.buymeacoffee.com/06yi7RLlT" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/black_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

# 概要
Switch テイルズ オブ ヴェスペリア REMASTERのセーブデータ編集Tool

# ソフト
* https://tov10th.tales-ch.jp/remaster/
* https://ec.nintendo.com/JP/ja/titles/70010000004646

# 実行に必要
* Windows マシン
* .NET Framework 4.7.2の導入
* セーブデータの吸い出し
* セーブデータの書き戻し

# Build環境
* Windows 10(64bit)
* Visual Studio 2017

# 編集時の手順
* saveDataを吸い出す
   * 結果、以下が取得可能
      * TLAchData
      * TLSaveData0-00(他)
      * TLSettings
* TLSaveData0-00(他)を読み込む
* 任意の編集を行う
* TLSaveData0-00(他)を書き出す
* saveDataを書き戻す
