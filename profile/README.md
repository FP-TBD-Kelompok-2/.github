## Executive Summary

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
# Navisatya Consign Store

Navisatya Consign Store merupakan platform e-commerce public yang bisa digunakan untuk jual beli barang. Sejauh ini, produk yang terdaftar hanya smartphone, namun tidak menutup kemungkinan akan ada jenis produk lainnya.
Di dalam Proyek ini, kami menggunakan 4 database:

- Graph Database (Neo4J)
 > Graph database digunakan untuk menampilkan rekomendasi produk berdasarkan ranking antutu score setiap produk. Fitur rekomendasi ini sementara hanya bekerja untuk categori produk *smartphone*.
 
- Document Database(mongoDB)
 > Document Database digunakan untuk halaman transaction dan *checkout*.
 
- Key-Value Database (redis)
 > Key Value Database digunakan untuk bagian keranjang atau *cart*. Key nya merupakan product ID dan valuenya berisi nama *product*, *stock*, *quantity*, dan harga.
 
- RDBMS (MySQL)
 > RDBMS digunakan untuk menyimpan semua data produk yang akan ditampilkan di katalog platform.

API dibangun menggunakan framework **Flask** dan framework yang digunakan untuk pembuatan website Navisatya Consign Store adalah **Laravel**.



## Member Kelompok 2 TBD A :
|No.|Nama|NRP|
|--|--------------------------|-----------------|
|1.| Isna Aulia Fadilla Norsi | 05211940000006
|2.| Muhammad Alif Amri Muzammil | 05211940000032
|3.| Indira Salsabila Ardan | 05211940000046
|4.| Ibadurrahman Ziaulhaq | 05211940000052
|5.| Kevianwillie Handoyo | 05211940000069
|6.| Arya Akbar Rivaldi | 05211940000074
|7.| Bayu Azra Yudhantorro | 05211940000076
|8.| Moch Farrel Arrizal Kusuma | 05211940000111
|9.| Evan Aldwin | 05211940000119
|10.| Evan Raditya | 05211940000139
|11.| Lidiya Yuniarti | 05211940007001
|12.| Alexander Nicolas Wonoadi | 05211942000008
