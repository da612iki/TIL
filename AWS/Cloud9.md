# 管理者不在のCloud 9環境に権限付与する方法
## SSO方式に変わり、以前の環境に入れなくなったとき用
```
aws cloud9 create-environment-membership --environment-id <環境ID> --user-arn <UserARN> --permissions <Permission> 
```
