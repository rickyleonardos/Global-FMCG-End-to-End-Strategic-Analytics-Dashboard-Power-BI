# Global FMCG End-to-End Strategic Analytics Dashboard | Power BI

## Project Overview

Proyek ini berawal dari tantangan nyata di industri FMCG multinasional, di mana data operasional sering kali terisolasi di masing-masing departemen (Data Silo). Tim penjualan, pemasaran, keuangan, dan logistik bekerja dengan sistem pelaporan terpisah, sehingga manajemen tingkat tinggi (C-Level) kesulitan mendapatkan visibilitas bisnis secara holistik.

Untuk mengatasi masalah tersebut, proyek end-to-end business intelligence ini dibangun dari tahap awal:

* Ekstraksi & Transformasi Data (ETL): Mengambil data mentah transaksi lintas negara, membersihkan anomali, dan menyelaraskan format penanggalan serta mata uang menggunakan Power Query.
* Pemodelan Data (Data Modeling): Merancang arsitektur database berbasis Star Schema, menghubungkan tabel fakta transaksi secara presisi dengan tabel dimensi produk, wilayah, kalender, dan saluran distribusi.
* Analisis Lanjutan (DAX): Merakit kalkulasi bisnis kustom (Time Intelligence, Conditional Filtering, dan Dynamic Contributions).
* Desain UI/UX Eksekutif: Menyusun tata letak dashboard 4 halaman yang bersih, menggunakan skema warna korporat yang diredam (muted corporate palette), dan fokus pada kemudahan pembacaan metrik (readability framework).

## Business Objective

* Menghancurkan Silo Data: Mengintegrasikan metrik performa Sales, Marketing, Portfolio Produk, dan Supply Chain ke dalam satu Single Source of Truth.
* Mitigasi Kebocoran Pendapatan: Mengidentifikasi produk atau wilayah yang mengalami erosi margin keuntungan (margin erosion).
* Optimasi Operasional: Menyelaraskan strategi promosi dengan kapasitas rantai pasok guna meminimalkan hilangnya potensi penjualan akibat kekosongan stok (stock-out).

## Key Findings

* Page 1: Executive Sales & Profitability Overview
  
1. Performa Keuangan Makro: Perusahaan mencetak Total Net Sales sebesar 458.89M dengan profitabilitas yang sangat sehat, mencatat Gross Profit senilai 454.05M dan rata-rata profit margin stabil di angka 39%.  
2. Peta Kekuatan Regional: Italia (137.19M) dan Spanyol (105.17M) keluar sebagai pangsa pasar terbesar yang menggerakkan mayoritas pendapatan global.  
3. Analisis Multi-Channel: Melalui visualisasi small multiples, performa penjualan kategori produk berhasil dipetakan secara komparatif di tiga jalur distribusi utama (E-commerce, Hypermarket, dan Supermarket).
  
* Page 2: Marketing Effectiveness & Weather-Driven Demand Analytics
  
1. Efisiensi Promosi: Kampanye pemasaran terbukti efektif di mana Promo Sales Contribution menyumbang 10.43% dari total volume penjualan dengan pemberian rata-rata diskon yang sangat terkontrol di angka 1.49%.
2. Analisis Perilaku Konsumen: Melalui Weather Sensitivity Analysis dan matriks pola belanja, terdeteksi adanya fluktuasi permintaan yang sensitif terhadap perubahan suhu serta lonjakan masif pada Holiday & Weekend Shopping Patterns.
  
* Page 3: Product Portfolio & Financial Profitability Analytics
  
1. Roda Penggerak Profit: Kategori Snacks menjadi kontributor laba tertinggi (Top Category by Profit) dengan menghasilkan keuntungan bersih 47.61M dari total nilai penjualan 125.26M (Margin Kontribusi: 38.01%).
2. Penyebaran Laba Kota: Berdasarkan analisis tren bulanan, margin profitabilitas perusahaan terkendali ketat di angka 38.53% secara akumulatif lintas kota-kota besar seperti Berlin, Rome, dan Barcelona.  

* Page 4: Supply Chain Operations & Inventory Health Diagnostics
  
1. Efisiensi Logistik: Risiko kehilangan momentum penjualan akibat kekosongan stok berhasil ditekan rendah dengan Stock-out Rate hanya sebesar 3.01%.
2. Kinerja Vendor: Kelancaran operasional ini didukung oleh performa pengiriman pemasok yang responsif dengan Average Lead Time sepanjang 6.50 hari.
3. Keseimbangan Inventori: Grafik Monthly Inventory Balance menunjukkan keselarasan yang presisi antara tingkat ketersediaan stok fisik gudang (Stock on Hand) dengan kecepatan produk keluar (Units Sold).  4. Strategic Recommendations

## Strategic Recommendations

* Skalabilitas Pasar Regional: Mereplikasi strategi penetapan harga dan model distribusi dari pasar sukses (Italia dan Spanyol) ke wilayah dengan penetrasi lebih rendah seperti Austria dan Perancis.  
* Prediktif Promosi Berbasis Musiman: Memanfaatkan data tren cuaca dan lonjakan Holiday Patterns untuk menjadwalkan promosi secara dinamis, alih-alih memberikan diskon rata sepanjang tahun.  
* Sinkronisasi Supply-Demand: Menggunakan visualisasi Monthly Inventory Balance untuk meningkatkan batas aman persediaan (safety stock) pada kategori dengan frekuensi stock-out tinggi menjelang bulan-bulan puncak penjualan historis.  

## Skills Demonstrated

* Advanced Data Modeling: Implementasi arsitektur tabel fakta (Fact Table) dan tabel dimensi (Dimension Tables) menggunakan skema bintang (Star Schema).
* Advanced DAX Formulas: Penguasaan fungsi Time Intelligence, Calculated Measures, X-Functions, serta Conditional Logical Filtering.
* Executive UI/UX Reporting Design: Menerapkan kerangka kerja berorientasi eksekutif (Fixed Grid Layout, penataan hierarki visual judul, KPI Cards Framework, dan optimalisasi visualisasi grafik batang komparatif).
* Business Acumen & Domain Knowledge: Memahami metrik operasional FMCG riil seperti pelacakan margin keuangan, kontribusi promosi, frekuensi stock-out, dan tata kelola lead time logistik.

## Tools Used

* Power BI Desktop: Digunakan sebagai mesin utama untuk pemodelan data, penulisan formula DAX, dan pembuatan visualisasi interaktif laporan.  
* Power Query: Digunakan untuk melakukan proses ETL (Extract, Transform, Load) data transaksi mentah.
* Microsoft Excel / CSV: Bertindak sebagai Data Source Layer tempat penyimpanan basis data transaksi awal.


