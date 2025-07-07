# qa-database-json-api
Penjelasan konsep Database, SQL, JSON, dan API untuk QA Engineer


#  Pemahaman Dasar QA Engineer: Database, SQL, JSON & API

Halo! Saya **Azizah**, seorang QA Engineer yang memiliki ketertarikan mendalam terhadap fondasi teknis yang menjadi tulang punggung aplikasi. Dalam repositori ini, saya ingin berbagi pemahaman mengenai bagaimana **Database**, **SQL**, **JSON**, dan **API** saling terhubung dan berperan penting dalam proses pengujian aplikasi.

---

##  Database

Database adalah tempat penyimpanan data yang digunakan oleh aplikasi. Semua informasi penting seperti data pengguna, produk, transaksi, hingga log aktivitas disimpan secara terstruktur dalam sistem database.

Sebagai QA, memahami bagaimana data disimpan dan digunakan memungkinkan saya untuk:
- Memverifikasi bahwa data ditampilkan dengan benar di UI
- Melakukan validasi terhadap hasil API
- Melakukan query untuk setup atau cleanup data saat testing

---

##  SQL (Structured Query Language)

SQL adalah bahasa yang digunakan untuk berinteraksi dengan database. QA dapat menggunakan SQL untuk:

-  Mengambil data dari database (`SELECT`)
-  Menambahkan data baru (`INSERT`)
-  Memperbarui data (`UPDATE`)
-  Menghapus data (`DELETE`)

Contoh query:
```sql
-- Mengambil semua produk dalam kategori 'elektronik'
SELECT* FROM produk WHERE kategori = 'elektronik';


JSON (JavaScript Object Notation)
JSON adalah format yang digunakan untuk mentransfer data, terutama dalam komunikasi antara client dan server.

Contoh struktur JSON:

```
{
  "id": 101,
  "nama": "Laptop Lenovo",
  "kategori": "elektronik",
  "harga": 7500000
}
```

Sebagai QA, saya menggunakan JSON untuk:

Memahami struktur respons API

Melakukan validasi nilai pada key tertentu

Membuat payload saat melakukan request API otomatis

API (Application Programming Interface)
API adalah jembatan komunikasi antara dua sistem atau layanan. Dalam konteks testing:

 QA menggunakan API untuk memastikan bahwa backend berfungsi sesuai ekspektasi.

 Diuji menggunakan tools seperti Postman, Rest Assured, atau cURL.

 Digunakan untuk validasi data, response code, dan integritas sistem.

Contoh request:

```
GET /api/produk/101
```
```
{
  "id": 101,
  "nama": "Laptop Lenovo",
  "kategori": "elektronik"
}
```




