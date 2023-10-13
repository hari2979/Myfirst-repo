To create an EC2 instance by CLI please use the following command.

aws ec2 run-instances --image-id ami-053b0d53c279acc90 --count 1 --instance-type t2.micro --key-name Docker --security-group-ids sg-04a8867b3eee2c54e --subnet-id subnet-08792e3bd5383ed24

**** Command break by break *****
* AWS - Refers the provider
* ec2 run-instances - Refers the EC2 state to run instance
* Image id - off course refers to ubuntu ami id which is taken from aws UI
* Count 1 - refers to how my machines do i need to create in envirnoment
* instance type - which refers to tyoe of instance do i need to implement in the envirnoment
* key name - key pair which created in our machine.
* security group id's - which is taken from security group in EC2 instances.
* subnet id - Which is taken from default subnet id from EC2 machine or it's taken from default id.

**** How to delete the EC2 instance *****

**** How to create an S3 Bucket to this CLI command *****

aws s3api create-bucket --bucket test-bucket-29799 --region us-east-1

Same has the above command states how to create an bucket.

* Same test-bucket-29799 states names has "Bucket name"

AWS S3 ls ---- Command helps us to view the buckets list which is avaiable in our console. Which is quite helpful.


