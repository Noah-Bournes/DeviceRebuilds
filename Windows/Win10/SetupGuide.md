# 💻 Complete Windows 10 Clean Installation Guide  
*Setting up Windows 10 device from scratch*  

---

## 📋 Prerequisites

- A computer or virtual machine ready for installation  
- **Windows 10 ISO** downloaded and burned to a USB (minimum 8GB) using [Rufus](https://rufus.ie) or the Media Creation Tool  
- Be aware this process will **erase all data** on the selected drive  

---

## 🚀 Installation Process

### Step 1: Boot and Initial Setup

1. **Insert the USB and power on the device**  
2. Enter BIOS (usually **F2**, **DEL**, or **F12**) and **set USB as first boot device**  
3. **Boot from USB** – press any key when prompted  
4. **Choose regional settings**:  
   - **Language**: English (United Kingdom)  
   - **Time and currency format**: English (Ireland)  
   - **Keyboard**: United Kingdom  
5. Click **Next**, then **Install Now**

### Step 2: License and Version Selection

6. If prompted for a license key:
   - Click **“I don’t have a product key”** if entering it later  
7. **Select Windows Edition**  
   - Choose: **Windows 10 Pro**  
   - Click **Next**, then accept license terms

### Step 3: Drive Partitioning

8. **Choose Custom: Install Windows only (advanced)**  
9. Select the **target SSD/HDD**  
   - ⚠️ **This will erase all partitions on that drive**  
10. **Delete all existing partitions**  
    - Highlight each partition and click **Delete**  
    - Continue until only **Unallocated Space** remains  
    - **Important**: Do **not delete** the USB key  
    - If no drives are listed, load storage drivers from the USB:  
      - Browse → USB → `cpm-tools > drivers > storage > VMD`  
      - Select and install  
11. Select the **Unallocated Space**  
    - Click **Next** (Windows will auto-create system partitions)

### Step 4: Installation Process

12. Windows 10 will begin installing  
    - Files will copy, and the system will restart several times  
    - **Do not remove the USB** until setup is complete  

---

## ⚙️ Initial Windows Setup

### Step 5: Admin Account Setup

13. On the first boot:  
    - Choose **Set up for personal use** or **organization**, as needed  
14. Create the primary user:  
    - Username: **Tarbh.Tech**  
    - Password: ******** (stored in 1Password)  
15. Skip Microsoft account sign-in if preferred by choosing **Offline account**

---

## 🔧 Post-Installation Configuration

### Step 6: Drivers

16. **Install manufacturer drivers**  
    - Search: **(Laptop/PC brand) support driver install tool**  
    - Download and run the support assistant (HP, Dell, Lenovo, etc.)  
    - Install any recommended drivers  
17. Open **Device Manager** to verify:  
    - Press **Windows + X** → **Device Manager**  
    - Look for missing driver icons  
18. Manually download any missing drivers from the vendor’s site

### Step 7: Enable .NET 3.5

19. Press **Start** → Search **“Windows Features”**  
20. Click **Turn Windows Features on or off**  
21. Check **.NET Framework 3.5**  
22. Click **OK** → Windows will download and install it  
    - This may take several minutes  

### Step 8: Essential Windows Updates

23. Open **Settings** → **Update & Security**  
24. Click **Check for Updates**  
25. Install all available updates  
26. Restart as prompted  
27. Go to **Advanced options** → **Optional Updates**  
    - Install all driver or firmware updates listed

---

## 🧾 Asset Management & App Setup

### Step 9: Device Info

28. Press **Ctrl + Shift + Esc** → Open **Task Manager**  
    - Go to **Performance** tab → note CPU, RAM, and GPU  
29. Press **Start** → Search for **Terminal**  
    - Type `hostname` → This is your **device name**  
    - Can be used to match serial numbers for inventory  

### Step 10: M1 Install (Croom Medical)

30. Open **File Explorer**  
    - Search for `cpm-hq-m1/m1`  
31. Locate the **Setup file**  
    - Right-click → **Run as Administrator**  
32. Two M1 apps will appear  
    - Run both as admin  
    - Let the install complete (may take several minutes)

---

## ✅ Final Verification Checklist

### System Checks

33. **System Info**:  
    - **Settings** → **System** → **About**  
    - Confirm version = Windows 10 Pro  
34. **Updates**:  
    - Check **Windows Update** again  
    - Confirm status = **“You’re up to date”**  
35. **Device Manager**:  
    - Confirm there are **no warnings or errors**  
36. **.NET Framework**:  
    - Go back to **Windows Features**  
    - Ensure **.NET Framework 3.5** is checked  

---

## 🆘 Troubleshooting

- **Install stuck**: Recreate the USB with [Rufus](https://rufus.ie) and double-check ISO integrity  
- **No network after install**: Use another device to download LAN/Wi-Fi drivers  
- **Can't activate**: Check license key or ensure PC is linked to Microsoft account  
- **Slow performance**: Install all updates, check startup apps in Task Manager  
- **Drivers missing**: Use manufacturer support assistant or download manually

---

*Guide created for TarbhTech – Internal Use Only*  
