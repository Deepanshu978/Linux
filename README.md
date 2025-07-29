# LinuxServer_Project 🚀

This project demonstrates a basic Linux server setup using:

- ✅ Apache Web Server
- ✅ MySQL Database (with external access)
- ✅ PHP Integration for DB queries
- ✅ AWS CloudWatch Agent Monitoring (EC2)

## 🖥️ Host Machines:
- `ubuntu1-server-node`: Main web + MySQL server
- `ubuntu2-backup-node`: Connected node for web access & DB query testing

## 💡 What I Learned:
- Set up LAMP stack (Linux, Apache, MySQL, PHP)
- Created MySQL DB and allowed remote access
- Wrote and debugged PHP to fetch DB data
- Installed and configured AWS CloudWatch Agent
- Troubleshoot IAM and Endpoint errors while configuring monitoring
- Explored JSON config file for AWS monitoring

## 📁 File Highlights:
- `dbtest.php`: PHP script to query the DB and show results on a webpage
- `cloudwatch-config.json`: Config for AWS CloudWatch Agent
- `sql-commands.sql`: All commands used for MySQL setup and user creation
- `linux-setup-commands.txt`: Linux, Apache, PHP installation steps

---

