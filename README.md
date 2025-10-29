# Install Autopsy and Analyze the Disk File and Folder Configuration

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
<img width="1031" height="565" alt="image" src="https://github.com/user-attachments/assets/207145e9-60d8-4c0b-80ea-87dcda46386f" />
<img width="1020" height="659" alt="image" src="https://github.com/user-attachments/assets/baaa0240-7356-4a98-8a84-be07f6fcccf0" />
<img width="1036" height="621" alt="image" src="https://github.com/user-attachments/assets/266b9681-4c1b-4755-be46-47d03fdaf9e3" />
<img width="1012" height="558" alt="image" src="https://github.com/user-attachments/assets/f4cb0fd1-a113-45df-bede-3557f9f13c69" />
<img width="995" height="541" alt="image" src="https://github.com/user-attachments/assets/0dbec751-6f9f-47e4-ab81-476b20af7bd7" />

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
