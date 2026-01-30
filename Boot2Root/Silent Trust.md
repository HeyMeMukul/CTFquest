After opening the file in any VM Manager , i used virt-manager 

1. press e for advanced option
2. type " init=/bin/bash " after the end of line starting with linux 
3. pres F10 ( and boom you will be the root )

To Change the Password Follow below steps 
1. mount -n -o remount,rw /
2. passwd root
3. exec /sbin/init

After that go to root/root.flag for the flag 

Image :

![50cd6f48-1136-4157-ba62-00c4a096be7e](https://github.com/user-attachments/assets/3e5948f9-bf00-46bf-9dbe-603901fbd387)
