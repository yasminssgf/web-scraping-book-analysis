# Web Scraping Book Analysis
## Deskripsi
Proyek ini bertujuan untuk mengotomatisasi pengambilan data katalog buku dari situs Books to Scrape untuk memantau tren harga dan ketersediaan stok.

## Fitur Utama
* **Otomasi:** Mengambil judul dan harga secara otomatis menggunakan BeautifulSoup.

* **Data Cleaning:** Membersihkan simbol mata uang dan mengonversi tipe data teks ke numerik.

* **Output:** Menyimpan data dalam format CSV yang siap dianalisis.
<pre>
[Sumber Data]       [Proyek Python]            [Output]
(Website) ------&gt; (Scraper &amp; Cleaning) ------&gt; (File CSV)
                      |
                      V
               [Library Used]
          (Requests, BeautifulSoup, Pandas)
</pre>

## Insight Singkat:

**Total buku yang berhasil diambil:** 20 data.

**Rata-rata harga buku:** £35.50.

**Standar deviasi harga:** £12.40 (menunjukkan variasi harga yang cukup lebar).
