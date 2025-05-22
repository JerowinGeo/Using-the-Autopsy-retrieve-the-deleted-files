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
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![image](https://github.com/user-attachments/assets/b6f16a77-8ecf-428a-9e0b-485f75f3af61)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![image](https://github.com/user-attachments/assets/d49b0e8f-7584-4d96-afec-ac6cd427eb4b)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![image](https://github.com/user-attachments/assets/b9da6b90-be8b-4e65-b4bd-28b62d9d587c)

- Select **Local Disk** → **next** 

![image](https://github.com/user-attachments/assets/2704e62d-57f7-457c-b3e8-70a76e1daf93)

- Select Disk → **Choose the VHD drive (`Drive1`)**

![image](https://github.com/user-attachments/assets/76adbb21-ed9b-495b-824c-468240117197)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![image](https://github.com/user-attachments/assets/e68af808-8aaa-433e-a65d-a9d6979a3c85)

![image](https://github.com/user-attachments/assets/4f13dcc0-8ccf-4eea-a8fe-185f65c8e5f7)

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![image](https://github.com/user-attachments/assets/dd8e5b86-7b68-4554-b26d-d87d156b8950)

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![image](https://github.com/user-attachments/assets/7921775c-1a59-4e02-a074-305689b42cba)

### Folder after deleting the files
![image](https://github.com/user-attachments/assets/52d64214-312e-456c-9c0c-627dd90df3ac)

### Folder after extracting the deleted images using autopsy
![image](https://github.com/user-attachments/assets/579319d4-f6c8-4aec-a773-df4d8a61cb16)

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
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
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![image](https://github.com/user-attachments/assets/92923157-b1ef-4812-bd00-b4590e4a3661)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![image](https://github.com/user-attachments/assets/f866d138-0b87-4539-a28b-1e09874925cd)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![image](https://github.com/user-attachments/assets/51084192-b57c-4960-96fb-1da13f94993e)

- Select **Local Disk** → **next** 

![image](https://github.com/user-attachments/assets/1bfe3c9b-f463-4802-b9cf-ff1fa661c126)

- Select Disk → **Choose the VHD drive (`Drive1`)**

![image](https://github.com/user-attachments/assets/ab8b703e-f613-472b-b2a0-944069732425)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![image](https://github.com/user-attachments/assets/3c69a803-b6c1-499f-b1c6-a4660b712920)

![image](https://github.com/user-attachments/assets/2fb0f0bf-4bbe-4ea6-acb1-3bc0664bfc89)

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![image](https://github.com/user-attachments/assets/128f3196-4367-4851-a158-73aaee0cd497)

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![image](https://github.com/user-attachments/assets/99c04e40-7485-4d86-ace7-901dd7994644)

### Folder after deleting the files
![image](https://github.com/user-attachments/assets/fb6bae9c-2deb-4f17-b290-d2b6c36cc804)

### Folder after extracting the deleted images using autopsy
![image](https://github.com/user-attachments/assets/b591608b-26e3-4478-9b51-712368e28b4b)

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
