# FInstallerv2
#!/bin/bash
#Pembuat : Tn.Alifio
#Mau Ngapain Lu Kesini Tanpa Izin Tn.Alifio
###########################################
clear

ulang="y"
while [ $ulang = "y" ];
do
  echo "«--------------------✧------------------»" | lolcat
  echo "Sedang Memuat Tampilan Pilihan...!" | lolcat
  echo "«--------------------✧------------------»" | lolcat
  sleep 1
  clear

  echo "==|=======>1)" | lolcat
  sleep 2
  clear

  echo "==|=======>2)" | lolcat
  sleep 3
  clear

  echo "==|=======>3)" | lolcat
  sleep 3
  clear

  echo "Selamat Datang Di Tools Tn.Alifio" | lolcat
  sleep 3
  clear

  echo "\033[31;1m<════════════════════════════════════════════>"
  echo "\033[31;1m    ⎈Author:TN.AlifioGans⎈"
  echo "\033[0;36m    Wa : 081211912925"
  echo "\033[0;32m    Thanks : Ga Ada Saya Solo Player:v"
  echo "    🅃🄾🄾🄻🅂 🅃🄴🅁🄼🅄🅇 🄸🄽🅂🅃🄰🄻🄻🄴🅁"
  echo "\033[0;36m<════════════════════════════════════════════>"  
  echo "════════════════════════════════════════"
  echo "\033[0;32m[ 1 ] install tools spam call"
  echo "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~"
  echo "[ 2 ] install metasploit"
  echo "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~"
  echo "[ 3 ] install crack Fb "
  echo "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~"
  echo "[ 4 ] install Hack-pulsa "
  echo "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~"
  echo "[ 5 ] install RED_HAWK "
  echo "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~"
  echo "[ 6 ] install Hack-Wifi(Root) "
  echo "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~"
  echo "[ 7 ] install hack-IG "
  echo "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~"
  echo "[ 8 ] install Hek-Nasa "
  echo "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~"
  echo "[ 0 ] exit"
  echo "\033[36;1mᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚ"
  read -p "Pilih Toolsnya Gan --> : " pilih;
  if [ $pilih = "1" ];
  then
      echo "install Spam Call "
      cd $HOME
      apt update && apt upgrade -y
      apt install git
      apt install php
      git clone https://github.com/siputra12/prank
      cd prank
      ls
      php wa.php
      sleep 1
  elif [ $pilih = "2" ];
  then
      echo "install Metasploit "
      pkg update && pkg upgrade
      pkg install wget
      wget https://5hady.github.io/metasploit.sh
      bash metasploit.sh
      msfconsole
      sleep 2
  elif [ $pilih = "3" ];
  then
      echo "install CrackFB Massal "
      cd $HOME
      pkg update && pkg upgrade
      pkg install curl git python2
      pkg install git
      pkg install python2
      pip2 install mechanize
      pip2 install requests
      git clone https://github.com/UziBorot/fbhack/
      ls
      cd fbhack
      python2 fbhack.py
      sleep 2
  elif [ $pilih = "4" ];
  then
       echo "install Hack-PulsaFree "
       cd $HOME
       apt update && apt upgrade
       apt install php
       apt install toilet
       apt install git
       git clone https://github.com/MrUncle/PulsaGratis
       cd PulsaGratis
       chmod +x *
       ls
       sh Pulsa.sh
       sleep 2
  elif [ $pilih = "5" ];
  then
      echo "install RED_HAWK "
      cd $HOME
      pkg install php
      pkg install curl
      git clone https://github.com/Tuhinshubhra/RED_HAWK
      ls
      cd RED_HAWK
      php rhawk.php
      sleep 2
  elif [ $pilih = "6" ];
  then
      echo "install Hack-Wifi(root) "
      cd $HOME
      pkg update && pkg upgrade
      pkg install python2
      pkg install git
      git clone https://github.com/derv82/wifite
      ls
      cd wifite
      python2 wifite.py
      sleep 2
  elif [ $pilih = "7" ];
  then
      echo "install Hack-IG "
      cd $HOME
      apt update && apt upgrade
      pkg install bash
      pkg install python2
      pkg install git
      pip2 install requests
      pip2 install mechanize
      git clone https://github.com/storiku/instahack
      ls
      cd instahack
      bash ig.sh
      sleep 2
  elif [ $pilih = "8" ];
  then
      echo "Sedang Install Hek-Nasa (Siap² kedatangan FBI) "
      cd $HOME
      sleep 2
      clear
      echo "
      ██▀▀▀▀███▀▀▀▀███▀▀▀▀██
      █┌─┐┌─┐█┌─┐┌─┐█┌─┐┌─┐█
      █└─┘└─┘█└─┘└─┘█└─┘└─┘█
      ██▌└┘▐███▌└┘▐███▌└┘▐██
      ██┼┼┼┼███┼┼┼┼███┼┼┼┼██
      ██▄▄▄▄███▄▄▄▄███▄▄▄▄██
      -- Sedang Hack Nasa...-- "
      echo
      echo "-Sedang Mendapatkan Akses Masuk..- "
      sleep 2
      clear
      echo "-Telah Mendapatkan Akses Masuk..- "
      sleep 2
      clear
      echo "──▄────▄▄▄▄▄▄▄────▄─── "
      echo " Author : Tn.Alifio "
      echo "──▄────▄▄▄▄▄▄▄────▄─── "
      echo "- Situs Nasa Berhasil Di Hack..-"
      echo "- Silahkan Lihat Situs Nasa..-"
      sleep 3
      clear
  elif [ $pilih = "0" ];
  then
       echo " Terima kasih Sudah Menggunakan Tools Tn.alifio "
       sleep 2
       exit
   else
       echo " ERROR GAN : Pilihan anda salah "
       sleep 2
       echo $ulang
    fi
  done
 

