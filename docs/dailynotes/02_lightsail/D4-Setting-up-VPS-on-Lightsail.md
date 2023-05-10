# Setting up a VPS on Amazon Lightsail


## Day 4 Checklist

- [ ] Walkthrough of  Amazon Lightsail account
- [ ] Understanding Blueprints
- [ ] Creating a new VPS using a LAMP Stack
- [ ] Connecting to the instance using web console


## Amazon Lightsail Dashboard Walkthrough

- The Amazon Lightsail dashboard is the main interface for managing your Lightsail resources.

- You'll see 
  - overview of your account, including information about your resources, billing, and notifications.
  - options to manage your instances, databases, load balancers, DNS zones, and more.
  - The Instances tab displays a list of your virtual private servers (VPS), including their current status, IP address, and region.
  - The Databases tab displays a list of your managed databases, including their status, endpoint, and engine type. 
  - The Load Balancers tab displays a list of your load balancers, including their current status and endpoint. 
  - The Networking tab includes options to manage your DNS zones, create static IP addresses, and configure firewall rules.


## Understanding Blueprints

- A blueprint in Amazon Lightsail is a pre-configured template for launching a virtual private server (VPS) or an application, such as a content management system (CMS) or a web application framework.

- Blueprints are designed to simplify the process of launching a new instance by providing a pre-built configuration that includes the necessary software, settings, and services.

- Each blueprint includes a specific operating system, application stack, and server configuration, along with recommended settings for security, performance, and scalability.

- Lightsail offers a wide variety of blueprints for different use cases, including popular CMS platforms like WordPress, Drupal, and Joomla, as well as web application frameworks like Ruby on Rails, Node.js, and Django.

## Creating a new VPS 

1. Click the "Create instance" button in the top right corner of the dashboard.
2. Select a blueprint for your instance. As of now use WordPress from Bitnami.
3. Choose your instance plan. 
4. Enter a unique name for your instance, and select the region where you want to launch it. 
5. Click the "Create instance" button to launch your new VPS.
6. Wait for Lightsail to provision your new instance. This may take a few minutes, depending on the size of your instance and the availability of resources in your selected region.
7. Once your instance is ready, you can access it via the Lightsail console. 
