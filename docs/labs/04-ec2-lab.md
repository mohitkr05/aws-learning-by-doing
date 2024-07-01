1. Launch an EC2 instance

![alt text](images/image-9.png)


2. Make sure you select AMI and Instance types for the free tier


3. Create a new key pair, use `.ppk` if you use putty else `.pem` if you use openssh/

![alt text](images/image-10.png) 


4. Enable port 22 for your IP address in the security group

![alt text](images/image-11.png)


5. Configure Putty to load the private key

![alt text](images/image-12.png)


6. Once the instance is in running state you can ssh into the instance

![alt text](images/image-13.png)


7. Alternatively, you can connect using the EC2 serial console, but for that you need to allow for this configuration (only available for Nitro system instances)

![alt text](images/image-16.png)
 

