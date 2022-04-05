
# Assigment2

### Aws Assigment 6
## Authors

### - Simranjeet Singh
## TO DO

### IAM roles and policies.

##### Create 3 Group's

##### 1. Devloper

###### set of permissions:

##### ec2

###### start
###### stop
###### change instance type
###### read

![](Capture1.PNG)
![](Capture2.PNG)
![](Capture4.PNG)

##### S3

###### create
###### list
###### get
###### put

![](Capture3.PNG)

##### CloudWatch

###### read only

![](Capture4.PNG)

##### Route53

###### read only

![](Capture4.PNG)

##### 2. DevOps

###### set of permissions:

###### DevOps should be able to manage all resources along with permission management.

![](Capture5.PNG)

##### 3. QA:

###### set of permissions:

##### S3

###### list
###### get

![](Capture10.PNG)

##### EC2

###### read only

![](Capture8.PNG)

##### Cloudwatch

###### read only

![](Capture9.PNG)

##### create 3 user for your ninja buddy ,cross-buddy,code-reviewer and assign them one Group to each and verify permissions

![](Capture11.PNG)

##### Create a role for EC2 which will have permissions for

###### S3

###### list
###### get
###### put
###### create

![](Capture13.PNG)
![](Capture14.PNG)

###### Now create a EC2 and attach the created role to it
###### Using aws-cli create a s3 bucket  using EC2 machine and try listing s3 bucket

![](Capture15.PNG)