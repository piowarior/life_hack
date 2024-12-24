Berikut ini adalah file `fungsi-perintah.md` yang berisi **tabel dengan 100 perintah beserta penjelasannya** untuk penggunaan **PHP**, **Linux**, dan **pengembangan aplikasi web**.

---

# Fungsi dan Penjelasan Perintah di Linux dan PHP

| **No** | **Perintah**                                | **Penjelasan**                                                                                 |
|--------|----------------------------------------------|-----------------------------------------------------------------------------------------------|
| 1      | `php artisan migrate:fresh`                 | Menghapus semua tabel di database dan menjalankan migrasi dari awal.                          |
| 2      | `rm -rf /path/to/folder/*`                  | Menghapus seluruh isi folder secara rekursif tanpa konfirmasi.                                |
| 3      | `sudo rm -rf /path/to/folder/{*,.*}`        | Menghapus semua file dan folder, termasuk file tersembunyi.                                   |
| 4      | `php artisan serve`                         | Menjalankan server lokal Laravel di port 8000 secara default.                                 |
| 5      | `ls -la`                                    | Menampilkan daftar file dan folder beserta detailnya, termasuk yang tersembunyi.              |
| 6      | `cd /path/to/folder`                        | Berpindah ke direktori tertentu.                                                              |
| 7      | `cp -r /source/folder /destination`         | Menyalin folder beserta isinya secara rekursif ke lokasi lain.                                |
| 8      | `mv /source/file /destination/`             | Memindahkan file ke folder tujuan.                                                            |
| 9      | `chmod 755 /path/to/file`                   | Memberikan hak akses baca, tulis, dan eksekusi pada pengguna, dan hanya baca untuk lainnya.   |
| 10     | `chown user:group /path/to/file`            | Mengubah kepemilikan file atau folder ke pengguna dan grup tertentu.                          |
| 11     | `php artisan config:cache`                  | Membuat cache untuk konfigurasi Laravel agar lebih cepat diakses.                             |
| 12     | `composer install`                          | Menginstal semua dependensi aplikasi PHP berdasarkan file `composer.json`.                    |
| 13     | `sudo apt update`                           | Memperbarui daftar paket dari repositori.                                                     |
| 14     | `sudo apt upgrade`                          | Memperbarui semua paket yang sudah terpasang di sistem.                                       |
| 15     | `npm install`                               | Menginstal semua dependensi Node.js berdasarkan file `package.json`.                          |
| 16     | `git clone https://repo.git`                | Mengkloning repositori Git dari URL ke direktori lokal.                                       |
| 17     | `git pull origin main`                      | Mengambil dan menggabungkan perubahan dari cabang `main`.                                     |
| 18     | `docker-compose up`                         | Menjalankan aplikasi menggunakan Docker Compose.                                              |
| 19     | `systemctl restart nginx`                   | Merestart layanan Nginx.                                                                      |
| 20     | `sudo ufw allow 80`                         | Membuka akses port 80 untuk HTTP melalui firewall.                                            |
| 21     | `ifconfig`                                  | Menampilkan informasi tentang konfigurasi jaringan.                                           |
| 22     | `ping 8.8.8.8`                              | Menguji koneksi jaringan dengan server tertentu.                                              |
| 23     | `whoami`                                    | Menampilkan nama pengguna aktif.                                                              |
| 24     | `php artisan make:migration create_table`   | Membuat file migrasi baru di Laravel.                                                         |
| 25     | `mysql -u user -p`                          | Masuk ke antarmuka MySQL sebagai pengguna tertentu.                                           |
| 26     | `df -h`                                     | Menampilkan penggunaan ruang disk dengan format yang mudah dibaca.                            |
| 27     | `du -sh /path/to/folder`                    | Menampilkan ukuran folder secara keseluruhan.                                                 |
| 28     | `history`                                   | Menampilkan daftar perintah yang sudah dijalankan.                                            |
| 29     | `clear`                                     | Membersihkan layar terminal.                                                                 |
| 30     | `echo "Hello, World!"`                      | Mencetak teks ke terminal.                                                                    |
| 31     | `touch /path/to/file`                       | Membuat file kosong baru.                                                                     |
| 32     | `php artisan route:list`                    | Menampilkan daftar rute yang tersedia di aplikasi Laravel.                                    |
| 33     | `npm run dev`                               | Menjalankan skrip pengembangan dari Node.js.                                                  |
| 34     | `tar -czvf archive.tar.gz /path/to/folder`  | Membuat arsip kompresi dari folder tertentu.                                                  |
| 35     | `unzip archive.zip`                         | Mengekstrak file arsip ZIP.                                                                   |
| 36     | `find / -name "filename"`                   | Mencari file tertentu di seluruh sistem.                                                      |
| 37     | `ps aux`                                    | Menampilkan semua proses yang berjalan di sistem.                                             |
| 38     | `kill -9 process_id`                        | Menghentikan proses dengan paksa menggunakan PID.                                             |
| 39     | `top`                                       | Menampilkan proses berjalan dan penggunaan CPU secara real-time.                              |
| 40     | `crontab -e`                                | Membuka editor untuk menjadwalkan tugas cron.                                                 |
| 41     | `ssh user@server_ip`                        | Masuk ke server jarak jauh melalui SSH.                                                       |
| 42     | `scp /local/file user@server:/remote/path`  | Mengirim file ke server jarak jauh menggunakan SCP.                                           |
| 43     | `wget https://file.url`                     | Mengunduh file dari URL tertentu.                                                             |
| 44     | `curl -I https://website.com`               | Menampilkan header respons HTTP dari website tertentu.                                        |
| 45     | `htop`                                      | Antarmuka interaktif untuk memonitor proses.                                                  |
| 46     | `sudo shutdown -h now`                      | Mematikan sistem segera.                                                                      |
| 47     | `sudo reboot`                               | Merestart sistem.                                                                             |
| 48     | `ng serve`                                  | Menjalankan server Angular untuk pengembangan.                                                |
| 49     | `pip install package_name`                  | Menginstal paket Python melalui `pip`.                                                        |
| 50     | `python3 script.py`                         | Menjalankan skrip Python 3.                                                                   |
| 51     | `alias ll='ls -la'`                         | Membuat alias untuk perintah agar lebih mudah digunakan.                                      |
| 52     | `env`                                       | Menampilkan semua variabel lingkungan.                                                        |
| 53     | `export VAR=value`                          | Menyimpan variabel lingkungan baru untuk sesi saat ini.                                       |
| 54     | `unset VAR`                                 | Menghapus variabel lingkungan tertentu.                                                       |
| 55     | `dig example.com`                           | Menampilkan informasi DNS dari domain tertentu.                                               |
| 56     | `nslookup example.com`                      | Mencari alamat IP dari domain tertentu.                                                       |
| 57     | `php artisan tinker`                        | Masuk ke konsol interaktif Laravel.                                                           |
| 58     | `git status`                                | Menampilkan status perubahan di repositori Git.                                               |
| 59     | `git add .`                                 | Menambahkan semua perubahan ke staging area Git.                                              |
| 60     | `git commit -m "message"`                   | Menyimpan perubahan dengan pesan tertentu.                                                    |
| 61     | `php -v`                                    | Menampilkan versi PHP yang terinstal.                                                         |
| 62     | `node -v`                                   | Menampilkan versi Node.js yang terinstal.                                                     |
| 63     | `npm -v`                                    | Menampilkan versi npm yang terinstal.                                                         |
| 64     | `docker -v`                                 | Menampilkan versi Docker.                                                                     |
| 65     | `service apache2 start`                     | Memulai layanan Apache.                                                                       |
| 66     | `service apache2 stop`                      | Menghentikan layanan Apache.                                                                  |
| 67     | `service apache2 restart`                   | Merestart layanan Apache.                                                                     |
| 68     | `mysqladmin -u root password`               | Mengatur atau mengubah password root MySQL.                                                   |
| 69     | `php artisan make:controller`               | Membuat controller baru di Laravel.                                                           |
| 70     | `composer require package_name`             | Menambahkan paket baru ke dalam proyek PHP menggunakan Composer.                              |
| 71     | `composer update`                           | Memperbarui semua paket yang terdaftar di `composer.json` ke versi terbaru.                   |
| 72     | `php artisan make:model ModelName`          | Membuat model baru di Laravel.                                                                |
| 73     | `php artisan make:middleware AuthMiddleware`| Membuat middleware baru di Laravel.                                                           |
| 74     | `curl -O https://file.url`                  | Mengunduh file dengan nama aslinya dari URL tertentu.                                         |
| 75     | `rsync -avz /source/ user@server:/destination/`| Menyalin file atau folder secara sinkron ke server jarak jauh.                            |
| 76     | `find /path -type f -mtime -7`              | Mencari file yang diubah dalam 7 hari terakhir.                                               |
| 77     | `sudo apt autoremove`                       | Menghapus paket yang tidak diperlukan lagi.                                                   |
| 78     | `php artisan migrate:rollback`              | Mengembalikan migrasi terakhir di Laravel.                                                    |
| 79     | `php artisan db:seed`                       | Menjalankan seed untuk mengisi data awal ke database.                                         |
| 80     | `echo $PATH`                                | Menampilkan jalur direktori yang digunakan untuk mencari perintah eksekusi.                   |
| 81     | `php -S localhost:8000`                     | Menjalankan server PHP built-in di port 8000.                                                 |
| 82     | `ssh-keygen -t rsa`                         | Membuat pasangan kunci SSH baru untuk otentikasi.                                             |
| 83     | `ssh-copy-id user@server_ip`                | Mengirim kunci publik SSH ke server untuk login tanpa kata sandi.                             |
| 84     | `sudo adduser newuser`                      | Menambahkan pengguna baru di sistem Linux.                                                    |
| 85     | `sudo passwd newuser`                       | Mengatur atau mengubah kata sandi untuk pengguna baru.                                        |
| 86     | `crontab -l`                                | Menampilkan tugas cron yang sudah dijadwalkan untuk pengguna saat ini.                        |
| 87     | `gzip file.txt`                             | Mengompres file teks menggunakan gzip.                                                        |
| 88     | `gunzip file.txt.gz`                        | Mengekstrak file yang dikompres menggunakan gzip.                                             |
| 89     | `docker ps -a`                              | Menampilkan semua kontainer Docker, termasuk yang sudah dihentikan.                           |
| 90     | `docker rm container_id`                    | Menghapus kontainer Docker tertentu.                                                          |
| 91     | `docker rmi image_id`                       | Menghapus image Docker dari sistem.                                                           |
| 92     | `php artisan optimize`                      | Mengoptimalkan aplikasi Laravel dengan membuat cache untuk rute dan konfigurasi.              |
| 93     | `df -Th`                                    | Menampilkan penggunaan disk dengan format tipe file system.                                   |
| 94     | `sudo nano /etc/hosts`                      | Membuka file `/etc/hosts` untuk mengedit DNS lokal.                                           |
| 95     | `hostnamectl set-hostname new_hostname`     | Mengubah nama host pada sistem.                                                               |
| 96     | `php artisan down`                          | Memasukkan aplikasi Laravel ke mode pemeliharaan.                                             |
| 97     | `php artisan up`                            | Mengembalikan aplikasi Laravel dari mode pemeliharaan.                                        |
| 98     | `watch -n 5 df -h`                          | Menjalankan perintah `df -h` setiap 5 detik.                                                  |
| 99     | `sudo lsof -i :80`                          | Menampilkan proses yang menggunakan port 80.                                                  |
| 100    | `exit`                                      | Keluar dari sesi terminal atau SSH.                                                           |
| 101    | `git clone https://repo.url`                 | Mengkloning repositori Git dari URL ke direktori lokal.                                        |
| 102    | `git remote add origin https://repo.url`     | Menambahkan remote baru bernama `origin` dengan URL tertentu ke repositori lokal.              |
| 103    | `git remote set-url origin https://new.url`  | Mengubah URL remote `origin` di repositori lokal.                                              |
| 104    | `git push origin master`                     | Mengirim perubahan dari cabang `master` lokal ke `origin`.                                     |
| 105    | `git fetch origin`                           | Mengambil perubahan terbaru dari remote `origin` tanpa menggabungkannya ke cabang lokal.       |
| 106    | `git merge origin/master`                    | Menggabungkan perubahan dari `master` remote ke cabang lokal saat ini.                        |
| 107    | `git pull origin master`                     | Mengambil perubahan dari `origin` dan langsung menggabungkannya ke `master` lokal.             |
| 108    | `git branch new-branch`                      | Membuat cabang baru di repositori lokal.                                                      |
| 109    | `git checkout new-branch`                    | Berpindah ke cabang baru.                                                                     |
| 110    | `git checkout -b new-branch`                 | Membuat dan langsung berpindah ke cabang baru.                                                |
| 111    | `git stash`                                  | Menyimpan perubahan yang belum di-commit ke dalam stash sementara.                            |
| 112    | `git stash pop`                              | Mengembalikan perubahan dari stash dan menghapusnya dari daftar stash.                        |
| 113    | `git rebase master`                          | Menyelaraskan cabang saat ini dengan `master` menggunakan rebase.                             |
| 114    | `git reset --hard HEAD`                      | Menghapus semua perubahan lokal yang belum di-commit.                                         |
| 115    | `git log`                                    | Menampilkan riwayat commit dari repositori.                                                   |
| 116    | `git diff`                                   | Menampilkan perbedaan antara perubahan lokal dan commit terakhir.                             |
| 117    | `git rm --cached file`                       | Menghapus file dari staging area tanpa menghapus dari direktori kerja.                        |
| 118    | `git status -s`                              | Menampilkan status repositori dalam format singkat.                                           |
| 119    | `git tag -a v1.0 -m "release 1.0"`           | Membuat tag dengan nama `v1.0` dan pesan tertentu.                                            |
| 120    | `git push origin --tags`                     | Mengirim semua tag yang ada ke remote `origin`.                                               |
| 121    | `git cherry-pick commit_hash`                | Mengambil commit tertentu dari cabang lain dan menerapkannya ke cabang saat ini.              |
| 122    | `git revert commit_hash`                     | Membatalkan commit tertentu dengan membuat commit baru yang berlawanan.                       |
| 123    | `git clean -fd`                              | Menghapus file yang tidak terlacak dan folder yang tidak diperlukan dari repositori lokal.     |
| 124    | `git blame file`                             | Menampilkan siapa yang mengubah setiap baris dalam file tertentu.                             |
| 125    | `git show commit_hash`                       | Menampilkan detail commit tertentu, termasuk perubahan file.                                  |
| 126    | `git bisect start`                           | Memulai proses `bisect` untuk menemukan commit yang menyebabkan bug.                          |
| 127    | `git bisect bad`                             | Menandai commit sebagai `bad` (terdapat bug) dalam proses bisect.                             |
| 128    | `git bisect good commit_hash`                | Menandai commit sebagai `good` (tanpa bug) dalam proses bisect.                               |
| 129    | `git rebase --abort`                         | Membatalkan proses rebase dan mengembalikan ke keadaan sebelumnya.                            |
| 130    | `git merge --abort`                          | Membatalkan proses merge jika terjadi konflik.                                                |
| 131    | `git commit --amend`                         | Mengubah atau memperbaiki commit terakhir.                                                    |
| 132    | `git reflog`                                 | Menampilkan riwayat lengkap referensi (termasuk branch yang dihapus).                         |
| 133    | `git config --global user.name "Your Name"`  | Mengatur nama pengguna global untuk Git.                                                      |
| 134    | `git config --global user.email "you@example.com"` | Mengatur email global untuk Git.                                                          |
| 135    | `git config --list`                          | Menampilkan konfigurasi Git saat ini.                                                        |
| 136    | `git reset --soft HEAD~1`                    | Mengembalikan commit terakhir tanpa menghapus perubahan di file kerja.                        |
| 137    | `git archive --format=tar --output=repo.tar master` | Membuat arsip `tar` dari cabang `master`.                                          |
| 138    | `git grep "search_term"`                     | Mencari teks tertentu dalam file yang terlacak oleh Git.                                      |
| 139    | `git submodule add https://repo.url`         | Menambahkan submodule ke dalam proyek Git.                                                   |
| 140    | `git submodule update --init --recursive`    | Menginisialisasi dan memperbarui semua submodule dalam proyek Git.                           |
| 141    | `git shortlog -s -n`                         | Menampilkan riwayat commit dalam format singkat dan mengelompokkan berdasarkan penulis.       |
| 142    | `git pull --rebase`                          | Menarik perubahan dari remote dan menerapkan rebase ketimbang merge.                         |
| 143    | `git remote show origin`                     | Menampilkan informasi detail tentang remote `origin`.                                        |
| 144    | `git push --force-with-lease`                | Memaksa pengiriman perubahan ke remote, tetapi tetap aman jika tidak ada perubahan di remote. |
| 145    | `git worktree add /path/to/dir branch_name`  | Membuat worktree terpisah untuk bekerja di cabang lain.                                      |
| 146    | `git revert --no-commit commit_hash`         | Membalikkan commit tanpa membuat commit baru secara otomatis.                                |
| 147    | `git submodule deinit /path/to/submodule`    | Menghapus submodule dari proyek tanpa menghapus file dari disk.                              |
| 148    | `git stash list`                             | Menampilkan daftar perubahan yang disimpan di stash.                                         |
| 149    | `git stash drop`                             | Menghapus stash dari daftar.                                                                 |
| 150    | `git reset --hard origin/master`             | Mengembalikan cabang lokal ke keadaan yang sama dengan cabang `master` di remote.             |


##
## buatan sendiri

### bagus ini buat hapus semua zone identi fire
find -type f -name "*:Zone.Identifier" -delete


### buatliat ukuran file fokder kita
du -sh