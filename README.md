# SES Lambda Terraform demo

## FIXME
* Tighter iam policy for ses kms decryption, currently any SES Service can use the kms key

## Terraforming

### Create the setup
```
$ terraform apply
```

## Destroy the setup
If you uploaded something into the s3 buckets you need to use `-force`
```
$ terraform destroy -force
```
