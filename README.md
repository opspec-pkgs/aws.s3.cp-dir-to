# problem statement
copies a dir to s3

# example usage

> note: in examples, VERSION represents a version of the aws.s3.cp-dir-to pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/aws.s3.cp-dir-to#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/aws.s3.cp-dir-to#VERSION
```

## compose

```
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/aws.s3.cp-dir-to#VERSION }
    inputs: { srcDir, s3URI, AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, AWS_DEFAULT_REGION }
```
