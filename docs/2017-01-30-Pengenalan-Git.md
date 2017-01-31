# Pengenalan Mengenai Git

## Apakah Git? 

Jika kita tahu mengenai asal usul Git, maka kita akan lebih memahami kenapa Git ini amat penting untuk digunakan semasa membangunkan aturcara kod.

Secara umumnya, Git membantu merekod kod-kod aturcara kita dan menyenangkan kita untuk mengurus versi applikasi kita.

Tidak kira samada kita menulis kod kita bersendirian atau secara berkumpulan. Untuk pembinaan kod secara berkumpulan, Git amat-amat 
diperlukan untuk merekod perubahan secara selamat.

Di dalam tulisan ini saya akan berkongsi pernggunaan git secara khusus untuk digunakan didalam komputer Mac

## Bagaimana nak mula menggunakan Git?

Sewaktu kita membina aplikasi kita, kita akan meletakkan kod sumber kita didalam Directory yang khusus. Untuk tujuan pembelajaran ini
saya menggunakan direktori belajar-kod.

Mula-mula sekali, masuk ke dalam direktori belajar-kod.

''' shell
$ cd belajar-kod
'''

Kemudian kita mulakan (initialise) Git kita di direktori tersebut

''' shell
$ git init
'''

Arahan init bermakna initialise. Arahan ini menyediakan segala alatan (tools) yang Git perlukan untuk mula merekod perubahan
yang berlaku di dalam projek kita.

Kalau anda lihat di dalam direktori tersebut (utk kes saya ialah direktori belajar-kod). Anda akan dapati ada direktori tersembunyi 
(hidden) bernama .git

''' shell
$ ls -a

.		.DS_Store	README.md	docs
..		.git		_config.yml

'''


