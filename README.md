# Remote-Termux
Fungsi untuk meremote termux ke PC menggunakan cmd, mobaxtream, putty dll tanpa harus menginstall bluestack android di PC.
<details open>
  <summary><strong><h2>How to Install</h2></strong></summary>
  
 
  
> Command install tools from termux
  
```bash
apt-get update
apt-get upgrade
pkg install openssh nmap
whoami
psswd
ifconfig
sshd
nmap -Pn localhost
```
> whoami = fungsi untuk mengetahui username kita di termux.<br>
> passwd = fungsi untuk membuat password baru dan konfirmasi password<br>
> nmap -Pn localhost = fungsi untuk melihat port yang terbuka<br>
> ifconfig = fungsi untuk mengetahui alamat ip, password ip ada di  IPv4 Address<br>
Salin semua dari username, port dan alamat IP. Kemudian buka cmd dan sejenisnya:
> ketikan di cmd misalnya: root -p 8022 root@192.168.19 kemudian enter, ketik yes dan masukan password yang sudah di buat dan selamat termux anda sudah berada di PC, tak perlu menginstall blustack lagi.

</details>
