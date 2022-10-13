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
```
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
1. / menggunakan CDN dibagian download, dicopy dan dipaste dibagian <head> /
2. Breakpoint :
3. Containers : layout basicnya bootstarp
4. Grid : menyediakan 12 kolom system
5. Columns : mengatur urutan posisi dan align
• Content pada bootstrap
• Component
1. 
• Website responsif menggunakan bootstrap
