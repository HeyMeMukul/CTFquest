After opening the file in any VM Manager , i used virt-manager 

1. press e for advanced option
2. type " init=/bin/bash " after the end of line starting with linux 
3. pres F10 ( and boom you will be the root )

To Change the Password Follow below steps 
1. mount -n -o remount,rw /
2. passwd root
3. exec /sbin/init

After that go to root/flag/root.txt for the flag 

Image : 

![f096635f-19dc-4291-824a-e79417400319](https://github.com/user-attachments/assets/8adb7fa1-039a-47e7-ab5b-45a178517c10)
