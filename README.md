# updateminecraftazure

Script used to update minecraft server from Azure Marketplace to version 1.13

To upgrade a Minecraft server on Azure (as long as it was originally deployed using the ARM template or Marketplace image)

## What it does
* Downloads the latest Minecraft server JAR file.
* Updates the minecraft-server systemctl service to point to the new JAR file.
* Restart the minecraft-server service.

## How to update

SSH to your VM and download the script

``` bash
wget https://raw.githubusercontent.com/xobsdk/updateminecraftazure/master/updateminecraft.sh
```

Run the script

``` bash
sudo bash ./updateminecraft.sh
```

Follow on screen message - have fun!

## Credits
Script and help found here: https://msftstack.wordpress.com/2016/06/25/upgrading-minecraft-on-an-azure-vm/
Thanks to @gbowerman - see https://github.com/gbowerman/azure-minecraft
