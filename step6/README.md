# Step6: Variables
https://developer.hashicorp.com/terraform/tutorials/aws-get-started/aws-variables

## 前提条件
step5まで使用したmain.tfを使用

## 概要
variables.tfで変数を定義してaws_instance.app_server.tags.Nameの値を指定
変数の値はコマンドから指定することができる
```
$ terraform apply -var "instance_name=YetAnotherName"
```
コマンドで指定した変数の値はどこにも保存されない

