# Ex--6-AWS-Account-setup-and-S3-creation-

## Introduction
In this lab, we are going to be introduced to one of the famous Cloud Service providers, Amazon Web Services (AWS). We will work on Amazon Simple Storage Service (S3), which provides storage through web service interfaces (REST, SOAP, and BitTorrent). In S3, the data is stored in the form of buckets. Buckets serve as root folders where we can add, create, or upload files and folders. We can create multiple buckets for different purposes, and each bucket can have different access control policies.

## Objectives
Create a Bucket in Amazon S3.
Add Objects (files and folders) to the bucket.
Access, move, download, and delete the objects.
Delete the Bucket.

## Illustration
# Step 1: Choose S3 Service
Choose the S3 service from the list of services provided by AWS.


<img width="887" height="468" alt="image" src="https://github.com/user-attachments/assets/7ee92a6c-da7b-443d-ae39-606f72bc543b" />

# Step 2: Create a Unique Bucket
After selecting the S3 service, click on the "Create Bucket" button on the page. The bucket name must be unique, contain no uppercase letters, and have no special characters. If you enter any of these, an error will display, preventing the bucket from being created.



<img width="887" height="425" alt="image" src="https://github.com/user-attachments/assets/c4e3c33d-2d25-4402-b754-36baf7167043" />

<img width="887" height="467" alt="image" src="https://github.com/user-attachments/assets/32aba100-1008-4a57-9f01-2cd34a3a3f36" />

<img width="885" height="467" alt="image" src="https://github.com/user-attachments/assets/46dad5c2-495e-4c7c-b559-4f642065c9ed" />

<img width="1035" height="543" alt="image" src="https://github.com/user-attachments/assets/45eafd48-222e-4b8e-8f43-56e5c9ce349a" />


<img width="992" height="518" alt="image" src="https://github.com/user-attachments/assets/317f36df-3b68-4a01-b300-aac45de68aca" />


For region selection, choose a region from the available list. It is recommended to select a region nearby your location for higher availability. In this lab, I selected Sydney, as it is near my country, New Zealand. Remember to provide a unique bucket name with no special characters or uppercase letters.

# Step 3: Upload Files to the Bucket
Now, I have uploaded some files into the bucket I just created. There are no restrictions on uploading file types, but the size of each file must be less than 5 terabytes.

<img width="1032" height="522" alt="image" src="https://github.com/user-attachments/assets/8a890268-5d90-4f8d-87e8-a9768e850ac2" />

<img width="465" height="402" alt="image" src="https://github.com/user-attachments/assets/08425c70-2f19-4440-9d42-aeb62132e39d" />

You can upload files of any extension, folders, and subfolders. The images below explain that you can drag and drop files or select them from your computer. After uploading a file, you can download, cut, copy, make it public, rename, or delete it. Making a file public means everyone can access it, and you will receive a link (e.g., https://s3-ap-southeast-2.amazonaws.com/...) to share it.



<img width="1031" height="451" alt="image" src="https://github.com/user-attachments/assets/1423464c-110b-41ff-8cc2-6fa522700f29" />

<img width="1036" height="486" alt="image" src="https://github.com/user-attachments/assets/7a33099f-a349-4d8e-b0e8-6edeec85ba95" />

Step 4: Upload a Folder
You can also upload a folder to the bucket. If your local folder contains subfolders and data, all data inside the parent folder will be uploaded. The images below show how to upload a folder by dragging and dropping or browsing.

<img width="883" height="351" alt="image" src="https://github.com/user-attachments/assets/8cd68c7d-f24f-4700-9dbd-f6d8a2f32027" />

# Step 5: Delete the Bucket
To delete a bucket, you must retype the bucket name. This policy is implemented by Amazon to confirm your action because deleting a bucket can remove large amounts of data.

<img width="1041" height="435" alt="image" src="https://github.com/user-attachments/assets/ba31fe75-9f78-4a40-bc6c-fa6d7e25496e" />


## Result
Successfully created, managed, and deleted an S3 bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon S3.








