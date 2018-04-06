# Update-Worker-VPS
These scripts have been tested on Ubuntu Server 16.04 LTS installed on Azure VPS.

To download this scripts, connect to the VPS and run this line:
```bash
sudo apt-get install git
```
Once git is installed, move to your home directory and clone the scripts.
```bash
git clone https://github.com/webmetender/Update-Worker-VPS.git
```
After file download, make the scripts executable:
```bash
sudo chmod +x ./ConfigUbuntuOnAzure/01_sys_update.sh
sudo chmod +x ./ConfigUbuntuOnAzure/02_worker_compile_config.sh
```
You'd be now able to run the first file, it updates the OS
You'll be asked to agree by hitting 'y' several times during the process.
```bash
sudo ./ConfigUbuntuOnAzure/01_sys_install_config.sh
```

Move to your home directory, to 242 folder and run the second script.
```bash
sudo ./ConfigUbuntuOnAzure/02_worker_compile_config.sh
```
