# Zona TM3 & Kab/Kota Indonesia

Repository ini berisi data referensi **Zona TM3 (Transverse Mercator 3°)** yang dihubungkan dengan **titik kabupaten/kota di Indonesia** untuk memudahkan pencarian dan pengecekan zona koordinat.

Tujuan utama repository ini adalah menyediakan cara yang lebih praktis untuk mengetahui **zona TM3 yang digunakan oleh suatu kabupaten/kota**, tanpa perlu melakukan analisis spasial secara manual.

---

## Tujuan

Menentukan **zona TM3 suatu kabupaten/kota** dengan cara:

1. Menggunakan **grid zona TM3** sebagai referensi wilayah zona.
2. Menggunakan **titik lokasi kabupaten/kota**.
3. Menggabungkan keduanya sehingga setiap titik kab/kota memiliki **atribut zona TM3**.

Dengan cara ini, pengguna dapat dengan mudah:

- Mengetahui zona TM3 suatu kabupaten/kota
- Melakukan pengecekan cepat terhadap sistem koordinat
- Menggunakan data tersebut untuk kebutuhan pemetaan atau konversi koordinat

---

## Isi Repository

Repository ini berisi beberapa file utama:

### 1. `grid_zona_tm3.geojson`

Grid zona TM3 dalam format **GeoJSON**.
Digunakan sebagai referensi batas setiap zona TM3 di Indonesia.

### 2. `kab_kota_pt_zona_tm3.xlsx`

Data tabel yang berisi:

- Nama kabupaten/kota
- Titik lokasi kabupaten/kota
- Zona TM3 hasil penggabungan

Format ini memudahkan penggunaan di **Excel atau aplikasi non-GIS**.

### 3. `kab_kota_pt_zona_tm3.geojson`

Versi **GeoJSON** dari data titik kabupaten/kota yang sudah memiliki atribut zona TM3.

Dapat digunakan langsung di berbagai software GIS seperti:

- QGIS
- ArcGIS
- MapLibre / Leaflet
- aplikasi web GIS lainnya

### 4. `kab_kota_pt_zona_tm3.kml`

Versi **KML** untuk digunakan di:

- Google Earth
- aplikasi peta berbasis KML lainnya.

---

## Visualisasi Peta

Untuk mempermudah pengecekan, data ini juga tersedia dalam bentuk **Google My Maps**:

**Zona TM3 & Kab/Kota**
https://goo.gl/maps/NsCDJ7BtyJaAChtH7?g_st=ac

Melalui peta ini pengguna dapat:

- Melihat distribusi zona TM3
- Mencari kabupaten/kota tertentu
- Mengecek zona TM3 secara visual

---

## Cara Menggunakan

### Untuk pengguna GIS

1. Buka `grid_zona_tm3.geojson`
2. Buka `kab_kota_pt_zona_tm3.geojson`
3. Gunakan sebagai referensi zona TM3 untuk analisis koordinat.

### Untuk pengguna non-GIS

Gunakan file:

```
kab_kota_pt_zona_tm3.xlsx
```

Cari nama kabupaten/kota untuk mengetahui zona TM3 yang digunakan.

---

## Catatan

Data ini dibuat untuk memudahkan proses **identifikasi zona TM3 kabupaten/kota di Indonesia**.
Pengguna tetap disarankan melakukan verifikasi tambahan jika digunakan untuk analisis spasial yang membutuhkan presisi tinggi.

---

## Kontribusi

Jika terdapat:

- kesalahan zona
- koreksi titik kabupaten/kota
- tambahan data

silakan membuat **Issue atau Pull Request** di repository ini.
