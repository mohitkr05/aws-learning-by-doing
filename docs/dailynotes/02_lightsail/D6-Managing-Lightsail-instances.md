# Managing your Lightsail instance

## Day 6

- [ ] Understanding more about the Lightsail instance
- [ ] Installing software on your instance
- [ ] Managing your Instance
- [ ] Monitoring the instance.
- [ ] Understand Burstable instances


## Understanding more about the Lightsail instance

- Use snapshots to backup your instance: Creating instance snapshots is an easy and effective way to backup your instance data and configuration.  
- Use DNS to manage your instance: Amazon Lightsail includes a DNS service that you can use to manage your instance's domain name and DNS records. 
- Use the Lightsail firewall for security: The Lightsail firewall provides a simple way to control inbound and outbound traffic to your instance. 
- Use instance metadata for automation: Amazon Lightsail instances include metadata that you can use to automate tasks and configure your instance. 


## Installing WordPress on your instance

1. Download WordPress & Unpack it

```bash
wget https://wordpress.org/latest.tar.gz
tar -xzvf latest.tar.gz
```

2. Create the Database

```bash

mysql -u root -p
```

```sql
CREATE DATABASE wordpress;
```

3. Configure the DB

```bash
cp wp-config-sample.php wp-config.php
vi wp-config.php
```

4. Define the config

```sql
define('DB_NAME', 'wordpress');
define('DB_USER', 'wordpressuser');
define('DB_PASSWORD', 'password');
define('DB_HOST', 'localhost');
```

5. Change the permissions and restart Apache

```bash
sudo chown -R www-data:www-data /var/www/html/wordpress/
sudo chmod -R 755 /var/www/html/wordpress/
sudo service apache2 restart
```

### Burstable instance

- Burstable instances are based on the T instance family, which provides a baseline level of CPU performance and a burstable CPU capability.
- The baseline performance is measured in CPU credits, which accumulate over time when the instance is idle or underutilized.
- When the instance requires more CPU performance than the baseline, it can use the accumulated CPU credits to burst above the baseline for short periods of time.[^1][^2]
- When the CPU usage returns to baseline levels, the instance begins accumulating CPU credits again.
- Think of a burstable instance like a car with a hybrid engine. 
- The electric motor provides a baseline level of power and efficiency, while the gas engine provides extra power when needed. When you're driving in the city, the car relies mostly on the electric motor for steady performance and fuel efficiency. 
- But when you need to accelerate quickly to merge onto the highway, the gas engine kicks in to provide extra power for a short burst.

To test we are going to use Apache benchmarking
```bash

ab -n 200 -c 20 http://localhost

```

## References

[^1]: (https://lightsail.aws.amazon.com/ls/docs/en_us/articles/amazon-lightsail-viewing-instance-burst-capacity)
[^2]: (https://lightsail.aws.amazon.com/ls/docs/en_us/articles/amazon-lightsail-viewing-instance-burst-capacity#viewing-instance-burst-capacity)
