# Operator-tidak-identik

- pengertian <br>
Operator tidak identik adalah Membandingkan nilai DAN tipe data.  
Kalau nilai atau tipe datanya beda maka hasilnya `true` 

adapun perbedaannya antara operator tidak identik dengan operator tidak sama ialah kalau yang tidak sama, itu dia hanya membandingkan nilainya saja, tipe data nya diabaikan

- contoh kode -
Sama persis logikanya
let a = 5;       // number
let b = "5";     // string

console.log(a != b);  // false -> karena nilainya sama
console.log(a !== b); // true  -> karena tipenya beda: number vs string

let c = 0;
let d = false;

console.log(c != d);  // false -> 0 dianggap sama dengan false
console.log(c !== d); // true  -> number tidak identik dengan boolean
