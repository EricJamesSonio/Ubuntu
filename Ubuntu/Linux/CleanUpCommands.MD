sudo apt clean              # Cleans up cached package files
sudo apt autoremove         # Removes unused dependencies
sudo du -sh /var/cache/apt  # Check how big your package cache is
sudo apt purge <package>    # Fully remove a package and config
