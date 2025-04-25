# Using-the-Autopsy-retrieve-the-deleted-files
## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
## 1. Copy Files to the Virtual Disk
       Open File Explorer → Go to the new drive (C: or D:), where the folder created in the New Virtual Disk
       Create a new folder (Autospy) and copy images or files into it.
## 2. Delete the Files
       Select any one or two images → Press Delete.
       Empty the Recycle Bin to permanently delete them.
## 3. Recover Deleted Files Using Autopsy
## Open Autopsy & Create a New Case
     Launch Autopsy and Run as a administrator
     Click Create New Case.
![image](https://github.com/user-attachments/assets/0eb6e830-10f3-45da-b795-fee7201050ca)
     Enter a Case Name (e.g., Autopsy1).
     Choose a Case Folder location.
     Click Next → Click Finish.
![image](https://github.com/user-attachments/assets/31f62a10-b05a-4a83-a309-915d6c29f41a)
## Add the Virtual Disk as an Evidence Source
     Click Add Data Source → Select Host
![image](https://github.com/user-attachments/assets/54255973-9fe0-45bc-b91a-34979d2b8bc5)

  Select Local Disk → next
![image](https://github.com/user-attachments/assets/99319067-b87d-4f51-a27b-2f7c582664cc)

  Select Disk → Choose the VHD drive (Drive1)
![image](https://github.com/user-attachments/assets/dd0fab99-87f3-4c88-b442-ac4b5b05af78)
   Click Next → Keep default settings → Click Finish.
   Wait for Autopsy to process the disk.
## Recover Deleted Files
   Go to File Views (left panel).
![image](https://github.com/user-attachments/assets/16f69b2c-9ff6-4dec-9ba3-154bfc8c671c)

![image](https://github.com/user-attachments/assets/36de7723-1ad8-43f2-b2df-adf7f8d43727)
     Click Deleted Files → Find your deleted images.
     Right-click an image → Click Extract File.

![image](https://github.com/user-attachments/assets/59eb0c14-d246-44d5-abc7-0dfc97322d22)
   Select a folder to see the recovered files (e.g., C:\forensic).
   Image is recovered successfully.


## OUTPUT:
## Folder before deleting the files
![image](https://github.com/user-attachments/assets/4517c531-500f-47a7-9823-84fa664789d2)
## Folder after deleting the files
![image](https://github.com/user-attachments/assets/117df597-dd06-41b1-9ef0-8ecb9218acf7)
## Folder after extracting the deleted images using autopsy
![Uploading image.png…]()

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
