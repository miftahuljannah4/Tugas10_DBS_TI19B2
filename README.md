# Tugas10_DBS_TI19B2
# Nama  : Miftahul Jannah
# Kelas : TI19B2
# NIM   :311910740

# Backup dan Restore

# 1 Masuk Ke Database
![image](https://user-images.githubusercontent.com/81582495/122663184-c1c97c80-d1c2-11eb-8a65-5cad6562d1c3.png)
![image](https://user-images.githubusercontent.com/81582495/122663163-a78f9e80-d1c2-11eb-9eb8-753aee1de2ea.png)

# 2 Melakukan Proses Penguncian
![image](https://user-images.githubusercontent.com/81582495/122663196-ddcd1e00-d1c2-11eb-80ad-356c67ee3693.png)
![image](https://user-images.githubusercontent.com/81582495/122663248-36042000-d1c3-11eb-95d4-6fc867d846cf.png)

# 3 Melakukan Backup dan Restore Menggunakan Perintahh SQL
![image](https://user-images.githubusercontent.com/81582495/122663271-61870a80-d1c3-11eb-85c0-3b5ddfb79ead.png)
![1](https://user-images.githubusercontent.com/81582495/122663286-795e8e80-d1c3-11eb-8db7-6e5c5004abea.PNG)

# 4 Melakukan Backup dan Restore Menggunakan Perintah MySQLDump
![2](https://user-images.githubusercontent.com/81582495/122663368-22a58480-d1c4-11eb-93e0-71046d51176f.PNG)
![3](https://user-images.githubusercontent.com/81582495/122663371-23d6b180-d1c4-11eb-84b9-91e60b5e55b9.PNG)

# Tulisakan script cron job untuk melakukan backupotomatis setiap hari minggu jam 12 malam !
# 1. Script Untuk menjalankan backup database setiap hari minggu jam 12 malam : script dibawah :
# 0 0 * * 7 mysqldump -u root -p31564 miftahul_311910740 > backup2.sql
