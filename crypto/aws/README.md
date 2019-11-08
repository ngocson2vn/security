## Command
```bash
$ keyID=<KMS_KEY_ID>
$ aws-encryption-cli --encrypt --input secret.txt --master-keys key=$keyID --encryption-context purpose=test --metadata-output ../metadata/test.txt --output .
```
