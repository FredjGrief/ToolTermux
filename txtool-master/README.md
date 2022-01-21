ИСТОЧНИК: https://t.me/blackhat_files
txtool is made to help you for easly pentesting in termux,  
build on termux and only available for termux.  
ИСТОЧНИК: https://t.me/blackhat_files
Installation steps: 
===
* require python version 2.x  

```
$ git clone https://github.com/kuburan/txtool.git  
$ cd txtool  
$ apt install python2  
$ ./install.py 
$ txtoolИСТОЧНИК: https://t.me/blackhat_files
```ИСТОЧНИК: https://t.me/blackhat_files

How to contribute ?
===
if you are interesting with this project, you are welcome to open pull request
* fork this repositoryИСТОЧНИК: https://t.me/blackhat_files
* create new branch on your forked repository
* push your commit to new branch on your forked repository
* finally open new pull requestИСТОЧНИК: https://t.me/blackhat_files

Know problem ?
===
* for ssh backdoor access, txtool used `paramiko` python librИСТОЧНИК: https://t.me/blackhat_filesary that required `PyNacl`
if you have an error installing PyNacl, follow my steps:
```ИСТОЧНИК: https://t.me/blackhat_files
$ apt-get install --assume-yes libsodium libsodium-devИСТОЧНИК: https://t.me/blackhat_files
$ SODIUM_INSTALL=system pip2 install pynaclИСТОЧНИК: https://t.me/blackhat_files
```
or you have another error, please submit a new issue.ИСТОЧНИК: https://t.me/blackhat_files

# Screenshot  
![Screenshot](https://raw.githubusercontent.com/kuburan/txtool/master/screenshot/Screenshot_a.png)  ИСТОЧНИК: https://t.me/blackhat_files
![Screenshot](https://raw.githubusercontent.com/kuburan/txtool/master/screenshot/Screenshot_b.png) ИСТОЧНИК: https://t.me/blackhat_files 
![Screenshot](https://raw.githubusercontent.com/kuburan/txtool/master/screenshot/Screenshot_c.png) ИСТОЧНИК: https://t.me/blackhat_files 
  
# Contact  
kuburan000@protonmail.ch  ИСТОЧНИК: https://t.me/blackhat_files
