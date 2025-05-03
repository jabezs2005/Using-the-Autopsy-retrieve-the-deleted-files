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
Autopsy Deleted File Recovery Steps
1. Copy Files to the Virtual Disk
Open File Explorer → Go to the new drive (C: or D:), where the folder created in the New Virtual Disk
Create a new folder (Autospy) and copy images or files into it.
2. Delete the Files
Select any one or two images → Press Delete.
Empty the Recycle Bin to permanently delete them.
3. Recover Deleted Files Using Autopsy
Open Autopsy & Create a New Case
Launch Autopsy and Run as a administrator
Click Create New Case.
![1](https://github.com/user-attachments/assets/c1c94552-d4cb-41b5-9d8a-4b7282e3d1aa)
- Enter a Case Name (e.g., Autopsy1).
- Choose a Case Folder location.
- Click Next → Click Finish.
- ![2](https://github.com/user-attachments/assets/aedf4a2a-5230-4d36-b3ae-fbff1eee0318)
### Add the Virtual Disk as an Evidence Source
- Click Add Data Source → Select Host
- ![3](https://github.com/user-attachments/assets/300b8077-e11e-4e62-8070-da64417442e7)
- Select Local Disk → next
- ![4](https://github.com/user-attachments/assets/11ab59eb-1981-4578-937b-4bfd79a1046c)
- Select Disk → Choose the VHD drive (Drive1)
![5](https://github.com/user-attachments/assets/9f211b82-b582-40ac-b916-0be5b0b94383)
- Click Next → Keep default settings → Click Finish.
- Wait for Autopsy to process the disk.
### Recover Deleted Files
- Go to File Views (left panel).
![6](https://github.com/user-attachments/assets/0a6d1232-d4fc-4f81-9fd1-d4417861635d)
![7](https://github.com/user-attachments/assets/27ddc15a-615b-4546-b423-8f054129dc97)
- Click Deleted Files → Find your deleted images.
- Right-click an image → Click Extract File.
![9](https://github.com/user-attachments/assets/0d236797-51be-4a0b-86ea-195046560586)
- Select a folder to see the recovered files (e.g., C:\forensic).
- Image is recovered successfully.
## OUTPUT:
Recovered Deleted File List and Details
### Folder before deleting the files
![10](https://github.com/user-attachments/assets/d9f56ad7-46a6-4b3d-b00e-8afdad25720c)
### Folder after deleting the files
![11](https://github.com/user-attachments/assets/428e5e55-81d7-4ff4-939f-4e3f0baa14b5)
### Folder after extracting the deleted images using autopsy
![12](https://github.com/user-attachments/assets/87205650-7a9b-4ace-96da-1ce34001a210)

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
