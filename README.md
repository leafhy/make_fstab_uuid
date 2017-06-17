# make_fstab_uuid
Convert /dev/sdX to UUID in fstab

## How To Use

**make script executable**

`chmod +x make_fstab_uuid`

**show changes without writing**

`./make_fstab_uuid /etc/fstab`

**convert /dev/sdX to UUID in /etc/fstab**

`./make_fstab_uuid /etc/fstab -i`


Verified working on Salix Os 14.1

Source https://forum.salixos.org/viewtopic.php?p=1597
