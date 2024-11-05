# 管理者不在のCloud 9環境に権限付与する方法
## SSO方式に変わり、以前の環境に入れなくなったとき用
Cloudshellから以下コマンドを実行する。
<UserARN>は右上のフェデレーティッドユーザー部分を転記する。
```
aws cloud9 create-environment-membership --environment-id <環境ID> --user-arn <UserARN> --permissions <Permission> 
```
