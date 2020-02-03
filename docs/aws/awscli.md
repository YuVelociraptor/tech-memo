# AWS CLI

## install
```
pip install awscli
```

## configure
```
aws configure --profile ローカル管理の名前
```

```
aws コマンド --profile ローカル管理の名前
```

```
export AWS_PROFILE=ローカル管理の名前
```


## s3
### バケットの一覧を表示する
```
aws s3 ls
```

### ローカルと同期（削除なし）
```
aws s3 sync {フォルダパス} s3://{バケット名}/{パス}
```
### ローカルと同期（削除あり）
```
aws s3 sync {フォルダパス} s3://{バケット名}/{パス}
```