# Operator-tidak-identik

- pengertian <br>
Operator tidak identik adalah Membandingkan nilai DAN tipe data.  
Kalau nilai atau tipe datanya beda maka hasilnya `true` 

adapun perbedaannya antara operator tidak identik dengan operator tidak sama ialah kalau yang tidak sama, itu dia hanya membandingkan nilainya saja, tipe data nya diabaikan

- contoh kode <br>
Sama persis logikanya <br>
let a = 5;       // number <br>
let b = "5";     // string  <br>

console.log(a != b);  // false -> karena nilainya sama<br>

console.log(a !== b); // true  -> karena tipenya beda: number vs string <br>


let c = 0; <br>

let d = false;<br>


console.log(c != d);  // false -> 0 dianggap sama dengan false<br>

console.log(c !== d); // true  -> number tidak identik dengan boolean<br>

#btw saya kerja dihp, jdi saya kerja seperti ini 🙏

