# Install Autopsy and Analyze the Disk File and Folder Configuration
# Name: janarthanan B
# Regno:212223100014
## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results

<img width="1919" height="1199" alt="Screenshot 2025-08-22 092244" src="https://github.com/user-attachments/assets/623a42b4-75f8-4ba0-a316-2691ecfd4f72" />
<img width="1919" height="1199" alt="Screenshot 2025-08-22 092307" src="https://github.com/user-attachments/assets/59794f5d-272f-4acf-8617-9b1a9bad4d4f" />
<img width="1919" height="1199" alt="Screenshot 2025-08-22 092340" src="https://github.com/user-attachments/assets/d389fb9a-aa7b-44d9-a02e-3fe6f7036d55" />
<img width="1919" height="1199" alt="Screenshot 2025-08-22 092353" src="https://github.com/user-attachments/assets/0c29030d-b4a4-4687-a303-e5c1afc684a5" />
<img width="1918" height="1199" alt="Screenshot 2025-08-22 092410" src="https://github.com/user-attachments/assets/143ba5ee-dc0c-4d48-8f70-4f2793345aac" />
<img width="1919" height="1199" alt="Screenshot 2025-08-22 092423" src="https://github.com/user-attachments/assets/a135cce5-9eaa-4ac9-8524-0e254558a00a" />
<img width="1919" height="1199" alt="Screenshot 2025-08-22 092435" src="https://github.com/user-attachments/assets/123ac555-f513-45a0-a8a7-fd7b9bfc5a8d" />
<img width="1919" height="1199" alt="Screenshot 2025-08-22 092450" src="https://github.com/user-attachments/assets/c879f766-648f-43cc-b8c0-79721f1b11ff" />
<img width="1919" height="1199" alt="Screenshot 2025-08-22 092501" src="https://github.com/user-attachments/assets/5c4d8342-d66d-4e06-832b-073f69d34d6c" />
<img width="1919" height="1199" alt="Screenshot 2025-08-22 092621" src="https://github.com/user-attachments/assets/bee44b9e-3a35-4347-98ba-41c7bf0ed02b" />
<img width="1919" height="1199" alt="Screenshot 2025-08-22 092907" src="https://github.com/user-attachments/assets/82e79a8f-fd8e-4391-976b-e559db662ac0" />
<img width="1919" height="1199" alt="Screenshot 2025-08-22 092935" src="https://github.com/user-attachments/assets/ef77521a-1e86-4b97-9e09-6474c4ea0452" />
<img width="1919" height="1199" alt="Screenshot 2025-08-22 092948" src="https://github.com/user-attachments/assets/59a2bb7d-6d63-4044-911b-a5e3662f0a84" />
<img width="1018" height="675" alt="Screenshot 2025-08-22 092959" src="https://github.com/user-attachments/assets/b3cd9121-ca37-4492-b9d8-573d011c32c0" />
<img width="614" height="418" alt="Screenshot 2025-08-22 093023" src="https://github.com/user-attachments/assets/0d71c412-8683-45db-9802-abd76ea60193" />
<img width="1919" height="1199" alt="Screenshot 2025-08-22 093952" src="https://github.com/user-attachments/assets/52bd68d1-ce63-4dbd-867c-51a33f33758c" />

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
