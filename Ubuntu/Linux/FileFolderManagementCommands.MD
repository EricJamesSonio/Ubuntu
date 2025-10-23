sudo mkdir /var/www/project         # Create a folder that needs root access
sudo rm -rf /var/www/project        # Force delete a folder (⚠️ careful!)
sudo chown eric:eric /var/www       # Change ownership of folder to your user
sudo chmod 755 /var/www             # Change folder permissions
sudo mv myfile.txt /etc/            # Move a file into a protected directory
sudo cp myfile.conf /etc/nginx/     # Copy a config file into a system folder
