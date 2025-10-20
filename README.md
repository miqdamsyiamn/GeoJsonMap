# 🗺️ Peta Digital Jalan Kecamatan Katapang

Repositori ini berisi data geospasial (peta) dari beberapa ruas jalan penting di wilayah **Kecamatan Katapang, Kabupaten Bandung**. Seluruh data disajikan dalam format **GeoJSON** yang modern dan mudah diintegrasikan dengan berbagai platform.

---

## 📍 Data Jalan yang Tersedia

Berikut adalah daftar 8 ruas jalan yang datanya tersedia dalam repositori ini:

1.  `Jl. Katapang Andir`
2.  `Jl. Cikambuy Girang`
3.  `Jl. Babakan`
4.  `Perumahan Junti Asri`
5.  `Jl. Pangauban`
6.  `Jl. Cikambuy Hilir`
7.  `Jl. SukaSari`
8.  `Jl. Bojong Tanjung`

---

## 🏗️ Struktur Data

Setiap file GeoJSON memiliki struktur yang konsisten dan mudah dipahami, terdiri dari `properties` (informasi) dan `geometry` (bentuk dan lokasi).

```json
{
  "type": "Feature",
  "properties": {
    "name": "Nama Jalan"
  },
  "geometry": {
    "type": "LineString",
    "coordinates": [
      [107.5538, -6.9989],
      [107.5545, -6.9991],
      // ...daftar koordinat lainnya
    ]
  }
}