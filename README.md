# dokumentasi belajar teknologi frontend

1. [css flexbox](#css-flexbox)

# css flexbox

property yang bisa di gunakan oleh parent elemen:

- **display:flex**, supaya element parent nya menjadi flexbox
- **flex-direction**, mengatur arah dan urutan itemnya
- **flex-wrap**, memaksa item untuk pindah baris jika parent elemennya sudah tidak muat
- **justify-content**, mengatur jarak antar item (secara horizontal)
- **align-items**, mengatur jarak antar item (secara vertikal)
- **align-content**, perilakunya sama seperti align-items, tetapi hanya berfungsi ketika itemnya lebih dari satu baris

property yang bisa digunakan oleh child elemen:

- **order**, untuk mengatur urutan itemnya
- **flex-grow / flex**, untuk mengatur ukuran itemnya
- **align-self**, untuk mengatur penjajaran hanya pada satu item saja

# css grid

terminology di css grid:

- **grid container**, elemen pembungkus grid
- **grid items**, elemen yang berada langsung di dalam **grid container** (child element)
- **grid line**, garis horizontal atau vertikal yang memisahkan grid menjadi beberapa bagian
- **grid cell**, perpotongan antara baris dan kolom di dalam grid
- **grid area**, kumpulan lebih dari satu grid cell yang membentuk sebuah kotak
- **grid track**, ukuran/jarak antara 2 grid cell, bisa horizontal atau vertikal
- **grid gap**, jarak antar grid track / cell

property yang bisa di gunakan oleh parent elemen:

property untuk mengatur baris dan kolo:

- **grid-template-columns**
- **grid-template-rows**
- **grid-auto-columns**
- **grid-auto-rows**
- **grid-auto-flow**

- **grid-template-areas**
- **grid-template**
- **grid-column-gap**
- **grid-row-gap**
- **grid-gap**
- **grid**
- **justify-items**
- **align-items**
- **place-items**
- **justify-content**
- **align-content**
- **place-content**

property yang bisa di gunakan oleh child elemen:

- **grid-column-start**
- **grid-column-end**
- **grid-row-start**
- **grid-row-end**
- **grid-column**
- **grid-row**
- **grid-area**
- **justify-self**
- **align-self**
- **place-self**
