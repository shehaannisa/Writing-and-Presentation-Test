### Sheha Luthfi Annisa | Back-End Development

## **Responsive Web Design**
#### • Responsive Web Design
<br> Memungkinkan website dapat diakses dimanapun (device apapun), tampilannya tetap bagus dan enak dilihat
#### • Tools untuk membuat website yang responsif
1. Menggunakan viewport
<br> Viewport : area website yang dapat diakses oleh user
- Setting viewport : Otomatis keluar saat menggunakan html dengan cara ketikan ! kemudian enter. Atau 
```javascript
<meta name="viewport">
```
2. Menggunakan Max-Width element
- misalnya menjadikan gambar lebih responsif
```javascript
<img scr=" " alt style="max-width:100%" />
```
3. Menggunakan CSS relative unit
-  relative length : em, rem, vw, vh, % (yg sering dipakai)
   - em : mengikuti ukuran huruf dari element dia berada. Nyari font size dengan parent element terdekat. Contoh : container dengan em nya
   - rem : mengikuti ukuran huruf dari root element (ukuran huruf html). Biasanya ukuran default html adalah 16px. Jadi 2rem = 2 x 16px = 32px
   - % : bergantung pada parent element 
   - Vw : relatife 1% dengan lebar viewport.. 50vw = 50% dari lebar viewport
   - Vh : relatife 1% dengan tinggi viewport. 50vh = 50% dari tinggi viewport
4. Menggunakan media query
<br> Membuat beberapa style bergantung pada jenis device
<br> Kata kunci : @media. Contoh :
```javascript
@media (max-width: 500px) {
}
```
<br> Keterangan : Jika ukuran layar dibawah 500px maka style settingan didalam @media yang berlaku

5. Menggunakan Flexbox dan Grid
- Flexbox
<br> Satu arah entah samping(kanan-kiri) atau atas bawah
- Grid
<br> Bisa kearah samping dan atas bawah

## **Bootstrap 5**
- Kapan menggunakan bootstrap?
<br> ketika kita ingin membuat website kita menjadi responsif dengan cara yang simple karena sudah ada templatenya dan tinggal dicopy paste untuk digunakan
- Layout pada bootstrap
1. Breakpoint : sebagai acuan untuk menyesuaikan tampilan dalam berbagai ukuran viewport. Beberapa breakpoint pada bootstrap 5 sm, md, lg, xl, xxl
2. Containers : layout basicnya bootstarp
   - Default Container
     <br> Class container memiliki sifat yang responsive dan fixed-width, yang berarti lebarnya akan berubah pada setiap breakpoint
     ```javascript
     <div class="container">
     <!-- Content here -->
     </div>
     ```
   - Fluid Container
     <br> Class container-fluid memiliki lebar yang sama dengan viewport
     ```javascript
     <div class="container-fluid">
     <!-- Content here -->
     </div>
     ``` 
   - Responsive Container
     ```
     <div class="container-sm">100% wide until small breakpoint</div>
     <div class="container-md">100% wide until medium breakpoint</div>
     <div class="container-lg">100% wide until large breakpoint</div>
     <div class="container-xl">100% wide until extra large breakpoint</div>
     <div class="container-xxl">100% wide until extra extra large breakpoint</div>
     ```
3. Grid : menyediakan 12 kolom system
<br> Grid system membagi lebar halaman menjadi 12 bagian. Sehingga apabila menggunakan class col-8, maka lebarnya akan menjadi 8/12 atau 2/3 dari lebar halaman.
5. Columns
<br> mengatur urutan posisi dan align
- Component pada bootstrap
<br> beberapa component pada bootstrap 5
   - Alerts
   - Breadcrumb
   - Buttons
   - Card
   - Modal
   - Navbar
   - Navs & tabs
   - Pagination
- Content pada bootstrap
   - Reboot
   - Typography
   - Images
   - Tables
   - Figures

##### Info : link bootstrap https://getbootstrap.com/
