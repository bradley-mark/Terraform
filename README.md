# Terraform

**Windows binary download**

**https://developer.hashicorp.com/terraform/downloads**

2/7 - latest version 1.3.7

1. Create **C:\Terraform** folder and copy terraform.exe
2. Run **terraform -version** at CMD

![image](https://user-images.githubusercontent.com/91480603/217376202-6ab6726e-aa21-4f33-8164-ff4bf413bd65.png)

3. Run **terraform init** at CMD

![image](https://user-images.githubusercontent.com/91480603/217376468-50222e09-53fa-48a6-9cd6-4c1b5aeb2196.png)

4. If required update system global path to include environment variable **C:\Terraform**

# AWS CLI

1. Run **AWS configure** enter access keys from user with permissions

![image](https://user-images.githubusercontent.com/91480603/217604759-daf54850-03bd-4cc9-abf2-e929a7a208b7.png)

![image](https://user-images.githubusercontent.com/91480603/217604838-ec4d2e6c-e2af-4a17-a1f9-6d5277549d49.png)

# Simple example

**example.tf** creates an EC2 **t2.micro** instance using **ami-2757f631** in **us-east-1**

![image](https://user-images.githubusercontent.com/91480603/217601984-435f85c0-457c-46cc-93b6-fe4f3c032977.png)

1. Run **terraform apply** within terraform folder that includes **example.tf** file

![image](https://user-images.githubusercontent.com/91480603/217601382-e4c4f823-7cc9-4804-9271-6daf25bc61db.png)

2. Enter a value **yes**

![image](https://user-images.githubusercontent.com/91480603/217601541-98279b12-09b8-4389-9cee-bd5c9ef6a29f.png)

3. Review status

![image](https://user-images.githubusercontent.com/91480603/217602561-46d4f93c-e621-4ad4-a233-fb0acd141700.png)

4. Validate EC2 instance

![image](https://user-images.githubusercontent.com/91480603/217602907-617fbe29-6bf9-4456-b8db-6ec4c973600b.png)



