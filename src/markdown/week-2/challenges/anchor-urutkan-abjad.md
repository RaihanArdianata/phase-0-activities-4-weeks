---
path: '/week-2/challenges/anchor-urutkan-abjad'
title: 'Urutkan Abjad'
---

# Logic Challenge - Urutkan Abjad

## Objectives
- Mampu memecahkan sebuah masalah yang diberikan
- Mampu mengurutkan sebuah karakter lain selain karakter bertipe number

**RESTRICTION**
Hanya boleh menggunakan built-in function .push()

## Directions

Diberikan sebuah function urutkanAbjad yang menerima satu parameter berupa string.

Function tersebut akan mengembalikan string baru yang telah diubah urutan abjadnya dari a hingga z. Contohnya, halo akan menjadi ahlo. Kamu tidak perlu memikirkan apabila ada simbol ataupun angka didalam string tersebut.


```JavaScript
function urutkanAbjad(str) {
  // you can only write your code here!
}

// TEST CASES
console.log(urutkanAbjad('hello')); // 'ehllo'
console.log(urutkanAbjad('truncate')); // 'acenrttu'
console.log(urutkanAbjad('developer')); // 'deeeloprv'
console.log(urutkanAbjad('software')); // 'aeforstw'
console.log(urutkanAbjad('aegis')); // 'aegis'
```