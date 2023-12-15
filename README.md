This project illustrates the process of  creating reusable infrastructure with Terraform modules, optimizing your deployment process. 

Through this project we will discover how modules empower scalability and efficiency in infrastructure as code, making setups smoother and more repeatable.

Attached to this repository is my Terraform project in the TERRAFORM-MODULES-MAIN-2 Repo

terraform-modules folder which contains 
1)(my ec2-ansible-docker directory from zhere ze zill be running our commands)

2)Modules repo in which i have the VPC repo(with main.tf variables.tf outputs.tf e2.cf)

From the ec2-ansible-docker directory we will initialise terraform by passing the 

"terraform init" command

![terraform init command](<Screenshot 2023-12-13 at 12.20.02.png>)

thereafter we will enter the 

"terraform apply" command to apply the configurations on our .tfvars files and state which availability zone you will want to create your resources in.

the result should look like on the image below if successful 

![Result of terraform apply](<Screenshot 2023-12-13 at 12.44.32.png>)

the image below will illustrate the instance created on AWS development environment eu-west-1

![AWS Instance created](<Screenshot 2023-12-13 at 12.49.34.png>)

![after connecting to the created instance](<Screenshot 2023-12-13 at 12.56.03.png>)

then to ensure that docker was installed we pass the docker command and had the follozing result

![docker installed](<Screenshot 2023-12-13 at 12.56.49.png>)

and also for the eu-central-1

![docker installed](<Screenshot 2023-12-13 at 17.32.56.png>)

