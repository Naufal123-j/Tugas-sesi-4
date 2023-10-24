# Tugas-sesi-4
Untuk keperluan tugas sesi 4 pemrograman berbasis platform 
// Mendefinisikan pendapatan yang diperoleh hari itu
const pendapatan = 600000; // Ganti angka ini sesuai dengan pendapatan yang diperoleh

// Mendefinisikan variabel uang jasa awal
let uangJasa = 0;

// Menggunakan if else untuk menentukan uang jasa berdasarkan pendapatan
if (pendapatan <= 200000) {
  uangJasa = 10000;
} else if (pendapatan <= 500000) {
  uangJasa = 20000;
} else {
  uangJasa = 30000;
}

// Menghitung komisi berdasarkan persentase
const komisi = pendapatan * (uangJasa === 10000 ? 0.1 : uangJasa === 20000 ? 0.15 : 0.2);

// Menampilkan hasil
console.log(`Pendapatan: Rp. ${pendapatan}`);
console.log(`Uang Jasa: Rp. ${uangJasa}`);
console.log(`Komisi: Rp. ${komisi}`);
