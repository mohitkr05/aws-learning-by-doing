# Lab 03 - Bucket Creation in S3


## 1. Bucket Creation

1.1. In the console, search for S3 

1.2. Click "Create Bucket".

1.3. Choose a name for the bucket and the region in which it should be located. The bucket name must be unique across all of AWS, not just your account.

1.4. In the "Configure options" menu, you can configure the bucket's versioning, logs, tags, activity record and encryption. For this lab, we will not make these settings. Click **Next**.

1.5. The "Define Permissions" menu is where you configure access permissions to the bucket and its objects. By default, public access to the bucket and its objects is blocked and it is highly recommended that you keep it that way. In the "Analysis" menu it is possible to review the settings made in the previous menus.

1.6. Review the settings and click **Create Bucket**. On the next screen, we will be able to see the created bucket.


## 2. Object Upload

2.1. Click the bucket to open and upload files. Click **Upload** to upload objects.

2.2. Click **Add File** and choose the object or objects you want to upload to the bucket.

2.3. In the **Define permissions** menu we can configure the access allowed to the object. Keep the default settings and click **Next**.

2.4. In the **Define Properties** menu, you can choose which S3 class the object will be stored in, as well as encryption and tag settings. Keep it at *Standard*, which is the default, and click **Next**.

2.5. In the **Analysis** menu it is possible to review the settings made in the previous menus and confirm the file upload. Click **Upload**.


## 3. Access Created Object

3.1. On the next screen, you can see the file already available in the created bucket. Click on the object.

3.2. On this screen, you can see information regarding the object and the URL for public access. Copy the URL and paste it into the browser and try to access the object.

3.3. This is the result of a query for the URL of a private object in the S3 bucket. For this lab, we will leave public access for testing.

3.4. To allow public access to objects, go back to the bucket page and access the **Permissions** menu. By default, the "Block all public access" checkbox is checked. Uncheck the checkbox and click **Save**. For security, you need to confirm this action. Please note that, according to best practices, all buckets must be private and this lab is for teaching purposes only.

3.5. After confirmation, select the object again and click **Make Public**.

3.6. Copy and paste the object access URL into the browser again. As a result you will be able to visualize the object.
