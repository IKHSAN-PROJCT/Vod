# Cara Install dan Mengubah tampilan di Termux

Ikuti langkah-langkah di bawah ini untuk menginstal dan menjalankan VOD di Termux:

## Langkah Instalasi

1. **Update dan Upgrade Termux:**

   ```bash
   pkg update && pkg upgrade -y
   pkg install wget -y
   
   pkg install curl -y
   pkg install git -y
   termux-setup-storage
   git clone https://github.com/IKHSAN-PROJCT/Vod.git
   cd Vod
   chmod +x *
   git pull
   ./run.sh
