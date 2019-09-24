# AWS CLI

## install
```
pip install awscli
```

## s3
### ローカルと同期（削除なし）
```
aws s3 sync {フォルダパス} s3://{バケット名}/{パス}
```
### ローカルと同期（削除あり）
```
aws s3 sync {フォルダパス} s3://{バケット名}/{パス}
```