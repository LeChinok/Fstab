# Fstab
A utility that processes a YAML file and output an etc/fstab file based on that yaml

Script will configure fstab based on the YAML configuration provided in file.

- Install dependencies via python -r requirements.txt
- run mountscript.py mount.yml via sudo (since we will be modifying file system)
- priority and attribute should be Observed like sample yaml structure.
- check out the /etc/fstab and if everything is right use mount -a
- For the root reserve section, please run tune2fs command to enable ext4 feature on your disk

