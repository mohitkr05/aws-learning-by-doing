1. Copy the following in the user script

![alt text](image-2.png)


```bash
#!/bin/bash
sudo yum -y update 
sudo yum install -y nginx  
sudo systemctl enable nginx
sudo systemctl start nginx
```

2. Make sure you have HTTP allowed in the security group

![alt text](image-3.png)

3. Test the connectivity

![alt text](image-4.png)