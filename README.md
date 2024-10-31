# Langkah Install DNS Server Apache di Debian 10
1. Masuk ke direktori bind
2. Masukkan nama sesuai dengan nama Anda
3. Masukkan zone "sekolah.sch.id" { type master;
4. Salin db.local menjadi db.sekolah.sch.id
5. Simpan dengan menekan ctrl+x lalu y (enter)
6. Edit file db.tkj2.net
7. Restart jaringan dengan perintah #/etc/init.d/networking restart
