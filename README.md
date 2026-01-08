# Big_Data_Final_Project
Maleakhi Nymmo Augustus - 1103220006
M Alwa Fahrizki - 1103220082

Implementasi Pipeline Big Data ETL dan ELT pada Studi Kasus Pengaruh Cuaca Terhadap Jasa Taksi di New York

Proyek ini bertujuan untuk menganalisis pengaruh kondisi cuaca (curah hujan, suhu) terhadap pola operasional dan pendapatan jasa taksi di New York City. Menggunakan data NYC Taxi Trip Records dan data cuaca historis dari Open-Meteo API (Periode Januari 2025), proyek ini mengimplementasikan dan membandingkan dua pendekatan pipeline data: ETL (Extract, Transform, Load) dan ELT (Extract, Load, Transform) untuk menghasilkan insight bisnis yang berharga.

perbedaan pendekatan ETL dan ELT
Lokasi Transformasi
Pipeline ETL: Di Aplikasi (Python/Pandas)
Pipeline ELT: Di Database (SQLite/SQL)

Waktu Load
Pipeline ETL: Lebih lambat (Cleaning dulu baru Load)
Pipeline ELT: Sangat Cepat (Load Raw Data langsung)

Fleksibilitas
Pipeline ETL: Tidak Fleksibel (Schema-on-Write)
Pipeline ELT: Fleksibel (Schema-on-Read)

Kompleksitas
Pipeline ETL: Code-Heavy (Script Python Panjang)
Pipeline ELT: Query-Heavy (Syntax SQL Kompleks)

