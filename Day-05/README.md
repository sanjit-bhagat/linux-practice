# 🛠 Linux Permissions & Ownership Practice

## 📌 About This Practice  
Today I worked on a small Linux practice project to get more comfortable with file permissions, ownership, and basic scripting.

Instead of just reading commands, I created a mini project and practiced hands-on.

---

## 📂 Project Structure

project/
├── app.py  
├── config.conf  
└── deploy.sh  

---

## 💻 What I Practiced

- Changing file ownership using chown  
- Updating file permissions using chmod  
- Checking changes with ls -l  
- Running a shell script  
- Adding content to files using echo  

---

## 🔧 Commands I Used

sudo chown :developer app.py  
sudo chown :developer config.conf  
sudo chown :developer deploy.sh  

sudo chmod 660 app.py  
sudo chmod 640 config.conf  
sudo chmod 754 deploy.sh  

echo "deployment start" >> deploy.sh  
./deploy.sh  

---

## 😅 Mistakes I Made (and What I Learned)

- Ran commands in wrong directory → got error  
- Script didn’t run properly → missing proper format  

Fix:
#!/bin/bash  
echo "deployment start"  

---

## 💡 What I Learned

- File ownership (user & group)  
- Permission levels (660, 640, 754)  
- Importance of execute permission  
- Learning from real mistakes  

---

## 🚀 Next Steps

- Practice more Linux commands  
- Learn bash scripting  
- Try automation  
- Explore cron jobs  

---

## 🙌 Final Thought

Still learning and improving every day 💪
