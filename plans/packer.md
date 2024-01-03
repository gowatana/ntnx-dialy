# AHV + Packer

Packer の Nutanix Plugin を試す。

* https://github.com/nutanix-cloud-native/packer-plugin-nutanix/tree/main

## 確認したいこと
* AHV イメージ サービスとの連携
* Nutanix 外部へのイメージ保存方法。disk image ファイル、または OVF エクスポートの方法
* cloud-init 対応のイメージを作成できるか

使用するディストリビューションの候補
* Oracle Linux 9
* CentOS 9
* RHEL 9
* Oracle Linux 8

## 参考情報
* CAPX の Image Builder
  https://blog.ntnx.jp/entry/2023/12/13/032701
