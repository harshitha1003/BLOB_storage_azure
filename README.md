# BLOB_storage_azure
Azure Cloud Computing
Minor Project- Task 1
Create an azure storage account using the azure portal and create a BLOB storage

I have followed the given steps to complete the task.
From the azure portal i have selected the storage accounts and clicked create.
I have given a new resource group name and storage account name.
I changed the redundancy to low redundancy storage (LRS) and performance to Standard.
In advance settings i have changed Minimum TLS version to version 1.2.
I checked the remaining options and went to review.
After the review is processed I have created the storage account.
In the container under the data storage I created a new container and named it “picture” and uploaded a picture in the container.
I changed its access level to private.
Same as the first container I created another container and named it “video” and uploaded a small video in it.
I changed its access level to Blobs by prefix(case sensitive).
I opened the Life cycle management in Data management and enabled “Access Tracking”.
I added a rule and named it “rule1” and added the condition that if  Base blob was created and not accessed for 10 days then move it to cold storage(access tier to cool).
Similarly I added another rule and named it “rule2” and added the condition that if Base blob was last accessed and is not accessed again for 45 days then delete the blob.

