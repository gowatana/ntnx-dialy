# AHV Processor Generation Compatibility

CPUモデルが異なるAHVでマルチ ノード クラスタを構成して、CPU 命令セット マスクの変化を確認してみる。

virsh dumpxml あたりを確認してみる。
- https://blog.ntnx.jp/entry/2018/12/09/223553

## 1. シングル ノードの Nutanix CE クラスタ x2 を構成

* Nutanix CE #1： CPU モデル1
* Nutanix CE #2： CPU モデル2

## 2. VM を起動して virsh dumpxml を確認

* Nutanix CE #1： CPU モデル1
* Nutanix CE #2： CPU モデル2

## 3. 3ノード以上の Nutanix CE クラスタを構成

Nutanix AHV クラスタの構成
* ネストで構成する。
* Prism Central なし。

## 4. Linux VM を作成 / 起動して、virsh dumpxml を確認

下記の構成で取得した dumpxml と比較してみる。
* Nutanix CE #1： CPU モデル1
* Nutanix CE #2： CPU モデル2
