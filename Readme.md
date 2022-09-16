## REACT CONTEXT
### Apa itu React Context
- React Context adalah library external JavaScript yang dapat digunakan pada React.js. selain itu React Context termasuk state management pada React.js
- Pada versi ke 16 React React Context dapat digunakan.
### Code Mengatur Level Suatu Heading pada React Context:
```
import { createContext } from 'react';
export const LevelHeadingContext = createContext;
```

- useContext dan Context.Consumer memiliki fungsi yang sama.
### Mengapa menggunakan React Context ?
1. Theming : menerapkan tema ke suluruh aplikasi dengan mendukung tema khusus, kertas mengekspor komponen penyedia.
2. Check current Account : memeriksa akun 
3. Data dibutuhkan untuk banyak component

### Didalam React Context terdapat Prop Drilling
- Yang dimaksud dengan Prop adalah Proses mengirimkan data melalui props yang dibutuhkan oleh component lain namun harus melalui beberapa component di bawahnya terlebih dahulu.

# Testing
## Step Sebuah Testing terdapat 3:
1. Assert / Hasl yg diharapkan: Langkah-langkah tindakan harus menimbulkan semacam tanggapan. Langkah-langkah tegas memverifikasi kebaikan atau keburukan respons itu. Terkadang, pernyataan sesederhana memeriksa nilai numerik atau string. Di lain waktu, mereka mungkin memerlukan pemeriksaan beberapa aspek sistem. Pernyataan pada akhirnya akan menentukan apakah tes lulus atau gagal.
2. Arrange/ Input dan Target : Mengatur langkah-langkah harus mengatur kasus uji. Apakah tes memerlukan objek atau pengaturan khusus? Apakah perlu menyiapkan database? Apakah perlu masuk ke aplikasi web? 
3. Act / Berdasarkan Perilaku Target: Langkah-langkah tindakan harus mencakup hal utama yang akan diuji. Ini bisa berupa memanggil fungsi atau metode, memanggil REST API, atau berinteraksi dengan halaman web. Jaga agar tindakan tetap fokus pada perilaku target.

### Testing dibagi menjadi 2:
1. Manual Testing
2. Automated Testing

### Alasan mengapa Menggunakan Testing:
- Aplikasi bebas dari error dan bug
- Aplikasi berjalan sesuai dengan ekspektasi
- Meningkatkan kualitas dari sebuah software dan kepuasan pengguna

### Alasan menggunakan Automated Testing
- Lebih reliable karena Manual Testing tetap berpotensi adanya kesalahan dan kekeliruan
- Lebih cepat dan efisien
- Mudah untuk dimaintain (Review, Edit, dan Add Collection of Tests)

### Yang termasuk dalam bagian Automated Testing
1. Unit Test
2. End to End Test
3. Integration Test

### Regression merupakan?
- Tipe testing yang dilakukan untuk mengecek apakah suatu fitur baru yang ditambahkan ke dalam aplikasi akan membuat error atau bug pada fitur sebelumnya.

### Code step Arrange dalam menyusun sebuah test.

``` 
cons num1 = 10;
cons num2 = 10;

const expectadSum = 20;
```
### Code step Act dalam menyusun sebuah test.

```
const actualSum = sum(num1, num2)
```

### Code step Assert dalam menyusun sebuah test.
```
expect(actualSum).toBe(expectedSum)
```

### Install React Testing Library
- npm install --save-dev @testing-library/react

### Apa itu React Testing Library (RTL)?

- Pustaka Pengujian React adalah pustaka yang memungkinkan seseorang untuk menguji komponen Bereaksi dengan meniru bagaimana pengguna sebenarnya akan berinteraksi dengan komponen tertentu. Itu tidak menyangkut dirinya dengan rincian implementasi komponen.
