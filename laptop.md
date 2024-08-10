## cara agar kita dapt mengetahui apa saja kesalahan yang terjadi pada laptop selama laptop kita pertama kali kita beli dan nyalakan yaitu menggunakan __Even Viewer__ 

Berikut adalah langkah-langkah untuk memeriksa Event Viewer di Windows:

1. *Buka *Event Viewer:
   - Klik tombol Start di Windows.
   - Ketik “Event Viewer” di kotak pencarian, lalu tekan Enter.

2. *Navigasi ke Log Sistem*:
   - Di jendela Event Viewer, Anda akan melihat panel navigasi di sebelah kiri. Klik pada “Windows Logs” untuk memperluasnya.
   - Di bawah “Windows Logs”, klik “System”. Ini akan menampilkan daftar peristiwa (event) yang terjadi di sistem Anda.

3. *Filter Event*:
   - Di panel kanan, Anda bisa menggunakan opsi “Filter Current Log” untuk menyaring log berdasarkan tingkat keparahan seperti Error, Warning, atau Critical.
   - Centang kotak di sebelah “Critical” dan “Error” untuk melihat peristiwa penting yang mungkin menunjukkan penyebab laptop mati tiba-tiba.

4. *Cari Peristiwa yang Relevan*:
   - Perhatikan waktu terjadinya peristiwa di log. Cari event yang terjadi tepat sebelum laptop mati. Peristiwa ini mungkin memberikan petunjuk tentang apa yang menyebabkan laptop mati mendadak.
   - Klik dua kali pada event yang ingin Anda lihat detailnya. Akan muncul jendela baru yang menjelaskan lebih lanjut tentang event tersebut.

5. *Catat dan Teliti Kode Kesalahan*:
   - Jika Anda menemukan event yang tampaknya terkait dengan masalah, catat kode kesalahan atau pesan yang ditampilkan. Anda bisa mencari kode tersebut di internet untuk informasi lebih lanjut atau mencari solusi yang sesuai.



## Sfc /Scannow fitur System File Checker (SFC) untuk memeriksa dan memperbaiki file sistem yang rusak. 

``` Caranya, buka Command Prompt sebagai administrator, lalu ketik sfc /scannow dan tekan Enter. Tunggu hingga proses selesai dan lihat apakah ada file yang diperbaiki. ```