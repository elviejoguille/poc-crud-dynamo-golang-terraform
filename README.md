# poc-crud-dynamo-golang-terraform

[![go](https://img.shields.io/badge/go-v1.14.4-5C4EE5.svg)](https://golang.org/)

## Quickstart

##### Environment Variables

```shell script
export AWS_ACCESS_KEY_ID="123456"
export AWS_SECRET_ACCESS_KEY="XXXXXX"
export AWS_SESSION_TOKEN="XXXXXXX"
```

##### Generate lambdas
```shell script
lambdas/./generate-lambdas
```

##### Create infrastructure
```shell script
terraform plan
terraform apply
```

## Another Similar Resources

- [PoC INTEGRACIÓN GRAPHQL POR MEDIO DE AWS APPSYNC Y MONGO UTILIZANDO LAMBDAS EN GOLANG](https://youtube.com/playlist?list=PL2gu2Qe_CGFmI_56oEuKW50_0_Rjw2PZD)
- [PoC Web Socket AWS, Terraform y Golang](https://www.youtube.com/playlist?list=PL2gu2Qe_CGFlZnQh2DEAbXSX30DsuOPB5)
- [ECS cn MS desarrollado en Golang y terraform](https://www.youtube.com/playlist?list=PL2gu2Qe_CGFn1pP049P7bXlukz3yk-EEL)
- [Introduccion a Performance Testing](https://www.youtube.com/playlist?list=PL2gu2Qe_CGFkZi0hTHWqq5J00T4gHRsZN)
- [Introduccion a K6](https://www.youtube.com/playlist?list=PL2gu2Qe_CGFmtELbhKS6bJyJNOukP5_AO)
- [Jmeter Remote Testing](https://www.youtube.com/playlist?list=PL2gu2Qe_CGFlBnBBHxFv2-fJOnGGqkWMr)


## Instalando terraform

Instalar un gestor https://github.com/tfutils/tfenv

for linux and ubuntu
git clone --depth=1 https://github.com/tfutils/tfenv.git ~/.tfenv
echo 'export PATH="$HOME/.tfenv/bin:$PATH"' >> ~/.zprofile
source ~/.zprofile
tfenv
tfm list
tfenv install
tfenv list
tfenv use 1.13.5

```shell script
$ terraform -version
```
Terraform v1.13.5
on linux_amd64