| Purpose                          | Command                                   | Description                                |
| -------------------------------- | ----------------------------------------- | ------------------------------------------ |
| 🧩 **Update system**             | `sudo apt update && sudo apt upgrade -y`  | Refresh and upgrade all installed packages |
| 📦 **Install software**          | `sudo apt install <package>`              | Example: `sudo apt install git`            |
| 🧹 **Clean up system**           | `sudo apt autoremove && sudo apt clean`   | Removes junk and unused dependencies       |
| 📁 **Create protected folder**   | `sudo mkdir /var/www/myproject`           | Make a folder that needs admin access      |
| 🪶 **Change file permissions**   | `sudo chmod 755 <file or folder>`         | Adjust file/folder access rights           |
| 👑 **Change ownership**          | `sudo chown $USER:$USER <file or folder>` | Give yourself ownership of a folder/file   |
| 📝 **Edit system config**        | `sudo nano /etc/hosts`                    | Edit important system files (like hosts)   |
| 🚀 **Move system files**         | `sudo mv myapp.conf /etc/nginx/`          | Move files into protected system dirs      |
| 🧠 **Run a service manually**    | `sudo service nginx start`                | Start or stop older-style services         |
| 🔑 **Run as root (full access)** | `sudo su`                                 | Switch to full root user (exit to go back) |

< ------------------------ BONUS ---------------------->

if u want to view the port of the container: 
--> curl http://localhost:3000

if u want to go directly in that port:
make sure to install wslu first! 
--> sudo apt install wslu
--> wslview http://localhost:3000