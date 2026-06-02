# Linux Permissions & Ownership Practice

Today I worked on a small Linux practice project to get more comfortable with file permissions, ownership, and basic scripting.

Instead of just reading commands, I created a mini project and practiced hands-on.

---

## Project Structure

project/
├── app.py  
├── config.conf  
└── deploy.sh  



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

