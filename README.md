# Create lamda api gateway with terraform

## What is Terraform?

<p>
HashiCorp Terraform is an infrastructure as code tool that lets you define both cloud and on-prem resources in human-readable configuration files that you can version, reuse, and share. You can then use a consistent workflow to provision and manage all of your infrastructure throughout its lifecycle. Terraform can manage low-level components like compute, storage, and networking resources, as well as high-level components like DNS entries and SaaS features.
</p>


## Project structure

```
.
├── hello-world
│   └── hello.js
├── hello-world.zip
├── main.tf
├── outputs.tf
├── README.md
├── terraform.tfstate
└── terraform.tfstate.backup
```

## Commands to create an instance

```
terraform init
```

![terraform init"](resources/img_1.jpeg)

```
terraform apply -auto-approve
```

![terraform apply -auto-approve"](resources/img_2.jpeg)
![terraform apply -auto-approve-3"](resources/img_3.jpeg)
![terraform apply -auto-approve-4"](resources/img_4.jpeg)
![terraform apply -auto-approve-5"](resources/img_5.jpeg)


## Consume the hello world endpoint 1

![terraform apply -auto-approve-5"](resources/img_7.jpeg)

## Consume the hello world endpoint 2

![terraform apply -auto-approve-5"](resources/img_6.jpeg)

```
terraform destroy
```
![terraform apply -auto-approve-5"](resources/img_8.jpeg)

