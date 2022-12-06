# How to get started with terraform

## We will be using ec2 instance for this practice

1.Launch an ec2 instance of type ubuntu

2.connect to ec2 instance using instance connect

3.Run the following command to install aws cli on your instance

```
sudo apt-get update
sudo apt-get install awscli
```
4.Now login to the iam user using the following command

``` aws configure ```

5.Enter your access key and security access key
6.download terraform on linux using the following documentation - [Install terraform](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)

7.Run the command

```
terraform --version
```
If you see the version of terraform you are good to go.

8.Now you need to auntheticate to the terraform

```


```
