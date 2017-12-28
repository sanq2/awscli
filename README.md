# awscli
## AWS CLI install
1. pip install
```
curl -kL https://bootstrap.pypa.io/get-pip.py | python
```
2. awscli install
```
pip install awscli --upgrade --user
```
ref.) http://docs.aws.amazon.com/ja_jp/cli/latest/userguide/installing.html

## configure
### 1. access key & secret key
- Step 1: Create a new access key, which includes a new secret access key.
  - ref.) https://console.aws.amazon.com/iam/home?region=us-east-1#/users
- Step 2: choose your IAM user
- Step 3: click [security_credentials:認証情報] tab 
- Step 4: click [create access key:アクセスキー作成] button
- Step 5: download new credentials csv file and [show] click
- Step 6: done
  - **※ If you already have the maximum of access keys(limit:5) you must delete one first before proceeding.**
### 2. aws configure
- Step 1: open a command line console or terminal
- Step 2: type command
```
aws configure
```
- Step 3: type your access key ID
- Step 4: type your secret key
- Step 5: type your region name
- Step 6: done

