## Projeto consiste em provisionar Security group usando data source para obter vpc id através da tag name da vpc

### Baixe o projeto
```bash
git clone https://github.com/deividduarte20/terraform-aws-sg.git
```

### Inicie o terraform
```bash
terraform init
```

### Aplique a infra como código
```bash
terraform apply
```

## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.0.3 |
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | >= 3.74.3 |
| <a name="requirement_git"></a> [git](#requirement\_git) | >= 2.10.1 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | 4.49.0 |


## Resources

| Name | Type |
|------|------|
| [aws_security_group.rules_access](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/security_group) | resource |
| [aws_vpc.selected](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/vpc) | data source |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_sg_number"></a> [sg\_number](#output\_sg\_number) | n/a |
