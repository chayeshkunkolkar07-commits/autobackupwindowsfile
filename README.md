# 🖥️ Auto Backup Desktop to D: Drive

Automated backup solution for Windows that copies all files from your **Desktop** to the **D: drive** using a scheduled task.

---

## 🚀 Setup Instructions

1. **Clone Repository**
   - Run the following command:
     ```bash
     git clone https://github.com/chayeshkunkolkar07-commits/autobackupwindowsfile.git
     ```

2. **Create Scheduled Task**
   a. Open **Task Scheduler** (`Win + R → taskschd.msc`)  
   b. Select **Create Basic Task** → Name: `Desktop_Auto_Backup`  
   c. Choose **Daily** (or preferred frequency)  
   d. Action → **Start a Program** → Select `backup_desktop.bat`  
   e. Save and test by running the task manually
## 📸 task schedule 
click basic Task 
![Task Scheduler Setup](images/taskscheduler1.png)
![Task Scheduler Setup](images/taskscheduler2.png)
![Task Scheduler Setup](images/taskscheduler3_1.png)
![Task Scheduler Setup](images/taskscheduler4.png)
![Task Scheduler Setup](images/taskscheduler5_1.png)
![Task Scheduler Setup](images/taskscheduler6.png)
## 📸 Setup Slides

<p align="center">
  <img src="images/taskscheduler1.png" alt="Step 1 - Clone Repo" width="400"/>
</p>

<p align="center">
  <img src="images/taskscheduler2.png" alt="Step 2 - Configure Script" width="400"/>
</p>

<p align="center">
  <img src="images/taskscheduler3_1.png" alt="Step 3 - Task Scheduler" width="400"/>
</p>




   
