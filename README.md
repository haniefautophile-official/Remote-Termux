# Remote-Termux
Fungsi untuk meremote termux ke PC menggunakan cmd, mobaxtream, putty dll tanpa harus menginstall bluestack android di PC.
<img src="https://github.com/haniefautophile-official/Remote-Termux/blob/main/SS/20250126_201408.jpg"/>
<details open>
  <summary><strong><h2>How to Install</h2></strong></summary>
  
 
  
> Command install tools from termux
  
```bash

whoami
psswd
ifconfig
sshd
nmap -Pn localhost
```
> whoami = fungsi untuk mengetahui username kita di termux.<br>
> passwd = fungsi untuk membuat password baru dan konfirmasi password<br>
> nmap -Pn localhost = fungsi untuk melihat port yang terbuka<br>
> ifconfig = fungsi untuk mengetahui alamat ip, password ip ada di  wlan0 di bagian inet<br>
Salin semua dari username, port dan alamat IP. Kemudian buka cmd dan sejenisnya:
> ketikan di cmd misalnya: root -p 8022 root@192.168.19 kemudian enter, ketik yes dan masukan password yang sudah di buat dan selamat termux anda sudah berada di PC, tak perlu menginstall blustack lagi.

</details>
