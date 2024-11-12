# Analisis Penggunaan dan Efisiensi TransJakarta

Tujuan dari analisis ini adalah memberikan wawasan mengenai pola penggunaan penumpang Transjakarta, jam sibuk, rute populer, dan metrik utama lainnya yang dapat mendukung pengambilan keputusan dalam optimasi rute dan alokasi sumber daya.
---

## Deskripsi Proyek

TransJakarta adalah sistem bus rapid transit (BRT) populer di Jakarta, Indonesia. Proyek ini bertujuan untuk menganalisis data penumpang TransJakarta guna mengidentifikasi tren dan pola yang dapat membantu meningkatkan efisiensi layanan, mengoptimalkan rute, dan meningkatkan pengalaman penumpang secara keseluruhan. Analisis utama meliputi identifikasi jam sibuk, rute paling banyak digunakan, dan demografi penumpang.

Dataset mencakup informasi mengenai perjalanan penumpang, seperti:
- `tapInHour` dan `tapOutHour`: Jam naik dan turun
- `tapInStopsName` dan `tapOutStopsName`: Nama halte tempat penumpang naik dan turun
- `payCardID`: ID unik penumpang
- `tapInStops` dan `tapOutStops`: ID halte
- `corridorName`: Nama koridor atau rute

## Langkah-Langkah Analisis

Analisis dilakukan melalui langkah-langkah utama berikut:
1. **Data Cleaning**: Memeriksa dan menangani missing value.
2. **Analisis Jam Sibuk**: Mengidentifikasi jam penggunaan tertinggi berdasarkan jumlah tap-in dan tap-out untuk menentukan jam sibuk.
3. **Identifikasi Rute Populer**: Menganalisis rute paling populer dan paling sepi.
4. **Demografi Penumpang**: Mengamati distribusi usia penumpang untuk memahami kelompok usia yang paling sering menggunakan TransJakarta.
5. **Analisis Performa Rute**: Mengelompokkan data berdasarkan koridor untuk mengetahui rute yang paling ramai dan paling sepi.
   
## Temuan Utama

1. **Jam Sibuk**: Data menunjukkan penggunaan puncak pada jam-jam berangkat dan pulang kerja, yang mengindikasikan tingginya jumlah penumpang selama jam sibuk.
2. **Rute Populer**: Beberapa rute memiliki jumlah penumpang yang jauh lebih tinggi, terutama rute yang menghubungkan area perkantoran dan area perumahan utama.
3. **Kelompok Usia Penumpang**: Sebagian besar penumpang berada dalam rentang usia 20-40 tahun, menunjukkan basis pengguna yang didominasi oleh kalangan muda.
4. **Performa Koridor**: Beberapa koridor memiliki lalu lintas yang lebih tinggi daripada yang lain, yang dapat menunjukkan kebutuhan akan penyesuaian rute atau alokasi sumber daya di area dengan lalu lintas tinggi.

## Rekomendasi

Berdasarkan temuan-temuan tersebut, berikut adalah rekomendasi untuk stakeholders:
- **Optimalkan Sumber Daya Selama Jam Sibuk**: Tingkatkan frekuensi atau kapasitas bus selama jam sibuk untuk mengakomodasi permintaan yang tinggi.
- **Penyesuaian Rute**: Tinjau ulang rute dengan permintaan rendah untuk optimalisasi atau alokasikan sumber daya ke rute yang lebih populer.
- **Layanan yang Berfokus pada Kalangan Muda**: Mengingat tingginya penggunaan oleh penumpang muda, pertimbangkan layanan atau fasilitas khusus yang ditargetkan untuk demografi ini.
