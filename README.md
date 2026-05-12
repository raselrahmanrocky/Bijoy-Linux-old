
# ⌨️ How to Install Bijoy Layout in Linux (IBus)
This guide will help you install the Bijoy Classic and Bijoy Unicode keyboard layouts on your Linux system using the **IBus m17n** engine.
### 🚀 Installation Steps### Step 1: Install IBus m17nOpen your terminal and run the following command to install the required package:
```bash
sudo apt-get install ibus-m17n
```
### Step 2: Set Directory PermissionsGrant temporary write permissions to the system's `m17n` folders so you can copy the layout files:
```bash
sudo chmod 777 /usr/share/m17n/   
```
```bash
sudo chmod 777 /usr/share/m17n/icons
```
### Step 3: Extract and Move Files1. Unzip the `bijoy linux.zip` file on your computer.2. Open the extracted folder.
3. Move the **two `.png` icon files** to this directory:
   ```text
   📁 File System > usr > share > m17n > icons
   ```
4. Move the **two `.mim` layout files** to this directory:
   ```text
   📁 File System > usr > share > m17n
   ```
### Step 4: Update Package DatabaseTo prevent the files from being deleted during system updates, you need to register them in the package database.
1. Give permission to edit the database list:
   ```bash
   sudo chmod 777 /var/lib/dpkg/info/m17n-db.list
   ```
2. Open the file using a text editor (e.g., Gedit):
   ```bash
   gedit /var/lib/dpkg/info/m17n-db.list
   ```    
3. Copy and paste the following lines at the end of that file, then **Save** and close it:
   ```text
   /usr/share/m17n/icons/bn-bijoyClassic.png
   /usr/share/m17n/bn-bijoyClassic.mim
   /usr/share/m17n/icons/bn-bijoyUnicode.png
   /usr/share/m17n/bn-bijoyUnicode.mim
   ```
## 📢 Support
If this guide helped you, please consider supporting the creator:

Thank you for using this layout!
