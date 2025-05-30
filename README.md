# TWRP Recovery for realme Note 50 (RMX3834)

## **Current Status**  
✅ **Working:**  
- Recovery boot  
- Read/write partitions (`system`, `vendor`, `data`)  
- ADB/MTP support  
- Backup/Restore (including `super` partition)  
- FBE decryption (if device is encrypted)  

⚠ **Partial/Limitations:**  
- OTA updates break `vbmeta` verification  
- Selinux in `permissive` mode  

❌ **Not Working:**  
- USB OTG (under testing)  

---

## **Installation Guide**  
### **Prerequisites**  
- Unlocked bootloader (**OEM Unlock** enabled in Developer Options)  
- ADB/Fastboot installed on PC  
- **Warning:** This will wipe all data! Backup first.  
