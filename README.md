# INSTALL GENIEACS OTOMATIS

### Memulai Install Genieacs
**pastikan sudah berada di root**
```
apt install git curl -y
git clone https://github.com/kendengisyudi/genieacs.git
cd genieacs
chmod +x install.sh && chmod +x darkmode.sh
```

### INSTALL GENIEACS DARKMODE Ubuntu OS 22.04
```
bash darkmode.sh
```
### INSTALL GENIEACS THEMA ORIGINAL v@1.2.13
```
bash install.sh
```

Baca terlebih dahulu !!!

#=== Script update GenieACS ====#

Config sebelumnya akan terhapus dan tergantikan oleh config baru

Yang akan diupdate, yaitu:
login:
username : admin
password : admin

### Login Superadmin
username : admin
password : 
   
#===Script/config tersebut akan terganti dengan yang baru ====#

Jika anda memiliki config/script custom buatan anda sendiri,<br> 
silahkan backup terlebih dahulu, kemudian setelah update lakukan config manual lagi sesuai config custom anda.<br>

Device, user, permisions, tidak akan terpengaruh<br>
Bagi yang confignya error, akan ter-repair dengan script ini<br>
Anda masih bisa kembali ke konfigurasi sebelumnya dengan memilih restore<br>
======= CARA RESTORE ========<br>
```
cd
```
```
sudo mongorestore --db=genieacs --drop genieacs-backup/genieacs
```
