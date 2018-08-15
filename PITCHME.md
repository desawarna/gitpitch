# Pengenalan Dasar MongoDB untuk Pemula

seperti saya

---

### SQL ( Structure Query Language)

- SQL adalah (Structured Query Language) adalah sebuah bahasa yang digunakan untuk mengakses data dalam basis data relasional. Saling terhubung

---

### Masalah

- _Ada beberapa kekurangan dalam database SQL yang pernah saya temukan, seperti skema database yang kaku (fixed), susah membuat query untuk tabel dengan relasi yang kompleks, susah diperbesar sekalanya, dsb._

---

### Solusi NoSQL

- _Database NoSQL_ (Not Only SQL) bukan database yang terstruktur hadir untuk menutupi kekurangan-kekurangan tersebut. Selain itu, NoSQL sudah menjadi tuntutan teknologi yang harus dipelajari dalam pengembangan software modern masa kini.

---

### Apa itu MongoDB?

_MongoDB_ adalah salah satu jenis database NoSQL yang berbasis dokumen dengan fomat _JSON_.

Pada database SQL, data disimpan dalam bentuk tabel. Sedangkan pada MongoDB data disimpan dalam bentuk dokumen dengan format JSON.

---

@title[Contoh Skrip Mongo DB]

<p><span class="slide-title">JavaScript Block</span></p>

```javascript
{
   "_id" : ObjectId("54c955492b7c8eb21818bd09"),
   "alamat" : {
      "street" : "2 Avenue",
      "zipcode" : "10075",
      "building" : "1480",
      "coord" : [ -73.9557413, 40.7720266 ]
   },
   "borough" : "Manhattan",
   "cuisine" : "Italian",
   "grades" : [
      {
         "date" : ISODate("2014-10-01T00:00:00Z"),
         "grade" : "A",
         "score" : 11
      },
      {
         "date" : ISODate("2014-01-16T00:00:00Z"),
         "grade" : "B",
         "score" : 17
      }
   ],
   "name" : "Vella",
   "restaurant_id" : "41704620"
}
```

---

### Instalasi MongoDB di Linux

Jika kita ingin menggunakan MongoDB versi terbaru, maka kita harus men-download versi terakhir di website reseminya di [mongodb.com](https://www.mongodb.com/download-center).
