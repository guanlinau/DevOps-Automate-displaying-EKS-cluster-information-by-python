### Automate displaying EKS cluster information by python

### Technologies used:
AWS EKS, Git, Python, Boto3

### Project Description:

1-Automate provisioning EKS cluster with Terraform

2-Write a Python script that fetches and displays EKS cluster status and information


### Instruction:

```
terraform init
```

```
terraform plan
```

###### Create VPC and EKS cluster

```
terraform apply
```

###### Destroy vpc and EKS cluster

```
terraform destroy
```


###### create requirements.txt in the dir folder and add boto3, schedule into requirements.txt
```
pip freeze > requirements.txt
```

###### install boto3 and schedule
```
pip install -r requirements.txt
```
7- run the main.py 
```
python main.py
```
