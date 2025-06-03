# 💻 Complete Windows 11 Clean Installation Guide
*Setting up Windows 11 device from scratch*

---

## 📋 Prerequisites

- A computer or virtual machine ready for installation
- Windows 11 ISO downloaded and burned to USB (minimum 8GB)
- Basic understanding that you'll be erasing the target drive

---

## 🚀 Installation Process

### Step 1: Boot and Initial Setup

1. **Boot from your Windows 11 installation media**
2. **Press any key** when prompted to boot from USB/DVD
3. **Select language and region settings**:
   - **Language**: English (United Kingdom)
   - **Time and currency format**: English (Ireland)
   - **Keyboard**: United Kingdom

4. **Click "Next"** and then **"Install now"**

### Step 2: License and Installation Type

5. **Select Windows Edition**
   - Choose: **Windows 11 Pro**
   - Accept the license terms

### Step 3: Disk Partitioning

6. **Drive Selection**
   - Choose your **SSD/Hard Drive** from the list
   - ⚠️ **Warning**: The next steps will erase everything on the selected drive

7. **Delete Existing Partitions** *(if any)*
   - Select each partition and click **"Delete"**
   - Continue until you have only "Unallocated Space"
   - Ensure you don't delete the USB key
   - If no partitions appear - go to drivers select the usb key - cpm tools - drivers - storage drivers - vmd - select - install
   - ⚠️ **Final warning**: This will permanently erase all data

8. **Create New Partition**
    - Select the unallocated space
    - Click **"Next"** (Windows will automatically create system partitions)

### Step 4: Installation Process

9. **Begin Installation**
    - Windows will copy files and install automatically.
    - The system will restart several times.
    - **Do not remove the USB** until installation completes.
      
---

## ⚙️ Initial Windows Setup 

### Step 5: Admin Login

10. **Login**
    - Enter: **Tarbh.Tech**
    - Password: **************** (1Password)
      
---

## 🔧 Post-Installation Configuration

### Step 6: Drivers

11. **Install Drivers**
    - Search online : **(Manufacturer) driver install.**
    - Install Support Assistant: *Each provider will have a version of this assistant to scan the device and identify the drivers needed.*
    - Install and download any drivers which are identified.
    - Search "Device Manager" and look for necessary drivers.
    - Look up any drivers you didn't find on the manufacturer site.
   
### Step 7: .NET 3.5

12. **Install .NET**
    - Search online : **(Manufacturer) driver install.**
    - Click **Start** → **Search** → **Turn Windows Features on or off**
    - Select .NET 3.5 and install
    - This will take several minutes.
   

### Step 8: Essential Windows Updates

1. **Open Settings**
   - Press **Windows key + I**
   - Or click **Start** → **Settings** 

2. **Install Windows Updates**
   - Go to **Windows Update** (left sidebar)
   - Click **"Check for updates"**
   - Install all available updates
   - **Restart when prompted**

3. **Install Optional Updates**
   - After restart, check for updates again
   - Click **"Advanced options"** → **"Optional updates"**
   - Install driver updates if available

### Step 9: Find device info for asset management

8. **Locate Hardware Specs**
   - Go to **Search Bar** → **Task Manager**
   - Select Performance
   - CPU, Memory, GPU
   **Locate Device Name**
   - Go to **Search Bar** → **Terminal**
   - Enter "Hostname"
   - Device Name will be displayed (Includes serial number)

### Step 10: M1 Install (Croom Medical)

8. **Locate File**
   - Go to **File Explorer** → **Search Bar** → "cpm-hq-m1/m1"
   - Locate the Setup file
   - Run as admin
   - You will see two M1 apps
   - Click Run as Admin on both
   - This will take several minutes

## ✅ Verification Steps

### Check Your Installation
After completing all steps, verify everything is working:

1. **Check System Information**:
   - Press (Settings → System → About)
   - Verify Windows 11 version and system specifications

2. **Test Windows Updates**:
   - Go to **Settings** → **Windows Update**
   - Should show "You're up to date"

3. **Check Device Manager**:
   - Right-click **Start** → **Device Manager**
   - Verify no devices show warning/error icons

4. **Verify .NET**:
   - Go to **Start** → **Search** → "Turn Windows features on or off"
   - .NET 3.5 Should show as selected

---

Your Windows 11 system is now ready for business use and productivity applications!

---

## 🆘 Troubleshooting

**If you encounter issues:**

1. **Installation fails**: Check hardware compatibility with PC Health Check tool
2. **No internet after install**: Update network drivers from manufacturer
3. **Activation issues**: Ensure valid license and check Microsoft account linking
4. **Performance issues**: Check for driver updates and disable startup programs
5. **Updates won't install**: Run Windows Update Troubleshooter

**Need help?** Contact the TarbhTech team or check Microsoft Support documentation.

---

*Guide created for TarbhTech - Internal Use Only*
