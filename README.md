# s3-Bucket-Versioning
This Repo steps to create a delete file and recover the file through bucket versioning
![2](https://github.com/user-attachments/assets/d17d7d9e-9476-4e59-b997-0abb7b0900f5)
# Navigate to the bucket in which we want to delete
![3](https://github.com/user-attachments/assets/41473fe7-5fbb-4881-8ac1-c556b8fc0bb9)
# Delete the object
![4](https://github.com/user-attachments/assets/a5f34a69-5d5a-47ff-91af-957c06de4bbe)
# Object was successfully deleted
![5](https://github.com/user-attachments/assets/b30aa7c2-8c7d-4f46-ac82-4f60d05a961b)
# Version was available in the above picture, select the file (delete marker) we want to recover and click delete 
![6](https://github.com/user-attachments/assets/faddbfd3-4ccb-4da5-8190-20b2833f1709)
# File will be recovered


# If Folder was deleted
Then we need to delete the marker for all the files in the folder then the files inside folder gets recovered ( for each file delete marker get allocated )

# if we want to delete the file version permanaently then select the delete marker and file associateed with it then it will get deleted permenantly
✅ Versioning States in S3 <br>
State                   	        Description <br>
Disabled Versioning	        ------          No versions will be there <br>
Enabled	Versioning is active ------  all changes create versions <br>
Suspended           -----    	No new versions are created behaves like an unversioned bucket, but old versions stay <br>
