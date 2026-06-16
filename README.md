# Installing ValoraOS Linux Distribution

Welcome to **ValoraOS Distribution**! This guide will walk you through installing the operating system from a USB drive.

> ⚠️ **Warning:** Installing an operating system may erase data on your drive. Back up important files before continuing.
> ⚠️ **Warning:** First Booting Up ValoraOS on USB takes 2-3 minutes, please dont shut off computer while installing

---

## 📋 Requirements

Before you begin, you'll need:

* A USB flash drive (8GB or larger recommended)
* The latest ISO file
* A stable power source

---

## 📥 Download the ISO

&emsp;Download the latest ISO release on https://valoraos.org/download

---

## 💾 Create a Bootable USB

### Balena Etcher (Recommended)

1. Open Balena Etcher.
2. Click **Flash from file**.
3. Select the ISO.
4. Choose your USB drive.
5. Click **Flash**.
6. Wait for the process to complete.

### Alternative Tools

* Rufus
* Ventoy
* Fedora Media Writer
* Iso Image Writer from Bazaar

---

## 🖥️ Boot From the USB

1. Shut down your computer.
2. Insert the USB drive.
3. Turn the computer on.
4. Open the boot menu and select the USB device.

| Manufacturer | Boot Key |
| ------------ | -------- |
| Dell         | F12      |
| HP           | F9       |
| Lenovo       | F12      |
| ASUS         | Esc      |
| Acer         | F12      |

---

## ⚙️ Start the Installer

Once the live environment loads:

1. Select **Install Your Linux Distribution**.
2. Choose your language and keyboard layout.
3. Select your time zone.
4. Continue to disk setup.

---

## 💽 Disk Setup - Choose One of the Following

### Erase Disk and Install
* Removes existing data on the selected drive.
* Installs the system automatically.

### Separate Partitioning
* Uses existing partitions on the selected drive.
* Installs the system on only that partition.
---

## 👤 Create Your Account

Enter:

* Username
* Computer name
* Password

Choose whether you want automatic login or password-protected login.

---

## 🚀 Install the System

Review your settings and click **Install**.

The installer will:

* Copy system files
* Configure the bootloader
* Create your user account
* Install default packages

Installation may take several minutes.

---

## 🔄 Restart

After installation completes:

1. Click **Restart Now**.
2. Remove the USB drive when prompted.
3. Allow the system to reboot.

---

## 🎉 First Boot

You're all set!

After logging in, consider:

* Connecting to the internet
* Installing updates
* Customizing your desktop
* Installing your favorite applications

---

## 🛠️ Troubleshooting

### USB Not Detected

* Recreate the bootable USB
* Try another USB port
* Check BIOS/UEFI settings

### Installation Failed

* Verify the ISO download
* Reflash the USB drive
* Ensure sufficient disk space

### System Won't Boot

* Check the boot order
* Verify the correct drive is selected
* Reinstall the bootloader if necessary

---

Need help? Contact Us Directly through Discord!
