# fastai-vpc
Default virtual private cloud configuration for [fastai](http://course.fast.ai/) on Amazon Web Services.

## Setup

1. [Install Terraform](https://www.terraform.io/intro/getting-started/install.html)
2. Clone this repository
3. *Optional* To see what the script will do, execute the command `terraform plan` from the `fastai-vpc` directory  
4. Execute `terraform apply` to create the VPC
    
    ```
    $ terraform apply
    ````
    
5. **Note**: if you plan to use version control, add your `.tfvars` file to `.gitignore`
