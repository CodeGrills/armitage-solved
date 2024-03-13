# armitage-solved


Getting Error : Armitage not found


Here's some steps in case anyone has issues:

1. Open /etc/apt/sources.list in your favorite editor as a root user .
2. Add the following lines to the list:
deb http://http.kali.org/kali kali main non-free contrib<br>
deb-src http://http.kali.org/kali kali main non-free contrib
4. Save File
5. Open Terminal > sudo apt-get update > sudo apt-get install armitage >sudo  service postgresql start > sudo msfdb init


And you are good to Go.......

