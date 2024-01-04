# AHV + Terraform

このRepoのサンプルを最新化して、ブログ投稿にする。
- https://github.com/gowatana/demo-terraform-nutanix

1. 環境準備、PC / PE 接続確認
   * 基本的に、Prism Central 経由にしておく

2. インフラ作成（Network/IPAM、Image など）
   * 既存リソースの Data Source についても説明する。
   * Nutanix クラスタの UUID は、クラスタ名から引く。

3. VM 作成 / 削除
   * OS の vDisk は、Image Serviceからクローン

4. できたら、cloud-init or ansible 連携
