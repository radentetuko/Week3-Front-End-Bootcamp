# Rangukam WEEK 3 - Front-end Bootcamp

## **React Context**

- ### **Apa itu React Context?**

  Context itu seperti variable global yang bisa kita akses dimana saja tanpa kita harus memparsing props ke setiap komponen.

- ### **Kapan bisa menggunakan React Context**

  ketika kita menggunakan React, kita harus menggunakan context ini segera. Tapi, kita harus menganalisis aplikasimu terlebih dahulu. Aplikasimu bakal besar atau tidak? Jika tidak, maka saya merekomendasikan untun menggunakan context ini.

  Jadi, kita di rekomendasikan menggunakan context ini jika kita mempunyai aplikasi dengan skala kecil ke menengah untuk membuat aplikasimu mudah di kembangkan dan mudah di mengerti oleh orang-orang.

- ### **Cara Import React Context**

  Cara importnya cukup mudah sekali, cukup tulis codingnya seperti ini :

  ```javascript
  import { createContext } from "react";

  export default createContext();
  ```

## **React Testing**

- ### **Apa itu React Testing?**

  seperangkat helpers yang memungkinkan Anda mengetes komponen pada React tanpa bergantung pada detail implementasinya.

- ### **Jenis - jenis Testing**

  - **Unit Testing** : unit testing memastikan component yang dibuat memenuhi output sesuai ekspektasi jika diberi input
  - **Integration Testing** : unit test yang individu digabung dan di test sebagai grup pada saat suatu waktu.

- ### **Manfaat Testing**

  Manfaat membuat test adalah:

  - Ketika aplikasi kita mempunyai coverage yang baik (mayoritas codebase tercover oleh test), Kita akan merasa percaya diri jika harus mengubah suatu bagian pada aplikasi kita. Saat kita mengubah bagian tersebut, dan ada bagian yang lain menjadi broken kita akan segera mengetahuinya.
  - Mengurangi bug pada aplikasi. Walaupun testing tidak menjamin aplikasi kita bebas bug, tetapi kita bisa mencegah beberapa hal yang berpotensi menjadi bug.
  - Kita menjadi terbiasa mendesain sebelum mengerjakan. Beberapa studi telah dilakukan dan hasilnya TDD sangat efektif meningkatkan produktifitas, karena ada objektif yang harus kita capai, yaitu menjadikan semua test case passed.

- ### **Apa itu TDD?**

  TDD adalah sebuah proses dalam pembuatan perangkat lunak yang dalam pelaksanaanya membuat test terlebih dahulu lalu kemudian membuat implementasinya.

- ### **Implementasi TDD**

  Ada sebuah strategy dalam membuat suatu test.

  - Buat test yang gagal (RED). Hal ini juga menghindari test yang lulus padahal seharusnya tidak
  - Buat kode yang minimum untuk memastikan test yang baru buat lolos (GREEN)
  - Refactor kode yang baru dibuat (REFACTOR).

Agar bisa menerapkan TDD, tentunya kita harus tahu terlebih dahulu tentang Jest dan Enzyme.

- ### **Apa itu Jest?**

  Jest adalah testing framework dengan jargon “Painless Javascript Testing”. testing framework besutan Facebook ini mempunyai kelebihan tersendiri pada running test suits-nya yang cepat.

  Jest digunakan untuk menjalankan test suits, serta untuk membuat assertion.

- ### **Apa itu Enzyme?**

  Enzyme adalah testing utility untuk React. Penggunaan Enzyme bisa dibilang mudah, sebab api-nya mirip dengan jQuery. Dengan utility ini kita bisa memanipulasi komponen, traversing komponen-komponen react, simulasi event dan lainnya.
