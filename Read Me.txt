########## first you have to install ibus using this command:

sudo apt-get install ibus-m17n

##########Then Place this two code:

sudo chmod 777 /usr/share/m17n/   
sudo chmod 777 /usr/share/m17n/icons

*********Now unzip the (the bijoy linux.zip) file.
Now open extract file and select (2) .png file and move it to: file system>usr>share>m17n>icons> there.
Now Select (2) .mim file and move it to: file system>usr>share>m17n> there.

############Now go to tarminal and copy paste this two code:

sudo chmod 777 /var/lib/dpkg/info/m17n-db.list

gedit /var/lib/dpkg/info/m17n-db.list     

################ Now open (m.17n-db.list) file to: system>var>lib>dpkg>info>m17n-db.list and copy below command and save the file.

/usr/share/m17n/icons/bn-bijoyClassic.png
/usr/share/m17n/bn-bijoyClassic.mim
/usr/share/m17n/icons/bn-bijoyUnicode.png
/usr/share/m17n/bn-bijoyUnicode.mim

 
##########################################################
Don't forget to subscribe our channel youtube.com/techtd
also share it with your family and friends.
Thank you !!!!!!!!!