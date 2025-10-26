 # 👋 Hi, I'm Shabbir
 ### 🧑‍💻 IT Engineer | Transitioning from IT Engineering → Cloud/DevOps

## 🧑‍💻 About Me
- 💡 Transitioning from IT Engineering → Cloud/DevOps
- 💬 Ask me about: Systems Administaration, Cloud Services, Automation & CICD.
- 📫 Connect: [LinkedIn](https://linkedin.com/in/yourprofile)

  
## 🔧 Tools & Technologies
Networking | Linux | AWS | Shell Scripting| Terraform | Git | Docker | Kubernetes | Jenkins | Ansibile

This portfolio highlights my Cloud/DevOps learning projects and hands-on automation Task.

## 📂 Featured Projects
🔵 Project 1:  Host a Static Website on AWS EC2 using Apache

🎯 Goal: Deploy a simple HTML website using Apache.

Steps:
#Launch an EC2 Instance
sudo yum update -y
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd

#Create a test webpage:

#echo "<h1>Welcome to My EC2 Web Server</h1>" | sudo tee /var/www/html/index.html


#Open your EC2 public IP in a browser → you should see the page.

#To customize, upload your HTML files via:

scp -i mykey.pem index.html ec2-user@<Public-IP>:/var/www/html/

✅ We just hosted a web server!




