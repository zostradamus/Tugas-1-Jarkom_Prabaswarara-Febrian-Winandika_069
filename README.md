# Tugas 1 Jarkom
| Nama | NRP |
|----------|----------|
| Prabaswara Febrian Winandika | 5027241069 |

Yayasan Pendidikan ARA akan membangun jaringan untuk beberapa unit kerja. Sebagian unit berada di kantor pusat, sedangkan Bidang Pengawas Sekolah berada di kantor cabang. IP yang bisa digunakan 

### Kantor Pusat

| **Ruang**                        | **Jumlah Host Aktif** |
| -------------------------------- | --------------------- |
| Bidang Guru & Tendik             | 95 host               |
| Bidang Kurikulum                 | 220 host              |
| Bidang Sarana Prasarana          | 45 host               |
| Bidang Pengawas Sekolah (Branch) | 18 host               |
| Server & Admin                   | 6 host                |
| Sekretariat                      | 380 host              |

### Kantor Cabang

| **Ruang**               | **Jumlah Host Aktif** |
| ----------------------- | --------------------- |
| Bidang Pengawas Sekolah | 18 host               |

1. Rancanglah topologinya menggunakan Cisco Packet Tracer.
2. Setiap mahasiswa memiliki base network unik, dengan aturan: 
`10.(NRP mod 256).0.0`
**NRP 5027241069 mod 256 = 109, maka base: 10.109.0.0.**
3. Lakukan perhitungan subnetting dengan VLSM & CIDR di Spreadsheet untuk seluruh jaringan LAN dan link antar-router.
4. Konfigurasikan alamat IP di setiap interface router dan host pada CPT sesuai tabel hasil subnetting di Spreadsheet.

## Topologi

