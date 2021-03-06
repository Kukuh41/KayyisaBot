# KayyisaBot

بِسْمِ اللهِ الرَّحْمٰنِ الرَّحِيْمِ

Tugas Akhir Pemrograman Python - Membuat Chatbot Telegram

Dibuat oleh : Nikmatun Aliyah Salsabila - 0102514014

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-generate-toc again -->
**Daftar isi**

- [Deskripsi](#deskripsi)
- [Cara Penggunaan Bot](#cara-penggunaan-bot)
- [Instalasi](#instalasi)

<!-- markdown-toc end -->

# Deskripsi

KayyisaBot merupakan chatbot telegram yang memiliki tiga fitur utama, yaitu 
jadwal shalat, Al-Qur'an, dan do'a sehari-hari. Dengan fitur jadwal shalat, 
bot akan menampilkan jadwal shalat sesuai wilayah yang dimasukkan oleh pengguna
pada hari ini. Pengguna dapat meminta bot untuk menampilkan ayat tertentu dengan
memanfaatkan fitur Al-QUr'an. Bukan hanya itu, pengguna pun dapat melihat catatan
depag mengenai terjemahan ayat dan mencari kata dalam Al-Qur'an, sehingga bot akan
menampilkan list surat dan ayatnya.

KayyisaBot dikembangkan dengan bahasa pemrograman python dan didukung API berikut:
- python-telegram-bot (http://python-telegram-bot.org)
- Prayer Times API (https://aladhan.com/prayer-times-api)
- API Fathimah (http://api.fathimah.ga)

KayyisaBot juga memanfaatkan data do'a sehari-hari di situs http://duaandazkar.com/chapter-4-daily-essential-duas/.

# Cara Penggunaan Bot
Cari KayyisaBot dengan mengetikkan @KayyisaBot pada kolom search. Kemudian start chat.
Terdapat beberapa perintah/commands pada KayyisaBot, yaitu:
- /start = menampilkan informasi mengenai KayyisaBot. Contoh : /start
- /shalat = menampilkan jadwal shalat hari ini sesuai masukan wilayah dari pengguna. Contoh : **/shalat Bekasi Utara**
- /quran = menampilkan ayat Al-Qur'an yang diinginkan pengguna. Contoh : **/quran 2:255-256**
- /cari = mencari kata tertentu dalam Al-Qur'an. Bot akan menampilkan list surat dan ayatnya. Contoh : **/cari puasa**
- /catatan = menampilkan catatan depag mengenai terjemahan ayat tertentu. Contoh : **/catatan 5**
- /doa = menampilkan do'a yang diinginkan pengguna sesuai daftar do'a yang ada. Contoh : **/doa 1**
- /setdaily = pengguna set perintah pada bot untuk mengirim ayat pilihan tiap hari. Contoh : **/setdaily**
- /help = bantuan. Contoh : **/help**

Berikut adalah contoh penggunaan KayyisaBot
![example]

[example]: http://imgur.com/6NLQwG2.png "Contoh percakapan"

# Instalasi
Untuk menjalankan program bot ini, pertama harus mendaftarkan bot kepada @BotFather dan mendapatkan token-nya.
Ubah token di bagian ini:
```python
updater = Updater('<your-token-here>')
```

Jika data belum tersedia, jalankan kode scraping.py untuk mendapatkan scraping.json dan file gambar.

Kemudian bisa menjalankan kode program bot dengan cara mengetikkan kode ini pada terminal (pastikan dahulu sudah berada pada direktori yang benar)
```python
python KayyisaBot.py
```

Apabila ada yang ingin memanfaatkan kode program KayyisaBot, silakan manfaatkan dengan baik, ya. Kalau untuk tugas kuliah, jangan dicopy paste semua! Buat belajar aja :)

Menemukan banyak kode yang kurang tepat atau sebagainya? Ayo kita sharing!
Kirim email aja ke nasalsabil23@gmail.com


Salam,

Empunya GitHub https://github.com/nasalsabila/KayyisaBot/ yang masih belajar mencintai coding
