# Praktikum 2: CSS Dasar

1. Buatlah **repository** baru dengan nama **Lab2Web.**

2. Kerjakan semua latihan yang diberikan sesuai urutannya.

3. Screenshot setiap perubahannya.

4. Buatlah file **README.md** dan tuliskan penjelasan dari setiap langkah praktikum beserta
screenshotnya.

5. **Commit** hasilnya pada **repository** masing-masing.

6. Kirim **URL repository** pada **e-learning** ecampus

## Instruksi Praktikum

1. Persiapkan text editor misalnya **VSCode.**

2. Buat file baru dengan nama **lab2_css_dasar.html**

3. Buat struktur dasar dari dokumen HTML.

4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

  a. **Membuat dokumen HTML**

  <img width="692" height="949" alt="image" src="https://github.com/user-attachments/assets/afc9af07-f3e2-4dfa-9021-9554bf0e5326" />

  <img width="957" height="948" alt="image" src="https://github.com/user-attachments/assets/1b2833e9-85cc-43c3-8b43-ae1836015104" />


  b. **Mendeklarasikan CSS Internal**

  <img width="580" height="663" alt="image" src="https://github.com/user-attachments/assets/6a6798dd-06e9-4526-b4cf-633c3ce6b3f3" />

  <img width="960" height="946" alt="image" src="https://github.com/user-attachments/assets/8cb7f05c-00d7-4648-938a-ef0014bc6f68" />

  c. **Menambahkan Inline CSS**

  <img width="635" height="116" alt="image" src="https://github.com/user-attachments/assets/bdc645f1-68fa-4239-aa50-b7d892b8dd26" />

  <img width="956" height="948" alt="image" src="https://github.com/user-attachments/assets/44493152-fff7-432a-92a6-da190641b9f7" />

  d. **Membuat CSS Eksternal**

  <img width="341" height="506" alt="image" src="https://github.com/user-attachments/assets/b95135d1-2c06-41fc-891a-0703198f8e62" />

  <img width="759" height="83" alt="image" src="https://github.com/user-attachments/assets/11419957-5424-4128-bc2b-a09f806b7bf9" />

  <img width="958" height="947" alt="image" src="https://github.com/user-attachments/assets/6c83f5f3-e8ba-4e6b-ab1f-cefcd85d8d19" />

  e. **Menambahkan CSS Selector**

  <img width="434" height="801" alt="image" src="https://github.com/user-attachments/assets/f968ccc5-812e-4957-a439-d299253d8b5e" />

  <img width="958" height="947" alt="image" src="https://github.com/user-attachments/assets/2c808e9d-f0e8-4b4b-92b8-c5dea9f2f07d" />

6. Lakukan validasi dokumen css dengan mengakses https://jigsaw.w3.org/css-validator/

  <img width="915" height="592" alt="image" src="https://github.com/user-attachments/assets/adf786f0-ebac-470f-9a08-9e8512e6563d" />

## Menjawab Pertanyaan

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

<img width="956" height="950" alt="image" src="https://github.com/user-attachments/assets/70bf9a52-0eb6-4b6a-89b7-001c5066fc05" />


2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!

Bayangin kamu punya banyak kucing. h1 itu kayak kamu manggil semua kucing di komplek: “Kucing! Sini!” Semua kucing datang, bahkan yang bukan punya kamu.

Nah, intro h1 itu kayak kamu manggil kucing yang tinggal di rumah kamu, di kamar tamu, dan namanya “Intro.” Jadi cuma kucing di ruangan itu yang datang. Artinya:

- h1 = Semua elemen h1 di halaman kena styling.

- intro h1 = Hanya h1 yang ada di dalam elemen dengan ID intro yang kena styling.

Jadi, yang satu general, yang satu spesifik. Kayak bedanya ngajak makan semua temen vs ngajak makan mantan yang masih kamu stalk.

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!

Ini kayak kamu punya tiga orang nyuruh kamu pakai baju:

- Eksternal CSS = Nyokap bilang, “Pakai baju batik.”

- Internal CSS = Kakak bilang, “Pakai hoodie.”

- Inline CSS = Pacar bilang, “Pakai jas biar ganteng.”

Dan karena kamu takut kehilangan pacar, kamu nurut sama dia. Jadi yang ditampilkan adalah inline CSS, karena dia paling kuat. Urutannya gini: Inline > Internal > Eksternal

5. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! (id="paragraf-1" class="text-paragraf")

Ini kayak kamu punya dua panggilan: nama panggilan (class) dan nama asli (ID). Kalau ada yang manggil dua-duanya, kamu lebih cepat respon ke nama asli, karena itu lebih personal. Jadi:

- ID lebih kuat daripada Class.

- Kalau ada konflik styling, yang dari ID akan ditampilkan.
