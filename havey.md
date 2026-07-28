<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=240&section=header&text=HARVEY%20MOEID&fontSize=58&fontColor=F7B32B&fontAlignY=38&desc=POS%20%26%20Inventory%20Systems%20Architect%20for%20Indonesian%20UMKM&descAlignY=56&descSize=17&descColor=E8E8E8" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=F7B32B&center=true&vCenter=true&width=680&lines=Point+of+Sale+%26+Inventory+System+Developer;Empowering+UMKM+Through+Technology;Real-Time+Stock+%2B+Smart+Cashier+Systems;Building+Scalable+Solutions%2C+One+Store+at+a+Time" alt="Typing SVG" />

<br/>

<img src="https://img.shields.io/badge/DOMAIN-Point%20of%20Sale-0F2027?style=for-the-badge&labelColor=203A43" />
<img src="https://img.shields.io/badge/SPECIALTY-Inventory%20Systems-0F2027?style=for-the-badge&labelColor=203A43" />
<img src="https://img.shields.io/badge/MARKET-UMKM%20Indonesia-0F2027?style=for-the-badge&labelColor=203A43" />
<img src="https://img.shields.io/badge/STATUS-Open%20to%20Work-2ECC71?style=for-the-badge&labelColor=203A43" />

</div>

<br/>

## Profil

Saya adalah pengembang perangkat lunak yang berfokus pada perancangan dan pembangunan **sistem Point of Sale (POS) dan manajemen Inventory** untuk pelaku Usaha Mikro, Kecil, dan Menengah (UMKM) di Indonesia. Fokus saya adalah menghadirkan teknologi kelas enterprise dengan pengalaman pengguna yang sederhana dan biaya yang terjangkau.

| | |
|---|---|
| **Peran** | Full-Stack Developer — POS & Inventory Systems |
| **Fokus Industri** | Retail, F&B, UMKM Digitalization |
| **Lokasi** | Indonesia |
| **Misi** | Membantu UMKM naik kelas melalui sistem digital yang andal |
| **Sedang Didalami** | Cloud Architecture, Offline-First Sync, Payment Gateway |
| **Terbuka Untuk** | Kolaborasi proyek UMKM, Freelance, Full-time |

<br/>

## Dampak &amp; Pencapaian

<div align="center">

<img src="https://img.shields.io/badge/UMKM%20Terbantu-50%2B-F7B32B?style=for-the-badge&labelColor=0F2027" />
<img src="https://img.shields.io/badge/Transaksi%20Diproses-100K%2B-F7B32B?style=for-the-badge&labelColor=0F2027" />
<img src="https://img.shields.io/badge/Uptime%20Sistem-99.9%25-F7B32B?style=for-the-badge&labelColor=0F2027" />

</div>

<sub>Ganti angka di atas dengan metrik nyata dari proyekmu — data konkret jauh lebih meyakinkan bagi recruiter dan klien.</sub>

<br/>

## Proyek Unggulan

<table>
<tr>
<td width="50%" valign="top">

### POS System UMKM
Aplikasi kasir modern dengan transaksi real-time, dukungan multi-outlet, cetak struk otomatis, dan integrasi berbagai metode pembayaran.

`React` `Node.js` `PostgreSQL`

**Kemampuan Utama**
- Checkout dalam hitungan detik
- Sinkronisasi multi-cabang
- Laporan penjualan otomatis harian/bulanan
- Mode offline-first — transaksi tetap jalan tanpa internet

<img src="https://img.shields.io/badge/status-in%20production-2ECC71?style=flat-square" />
<a href="#"><img src="https://img.shields.io/badge/Live%20Demo-203A43?style=flat-square&logo=vercel&logoColor=white" /></a>

</td>
<td width="50%" valign="top">

### Inventory Management System
Sistem manajemen stok real-time dengan notifikasi otomatis, pelacakan barang masuk/keluar, dan integrasi langsung dengan sistem POS.

`TypeScript` `Express` `MySQL`

**Kemampuan Utama**
- Notifikasi stok menipis otomatis
- Audit trail pergerakan barang
- Terintegrasi penuh dengan modul POS
- Analitik produk terlaris dan slow-moving

<img src="https://img.shields.io/badge/status-in%20production-2ECC71?style=flat-square" />
<a href="#"><img src="https://img.shields.io/badge/Live%20Demo-203A43?style=flat-square&logo=vercel&logoColor=white" /></a>

</td>
</tr>
</table>

<br/>

## Arsitektur Sistem

```mermaid
flowchart LR
    A[Kasir / POS Frontend] -->|REST API| B(Backend Node.js)
    M[Mobile Dashboard] -->|REST API| B
    B --> C[(PostgreSQL)]
    B --> D[Inventory Service]
    D --> E[(MySQL)]
    B --> F[Payment Gateway]
    D -->|Real-time Sync| A
    B --> G[Report Engine]
    G --> H[PDF / Excel Export]
