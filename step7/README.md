# Step7: Outputs
https://developer.hashicorp.com/terraform/tutorials/aws-get-started/aws-outputs

## 前提条件
step6までの作業を終わらせてること

## 概要
指定の情報を出力できるようにする、今回はinstanceのIDとそのインスタンスのpublic ip
出力設定はoutputs.tfに記述

applyを実行した後にoutputs.tfで記述した内容が出力
```
$ terraform apply
```

指定の情報のみを取得したい場合はoutputを実行する
```
$ terraform output
```

