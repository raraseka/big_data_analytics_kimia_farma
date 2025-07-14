# Big Data Analytics Kimia Farma 
## Project Based Internship Kimia Farma x Rakamin Academy
Project ini merupakan tugas akhir dari magang virtual yang diselenggarakan oleh Rakamin Academy
### Tools:
- BigQuery
- Looker
------
Pada proyek ini, anda juga diminta untuk membuat tabel analisa
berdasarkan hasil aggregasi dari ke-empat tabel yang sudah
diimport sebelumnya. Berikut ini adalah kolom-kolom yang
mandatory pada tabel tersebut:
- transaction_id : kode id transaksi,d
- date : tanggal transaksi dilakukan,
- branch_id : kode id cabang Kimia Farma,
- branch_name : nama cabang Kimia Farma,
- kota : kota cabang Kimia Farma,
- provinsi : provinsi cabang Kimia Farma,
- rating_cabang : penilaian konsumen terhadap cabang Kimia Farma
- customer_name : Nama customer yang melakukan transaksi,
- product_id : kode product obat,
- product_name : nama obat,
- actual_price : harga obat,
- discount_percentage : Persentase diskon yang diberikan pada obat,
- persentase_gross_laba : Persentase laba yang seharusnya
  diterima dari obat dengan ketentuan berikut:
  Harga <= Rp 50.000 -> laba 10%
  Harga > Rp 50.000 - 100.000 -> laba 15%
  Harga > Rp 100.000 - 300.000 -> laba 20%
  Harga > Rp 300.000 - 500.000 -> laba 25%
  Harga > Rp 500.000 -> laba 30%,
- nett_sales : harga setelah diskon,
- nett_profit : keuntungan yang diperoleh Kimia Farma,
- rating_transaksi : penilaian konsumen terhadap transaksi yang dilakukan.
