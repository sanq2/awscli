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
  - ref.) [http://docs.aws.amazon.com/ja_jp/cli/latest/userguide/installing.html](http://docs.aws.amazon.com/ja_jp/cli/latest/userguide/installing.html)
  - If you have a Mac, type this 1 line command done!
  ```
  brew install awscli
  ```

## configure
### 1. access key & secret key
- Step 1: Create a new access key, which includes a new secret access key.
  - ref.) [https://console.aws.amazon.com/iam/home?region=us-east-1#/users](https://console.aws.amazon.com/iam/home?region=us-east-1#/users)
- Step 2: choose your IAM user
- Step 3: click [security_credentials: 認証情報] tab
- Step 4: click [create access key: アクセスキー作成] button
- Step 5: download new credentials csv file and [show] click
- Step 6: done

<font color="Tomato">caution: If you already have the maximum of access keys(**limit: 5**) must be delete one first before proceeding.</font>

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
