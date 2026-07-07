# notes.md

Format wajib per entry — jangan menyimpang dari 4 field ini:

### N-{nomor} | {judul singkat}
Evidence: {EVID-id atau "-" kalau tidak ada}
Type: fact | inference | assumption
Isi: {satu-dua kalimat, faktual untuk fact, jelas ditandai kalau dugaan}

Aturan:
- fact = langsung teramati dari evidence, tidak ada interpretasi
- inference = kesimpulan Anda dari satu/lebih fact
- assumption = dugaan tanpa bukti langsung, harus diverifikasi sebelum dipakai
- Jangan pernah menulis assumption sebagai fact walau "kelihatannya jelas"

---

<!-- Mulai isi di bawah baris ini -->
### N-001 | untuk penilaian soal UTBK di penilaiannya pake IRT
Evidence: EVID-001 - method penilaian
Type: assumption
Isi: refreensi nya ada dari platform gradient, zenius, dll katanya pake method IRT tapi irt nya belum jelas pake IRT L1/L2/L3 tapi asumsi nya pake IRT untuk cara kerja IRT itu harus ada kolom difficulty di soal nya dengan rentang value -2 s/d 2 (sangat mudah - sangat sulit) kalo pake method l2,l3 itu harus pake kolom lain seperti discrimination (untuk) referensi kredibel nya banyak contoh nya : https://www.ruangguru.com/blog/sistem-penilaian-irt-di-utbk-sbmptn-dan-strategi-mengerjakannya

### N-002 - penilaian IRT
Evidence: 
Type: assumption
Isi: saya waktu saya lihat di gradient mencoba try out saya mendaptkan skor 650 nah saya bingung skor 650 itu perhitungan nya gimana dari 130 soal dan beberapa subtest yang ada ternyata katanya pake method IRT nah dari referensi jenis itu method irt itu punya nilai maksimal 1000 dan belum pernah ada yang mecahin rekor ini perlu di verifikasi https://www.zenius.net/blog/try-out-utbk-cara-dapatkan-nilai-maksimal-utbk/

### N-003
Evidence: 
Type: assumption
Isi: karena untuk tryout utbk format penialian ya pake IRT dan bisa jadi di ujian lain format penilaian nya beda penting untuk mempelajari bagaimaa cara kerja penilaian IRT dan mengimplementasikan nya secara agloritma

### N-004 - cara menghitung nilai UTB sebagai referensi algoritma IRT secara manual
Evidence: 
Type: assumption
Isi: https://www.zenius.net/blog/cara-mengecek-nilai-utbk/, https://aimasukptn.com/blog/cara-kerja-irt-utbk-2026-penjelasan-lengkap

### N-004 - cara menghitung nilai UTB sebagai referensi algoritma IRT secara manual
Evidence: 
Type: assumption
Isi : cara menghitung skor method konvensional dan IRT itu beda kalo konvensioal (skor = jumlah jawaban benar x bobot soal (jika ada)) https://aimasukptn.com/blog/irt-utbk-2026-panduan-lengkap-pemula

### N-005 - berikut adalah temuan saya dari aplikasi gradient
Evidence: [Lihat gambar](evidence/evi-006-test-dibagi-3-utbk-ujian-mandiri-tka.jpeg)
Type: fact
Isi : ok jadi secara tipe test di bagi 3 utbk (tryout),ujian mandiri(untuk masuk ptn), tka, next harus di coba masing-masing


### N-006 - berikut adalah temuan saya dari aplikasi gradient : https://gradient.academy/
Evidence: [kalkulator](evidence/evi-007-kalkulator-tryout-simulasi-untuk-uji-apakah-masuk-ptn.jpeg) [hasil kalkulator](evidence/evi-007a.jpeg)
Type: fact
Isi : ini menarik perlu dibedah bagiamana cara kerja kalukator karena berhubugan dengan cara penilaian skor tryout yang saya coba jika masukan semua skor 1000 maka presentase jadi 100% asumsi saya ini berhubungan dengan sistem penilaian IRT

### N-006 - berikut adalah temuan saya dari aplikasi gradient
Evidence: [kalkulator](evidence/evi-007-kalkulator-tryout-simulasi-untuk-uji-apakah-masuk-ptn.jpeg) [hasil kalkulator](evidence/evi-007a.jpeg)
Type: fact
Isi : 

### N-007 - pembagian menu soal
Evidence: [preview](evidence/evi-001-materi-pelalajaran-dibagi-ke-beberapa-subtest-uniknya-soal-utbk-juga-dikelompokan-subtest.jpeg)  [preview](evidence/evi-002-soal-try-out-dikelompokan-jadi-subtest.jpeg)
Type: fact
Isi : di gradient  materi dan soal utbk tidak deklompokan ke dalam mata pelajaran atau level kesulitan tapi lebih ke subtest seperti penalaiaran umum dan matematika dll, saya lihat di zenius juga, jadi bisa jadi secara sistem nasional pengelompokan soal tryout utbk mungkin seperti ini jadi perlu dipertimbangkan adanya meta soal untuk subtest

### N-008 - pilih ptn sebelum try out
Evidence: [preview](evidence/evi-003-sebelum-mulai-pilih-tryout-pilih-dulu-ptn-dan-jurusan.jpeg)
Type: fact
Isi : unikya sebelum memilih paket soal tryout dia harus pilih dulu ptn dan jurusan nya katanya ini untuk menentukan tingkat kesulitan soal yang akan di tryoutkan, tapi untuk setup ptn ini sifat nya global sekali

### N-009 - pembagian paket soal
Evidence: [preview](evidence/evi-004-soal-dibagi-jadi-beberapa-paket.jpeg)
Type: fact 
isi kalo di gradient soal itu di bagi ke beberapa paket atribut paket (jumlah soal, waktu, progress, dan tipe) kalo tipe default nya semua utbk tapi kayanya ada tipe lain seperti TKA,SIMAK UI (untuk ujian UI) untuk progress kanya diamil dari last session, nah yang unik adalah sistem soal di pecah jadi paket 1 paket 130 soal, sedangkan di sistem yang akan kita buat soal nya akan diambil random 130 soal dari 1000 bank soal

### N-009 - isi satu sessi
Evidence: [preview](evidence/evi-005-disini-diperlihatkan-progress-tapi-tidak-multi-session.jpeg)
Type: fact 
isi : satu paket soal dibagi ke beberapa subset uniknya masing-masing subset ada durasi pengerjaan nya jadi durasi pengerjakan tidak di terapkan di level soal atau level tryout dan ketika sudah mengerjakan satu subset bisa mengerjakan ulang, tapi kalo pilih next subset tidak bisa balik lagi

### N-010 - tryout ujian mandiri
Evidence: [preview](evidence/evi-009-ujian-mandiri.png) [preview](evidence/evi-009a.png) [preview](evidence/evi-009b.png) [pembagian subtest beda dengan utbk](evidence/evi-009b.png)
Type: fact 
isi : ini adalah isi dari menu tryout ujian mandiri yang berbeda dari utbk yang unik disini soal ujian dikelompokan jadi berbgai Kampus, bisa jadi untuk setiap kampus dia punya atribut dan cara penilaian sendiri, yang unik dari ujian ini adalah ada leaderboard nya dan soal pembagian subtest nya beda seperti utbk (penalaran umum, matematika dst) jadi ada kemungkinan butuh data master subtest sebagai parent soal

### N-011 - hasil report tryout simak UI/asumsi yang utbk juga sama
Evidence: [preview](evidence/evi-010.png) 
type: fact
isi : ok untuk menu dibagi 3 : nilai, pembahasan, leaderboard, utnuk pembaghasan yang ditampilkan ada opsi yang dijawab, opsi benar yang seharusnya dijawab, dan rekomendasi materi (asumsi bisa jadi ada linking ke module materi nantinya, makanya bisa jadi penting dalam input soal ditentukan mapel dan submapel nya)

### N-011 - wahh ternyata soal bisa puny option multiple
Evidence: [preview](evidence/evi-011.png) 
type: fact
isi : dari sini saya berasumsi kita harus melihat simulasi rill dari platform utbk yang digunakan pemerintah wkwkwk


### N-012 - report tryout utbk sedikit beda degan report tka mandiri UI
Evidence: [preview](evidence/evi-12.png) 
type: fact
isi : jadi hasil report analisa soal nya dibagi ke per subset tidak 1 tryout kalo mode pembahasan nya sih sama