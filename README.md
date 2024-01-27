jawaban uas 

1. {
  "universitas": "Djuanda",
  "prodi": "Ilmu Komputer",
  "iat": 1674270000
}



2. 
<table border="1">
  <tr>
    <th>Aspek</th>
    <th>Arsitektur Monolitik</th>
    <th>Arsitektur Mikroservis</th>
  </tr>
  <tr>
    <td>Struktur Aplikasi</td>
    <td>Terdiri dari satu kesatuan besar (monolit)</td>
    <td>Terdiri dari beberapa layanan independen (mikroservis) </td>
  </tr>
  <tr>
    <td>Skalanilitas</td>
    <td> Keseluruhan aplikasi harus ditingkatkan bersama-sama</td>
    <td>Setiap layanan dapat ditingkatkan secara independen</td>
  </tr>
  <tr>
    <td>Pengembangan dan pemeliharaan</td>
    <td>Lebih mudah dalam pengembangan awal dan pemeliharaan, karena semuanya berada dalam satu kode basis</td>
    <td>Memerlukan manajemen kode yang lebih kompleks dan tim yang terdiri dari spesialis berbeda untuk setiap layanan </td>
  </tr>
  <tr>
 <td>Ketergantungan Antar Komponen </td>
    <td> Komponen-komponen saling terkait dan berbagi kode basis, sehingga perubahan di satu area dapat memengaruhi seluruh aplikasi</td>
    <td> Setiap layanan memiliki lingkup yang lebih terisolasi, sehingga perubahan pada satu layanan tidak harus memengaruhi lainnya</td>
  </tr>
  <tr>
    <td>Teknologi dan Bahasa Pemrograman </td>
    <td>Biasanya menggunakan satu teknologi dan bahasa pemrograman untuk keseluruhan aplikasi </td>
    <td> Dapat menggunakan teknologi dan bahasa pemrograman yang berbeda untuk setiap layanan sesuai dengan kebutuhan</td>
  </tr>
  <tr>
    <td>Pengelolaan Data</td>
    <td> Biasanya menggunakan satu basis data untuk seluruh aplikasi</td>
    <td> Setiap layanan dapat memiliki basis data sendiri, memungkinkan lebih besar dalam hal pemisahan data dan skema</td>
  </tr>
</table>

3.Middleware adalah perangkat lunak yang bertindak sebagai jembatan antara aplikasi atau komponen perangkat lunak yang berbeda. Ini menyediakan layanan tambahan di 
 atas sistem operasi yang mendasarinya, seperti manajemen sumber daya dan komunikasi antara aplikasi.
-Keuntungan dari penerapan middleware
 Interoperabilitas: Memungkinkan integrasi mudah antara sistem dan aplikasi yang berbeda.
 Abstraksi Kompleksitas: Mengelola kompleksitas infrastruktur dan memungkinkan fokus pada logika bisnis.
 Skalabilitas: Mendukung penskalaan aplikasi dengan efisien.
 Keamanan: Menyediakan lapisan tambahan keamanan untuk melindungi aplikasi dari ancaman.
 Pengembangan Cepat: Mempercepat pengembangan aplikasi dengan memanfaatkan fungsionalitas yang sudah ada.
 Manajemen Layanan: Membantu dalam pemantauan kinerja, penanganan kesalahan, dan manajemen layanan secara keseluruhan.

4. Unit Testing adalah praktik pengujian perangkat lunak di mana setiap komponen atau unit program diuji secara terpisah untuk memastikan fungsinya dengan benar.
	 ini dilakukan dengan menulis kode pengujian kecil yang menguji fitur atau metode tertentu.
-Beberapa metode yang umum digunakan dalam unit testing meliputi
 Test Case: Kode untuk menguji satu fitur atau perilaku aplikasi.
 Assertion: Memeriksa apakah hasil pengujian sesuai dengan yang diharapkan.
 Test Fixture: Kondisi awal atau lingkungan yang dipersiapkan sebelum menjalankan test case.
 Test Suite: Kumpulan test case yang berhubungan dan dijalankan bersama-sama.
 Test Driven Development (TDD): Menulis test case sebelum kode program yang sebenarnya.
 Mocking: Menggantikan objek riil dengan objek palsu yang mensimulasikan perilaku.

5. -Kontainerisasi adalah Pendekatan untuk mengemas dan menjalankan aplikasi secara terisolasi dalam lingkungan yang seragam disebut kontainer, memungkinkan
   	portabilitas dan efisiensi.
	 -Docker adalah Platform kontainerisasi populer yang menyediakan alat untuk membuat, mengemas, dan menjalankan aplikasi dalam kontainer, memastikan konsistensi
   	dan portabilitas di berbagai lingkungan.
	 -Kubernetes adalah Sistem orkestrasi kontainer yang otomatisasi penjadwalan, manajemen, dan skalabilitas aplikasi dalam kontainer, memungkinkan pengelolaan
   	efisien di lingkungan yang kompleks dan terdistribusi.

6. CI/CD adalah praktik otomatisasi pengujian dan pengiriman kode.
	 Continuous Integration (CI) fokus pada penggabungan dan pengujian kode secara teratur,
   Continuous Delivery (CD) dan Continuous Deployment (CD) fokus pada pengiriman kode ke lingkungan pengujian atau produksi secara otomatis

7. https://epullss.github.io/
