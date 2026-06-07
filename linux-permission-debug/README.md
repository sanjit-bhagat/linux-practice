# 🔧 Linux Permission Debugging Practice

## 📌 Issue Faced  
While testing as another user:

Permission denied

User was part of the correct group but still couldn't write to the file.

---

## 🔍 Root Cause

- File permission: 640  
- Group had only read access (no write)  
- User needed write access  

---

## ✅ Fix Applied

```bash
chmod 660 app/config.php
chmod 770 app
chown :devteam app/config.php
