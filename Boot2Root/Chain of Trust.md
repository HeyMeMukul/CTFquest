After opening the file in any VM Manager , i used virt-manager 

1. press e for advanced option
2. type " init=/bin/bash " after the end of line starting with linux 
3. pres F10 ( and boom you will be the root )


To Change the Password Follow below steps 
1. mount -n -o remount,rw /
2. passwd root
3. exec /sbin/init

After that go to root/root.txt for the flag 

![fdedff8d-da31-4979-a287-df45cd5d6564](https://github.com/user-attachments/assets/15e74c02-52b8-48f1-9ad1-48fd537d4d33)
