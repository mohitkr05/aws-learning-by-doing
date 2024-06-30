1. Launch an EC2 instance

![alt text](image-9.png)


2. Make sure you select AMI and Instance types for the free tier


3. Create a new key pair, use `.ppk` if you use putty else `.pem` if you use openssh/

![alt text](image-10.png) 


4. Enable port 22 for your IP address in the security group

![alt text](image-11.png)


5. Configure Putty to load the private key

![alt text](image-12.png)


6. Once the instance is in running state you can ssh into the instance

![alt text](image-13.png)
