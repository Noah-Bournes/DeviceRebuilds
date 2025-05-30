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
   - Choose: **Windows 11 Pro** (recommended for business use)
   - Accept the license terms

### Step 3: Disk Partitioning

6. **Drive Selection**
   - Choose your **SSD/Hard Drive** from the list
   - ⚠️ **Warning**: The next steps will erase everything on the selected drive

7. **Delete Existing Partitions** *(if any)*
   - Select each partition and click **"Delete"**
   - Continue until you have only "Unallocated Space"
   - Ensure you don't delete the USB key
   - If no partitions appear - go to drivers select the usb key - cpm tools - drivers - storage drivers  
   - ⚠️ **Final warning**: This will permanently erase all data

8. **Create New Partition**
    - Select the unallocated space
    - Click **"Next"** (Windows will automatically create system partitions)

### Step 4: Installation Process

11. **Begin Installation**
    - Windows will copy files and install automatically
    - The system will restart several times
    - **Do not remove the USB** until installation completes

12. **First Boot Setup**
    - Wait for "Getting ready" process to complete
    - The system will boot to the initial setup screen

---

## ⚙️ Initial Windows Setup (OOBE)

### Step 5: Out-of-Box Experience Configuration

13. **Region Selection**
    - Choose: **Ireland**

14. **Keyboard Layout**
    - Choose: **United Kingdom**
    - Skip adding a second keyboard layout

15. **Network Connection**
    - **For Ethernet**: Connection will be automatic
    - **For Wi-Fi**: Select your network and enter password
    - Click **"Next"**

16. **Microsoft Account Setup**
    - **Option 1**: Sign in with existing Microsoft account
    - **Option 2**: Create new Microsoft account
    - **Option 3**: Click **"Sign-in options"** → **"Domain join instead"** for local account

17. **Privacy Settings**
    - Review and configure privacy options according to your preferences:
      - **Location**: Recommended to disable for business use
      - **Find my device**: Enable if desired
      - **Diagnostic data**: Set to "Required diagnostic data only"
      - **Tailored experiences**: Disable for privacy
      - **Advertising ID**: Disable for privacy

---

## 🔧 Post-Installation Configuration

### Step 6: Essential Windows Updates

Once on the desktop, perform these critical updates:

1. **Open Settings**
   - Press **Windows key + I**
   - Or click **Start** → **Settings** (gear icon)

2. **Install Windows Updates**
   - Go to **Windows Update** (left sidebar)
   - Click **"Check for updates"**
   - Install all available updates
   - **Restart when prompted**

3. **Install Optional Updates**
   - After restart, check for updates again
   - Click **"Advanced options"** → **"Optional updates"**
   - Install driver updates if available

### Step 7: Configure Windows Settings

#### System Configuration

4. **Set Computer Name**
   - Go to **Settings** → **System** → **About**
   - Click **"Rename this PC"**
   - Enter desired name (e.g., `TARBHTECH-PC01`)
   - **Restart when prompted**

5. **Configure Power Settings**
   - Go to **Settings** → **System** → **Power**
   - Set **"Screen and sleep"** times according to preference
   - Click **"Additional power settings"**
   - Select **"High performance"** or **"Balanced"**

#### Security Configuration

6. **Configure Windows Defender**
   - Go to **Settings** → **Privacy & security** → **Windows Security**
   - Click **"Open Windows Security"**
   - Verify all protection areas show green checkmarks
   - Enable **"Cloud-delivered protection"** and **"Automatic sample submission"**

7. **Configure User Account Control (UAC)**
   - Search for **"UAC"** in Start menu
   - Set to **"Always notify"** for maximum security
   - Or **"Default"** for balanced security/usability

#### Privacy Configuration

8. **Configure Privacy Settings**
   - Go to **Settings** → **Privacy & security**
   - Review and configure:
     - **General**: Disable advertising and tracking options
     - **Speech**: Disable if not needed
     - **Diagnostics & feedback**: Set to **"Required diagnostic data only"**
     - **Activity history**: Disable if privacy is a concern

### Step 8: Install Essential Software

#### Web Browsers
9. **Install Web Browser**
   - **Chrome**: Download from https://www.google.com/chrome/
   - **Firefox**: Download from https://www.mozilla.org/firefox/
   - **Edge**: Already installed (update via Windows Update)

#### Security Software
10. **Install Additional Security Tools** *(Optional)*
    - **Malwarebytes**: For additional malware protection
    - **7-Zip**: For file compression/extraction
    - Download only from official websites

#### Essential Utilities
11. **Install System Utilities**
    - **Windows Terminal**: Install from Microsoft Store
    - **PowerToys**: Download from Microsoft Store or GitHub
    - **Notepad++**: For advanced text editing

### Step 9: Configure Windows Features

12. **Enable/Disable Windows Features**
    - Search for **"Turn Windows features on or off"**
    - **Enable useful features**:
      - ✅ **Windows Subsystem for Linux** (if needed)
      - ✅ **Hyper-V** (Windows 11 Pro only, if virtualization needed)
    - **Disable unnecessary features**:
      - ❌ **Internet Explorer 11** (deprecated)
      - ❌ **Windows Media Player** (if not needed)

13. **Configure File Explorer**
    - Open **File Explorer**
    - Click **View** → **Show** → **File name extensions**
    - Click **View** → **Show** → **Hidden items**
    - Go to **File** → **Options** → **View** tab
    - **Uncheck**: "Hide extensions for known file types"
    - **Check**: "Show hidden files, folders, and drives"

---

## 🌐 Network and Remote Access Configuration

### Step 10: Network Setup

14. **Configure Network Profile**
    - Go to **Settings** → **Network & internet**
    - Click on your connection (Wi-Fi or Ethernet)
    - Set network profile to:
      - **Private**: For home/office networks
      - **Public**: For public networks

15. **Enable Remote Desktop** *(Optional)*
    - Go to **Settings** → **System** → **About**
    - Click **"Advanced system settings"**
    - In **Remote** tab, enable **"Enable Remote Desktop"**
    - Configure user permissions as needed

### Step 11: Windows Defender Firewall

16. **Configure Firewall**
    - Search for **"Windows Defender Firewall"**
    - Verify firewall is enabled for both networks
    - Configure exceptions if needed for specific applications

---

## ✅ Verification Steps

### Check Your Installation
After completing all steps, verify everything is working:

1. **Check System Information**:
   - Press **Windows key + Pause** (or go to Settings → System → About)
   - Verify Windows 11 version and system specifications

2. **Verify Windows Activation**:
   - Go to **Settings** → **System** → **Activation**
   - Should show "Windows is activated"

3. **Test Windows Updates**:
   - Go to **Settings** → **Windows Update**
   - Should show "You're up to date"

4. **Check Device Manager**:
   - Right-click **Start** → **Device Manager**
   - Verify no devices show warning/error icons

---

## 🎯 Final Notes

- **Edition**: Windows 11 Pro recommended
- **User Account**: Microsoft account or local account configured
- **Updates**: All critical updates installed
- **Security**: Windows Defender and firewall enabled
- **Privacy**: Settings configured for business use

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