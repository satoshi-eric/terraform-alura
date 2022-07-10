# terraform-alura
Cursos de Terraform da Alura

**Configurar IAM**: usuário com privilégio de ADM

**Baixar csv**: arquivo de configurações

**Configurar usuário CLI**: `aws configure`

**VSCode**: Extensão Terraform

**Criar chave ssh**
`ssh-keygen -f <nome> -t <algoritmo>`
`ssh-keygen -f terraform-aws -t rsa`
Na AWS importar chave

**Aplicar mudanças**:
```
terraform init
terraform plan
terraform apply
```

**Mostrar estado dos recursos**:
```
terraform show
```

**Remover recursos**:
```
terraform destroy -target aws_s3_bucket.dev4
```
Remove recurso e suas dependencias

**Restart**
```
terraform refresh
```

