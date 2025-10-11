Buku Panduan menjaga diri didalam "dark forest"<br>
*Pelajari dan kuasai, jadilah pakar untuk keamanan pribadi (aset) kriptomu.<br>*

:fire:Situs web: https://darkhandbook.io/<br>
:cn:中文版：[《区块链黑暗森林自救手册》](README_CN.md)<br>
:us:English: [Blockchain dark forest selfguard handbook](README.md)<br>
:jp:日本語版：[ブロックチェーンのダークフォレストにおける自己防衛のためのハンドブック](README_JP.md)<br>
:kr:한국어 버전: [블록체인 다크 포레스트 셀프가드 핸드북](README_KR.md)<br>
:saudi_arabia:اللغة العربية: [دليل النجاة في الغابة المظلمة للبلوكتشين](README_AR.md)<br>

Pengarang buku: Cos@SlowMist Team<br>
Kontak (pengarang buku): Twitter ([@evilcos](https://twitter.com/evilcos)), Jike App (@余弦.jpg)

Penterjemah: 
>[Finball](https://x.com/GreyMatatabi)

![alt this](res/this.png)

:anchor:**Daftar Isi**
- [Prolog](#prolog)
- [Diagram](#diagram)
  - [Membuat Dompet](#membuat-dompet)
    - [Unduh](#unduh)
    - [Frasa Mnemonik](#frasa-mnemonik)
    - [Tanpa Kunci (keyless)](#tanpa-Kunci-keyless)
  - [Cadangkan Dompet Anda](#cadangkan-dompet-anda)
    - [Frasa Mnemonik / Kunci Pribadi](#frasa-mnemonik--kunci-pribadi)
    - [Enkripsi](#enkripsi)
  - [Cara Menggunakan Dompet Anda](#cara-menggunakan-dompet-anda)
    - [AML (anti pencucian uang)](#aml-anti-pencucian-uang)
    - [Dompet Dingin (cold wallet)](#dompet-dingin-cold-wallet)
    - [Dompet Panas (hot wallet)](#dompet-panas-hot-wallet)
    - [Apa Itu Keamanan DeFi?](#apa-itu-keamanan-defi)
    - [Keamanan NFT](#keamanan-nft)
    - [HATI-HATI Saat Penandatanganan (signing)!](#hati-hati-saat-penandatanganan-signing)
    - [HATI-HATI Dengan Permintaan Tanda Tangan karena "ini tampak biasa saja atau normal"!](#hati-hati-dengan-permintaan-tanda-tangan-karena-ini-tampak-biasa-saja-atau-normal)
    - [Beberapa Metodologi Penyerangan Tingkat Lanjut](#beberapa-metodologi-penyerangan-tingkat-lanjut)
  - [Perlindungan Privasi Tradisional](#perlindungan-privasi-tradisional)
    - [Sistem Operasi](#sistem-operasi)
    - [Telepon Seluler (mobile phone)](#telepon-seluler-mobile-phone)
    - [Jaringan](#jaringan)
    - [Perambah](#perambah)
    - [Pengelola Kata Sandi (password manager)](#pengelola-kata-sandi-password-manager)
    - [Otentikasi Dua Faktor (2FA)](#otentikasi-dua-faktor-2fa)
    - [HATI-HATI Berinternet (selalu jaga keamananmu)](#hati-hati-berinternet-selalu-jaga-keamananmu)
    - [Email](#email)
    - [Kartu SIM](#kartu-sim)
    - [GPG](#gpg)
    - [Pemisahan (segregation)](#pemisahan-segregation)
  - [Keamanan Sifat Manusia](#keamanan-sifat-manusia)
    - [Telegram](#telegram)
    - [Discord](#discord)
    - [Phishing "Resmi"](#phishing-resmi)
    - [Masalah Privasi Web3](#masalah-privasi-web3)
- [Kejahatan Blockchain](#kejahatan-blockchain)
- [Apa yang Harus Dilakukan Jika Komputer Anda "terkompromi"](#apa-yang-harus-dilakukan-jika-komputer-anda-terkompromi)
- [Apa Yang Harus Dilakukan Ketika Anda Diretas](#apa-yang-harus-dilakukan-ketika-anda-diretas)
  - [Hentikan Kerugian Terlebih Dahulu](#hentikan-kerugian-terlebih-dahulu)
  - [Karantina Tempat Kejadian](#karantina-tempat-kejadian)
  - [Analisis Akar Masalah](#analisis-akar-masalah)
  - [Penelusuran Sumber (source tracing)](#penelusuran-sumber-source-tracing)
  - [Kesimpulan Kasus](#kesimpulan-kasus)
- [Kesalahpahaman (misconception)](#kesalahpahaman-misconception)
  - [Kode Adalah Hukum (code is law)](#kode-adalah-hukum-code-is-law)
  - [Bukan Kunci Anda, Bukan Koin Anda](#bukan-kunci-anda-bukan-koin-anda)
  - [Di Blockchain Kami Percaya (seluruhnya)](#di-blockchain-kami-percaya-seluruhnya)
  - [Keamanan Kriptografis Adalah Keamanan (pada umumnya)](#keamanan-kriptografis-adalah-keamanan-pada-umumnya)
  - [Apakah Memalukan Saat (kau menyadari menjadi korban) Diretas?](#apakah-memalukan-saat-kau-menyadari-menjadi-korban-diretas)
  - [Segera Perbarui (immediately update)](#segera-perbarui-immediately-update)
- [Kesimpulan](#kesimpulan)
- [Lampiran](#lampiran)
  - [Aturan Dan Prinsip Keamanan](#aturan-dan-prinsip-keamanan)
  - [Kontributor](#kontributor)
  - [Alat2nya (tools)](#alat2nya-tools)
  - [Situs Resmi](#situs-resmi)

# Prolog

Pertama-tama, selamat karena telah menemukan buku pegangan ini! Siapa pun Anda — jika Anda adalah Holder mata uang kripto atau ingin terjun ke dunia kripto di masa mendatang, buku pegangan ini akan sangat membantu Anda. Anda harus membaca buku pegangan ini dengan saksama dan menerapkan ajarannya dalam kehidupan nyata.

Selain itu, untuk memahami buku pegangan ini secara menyeluruh diperlukan beberapa pengetahuan dasar. Namun, jangan khawatir. Bagi pemula, jangan takut dengan kendala pengetahuan yang dapat diatasi. Jika Anda menemukan sesuatu yang tidak Anda pahami, dan perlu mencari tahu lebih lanjut, Google sangat direkomendasikan. Selain itu, penting untuk mengingat satu aturan keamanan: Bersikaplah skeptis! Apa pun informasi yang Anda lihat di web, Anda harus selalu mencari setidaknya dua sumber untuk dikroscek atau referensi silang.

Sekali lagi, selalu bersikap skeptis :) termasuk pengetahuan yang disebutkan dalam buku pegangan ini.

Blockchain adalah penemuan hebat yang membawa perubahan dalam hubungan produksi dan memecahkan masalah kepercayaan sampai taraf tertentu. Secara khusus, blockchain menciptakan banyak skenario "kepercayaan" tanpa perlu sentralisasi dan pihak ketiga, seperti kekekalan (immutable), pelaksanaan sesuai kesepakatan, dan pencegahan tas penolakan. Namun, kenyataan itu kejam. Ada banyak miskonsepsi tentang blockchain, dan orang jahat akan menggunakan miskonsepsi ini untuk mengeksploitasi celah dan mencuri uang dari orang-orang, yang menyebabkan banyak kerugian finansial. Saat ini, dunia kripto telah menjadi seperti hutan gelap.

Harap diingat dua aturan keamanan berikut untuk bertahan hidup di hutan gelap blockchain.

1. **(Mulailah dengan) Kepercayaan Nol**: Untuk membuatnya sederhana, tetaplah skeptis, dan selalu bersikap demikian.
2. **Validasi Keamanan Berkelanjutan**: Untuk mempercayai sesuatu, Anda harus memvalidasi apa yang Anda ragukan, dan menjadikan validasi sebagai kebiasaan.

*Catatan: Dua aturan keamanan di atas adalah prinsip inti dari buku pegangan ini, dan semua prinsip keamanan lainnya yang disebutkan dalam buku pegangan ini berasal darinya.*

Baiklah, itu saja untuk pengantar kita. Mari kita mulai dengan diagram dan jelajahi hutan gelap bersama kami dan melihat risiko apa yang akan kita hadapi dan bagaimana kita harus mengatasinya.

# Diagram

![](res/web3_hacking_map.jpg)

Anda dapat membaca sekilas diagram ini sebelum membaca lebih lanjut bagian lainnya dari buku pegangan ini. Buku ini membahas semua aktivitas utama di dunia ini (apa pun sebutannya: blockchain, mata uang kripto, atau Web3), yang terdiri dari tiga proses utama: membuat dompet, mencadangkan dompet, dan menggunakan dompet.

Mari kita ikuti ketiga proses ini dan menganalisis masing-masingnya.

## Membuat Dompet

Ini adalah Inti dari dompet yaitu kunci privat (frasa awal/seed phrase).

Seperti inilah tampilan kunci privat:

>0xa164d4767469de4faf09793ceea07d5a2f5d3cef7f6a9658916c581829ff5584

Selain itu, seperti inilah tampilan frasa awal:

>cruel weekend spike point innocent dizzy alien use evoke shed adjust wrong

*Catatan: Kami menggunakan Ethereum sebagai contoh di sini. Silakan periksa sendiri detail lebih lanjut tentang kunci privat/frasa awal.*

Kunci privat adalah ID Anda. Jika kunci privat hilang/dicuri, maka Anda kehilangan ID Anda. Ada banyak aplikasi dompet yang terkenal, dan buku pegangan ini tidak akan membahas semuanya.

Namun, saya akan menyebutkan beberapa dompet tertentu. Harap dicatat, dompet yang disebutkan di sini dapat dipercaya sampai tingkat tertentu. Namun, saya tidak dapat menjamin bahwa dompet tersebut tidak akan memiliki masalah keamanan atau risiko, yang diharapkan atau tidak diharapkan, selama penggunaan (saya tidak akan mengulanginya lagi. Harap selalu ingat dua aturan keamanan utama yang disebutkan dalam prolog)

Diklasifikasikan berdasarkan aplikasi, ada dompet Desktop, dompet ekstensi browser, dompet seluler, dompet HW (perangkat keras), dan dompet web. Dalam hal koneksi internet, dompet tersebut dapat dibagi menjadi Cold Wallet (dompet dingin) dan Hot Wallet (dompet panas). Sebelum kita terjun ke dunia kripto, pertama-tama kita harus memikirkan tujuan dompet tersebut. Tujuan tidak hanya menentukan dompet mana yang harus kita gunakan, tetapi juga bagaimana kita menggunakan dompet tersebut.

Apa pun jenis dompet yang Anda pilih, satu hal yang pasti: setelah Anda memiliki cukup pengalaman di dunia (blockchain) ini, satu dompet saja tidak cukup.

Di sini kita harus mengingat prinsip keamanan lainnya: isolasi, yaitu, jangan menaruh semua telur Anda dalam satu keranjang. Semakin sering dompet digunakan, semakin berisiko dompet tersebut. Selalu ingat: saat mencoba sesuatu yang baru, pertama-tama siapkan dompet terpisah dan cobalah sebentar dengan mengisi sedikit uang. Bahkan bagi seorang veteran kripto seperti saya, jika sedang ingin "bermain api, Anda akan lebih mudah terbakar".

### Unduh

Kedengarannya sederhana, tetapi sebenarnya tidak mudah. Alasannya adalah sebagai berikut:

1. Banyak orang tidak dapat menemukan situs web resmi yang asli, atau pasar aplikasi yang tepat, dan akhirnya memasang dompet palsu.
2. Banyak orang tidak tahu cara mengidentifikasi apakah aplikasi yang diunduh telah dirusak (disusupi malware) atau tidak.

Jadi, bagi banyak orang, sebelum mereka memasuki dunia blockchain, dompet mereka sudah kosong dan terkuras.

Untuk mengatasi masalah pertama di atas, ada beberapa teknik untuk menemukan situs web resmi yang benar, seperti

* menggunakan Google (Berhati-hatilah dengan entri yang diiklankan dalam hasil pencarian, karena sering kali tidak dapat diandalkan.)
* menggunakan situs web resmi yang terkenal, seperti CoinMarketCap
* bertanya kepada orang dan teman yang tepercaya

Anda dapat merujuk silang informasi yang diperoleh dari berbagai sumber ini, dan pada akhirnya hanya akan ada satu kebenaran :) Selamat, Anda telah menemukan situs web resmi yang benar.

Selanjutnya, Anda harus mengunduh dan memasang aplikasi tersebut. **Jika itu dompet Desktop**, setelah mengunduh dari situs web resmi, Anda perlu menginstalnya sendiri. Sangat disarankan untuk memverifikasi apakah tautan telah dirusak sebelum menginstal. Meskipun verifikasi ini mungkin tidak mencegah kasus-kasus di mana kode sumber diubah sepenuhnya (karena insider scam, peretasan internal, atau situs web resmi mungkin terkena hijack, dll.), namun, hal itu dapat mencegah kasus-kasus seperti perusakan sebagian kode sumber, serangan man-in-the-middle, dll.

Metode untuk memverifikasi apakah suatu file telah dirusak adalah pemeriksaan konsistensi file. Biasanya ada dua cara:

* **Pemeriksaan hash**: seperti MD5, SHA256, dll. MD5 berfungsi untuk sebagian besar kasus, tetapi masih ada sedikit risiko error crashed hash, jadi kami biasanya memilih SHA256, yang cukup aman.
* **Verifikasi tanda tangan GPG**: metode ini juga sangat populer. Sangat disarankan untuk sudah ahli dengan Tools, Command, dan metode GPG. Meskipun metode ini agak sulit bagi pendatang baru, Anda akan merasa sangat berguna setelah Anda terbiasa dengannya.

Namun, tidak banyak proyek di dunia kripto yang menyediakan verifikasi. Jadi, beruntunglah jika menemukannya. Misalnya, berikut adalah dompet bitcoin bernama Sparrow Wallet. Halaman unduhannya menyebutkan "Verifying the Release", yang sangat mengesankan, dan ada panduan yang jelas untuk kedua metode yang disebutkan di atas, sehingga Anda dapat menggunakannya sebagai referensi:

>https://sparrowwallet.com/download/

Halaman unduhan menyebutkan dua alat GPG:

* GPG Suite, untuk MacOS.
* Gpg4win, untuk Windows.

Jika Anda memperhatikan, Anda akan menemukan halaman unduhan untuk kedua alat GPG memberikan beberapa petunjuk tentang cara memeriksa konsistensi kedua metode tersebut. Namun, tidak ada panduan langkah demi langkah, artinya, Anda perlu belajar dan berlatih sendiri :)

**Jika itu adalah dompet ekstensi browser**, seperti MetaMask, satu-satunya hal yang harus Anda perhatikan adalah jumlah unduhan dan peringkat di toko web Chrome. MetaMask, misalnya, memiliki lebih dari 10 juta unduhan dan lebih dari 2.000 Rating (meskipun peringkat keseluruhannya tidak tinggi). Beberapa orang mungkin berpikir bahwa jumlah unduhan dan peringkat mungkin dilebih-lebihkan. Sejujurnya, sangat sulit untuk memalsukan angka sebesar itu.

**Dompet seluler (mobile wallet)** mirip dengan dompet ekstensi peramban. Namun, perlu dicatat bahwa App Store memiliki versi yang berbeda untuk setiap wilayah. Mata uang kripto dilarang di Tiongkok Daratan, jadi jika Anda mengunduh dompet dengan akun App Store Tiongkok Anda, hanya ada satu saran: jangan menggunakannya, ubah ke akun lain di wilayah lain seperti AS, lalu unduh ulang. Selain itu, situs web resmi yang benar juga akan mengarahkan Anda ke metode pengunduhan yang benar (seperti imToken, OneKey, Trust Wallet, dll. Penting bagi situs web resmi untuk menjaga keamanan situs web yang tinggi. Jika situs web resmi diretas, akan ada masalah besar.).

**Jika itu adalah dompet perangkat keras (hardware wallet)**, sangat disarankan untuk membelinya dari situs web resmi. Jangan membelinya dari toko daring. Setelah Anda menerima dompet, Anda juga harus memperhatikan apakah dompet itu utuh. Tentu saja, ada beberapa kecurangan pada kemasan yang cukup sulit dideteksi. Bagaimanapun, saat menggunakan dompet perangkat keras, Anda harus membuat frasa awal dan alamat dompet (wallet address) setidaknya mengacak tiga kali dari bawaan (default). Dan pastikan itu tidak diulang.

**Jika dompet web**, kami sangat menyarankan untuk tidak menggunakannya. Kecuali Anda tidak punya pilihan lain, pastikan dompet tersebut asli, lalu gunakan dengan hemat dan jangan pernah mengandalkannya.

### Frasa Mnemonik

Setelah membuat dompet, hal utama yang kita tangani secara langsung adalah frasa mnemonik/frasa awal (seed phrase), bukan kunci pribadi, yang lebih mudah diingat. Ada konvensi standar untuk frasa mnemonik (misalnya, BIP39); ada 12 kata bahasa Inggris secara umum; bisa berupa angka lain (kelipatan 3), tetapi tidak lebih dari 24 kata. Jika tidak, dompet tersebut terlalu rumit dan tidak mudah diingat. Jika jumlah kata kurang dari 12, keamanannya tidak dapat diandalkan. Umumnya, terdapat 12/15/18/21/24 kata. Di dunia blockchain, 12 kata cukup populer dan aman. Namun, masih ada dompet perangkat keras yang sulit seperti Ledger yang dimulai dengan 24 kata. Selain kata-kata dalam bahasa Inggris, beberapa bahasa lain juga tersedia, seperti bahasa Mandarin, Jepang, Korea, dan sebagainya. Berikut adalah daftar 2048 kata untuk referensi:

>https://github.com/bitcoin/bips/blob/master/bip-0039/bip-0039-wordlists.md

Saat membuat dompet, frasa awal Anda rentan. Anda harus memastikan bahwa Anda tidak dikelilingi oleh orang atau webcam atau apa pun yang dapat mencuri frasa awal (seed phrase) Anda.

Juga, harap perhatikan apakah frasa awal dibuat secara acak. Biasanya dompet yang terkenal dapat menghasilkan sejumlah frasa awal acak yang cukup. Namun, Anda harus selalu berhati-hati. Sulit untuk mengetahui apakah ada yang salah dengan dompet tersebut. Bersabarlah karena akan sangat bermanfaat untuk mengembangkan kebiasaan ini demi keamanan Anda. Terakhir, terkadang Anda bahkan dapat mempertimbangkan untuk memutuskan sambungan dari Internet untuk membuat dompet, terutama jika Anda akan menggunakan dompet tersebut sebagai dompet dingin (Cold Wallet). Memutus sambungan dari Internet selalu berhasil.

### Tanpa Kunci (keyless)

Tanpa kunci berarti tidak ada kunci pribadi (Private Key). Di sini kami membagi Keyless menjadi dua skenario utama (untuk memudahkan penjelasan. Pembagian seperti ini bukanlah standar industri)

* **Kustodian**. Contohnya adalah CEX atau Centralized Exchange, di mana pengguna hanya perlu mendaftarkan akun dan tidak memiliki kunci pribadi. Keamanan mereka sepenuhnya bergantung pada platform terpusat ini.
* **Non-Kustodian**. Pengguna memiliki kekuatan kontrol seperti kunci pribadi, tapi bukan kunci pribadi yang sebenarnya (atau frasa awal). Ia bergantung pada platform Cloud yang terkenal untuk hosting dan autentikasi/otorisasi. Oleh karena itu, keamanan platform Cloud menjadi bagian yang paling rentan. Yang lain menggunakan komputasi multi-pihak (MPC) yang aman untuk menghilangkan risiko titik tunggal, dan juga bermitra dengan platform Cloud populer untuk memaksimalkan pengalaman pengguna.

Secara pribadi, saya telah menggunakan berbagai jenis alat Keyless. CEX atau Centralized Exchange dengan kantong tebal dan reputasi baik memberikan pengalaman terbaik. Selama Anda tidak bertanggung jawab secara pribadi atas hilangnya token (seperti jika informasi akun Anda diretas), CEX atau Centralized Exchange biasanya akan mengganti kerugian Anda. Program Keyless berbasis MPC terlihat sangat menjanjikan dan harus dipromosikan. Saya memiliki pengalaman yang baik dengan ZenGo, Fireblocks, dan Safeheron. Keuntungannya jelas:

* Rekayasa algoritma MPC menjadi semakin matang pada blockchain yang terkenal, dan hanya perlu dilakukan untuk kunci privat.
* Satu set ide dapat memecahkan masalah blockchain yang berbeda yang memiliki skema multi-tanda tangan yang sangat berbeda, menciptakan pengalaman pengguna yang konsisten, yang sering kita sebut: multi-tanda tangan universal.
* Ini dapat memastikan bahwa kunci privat yang sebenarnya tidak pernah muncul dan memecahkan satu titik risiko melalui perhitungan multi-tanda tangan.
* Dikombinasikan dengan Cloud (atau teknologi Web2.0) membuat MPC tidak hanya aman tetapi juga menciptakan pengalaman yang baik.

Namun, tetap masih ada beberapa kelemahan:

* Tidak semua proyek sumber terbuka dapat memenuhi standar industri yang diterima. Lebih banyak pekerjaan yang perlu dilakukan.
* Banyak orang pada dasarnya hanya menggunakan Ethereum (atau blockchain berbasis EVM) Dengan demikian, solusi multi tanda-tangan (multi-signature) berdasarkan pendekatan kontrak pintar seperti Gnosis Safe sudah cukup.

Secara keseluruhan, apa pun alat (tools) yang Anda gunakan, selama Anda merasa aman dan memiliki kendali serta memiliki pengalaman yang baik, itu adalah alat yang bagus.

Sejauh ini kita telah membahas apa yang perlu kita waspadai terkait pembuatan dompet. Masalah keamanan umum lainnya akan dibahas di bagian selanjutnya.

## Cadangkan Dompet Anda

Di sinilah banyak orang baik akan jatuh ke dalam perangkap, termasuk saya sendiri. Saya tidak mencadangkan dengan benar dan saya tahu itu akan terjadi cepat atau lambat. Untungnya, itu bukan dompet dengan sejumlah besar aset dan teman-teman di SlowMist membantu saya memulihkannya. Tetap saja, itu adalah pengalaman yang menakutkan yang menurut saya tidak akan pernah diinginkan siapa pun. Jadi, kencangkan sabuk pengaman dan mari pelajari cara mencadangkan dompet Anda dengan aman.

### Frasa Mnemonik / Kunci Pribadi

Saat kita berbicara tentang pencadangan dompet, pada dasarnya kita berbicara tentang pencadangan frasa mnemonik (atau kunci pribadi. Untuk kenyamanan, kita akan menggunakan frasa mnemonik berikut ini). Sebagian besar frasa mnemonik dapat dikategorikan sebagai berikut:

* Teks Biasa
* Dengan Kata Sandi
* Multitanda Tangan (Multisign)
* Shamir’s Secret Sharing, atau disingkat SSS

Saya akan menjelaskan masing-masing jenis secara singkat.

**Teks Biasa**, Teks biasa mudah dipahami. Setelah Anda memiliki 12 kata bahasa Inggris tersebut, Anda memiliki aset di dompet. Anda dapat mempertimbangkan untuk melakukan pengacakan khusus, atau bahkan mengganti salah satu kata dengan kata lain. Keduanya akan meningkatkan kesulitan bagi peretas untuk meretas dompet Anda, namun, Anda akan mengalami sakit kepala besar jika Anda lupa tentang aturannya. Memori Anda tidak bulletproof. Percayalah, memori Anda akan kisut setelah beberapa tahun. Beberapa tahun yang lalu, ketika saya menggunakan dompet perangkat keras Ledger, saya mengubah urutan frasa mnemonik 24 kata. Setelah beberapa tahun, saya lupa urutannya dan saya tidak yakin apakah saya telah mengganti kata apa pun. Seperti yang disebutkan sebelumnya, masalah saya terpecahkan dengan program pemecah kode khusus yang menggunakan brute force untuk menebak urutan dan kata yang benar.

**Dengan Kata Sandi**, Menurut standar, frasa mnemonik dapat memiliki kata sandi. Itu masih frasa yang sama tetapi dengan kata sandi, frasa awal yang berbeda akan diperoleh. Frasa awal digunakan untuk memperoleh serangkaian kunci pribadi, kunci publik, dan alamat yang sesuai. Jadi, Anda tidak hanya harus mencadangkan frasa mnemonik, tetapi juga kata sandinya. Omong-omong, kunci pribadi juga dapat memiliki kata sandi dan memiliki standarnya sendiri, seperti BIP 38 untuk bitcoin dan Keystore untuk ethereum.

**Multitanda Tangan (Multisign)**, Seperti namanya, diperlukan tanda tangan dari banyak orang untuk mengakses dompet. Ini sangat fleksibel karena Anda dapat menetapkan aturan Anda sendiri. Misalnya, jika ada 3 orang yang memiliki kunci (kata mnemonik atau kunci pribadi), Anda dapat mengatur agar setidaknya dua orang untuk menandatangani untuk mengakses dompet. Setiap blockchain memiliki solusi multi-signature-nya sendiri. Sebagian besar dompet Bitcoin yang terkenal mendukung multi-signature. Namun, di Ethereum, multi-signature terutama didukung melalui kontrak pintar, seperti Gnosis Safe. Lebih jauh lagi, MPC, atau Secure Multi-Party Computation menjadi semakin populer. MPC memberikan pengalaman yang mirip dengan multi-signature tradisional, tetapi dengan teknologi yang berbeda. Tidak seperti multi-signature, MPC bersifat blockchain agnostik dan dapat bekerja dengan semua protokol.

**Shamir’s Secret Sharing, atau disingkat SSS**, SSS memecah seed menjadi beberapa share (biasanya, setiap share berisi 20 kata). Untuk memulihkan dompet, sejumlah share tertentu harus dikumpulkan dan digunakan. Untuk detailnya, lihat praktik terbaik industri di bawah ini:

>https://guide.keyst.one/docs/shamir-backup<br>
>https://wiki.trezor.io/Shamir_backup

Menggunakan solusi seperti multi-signature dan SSS akan memberi Anda ketenangan pikiran dan menghindari risiko titik tunggal, tetapi dapat membuat manajemen menjadi relatif rumit dan terkadang melibatkan banyak pihak. Selalu ada kompromi antara kenyamanan dan keamanan. Terserah individu untuk memutuskan tetapi jangan pernah malas dalam prinsip.

### Enkripsi

Enkripsi adalah konsep yang sangat, sangat luas. Tidak masalah apakah enkripsi tersebut simetris, asimetris, atau menggunakan teknologi canggih lainnya; selama pesan terenkripsi dapat dengan mudah didekripsi oleh Anda atau tim penanganan darurat Anda dengan mudah tetapi tidak ada orang lain setelah beberapa dekade, itu adalah enkripsi yang baik.

Berdasarkan prinsip keamanan "zero trust", saat kita mencadangkan dompet, kita harus berasumsi bahwa setiap langkah dapat diretas, termasuk lingkungan fisik seperti brankas. Ingatlah bahwa tidak ada orang lain selain diri Anda yang dapat dipercaya sepenuhnya. Faktanya, terkadang Anda bahkan tidak dapat mempercayai diri sendiri, karena ingatan Anda mungkin memudar atau hilang. Namun, saya tidak akan selalu membuat asumsi pesimistis, jika tidak, hal itu akan membawa saya pada beberapa hasil yang tidak diinginkan.

Saat melakukan pencadangan, pertimbangan khusus harus diberikan pada pemulihan bencana. Tujuan utama pemulihan bencana adalah untuk menghindari satu titik risiko. Apa yang akan terjadi jika Anda pergi atau lingkungan tempat Anda menyimpan cadangan sedang tidak berfungsi? Oleh karena itu, untuk hal-hal penting, ada beberapa hal yang perlu diperhatikan.

Jika Anda adalah orang yang ahli dalam pemulihan bencana, maka harus ada beberapa cadangan.

Saya tidak akan menjelaskan terlalu banyak tentang cara memilih orang yang ahli dalam pemulihan bencana karena itu tergantung pada siapa yang Anda percaya. Saya akan fokus pada cara melakukan beberapa cadangan. Mari kita lihat beberapa bentuk dasar lokasi cadangan:

* Cloud
* Paper
* Device
* Brain (ingatan)

**Cloud**, Banyak orang yang tidak mempercayai backup di Cloud, mereka menganggapnya rentan terhadap serangan hacker. Pada akhirnya, yang terpenting adalah pihak mana — penyerang atau bertahan — yang memberikan upaya lebih besar, baik dari segi tenaga maupun anggaran. Secara pribadi, saya percaya pada layanan cloud yang didukung oleh Google, Apple, Microsoft, dll., karena saya tahu seberapa kuat tim keamanan mereka dan berapa banyak yang mereka keluarkan untuk keamanan. Selain berjuang melawan peretas eksternal, saya juga sangat peduli dengan pengendalian risiko keamanan internal dan perlindungan data pribadi. Beberapa penyedia layanan yang saya percaya melakukan pekerjaan yang relatif lebih baik di bidang ini. Tapi tidak ada yang mutlak. Jika saya memilih salah satu layanan cloud ini untuk mencadangkan data penting (seperti dompet), saya pasti akan mengenkripsi dompet setidaknya sekali lagi.

Saya sangat merekomendasikan menguasai GPG. Ini dapat digunakan untuk "verifikasi tanda tangan", dan sementara itu memberikan keamanan enkripsi dan dekripsi yang kuat. Anda dapat mempelajari lebih lanjut tentang GPG di:

>https://www.ruanyifeng.com/blog/2013/07/gpg.html

Oke, Selamat jika Anda sudah menguasai GPG :) Sekarang Anda telah mengenkripsi data terkait di dompet Anda (frasa mnemonik atau kunci pribadi) dengan GPG di lingkungan offline yang aman, kini Anda dapat membuang file terenkripsi langsung ke layanan cloud ini dan menyimpannya di sana. Semua akan baik baik saja. Tapi saya perlu mengingatkan Anda di sini: jangan pernah kehilangan kunci pribadi GPG Anda atau lupa kata sandi kunci pribadi (Private Key)…

Pada titik ini, Anda mungkin merasa tingkat keamanan ekstra ini cukup merepotkan: Anda harus mempelajari tentang GPG dan membuat cadangan kunci pribadi dan kata sandi GPG Anda. Pada kenyataannya, jika Anda telah melakukan semua langkah di atas, Anda sudah terbiasa dengan prosesnya dan tidak akan menganggapnya sulit atau menyusahkan. Saya tidak akan berkata apa-apa lagi karena latihan membuat menjadi sempurna.

Jika Anda ingin menghemat tenaga, ada kemungkinan lain namun keamanannya mungkin diabaikan. Saya tidak dapat mengukur diskon pastinya tetapi terkadang saya malas saat menggunakan beberapa alat terkenal untuk mendapatkan bantuan. Alat itu adalah 1Password. Versi terbaru 1Password sudah mendukung penyimpanan langsung data terkait dompet, seperti kata mnemonik, kata sandi, alamat dompet, dll., yang nyaman bagi pengguna. Alat lain (seperti Bitwarden) dapat mencapai hal serupa, tetapi tidak senyaman itu.

**Paper**, Banyak dompet perangkat keras dilengkapi dengan beberapa kartu kertas berkualitas tinggi tempat Anda dapat menuliskan frasa mnemonik Anda (dalam teks biasa, SSS, dll.). Selain kertas, ada juga yang menggunakan pelat baja (tahan api, tahan air, dan tahan korosi, tentunya saya belum mencobanya). Ujilah setelah Anda menyalin frasa mnemonik dan jika semuanya berfungsi, letakkan di tempat yang Anda rasa aman, seperti di brankas. Saya pribadi sangat suka menggunakan kertas karena jika disimpan dengan benar, kertas memiliki umur yang jauh lebih lama dibandingkan barang elektronik.

**Device**, Ini mengacu pada semua jenis peralatan; elektronik adalah jenis cadangan yang umum, seperti komputer, iPad, iPhone, atau hard drive, dll, tergantung pada preferensi pribadi. Kita juga harus memikirkan transmisi yang aman antar perangkat. Saya merasa nyaman menggunakan metode peer-to-peer seperti AirDrop dan USB karena perantara sulit membajak prosesnya. Saya tentu saja tidak nyaman dengan kenyataan bahwa peralatan elektronik mungkin rusak setelah beberapa tahun, jadi saya menjaga kebiasaan memeriksa perangkat setidaknya setahun sekali. Ada beberapa langkah berulang (seperti enkripsi) yang dapat Anda rujuk ke bagian Cloud.

**Brain (ingatan)**, Mengandalkan ingatanmu itu mengasyikkan. Faktanya, setiap orang memiliki "istana kenangan" masing-masing. Memori tidaklah misterius dan dapat dilatih untuk bekerja lebih baik. Ada hal-hal tertentu yang memang lebih aman dengan ingatan. Apakah hanya mengandalkan otak atau tidak adalah pilihan pribadi. Namun perhatikan dua risiko: pertama, ingatan memudar seiring berjalannya waktu dan dapat menyebabkan kebingungan; risiko lainnya adalah Anda mungkin mengalami kecelakaan. Saya akan berhenti di sini dan membiarkan Anda menjelajah lebih jauh.

Sekarang Anda semua sudah dicadangkan. Jangan mengenkripsi terlalu banyak, jika tidak, Anda akan menderita sendiri setelah beberapa tahun. Sesuai dengan prinsip keamanan "verifikasi berkelanjutan", metode enkripsi dan pencadangan Anda, baik berlebihan atau tidak, harus diverifikasi terus-menerus, baik secara berkala maupun acak. Frekuensi verifikasi bergantung pada memori Anda dan Anda tidak harus menyelesaikan seluruh proses. Selama prosesnya benar, verifikasi parsial juga berfungsi. Terakhir, kerahasiaan dan keamanan proses otentikasi juga perlu diperhatikan.

Oke, mari kita tarik napas dalam-dalam di sini. Memulai adalah bagian tersulit. Sekarang kamu sudah siap, ayo masuki hutan gelap ini :)

## Cara Menggunakan Dompet Anda

Setelah Anda membuat dan mencadangkan dompet Anda, inilah tantangan sebenarnya. Jika Anda tidak sering berpindah-pindah aset, atau Anda jarang berinteraksi dengan kontrak pintar (Smart Contract) DeFi, NFT, GameFi, atau Web3, istilah populer yang sering digunakan saat ini, aset Anda akan mungkin relatif aman.

### AML (anti pencucian uang)

Namun, "relatif aman" bukan berarti "tidak ada risiko sama sekali" bukan. Sebab "kamu tidak pernah tahu mana yang akan datang terlebih dulu, hari esok atau kecelakaan", bukan?. Kenapa sih? Coba pikirkan, dari mana Anda mendapatkan mata uang kripto tersebut? Itu tidak datang begitu saja, bukan? Anda mungkin menemukan AML (Anti Pencucian Uang) pada semua mata uang kripto yang Anda dapatkan kapan saja. Artinya, mata uang kripto yang Anda pegang saat ini mungkin "kotor", dan jika Anda tidak beruntung, mata uang tersebut bahkan mungkin langsung dibekukan di rantainya. Menurut laporan publik, Tether pernah membekukan beberapa aset USDT sesuai permintaan lembaga penegak hukum. Daftar dana yang dibekukan dapat dilihat di sini.

>https://dune.xyz/phabc/usdt---banned-addresses

Anda dapat memverifikasi apakah suatu alamat dibekukan oleh Tether dari kontrak USDT.

>https://etherscan.io/token/0xdac17f958d2ee523a2206206994597c13d831ec7#readContract

<img src="res/usdt_isblacklisted.png" width="700">

Gunakan alamat dompet target sebagai input di "isBlackListed" untuk memeriksa. Chain lain yang menggunakan USDT juga memiliki cara verifikasi serupa.

Meskipun aset BTC dan ETH Anda tidak akan dibekukan di blockchain, bursa terpusat (centralized exchanges atau CEX) mungkin membekukan aset Anda sesuai dengan persyaratan AML setelah aset Anda ditransfer ke platform ini dan jika mereka terlibat dalam kasus terbuka yang sedang ditangani oleh penegak hukum.

Untuk menghindari masalah AML dengan lebih baik, selalu pilih platform dan individu dengan reputasi baik sebagai rekanan Anda. Sebenarnya ada beberapa solusi untuk masalah seperti ini. Misalnya, di Ethereum, hampir semua penjahat dan orang yang sangat peduli dengan privasi mereka menggunakan Tornado Cash untuk "mencampur" koin. Saya tidak akan menggali lebih jauh topik ini karena sebagian besar metode di sini digunakan untuk melakukan kejahatan.

### Dompet Dingin (cold wallet)

Ada berbagai cara untuk menggunakan dompet dingin. Dari sudut pandang dompet, ini dapat dianggap sebagai dompet dingin selama tidak terhubung ke jaringan (internet) apa pun. Tapi bagaimana cara menggunakannya saat offline? Pertama-tama, jika Anda hanya ingin menerima cryptocurrency, itu bukan masalah besar. Dompet dingin dapat memberikan pengalaman luar biasa dengan bekerja dengan dompet khusus "watch only" (dimana kita hanya memantau asset kita saja), seperti imToken, OneKey, Trust Wallet, dll. Dompet ini dapat diubah menjadi dompet "watch only" hanya dengan menambahkan alamat dompet target.

Jika kita ingin mengirim cryptocurrency menggunakan cold wallet, berikut cara yang paling umum digunakan:

* Kode QR
* USB
* Bluetooth

Semua ini memerlukan aplikasi khusus (disebut Aplikasi Ringan atau Light App di sini) untuk bekerja dengan dompet dingin (cold wallet). Aplikasi Ringan akan online bersama dengan dompet khusus "watch only" yang disebutkan di atas. Setelah kita memahami prinsip esensial yang mendasarinya, kita seharusnya mampu memahami pendekatan-pendekatan ini. Prinsip pentingnya adalah: pada akhirnya, ini hanyalah mencari tahu cara menyiarkan konten yang ditandatangani ke dalam blockchain. Proses detailnya adalah sebagai berikut:

* Konten yang akan ditandatangani dikirimkan oleh Light App ke Cold Wallet melalui salah satu cara berikut.
* Tanda tangan (signature) diproses oleh Cold Wallet yang memiliki kunci pribadi dan kemudian dikirimkan kembali ke Cold Wallet menggunakan cara yang sama
* Light App menyiarkan konten yang ditandatangani di blockchain.

Jadi apapun metode yang digunakan, kode QR, USB atau Bluetooth, harus mengikuti proses di atas. Tentu saja, detailnya mungkin berbeda untuk setiap metode. Misalnya kode QR memiliki kapasitas informasi yang terbatas, sehingga jika data tanda tangan terlalu besar, kita harus membaginya.

Tampaknya memang merepotkan, tetapi akan lebih baik jika Anda terbiasa. Anda bahkan akan merasakan rasa aman sepenuhnya. Namun jangan dianggap 100% aman karena disini masih ada resiko dan banyak kasus kerugian besar akibat resiko tersebut. Berikut poin risikonya:

* Alamat tujuan transfer koin tidak diperiksa dengan cermat sehingga mengakibatkan koin tersebut ditransfer ke orang lain. Kadang-kadang orang malas dan ceroboh. Misalnya, seringkali mereka hanya memeriksa bagian awal dan akhir alamat dompet daripada memeriksa seluruh alamat secara keseluruhan. Hal ini menyisakan pintu belakang (Backdoor) bagi orang-orang jahat. Mereka akan menjalankan program untuk mendapatkan alamat dompet dengan beberapa bit pertama dan terakhir yang sama dengan alamat target yang Anda inginkan dan kemudian mengganti alamat target transfer koin Anda dengan alamat yang berada di bawah kendali mereka menggunakan beberapa trik.
* Koin diotorisasi ke alamat yang tidak diketahui. Biasanya otorisasi adalah mekanisme token kontrak pintar Ethereums, fungsi "setujui", dengan satu argumen sebagai alamat otorisasi target dan argumen lainnya sebagai kuantitas (jumlah). Banyak orang tidak memahami mekanisme ini, sehingga mereka mungkin mengotorisasi token dalam jumlah tidak terbatas ke alamat target, dan pada saat itu alamat target memiliki izin untuk mentransfer semua token tersebut. Ini disebut pencurian koin terotorisasi, dan ada varian lain dari teknik ini, namun saya tidak akan membahasnya di sini.
* Beberapa tanda tangan (signature) yang tampaknya tidak penting sebenarnya memiliki jebakan besar di belakangnya, dan saya tidak akan membahasnya sekarang, tetapi akan menjelaskan detailnya nanti.
* Cold Wallet mungkin tidak memberikan cukup informasi yang diperlukan, sehingga menyebabkan Anda menjadi ceroboh dan salah menilai.

Semuanya bermuara pada dua poins:

* Mekanisme keamanan interaksi pengguna "Apa yang Anda lihat adalah apa yang Anda tandatangani" tidak ada ataupun tersedia.
* Kurangnya latar belakang pengetahuan yang relevan dari pengguna.

### Dompet Panas (hot wallet)

Dibandingkan dengan dompet dingin, dompet panas pada dasarnya memiliki semua risiko yang dimiliki dompet dingin. Ditambah lagi, ada satu lagi: risiko pencurian frase rahasia (atau kunci pribadi). Pada titik ini ada lebih banyak masalah keamanan yang perlu dipertimbangkan dengan hot wallet, seperti keamanan runtime environment. Jika ada virus yang terkait dengan runtime environment, maka ada risiko dicuri. Ada juga dompet panas yang memiliki kerentanan tertentu sehingga frasa rahasia dapat mudah dicuri.

Selain fungsi transfer koin biasa, jika Anda ingin berinteraksi dengan DApps lain (DeFi, NFT, GameFi, dll.), Anda harus mengaksesnya langsung dengan browser Anda sendiri atau berinteraksi dengan DApps yang dibuka di browser PC Anda melalui protokol "WalletConnect".

*Catatan: Referensi DApps dalam buku pegangan ini merujuk secara default ke proyek (smart contract) kontrak pintar yang berjalan di blockchain Ethereum.*

Secara default, interaksi seperti itu tidak mengarah pada pencurian frase rahasia, kecuali ada masalah dengan desain keamanan dompet itu sendiri. Dari audit keamanan dan riwayat penelitian keamanan kami, terdapat risiko frasa rahasia dompet dicuri langsung oleh JavaScript berbahaya di halaman target. Namun, ini adalah kasus yang jarang terjadi, karena sebenarnya ini adalah kesalahan tingkat dasar yang tidak mungkin dilakukan oleh proyek dompet (Wallet) terkenal mana pun.

Tak satu pun dari hal ini yang benar-benar menjadi kekhawatiran saya di sini, hal tersebut dapat ditangani oleh saya (dan untuk Anda juga). Kekhawatiran terbesar saya adalah: bagaimana setiap iterasi dompet terkenal memastikan tidak ada kode berbahaya atau pintu belakang yang ditanam? Implikasi dari pertanyaan ini jelas: Saya memverifikasi bahwa versi dompet saat ini tidak memiliki masalah keamanan dan saya merasa nyaman menggunakannya, namun saya tidak tahu seberapa aman versi berikutnya. Lagi pula, saya atau tim keamanan saya tidak punya banyak waktu dan tenaga untuk melakukan semua verifikasi.

Ada beberapa insiden pencurian koin yang disebabkan oleh kode berbahaya atau pintu belakang seperti yang dijelaskan di sini, seperti CoPay, AToken, dll. Anda dapat mencari sendiri insiden spesifiknya.

Dalam hal ini, ada beberapa cara untuk berbuat jahat:

* Saat dompet berjalan (sedang aktif), kode berbahaya mengemas dan mengunggah frasa rahasia yang relevan langsung ke server yang dikendalikan hacker.
* Saat dompet berjalan dan pengguna memulai transfer, informasi seperti alamat target dan jumlah secara diam-diam diganti di backend dompet, dan sulit bagi pengguna untuk menyadarinya.
* Merusak nilai entropi bilangan acak yang terkait dengan pembuatan frasa rahasia, yang membuatnya relatif mudah untuk diuraikan.

Keamanan terkadang adalah sesuatu yang kita acuhkan dan sekedar diketahui saja, dan ada banyak hal yang dapat dengan mudah diabaikan atau dilewatkan. Jadi untuk dompet yang menyimpan aset penting, aturan keamanan saya juga sederhana: "if it ain’t broke, don’t fix it" jika masih bisa bekerja dengan baik, tidak perlu diperbaharui dulu.

### Apa Itu Keamanan DeFi?

Ketika kita berbicara tentang DApp, bisa berupa DeFi, NFT atau GameFi dll. Dasar-dasar keamanannya sebagian besar sama, tetapi memiliki spesifikasinya masing-masing. Pertama mari kita ambil DeFi sebagai contoh untuk menjelaskannya. Ketika kita berbicara tentang keamanan DeFi, apa sebenarnya yang kita maksud? Orang-orang di industri ini hampir selalu hanya melihat kontrak pintar. Tampaknya ketika kontrak pintar bagus, semuanya akan baik-baik saja. Sebenarnya, ini jauh dari benar.

Keamanan DeFi setidaknya mencakup komponen berikut:

* Keamanan Kontrak Cerdas (smart contract)
* Keamanan Yayasan Blockchain (blockchain foundation)
* Keamanan Bagian Depan (front end)
* Keamanan Komunikasi
* Keamanan Manusia
* Keamanan Keuangan
* Keamanan Kepatuhan (compliance)

**Keamanan Kontrak Cerdas**

Keamanan kontrak pintar (smart contract) memang merupakan titik masuk paling penting untuk audit keamanan, dan standar audit keamanan SlowMist untuk kontrak pintar dapat ditemukan di:

>https://www.slowmist.com/service-smart-contract-security-audit.html

Untuk user tingkat lanjut, jika keamanan bagian kontrak pintar itu sendiri dapat dikontrol (apakah mereka dapat mengaudit dirinya sendiri atau memahami laporan audit keamanan yang dikeluarkan oleh organisasi profesional), maka tidak masalah jika bagian lainnya aman. Dapat dikontrol adalah konsep yang rumit, beberapa di antaranya bergantung pada kekuatan user itu sendiri. Misalnya, user sudah memiliki persyaratan tertentu sehubungan dengan risiko dari otoritas kontrak pintar yang berlebihan. Jika proyek itu sendiri kuat dan orang-orang di belakangnya mempunyai reputasi yang baik, sentralisasi penuh tidak akan menjadi masalah. Namun, untuk proyek-proyek yang kurang terkenal, kontroversial, atau sedang berkembang, jika Anda menyadari bahwa kontrak pintar proyek tersebut memiliki risiko izin yang berlebihan, terutama jika izin tersebut juga dapat mempengaruhi asset atau penghasilan Anda, Anda pasti akan enggan.

Risiko izin yang berlebihan sangat kecil. Dalam banyak kasus, admin proyek bertanggung jawab untuk melakukan tata kelola yang relevan dan kontinjensi risiko. Namun bagi pengguna, ini adalah ujian terhadap sifat manusia. Bagaimana jika tim memutuskan untuk melakukan kejahatan? Jadi ada praktik trade-off di industri ini: menambahkan Timelock untuk mengurangi risiko izin yang berlebihan, misalnya:

> Compound, sebuah proyek DeFi yang mapan dan terkenal, modul kontrak pintar inti Pengawas Keuangan dan Tata Kelola, keduanya memiliki mekanisme Timelock yang ditambahkan ke izin adminnya:<br>
> Pengawas Keuangan(0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b)<br>
> Tata Kelola(0xc0da02939e1441f497fd74f78ce7decb17b66529)<br>
> Admin 2 modul ini adalah<br>
> Kunci Waktu (Timelock)(0x6d903f6003cca6255d85cca4d3b5e5146dc33925)

Anda dapat langsung mengetahui on chain bahwa Timelock (variabel penundaan) adalah 48 jam (172.800 detik):

<img src="res/compound_timelock.png" width="700">

Artinya, jika admin Compound perlu mengubah beberapa variabel kunci dari kontrak pintar target, transaksi akan dicatat setelah dimulai pada blockchain, namun 48 jam harus menunggu sebelum transaksi dapat diselesaikan dan dieksekusi. Artinya, jika mau, Anda dapat mengaudit setiap operasi dari admin, dan Anda memiliki waktu setidaknya 48 jam untuk bertindak. Misalnya, jika Anda tidak yakin, Anda dapat menarik dana Anda dalam waktu 48 jam.

Cara lain untuk memitigasi risiko izin admin yang berlebihan adalah dengan menambahkan multi-signature, seperti menggunakan Gnosis Safe untuk pengelolaan multisig, sehingga setidaknya tidak ada diktator. Perlu dicatat di sini bahwa multisig bisa menjadi "baju baru kaisar". Misalnya, satu orang mungkin memegang banyak kunci. Oleh karena itu, strategi multisig dari proyek sasaran perlu dinyatakan dengan jelas. Siapa yang memegang kunci, dan identitas masing-masing pemegang kunci harus mempunyai reputasi baik. 

Perlu disebutkan di sini bahwa strategi keamanan apa pun dapat mengarah pada masalah "pakaian baru kaisar", yang mana strategi tersebut mungkin tampak dilakukan dengan baik, namun kenyataannya tidak, sehingga menghasilkan ilusi keamanan. Ambil contoh lain, Timelock terlihat bagus di atas kertas. Sebenarnya, ada beberapa kasus di mana Timelock yang diterapkan oleh beberapa proyek memiliki pintu belakang. Umumnya, pengguna tidak melihat kode sumber Timelock, dan mereka belum tentu memahaminya meskipun mereka melakukannya, jadi admin memasang pintu belakang di sana, dan tidak ada yang akan menyadarinya untuk waktu yang cukup lama.

Selain risiko izin yang berlebihan, elemen keamanan kontrak pintar lainnya juga penting. Namun, saya tidak akan membahasnya di sini, dengan mempertimbangkan prasyarat pemahaman anda. Inilah saran saya: Anda setidaknya harus belajar membaca laporan audit keamanan, dan dari banyak latihan akan menjadi sempurna.

**Keamanan Yayasan Blockchain**

Keamanan dasar Blockchain mengacu pada keamanan blockchain itu sendiri, seperti keamanan buku besar konsensus (consensus ledger), keamanan mesin virtual, dll. Jika keamanan blockchain itu sendiri mengkhawatirkan, proyek kontrak pintar (smart contract) yang berjalan pada rantai tersebut akan terkena dampak langsung. Sangat penting untuk memilih blockchain dengan mekanisme keamanan dan reputasi yang memadai, dan lebih baik dengan kemungkinan umur panjang yang lebih tinggi.

**Keamanan Bagian Depan**

Keamanan frontend benar-benar buruk. Itu terlalu dekat dengan pengguna, dan sangat mudah untuk membodohi pengguna hingga menipu. Mungkin fokus utama setiap orang adalah pada keamanan dompet dan kontrak pintar, sehingga keamanan frontend mudah diabaikan. Saya ingin menekankan lagi bahwa keamanan frontend adalah seperti iblis! Izinkan saya menggali lebih dalam.

Kekhawatiran terbesar saya mengenai keamanan frontend adalah: Bagaimana saya tahu bahwa kontrak yang saya gunakan untuk berinteraksi dari halaman frontend khusus ini adalah kontrak pintar yang saya harapkan?

Kecemasan ini terutama disebabkan oleh dua faktor:

* Pekerjaan orang dalam (Inside job)
* Pihak ketiga (Third party)

Sangat mudah untuk memahami pekerjaan orang dalam. Misalnya, pengembang secara diam-diam mengganti alamat kontrak pintar (smart contract) target di halaman depan dengan alamat kontrak yang memiliki pintu belakang (backdoor), atau menanam skrip otorisasi phishing. Saat Anda mengunjungi halaman frontend yang dicurangi ini, serangkaian operasi selanjutnya yang melibatkan kripto di dompet Anda mungkin dilakukan masuk ke dalam jebakan. Sebelum Anda menyadarinya, koin-koin itu sudah hilang.

Pihak ketiga terutama mengacu pada dua jenis:

* Salah satunya adalah rantai ketergantungan (dependencies chain) yang disusupi. Misalnya, ketergantungan pihak ketiga yang digunakan oleh halaman frontend memiliki pintu belakang yang menyelinap ke halaman frontend target bersama dengan pengemasan dan rilis. Berikut struktur ketergantungan paket SushiSwap (ini hanya sebagai ilustrasi saja, belum tentu berarti proyek di tangkapan layar memiliki masalah seperti itu):<br>
    <img src="res/sushiswap_3rd.png" width="500">

* Contoh lainnya adalah file JavaScript jarak jauh pihak ketiga yang diimpor oleh halaman frontend. Jika file JavaScript ini diretas, kemungkinan halaman frontend target juga terpengaruh, seperti OpenSea (ini hanya sebagai ilustrasi saja, bukan berarti proyek di tangkapan layar tersebut mengalami masalah seperti itu):<br>
    <img src="res/opensea_3rd.png" width="800">

Alasan mengapa kami mengatakan hal ini mungkin terjadi namun belum pasti adalah karena risikonya dapat dihindari jika pengembang merujuk ke file JavaScript jarak jauh pihak ketiga di halaman frontend dengan cara berikut:

><script src="https://example.com/example-framework.js" integrity="sha384-Li9vy3DqF8tnTXuiaAJuML3ky+er10rcgNR/VqsVpcw+ThHmYcwiB1pbOxEbzJr7" crossorigin="anonymous"></script>

Poin kuncinya di sini adalah mekanisme keamanan HTML5 yang bagus: atribut integritas dalam tag (mekanisme SRI). integritas mendukung SHA256, SHA384 dan SHA512. Jika file JavaScript pihak ketiga tidak memenuhi pemeriksaan integritas hash, file tidak akan dimuat. Ini bisa menjadi cara yang baik untuk mencegah eksekusi kode yang tidak diinginkan. Namun, pemanfaatan mekanisme ini memerlukan sumber daya target untuk mendukung respons CORS. Untuk detailnya, lihat berikut ini:

>https://developer.mozilla.org/zh-CN/docs/Web/Security/Subresource_Integrity

**Keamanan Komunikasi**

Mari fokus pada keamanan HTTPS di bagian ini. Pertama, situs web target harus menggunakan HTTPS, dan transmisi teks biasa HTTP tidak boleh diizinkan. Hal ini karena transmisi teks biasa HTTP terlalu mudah untuk dibajak oleh serangan man-in-the-middle. Saat ini HTTPS sangat umum sebagai protokol transmisi yang aman. Jika ada serangan man-in-the-middle pada HTTPS, dan penyerang telah menyuntikkan JavaScript berbahaya ke front-end aplikasi web, peringatan kesalahan sertifikat HTTPS yang sangat jelas akan ditampilkan di browser pengguna.

Mari kita gunakan kejadian MyEtherWallet sebagai contoh untuk mengilustrasikan hal ini.

MyEtherWallet dulunya adalah dompet aplikasi web yang sangat populer, dan hingga saat ini masih sangat terkenal. Namun ini bukan lagi sekedar dompet aplikasi web. Seperti disebutkan sebelumnya, saya sangat tidak menyarankan penggunaan dompet aplikasi web karena alasan keamanan. Selain berbagai masalah keamanan front-end, pembajakan HTTPS juga mempunyai potensi risiko yang besar.

Pada tanggal 24 April 2018, terjadi insiden keamanan besar berupa pembajakan HTTPS di MyEtherWallet. Rekap kejadiannya bisa dilihat di sini:

>https://www.reddit.com/r/MyEtherWallet/comments/8eloo9/official_statement_regarding_dns_spoofing_of/<br>
>https://www.reddit.com/r/ethereum/comments/8ek86t/warning_myetherwalletcom_highjacked_on_google/

![](res/myetherwallet_https_hijack.png)

Dalam serangan tersebut, peretas (hacker) membajak layanan DNS (Google Public DNS) yang digunakan oleh sejumlah besar pengguna MyEtherWallet melalui BGP, sebuah protokol perutean kuno, yang secara langsung menyebabkan tampilan peringatan kesalahan HTTPS di setiap browser pengguna ketika mereka mencoba mengunjungi. Faktanya, pengguna harus berhenti ketika mereka melihat peringatan ini, karena pada dasarnya ini menunjukkan bahwa halaman web target telah dibajak. Namun kenyataannya, banyak pengguna dengan cepat mengabaikan peringatan tersebut dan terus melanjutkan interaksi mereka dengan situs yang dibajak, karena mereka sama sekali tidak memahami risiko keamanan di balik peringatan kesalahan HTTPS.

Karena halaman web target telah dibajak dan Hacker telah menyuntikkan JavaScript berbahaya di sana, berdasarkan interaksi pengguna, Hacker akan berhasil mencuri kunci pribadi teks biasa mereka dan mentransfer dana mereka (kebanyakan ETH).

Ini jelas merupakan kasus klasik di mana Hacker menggunakan teknik pembajakan BGP untuk mencuri kripto. Itu (metode yang) berlebihan. Setelah itu masih banyak lagi kasus serupa yang terjadi, dan saya tidak akan menyebutkannya secara detail di sini. Bagi pengguna hanya ada satu hal yang benar-benar perlu diperhatikan: jika Anda memutuskan untuk menggunakan dompet aplikasi web, atau mencoba berinteraksi dengan DApp, selalu pastikan Anda menghentikan dan menutup halaman setiap kali Anda melihat peringatan kesalahan sertifikat HTTPS! Dan dana Anda akan baik-baik saja. 

Ada kenyataan kejam dalam keamanan: ketika ada risiko, jangan berikan pilihan apa pun kepada pengguna. Seolah-olah Anda melakukannya, akan selalu ada pengguna yang jatuh ke dalam perangkap karena alasan apa pun. Faktanya, tim proyek perlu mengambil tanggung jawab. Saat ini, sudah ada solusi keamanan yang sangat efektif untuk masalah pembajakan HTTPS yang disebutkan di atas: tim proyek perlu mengonfigurasi HSTS dengan benar. HSTS adalah singkatan dari HTTP Strict Transport Security; ini adalah mekanisme kebijakan keamanan web yang didukung oleh sebagian besar browser modern. Jika HSTS diaktifkan, jika terjadi kesalahan sertifikat HTTPS, browser akan memaksa pengguna untuk berhenti mengakses aplikasi web target dan pembatasan itu tidak akan dapat dilewati. Sekarang Anda mengerti maksud saya?

**Keamanan Manusia**

Bagian ini mudah dimengerti. Misalnya tim proyek berpikiran jahat dan bertindak tidak jujur. Saya telah menyebutkan beberapa konten yang relevan di bagian sebelumnya, jadi di sini saya tidak akan membahas lebih detail. Lebih banyak lagi yang akan dibahas di bagian selanjutnya.

**Keamanan Keuangan**

Keamanan Finansial (keuangan) harus dibahas mendalam dan dihargai setinggi-tingginya. Di DeFi, pengguna sangat memperhatikan harga dan pengembalian token. Mereka menginginkan laba atas investasi unggul mereka, atau setidaknya stabil. Dengan kata lain, sebagai pengguna, saya memainkan permainan untuk menang (i play to win) dan jika saya kalah, setidaknya saya harus yakin bahwa ini adalah permainan yang adil. Ini hanyalah sifat manusia.

Keamanan finansial di DeFi rentan terhadap serangan berupa:

* Praktik peluncuran token (launchpad) yang tidak adil seperti pra-penambangan (pre-mining) atau pra-penjualan (pre-sale);
* Serangan paus kripto (whale);
* Pompa dan buang (pump n dump);
* Peristiwa angsa hitam (blackswan) seperti curahan air dari air terjun yang masuk ke pasar dan menyebabkan keruntuhan; atau katakanlah ketika satu protokol DeFi menjadi semacam sarang besar atau dioperasikan dengan bermacam DeFi/Token lain, dan keamanan/keandalannya akan sangat bergantung pada protokol lain;
* Serangan teknis lainnya atau yang kita sebut dengan teknik ilmiah seperti front running, sandwich Attack, Flash Loan Attack, dll.

**Keamanan Kepatuhan**

Persyaratan kepatuhan adalah topik yang sangat besar, AML "anti money laundering" (Anti Pencucian Uang) yang disebutkan sebelumnya hanyalah salah satu poinnya. Ada juga aspek seperti KYC (Kenali Pelanggan Anda), sanksi, risiko sekuritas, dll. Sebenarnya bagi kami pengguna, hal ini bukanlah sesuatu yang berada di bawah kendali kami. Saat kami berinteraksi dengan proyek tertentu, karena proyek tersebut mungkin tunduk pada peraturan terkait di negara tertentu, informasi privasi kami mungkin dikumpulkan. Anda mungkin tidak peduli dengan masalah privasi seperti itu, tetapi ada orang yang peduli.

Misalnya, di awal tahun 2022 terjadi insiden kecil: beberapa dompet memutuskan untuk mendukung protokol Address Ownership Proof Protocol (AOPP):

Saya melihat desain protokolnya, ternyata dompet yang mendukung AOPP bisa saja membocorkan privasi pengguna: regulator mungkin mengetahui interkoneksi antara pertukaran kripto yang diatur dan alamat dompet eksternal yang tidak diketahui:

>https://gitlab.com/aopp/address-ownership-proof-protocol

Tidak heran banyak dompet yang berorientasi privasi sangat memperhatikan masukan pengguna dan dengan cepat menghapus dukungan AOPP dari produk mereka. Tapi sejujurnya: Desain protokolnya cukup menarik. Saya perhatikan bahwa beberapa dompet tidak berencana menghapus dukungan untuk AOPP, seperti EdgeWallet. Pendapat mereka adalah bahwa AOPP tidak serta merta mengekspos lebih banyak privasi pengguna, sebaliknya justru membantu meningkatkan sirkulasi mata uang kripto. Di banyak bursa kripto yang diatur, pengguna tidak diperbolehkan menarik dana (Withdraw) ke alamat dompet eksternal tertentu, sebelum ia dapat membuktikan kepemilikannya atas alamat tersebut.

Pada awalnya, dompet perangkat keras (Hardware Wallet) terkenal Trezor menolak untuk menghapus dukungan AOPP. Namun kemudian terpaksa berkompromi dan melakukannya karena tekanan dari komunitas dan pengguna Twitter. 

Seperti yang Anda lihat, ini adalah insiden kecil tetapi bagi sebagian orang, privasi sangatlah penting. Hal ini bukan berarti kita harus melanggar peraturan dan mengabaikan persyaratan kepatuhan. Faktanya, saya yakin perlu adanya kompromi pada tingkat tertentu terhadap persyaratan kepatuhan. Kami tidak akan membahas topik ini secara lebih dalam, silakan cerna isinya dengan cara Anda sendiri.

Sejauh ini, kami telah membahas sebagian besar konten di bagian Keamanan DeFi.

Terlebih lagi, ada juga masalah keamanan yang disebabkan oleh penambahan atau pembaruan di masa mendatang. Kita sering mengatakan "postur keamanan itu dinamis, bukan statis". Misalnya saat ini sebagian besar tim proyek melakukan audit keamanan dan menampilkan laporan audit keamanan yang bersih. Jika Anda pernah membaca laporan berkualitas baik dengan cermat, Anda akan melihat bahwa laporan ini akan dengan jelas menjelaskan cakupan, jangka waktu, dan pengidentifikasi unik dari konten yang diaudit (misalnya alamat kontrak pintar sumber terbuka yang terverifikasi, atau alamat penerapan di repo GitHub, atau hash dari file kode sumber target). Artinya, laporan tersebut statis, tetapi jika dalam suatu proyek Anda mengamati adanya penyimpangan dari apa yang disebutkan dalam laporan, Anda dapat melihatnya.

### Keamanan NFT

Semua konten keamanan DeFi yang disebutkan sebelumnya dapat diterapkan pada keamanan NFT, dan NFT sendiri memiliki beberapa topik keamanan yang sangat spesifik dan unik, misalnya:

* Keamanan metadata
* Keamanan tanda tangan (signature)

Metadata terutama mengacu pada gambar yang disematkan, gambar bergerak, dan konten lainnya. Disarankan untuk merujuk ke OpenSea pada standar spesifik:

>https://docs.opensea.io/docs/metadata-standards

Ada dua masalah keamanan utama yang mungkin timbul di sini:

* Salah satunya adalah URI yaitu tempat penyimpanan gambar (atau film) berada mungkin tidak dapat dipercaya. Bisa saja berupa layanan terpusat yang dipilih secara acak, di satu sisi tidak ada jaminan ketersediaan, di sisi lain tim proyek bisa memodifikasi gambar sesuka hati, sehingga NFT tidak lagi menjadi "barang koleksi digital" yang tidak dapat diubah. Umumnya disarankan untuk menggunakan solusi penyimpanan terdesentralisasi seperti IPFS, Arweave, dan pilih layanan gateway URI yang terkenal.
* Potensi lainnya adalah potensi kebocoran privasi. Layanan URI yang dipilih secara acak mungkin menangkap informasi dasar pengguna (seperti IP, Agen-Pengguna, dll)

SKeamanan penandatanganan (signing) adalah masalah besar lainnya di sini, dan kami akan mengilustrasikannya di bawah.

### HATI-HATI Saat Penandatanganan (signing)!

Keamanan tanda tangan adalah sesuatu yang ingin saya bahas secara spesifik karena ada BANYAK jebakan. dan Anda harus selalu berhati-hati. Ada beberapa kejadian terutama pada perdagangan NFT. Namun, saya memperhatikan bahwa tidak banyak orang yang memahami cara mempersiapkan diri dan menangani masalah keamanan tersebut. Alasan mendasarnya adalah hanya sedikit orang yang bisa menjelaskan masalahnya dengan cukup jelas atau detail.

Prinsip keamanan NO.1 dan paling penting dalam keamanan tanda tangan adalah: **Apa yang Anda lihat adalah apa yang Anda tandatangani**. Artinya, pesan dalam permintaan tanda tangan yang Anda terima adalah apa yang Anda harapkan setelah penandatanganan (signing). Setelah Anda menandatanganinya, hasilnya harus seperti yang Anda harapkan, bukan sesuatu yang akan Anda sesali.

Beberapa rincian keamanan tanda tangan telah disebutkan di bagian "Dompet Dingin". Jika Anda tidak dapat mengingatnya, saya sarankan Anda mengunjungi kembali bagian itu. Pada bagian ini, kami akan fokus pada aspek lainnya.

Ada beberapa peretasan NFT yang terkenal di OpenSea sekitar tahun 2022. Pada tanggal 20 Februari 2022, terjadi wabah besar (banyak insiden). Akar penyebabnya adalah:

* Pengguna menandatangani permintaan daftar (listing) NFT di OpenSea.
* Hacker melakukan phishing untuk mendapatkan tanda tangan yang relevan dari pengguna.

Sebenarnya tidak sulit bagi Hacker untuk mendapatkan tanda tangan terkait. Hacker perlu 1). menyusun pesan yang akan ditandatangani, 2). meng hash itu, 3). mengelabui pengguna target untuk menandatangani permintaan (ini akan menjadi penandatanganan buta atau "blind signing", yang berarti pengguna tidak benar-benar tahu apa yang mereka tandatangani), 4). dapatkan konten yang ditandatangani dan buat datanya. Pada titik ini, pengguna telah dihack.

Saya akan menggunakan Opensea sebagai contoh (pada kenyataannya, ini bisa berupa pasar NFT APAPUN). Setelah pengguna target mengotorisasi operasi pencatatan (Signing) NFT di pasar, Hacker akan membuat pesan untuk ditandatangani. Setelah melakukan hashing dengan Keccak256, permintaan tanda tangan akan muncul di halaman phishing. Pengguna akan melihat sesuatu seperti berikut:

<img src="res/metamask_sign.jpg" width="360">

Perhatikan baik-baik. Informasi apa saja yang bisa kita peroleh dari jendela popup MetaMask ini? Info Akun dan saldo akun, situs web sumber asal permintaan tanda tangan, pesan yang akan ditandatangani pengguna dan…tidak ada yang lain. Bagaimana pengguna bisa curiga bahwa bencana sedang terjadi? Dan bagaimana mereka bisa menyadari bahwa begitu mereka mengklik tombol "Tanda Tangan", NFT mereka akan dicuri.

Ini sebenarnya adalah contoh penandatanganan buta (blind signing). Pengguna tidak diharuskan masuk ke pasar NFT. Sebaliknya, pengguna dapat tertipu ke situs web phishing mana pun untuk menandatangani pesan tanpa sepenuhnya memahami arti sebenarnya dan konsekuensi dari tanda tangan tersebut. Sayangnya, Hacker mengetahuinya. Sebagai pengguna, perlu diingat: JANGAN PERNAH BLIND SIGN APA PUN. OpenSea dulunya mempunyai masalah penandatanganan buta, dan mereka memperbaikinya dengan mengadopsi EIP-712 setelah 20 Februari 2022. Namun, tanpa penandatanganan buta, pengguna masih bisa ceroboh dan diretas dengan cara lain.

Alasan paling penting mengapa hal ini terjadi adalah penandatanganan tidak dibatasi untuk mengikuti kebijakan asal yang sama pada browser. Anda dapat memahaminya sebagai berikut: kebijakan asal yang sama dapat memastikan bahwa suatu tindakan hanya terjadi pada domain tertentu dan tidak akan melintasi domain, kecuali tim proyek dengan sengaja menginginkan terjadinya penyeberangan domain. Jika penandatanganan mengikuti kebijakan asal yang sama, bahkan jika pengguna menandatangani permintaan tanda tangan yang dihasilkan oleh domain non-target, Hacker tidak dapat menggunakan tanda tangan tersebut untuk menyerang di bawah domain target. Saya akan berhenti di sini sebelum membahas lebih detail. Saya telah memperhatikan usulan baru mengenai peningkatan keamanan di tingkat protokol, dan saya berharap situasi ini dapat diperbaiki secepatnya.

Kami telah menyebutkan sebagian besar format serangan utama yang dapat terjadi saat menandatangani (signing) pesan, namun sebenarnya ada beberapa varian. Betapapun berbedanya penampilan mereka, mereka mengikuti pola yang sama. Cara terbaik untuk memahaminya adalah dengan mereproduksi sendiri serangan dari awal hingga akhir, atau bahkan membuat beberapa metode serangan unik. Misalnya, serangan permintaan tanda tangan yang disebutkan di sini sebenarnya berisi banyak detail, seperti bagaimana membuat pesan yang akan ditandatangani, dan apa yang sebenarnya dihasilkan setelah penandatanganan? Apakah ada metode otorisasi selain "Setujui" (ya, misalnya: peningkatan Tunjangan). Ya, akan terlalu teknis jika kita memperluasnya di sini. Hal baiknya adalah Anda sudah memahami pentingnya menandatangani pesan.

Pengguna dapat mencegah serangan tersebut pada sumbernya dengan membatalkan otorisasi/persetujuan. Berikut ini adalah beberapa alat (tools) terkenal yang dapat Anda gunakan.

* Persetujuan Token
    >https://etherscan.io/tokenapprovalchecker<br>
    >Ini adalah alat untuk pemeriksaan otorisasi dan pembatalan yang disediakan oleh browser resmi Ethereum. Blockchain lain yang kompatibel dengan EVM memiliki sesuatu yang serupa karena browser blockchain mereka pada dasarnya dikembangkan oleh Etherscan. Misalnya:<br>
    >https://bscscan.com/tokenapprovalchecker<br>
    >https://hecoinfo.com/tokenapprovalchecker<br>
    >https://polygonscan.com/tokenapprovalchecker<br>
    >https://snowtrace.io/tokenapprovalchecker<br>
    >https://cronoscan.com/tokenapprovalchecker

* Revoke.cash
    >https://revoke.cash/<br>
    >Sebuah projek OG dengan ketenaran yang bagus & mendukung Multi-rantai dengan kekuatan yang semakin meningkat

* Rabby extension wallet
    >https://rabby.io/<br>
    >Salah satu dompet yang sering kami kolaborasi. Jumlah blockchain yang kompatibel dengan EVM di mana mereka menyediakan fungsi "pemeriksaan dan pembatalan otorisasi" adalah yang terbanyak yang pernah saya lihat

:warning:**Catatan**: Jika Anda ingin pemahaman yang lebih komprehensif dan mendalam tentang SIGNATURE SECURITY, silakan periksa ekstensi pada penambahan repositori berikut sebagai referensi:

>https://github.com/evilcos/darkhandbook<br>
>Memang benar bahwa pengetahuan tentang KEAMANAN TANDA TANGAN cukup menantang bagi pemula. Repositori ini mengkompilasi konten yang relevan, dan membacanya dengan cermat akan membantu Anda memahami pengetahuan keamanan. Dengan demikian, Anda tidak akan kesulitan lagi. (Jika Anda bisa membaca dan memahami semuanya, saya yakin pengetahuan keamanan tidak lagi sulit bagi Anda :)

### HATI-HATI Dengan Permintaan Tanda Tangan karena "ini tampak biasa saja atau normal"!

Saya ingin menyebutkan secara khusus risiko lain: **risiko kontra-intuitif**.

Apa itu kontra-intuitif? Misalnya, Anda sudah sangat familiar dengan Ethereum, dan telah menjadi OG dari semua jenis DeFi dan NFT. Saat pertama kali memasuki ekosistem Solana, Anda mungkin akan menemukan beberapa situs phishing serupa. Anda mungkin merasa sangat siap sehingga Anda mulai berpikir, "Saya telah melihatnya ribuan kali di ekosistem Ethereum dan bagaimana saya bisa tertipu?"

Sementara itu, Hacker akan senang karena Anda telah tertipu. Orang-orang yang terlalu mengikuti perasaan intuitif mereka itu membuat mereka ceroboh. Ketika terjadi serangan seperti ini, orang-orang akan jatuh ke dalam perangkap.

Oke, mari kita lihat kasus nyata yang memanfaatkan kontra-intuitif.

<img src="res/solana_nft_phishing.jpg" width="800">

Pertama-tama, sebuah peringatan: Otorisasi phishing di Solana jauh lebih kejam. Contoh di atas terjadi pada tanggal 5 Maret 2022. Penyerang mengirimkan NFT ke pengguna secara berkelompok atau batch (Gambar 1). Pengguna memasuki situs web target melalui tautan dalam deskripsi NFT yang dijatuhkan via airdrop (www_officialsolanarares_net) dan menghubungkan dompet mereka (Gambar 2). Setelah mereka mengklik tombol "Mint" di halaman tersebut, jendela persetujuan muncul (Gambar 3). Perhatikan bahwa tidak ada pemberitahuan atau pesan khusus di jendela pop up saat ini. Setelah disetujui, semua SOL di dompet akan ditransfer.

Saat pengguna mengklik tombol "Setujui", mereka sebenarnya berinteraksi dengan kontrak pintar berbahaya yang digunakan oleh penyerang:
*3VtjHnDuDD1QreJiYNziDsdkeALMT6b2F9j3AXdL4q8v*

Tujuan akhir dari kontrak pintar berbahaya ini adalah untuk memulai "Transfer SOL", yang mentransfer hampir semua SOL pengguna. Dari analisis data on-chain, perilaku phishing berlanjut selama beberapa hari, dan jumlah korban terus meningkat selama periode tersebut.

Ada dua lubang jebakan dari contoh ini yang perlu Anda perhatikan:
1. Setelah pengguna menyetujuinya, kontrak pintar berbahaya dapat mentransfer aset asli pengguna (dalam hal ini SOL). Hal ini tidak mungkin dilakukan di Ethereum. Otorisasi phishing pada Ethereum hanya dapat memengaruhi token lain tetapi tidak pada aset asli ETH. Ini adalah bagian kontra-intuitif yang akan membuat kewaspadaan pengguna menjadi lebih rendah.
2. Dompet paling terkenal di Solana, Phantom, memiliki celah dalam mekanisme keamanannya sehingga tidak mengikuti prinsip "apa yang Anda lihat adalah apa yang Anda tandatangani" (kami belum menguji dompet lain), dan tidak memberikan peringatan risiko yang cukup kepada pengguna. Hal ini dapat dengan mudah menciptakan titik buta keamanan yang merugikan pengguna.

### Beberapa Metodologi Penyerangan Tingkat Lanjut

Sebenarnya ada banyak metodologi penyerangan tingkat lanjut, namun sebagian besar dianggap sebagai phishing dari sudut pandang publik. Namun, beberapa di antaranya bukan serangan phishing biasa. Misalnya:

>https://twitter.com/Arthur_0x/status/1506167899437686784

Hacker mengirim email phishing dengan lampiran berikut:
>A Huge Risk of Stablecoin (Protected).docx

Sejujurnya, ini adalah dokumen yang menarik. Namun, begitu dibuka komputer pengguna akan ditanamkan Trojan (umumnya melalui makro Office atau eksploitasi zero day/ 1 hari), yang biasanya berisi fungsi-fungsi berikut:

* Mengumpulkan segala macam kredensial, misalnya terkait browser, atau terkait SSH, dll. Dengan cara ini, hacker dapat memperluas akses mereka ke layanan lain dari pengguna target. Oleh karena itu, setelah infeksi, pengguna umumnya disarankan tidak hanya membersihkan perangkat target, tetapi juga izin akun yang relevan.
* Keylogger, khususnya menargetkan informasi sensitif yang muncul sementara seperti kata sandi.
* Mengumpulkan tangkapan layar (screenshot) yang relevan, file sensitif, dll.
* Jika itu adalah ransomware, semua file di sistem target akan dienkripsi dengan kuat, dan menunggu korban membayar uang tebusan, biasanya dengan bitcoin. Namun dalam kasus ini bukan ransomware yang memiliki perilaku lebih jelas & intrusive serta niat yang lugas.

Selain itu, Trojan yang menargetkan industri kripto akan disesuaikan secara khusus untuk mengumpulkan informasi sensitif dari dompet atau bursa (CEX) terkenal, untuk mencuri dana pengguna. Menurut analisis profesional, Trojan yang disebutkan di atas akan melakukan serangan yang ditargetkan on Metamask:

>https://securelist.com/the-bluenoroff-cryptocurrency-hunt-is-still-on/105488/

Trojan akan menggantikan MetaMask (asli) pengguna dengan yang palsu dan memiliki backdoor. MetaMask yang memiliki pintu belakang (backdoor) pada dasarnya berarti bahwa dana apa pun yang Anda simpan di dalamnya bukan lagi milik Anda. Bahkan jika Anda menggunakan dompet perangkat keras, MetaMask palsu ini akan berhasil mencuri dana Anda dengan memanipulasi alamat tujuan atau informasi jumlah.

Pendekatan ini dirancang khusus untuk target terkenal dengan alamat dompet yang diketahui. Apa yang saya perhatikan adalah banyak orang yang terlalu sombong untuk mencegah diri mereka diretas. Setelah peretasan, banyak yang akan belajar dari pengalaman tersebut, melakukan peninjauan menyeluruh, mendapatkan peningkatan yang signifikan, dan juga menjalin kerja sama dan persahabatan jangka panjang dengan profesional atau lembaga keamanan tepercaya. Namun, selalu ada pengecualian di dunia ini. Beberapa orang atau proyek terus diretas berulang kali. Jika setiap kali hal ini terjadi karena sesuatu yang belum pernah ditemui sebelumnya, saya akan sangat menghormati mereka dan menyebut mereka pionir. Kemungkinan besar mereka akan sukses seiring berjalannya waktu. Sayangnya banyak insiden yang terjadi akibat kesalahan bodoh dan berulang-ulang yang sebenarnya bisa dihindari dengan mudah. Saya menyarankan untuk menjauhi proyek-proyek ini.

Sebagai perbandingan, serangan phishing massal tersebut tidak canggih sama sekali. Penyerang akan menyiapkan sekumpulan nama domain yang serupa dan menyebarkan muatannya dengan membeli akun, pengikut, dan retweet di Twitter (kini "X") atau platform sosial lainnya. Jika dikelola dengan baik, banyak orang yang akan terjerumus ke dalam perangkap. Sebenarnya tidak ada yang istimewa dalam serangan phishing semacam ini, dan biasanya penyerang akan secara brutal membuat pengguna mengotorisasi token (termasuk NFT) untuk mentransfernya.

Ada jenis serangan tingkat lanjut lainnya, misalnya menggunakan teknik seperti XSS, CSRF, Reverse Proxy untuk memperlancar proses serangan. Saya tidak akan menguraikan semuanya di sini, kecuali satu kasus yang sangat khusus (Serangan Cloudflare Man-in-the-Middle) yang merupakan salah satu skenario di Reverse Proxy. Ada serangan nyata yang menyebabkan kerugian finansial dengan menggunakan metode yang sangat rahasia ini.

Masalahnya di sini bukanlah Cloudflare itu sendiri yang jahat atau diretas. Sebaliknya, akun Cloudflare tim proyeklah yang disusupi. Umumnya prosesnya seperti ini: Jika Anda menggunakan Cloudflare, Anda akan melihat modul "Pekerja" (worker) ini di dashboard, yang deskripsi resminya adalah:

>Membangun aplikasi tanpa server dan menerapkannya secara instan di seluruh dunia, mencapai kinerja, keandalan, dan skala yang luar biasa. Untuk detailnya, silakan merujuk ke
>https://developers.cloudflare.com/workers/

Saya membuat halaman pengujian sejak lama:

>https://xssor.io/s/x.html

Saat Anda mengunjungi halaman tersebut akan ada jendela pop-up yang mengatakan:

>xssor.io, Dibajak oleh Cloudflare.

Faktanya, pop-up ini, dan bahkan seluruh konten x.html, bukan milik dokumen itu sendiri. Semuanya disediakan oleh Cloudflare. Mekanismenya ditunjukkan di bawah ini:

<img src="res/cloudflare_worker.png" width="800">

Indikasi cuplikan kode (snippet) di tangkapan layar sangat sederhana: Jika saya adalah Hacker dan saya telah mengontrol akun Cloudflare Anda, saya dapat menggunakan Worker untuk memasukkan skrip berbahaya yang sewenang-wenang ke halaman web mana pun. Dan sangat sulit bagi pengguna untuk menyadari bahwa halaman web target telah dibajak dan dirusak, karena tidak akan ada peringatan kesalahan (seperti kesalahan sertifikat HTTPS). Bahkan tim proyek tidak akan dengan mudah mengidentifikasi masalah tanpa harus menghabiskan banyak waktu untuk memeriksa keamanan server dan personel mereka. Pada saat mereka menyadari bahwa itu adalah Cloudflare Workers, kerugiannya sudah sangat besar.

Cloudflare sebenarnya adalah alat yang bagus. Banyak situs web atau aplikasi web yang menggunakannya sebagai firewall aplikasi web, solusi anti DDoS, CDN global, reverse proxy, dll. Karena ada versi gratisnya, mereka memiliki basis pelanggan yang besar. Alternatifnya, ada layanan seperti Akaimai dll.

Pengguna harus memperhatikan keamanan akun tersebut. Masalah keamanan akun muncul seiring dengan munculnya Internet. Ini adalah topik umum di dunia sehingga hampir semua orang membicarakannya di mana-mana, namun masih banyak orang yang diretas karenanya. Beberapa penyebab utama mungkin adalah mereka tidak menggunakan kata sandi unik yang kuat untuk layanan penting (Pengelola kata sandi seperti 1Password tidak begitu populer), beberapa mungkin karena mereka tidak repot-repot mengaktifkan otentikasi 2 faktor (2FA), atau mungkin mereka bahkan tidak mengetahui bahwa ada itu. Belum lagi untuk beberapa layanan tertentu, kata sandi harus direset setidaknya setiap tahun.

Baiklah, ini akan menjadi akhir dari bagian ini. Anda hanya perlu memahami bahwa ini memang hutan gelap (dark forest), dan Anda harus mengetahui sebanyak mungkin metodologi penyerangan. Setelah melihat cukup banyak di atas kertas, jika Anda setidaknya pernah jatuh ke dalam perangkap satu atau dua kali, Anda dapat menganggap diri Anda sebagai profesional keamanan amatir (yang bagaimanapun juga akan menguntungkan diri Anda sendiri).

## Perlindungan Privasi Tradisional

Selamat, Anda berhasil mencapai bagian ini. Perlindungan privasi tradisional adalah sebuah topik lama: Inilah artikel yang saya tulis pada tahun 2014.

>Anda harus mempelajari beberapa trik untuk melindungi diri Anda di era pelanggaran privasi.<br>
>https://evilcos.me/yinsi.html

Membaca ulang artikel ini, meskipun ini adalah artikel entry level pada tahun 2014, namun sebagian besar saran di dalamnya masih relevan. Setelah membaca artikel ini lagi, saya akan memperkenalkan sesuatu yang baru di sini: sebenarnya, perlindungan privasi berkaitan erat dengan keamanan . Privasi tradisional adalah landasan keamanan. Bagian ini mencakup kunci pribadi Anda yang merupakan bagian dari privasi. Jika batu pijakan tidak aman, privasi batu pijakan itu tidak ada artinya, maka bangunan yang berdiri diatasnya akan menjadi rapuh seperti istana pasir.

Dua sumber daya berikut sangat direkomendasikan:

>PERTAHANAN DIRI PENGAWASAN<br>
>TIPS, ALAT DAN CARA KOMUNIKASI ONLINE LEBIH AMAN<br>
>https://ssd.eff.org/

SURVEILLANCE SELF-DEFENSE adalah kependekan dari SSD. Diluncurkan oleh Electronic Frontier Foundation (EFF) yang terkenal, yang secara khusus telah mengeluarkan pedoman yang relevan untuk memberi tahu Anda cara menghindari "big brother" mengawasi Anda di dunia pemantauan Internet, yang mencakup beberapa alat yang berguna (seperti Tor, WhatsApp, Signal, PGP, dll.)

>Panduan Privasi: Lawan Pengawasan dengan Alat Enkripsi dan Privasi<br>
>https://www.privacytools.io/

Situs web di atas berisi daftar lengkap sejumlah alat. Ini juga merekomendasikan beberapa CEX kripto, dompet, dll. Namun, perlu dicatat bahwa saya tidak menggunakan banyak alat yang terdaftar di situs web, karena saya punya cara saya sendiri. Oleh karena itu, sebaiknya Anda juga mengembangkan cara Anda sendiri, dengan membandingkan dan meningkatkan secara terus menerus.

Berikut adalah beberapa hal penting dari alat yang saya sarankan untuk Anda gunakan.

### Sistem Operasi

Windows 10 Edition (dan lebih tinggi) dan macOS keduanya merupakan opsi yang aman. Jika Anda memiliki kemampuan, Anda dapat memilih Linux, seperti Ubuntu, atau bahkan yang sangat berfokus pada keamanan & privasi seperti Tails, atau Whonix.

Pada topik Sistem Operasi, prinsip keamanan yang paling jelas adalah: perhatikan baik-baik pembaruan sistem, dan terapkan secepatnya jika tersedia. Kemampuan untuk menguasai Sistem Operasi adalah yang berikutnya. Mungkin ada yang bertanya, apa sih yang perlu Anda pelajari untuk menguasai Sistem Operasi seperti Windows atau MacOS? Bukankah itu hanya sekedar mengklik? Sebenarnya itu masih jauh dari cukup. Bagi pengguna pemula, perangkat lunak antivirus yang bagus, seperti Kaspersky, BitDefender, adalah suatu keharusan, dan keduanya tersedia di MacOS.

Lalu, jangan lupa tentang keamanan pengunduhan, yang telah saya sebutkan sebelumnya. Anda akan menghilangkan sebagian besar risiko, jika Anda tidak mengunduh dan menginstal program secara sembarangan.

Selanjutnya, pikirkan apa yang akan Anda lakukan jika komputer Anda hilang atau dicuri. Memiliki kata sandi booting jelas tidak cukup baik. Jika enkripsi disk tidak diaktifkan, pelaku kejahatan dapat langsung mengeluarkan harddisk dan mengambil data di dalamnya. Jadi saran saya adalah enkripsi disk harus diaktifkan untuk komputer penting.

>https://docs.microsoft.com/en-us/windows/security/encryption-data-protection<br>
>https://support.apple.com/en-us/HT204837

Kami juga memiliki alat yang kuat dan legendaris seperti VeraCrypt (sebelumnya TrueCrypt), silakan mencobanya jika Anda tertarik:

>https://veracrypt.fr/

Anda dapat melangkah lebih jauh dengan mengaktifkan kata sandi BIOS atau firmware. Saya telah melakukannya sendiri tetapi itu sepenuhnya terserah pilihan Anda sendiri. Ingat saja: jika Anda melakukannya, ingatlah kata sandinya dengan sangat jelas, atau tidak ada yang bisa membantu Anda. Saya cukup beruntung telah jatuh ke dalam lubang kelinci sebelumnya, yang menghabiskan biaya sebuah laptop, beberapa kripto, dan waktu seminggu. Di sisi lain, ini juga merupakan pengalaman belajar yang sangat bagus.

### Telepon Seluler (mobile phone)

Saat ini iPhone dan Android adalah dua kategori ponsel utama. Saya dulunya adalah penggemar berat BlackBerry, namun kejayaannya memudar seiring berjalannya waktu. Di masa lalu, kondisi keamanan ponsel Android sangat mengkhawatirkan saya. Di satu sisi masih dalam tahap awal, di sisi lain versinya sangat terfragmentasi, masing-masing merek pasti memiliki versi Android fork nya masing-masing. Tapi sekarang segalanya telah membaik.

Di ponsel kita juga perlu memperhatikan pembaruan keamanan dan keamanan unduhan. Selain itu, perhatikan hal-hal berikut ini:

* Jangan melakukan jailbreak/root ponsel Anda, hal ini tidak diperlukan kecuali Anda melakukan riset keamanan yang relevan. Jika Anda melakukannya untuk perangkat lunak bajakan, hal ini sangat bergantung pada seberapa baik Anda dapat menguasai keterampilan tersebut.
* Jangan mengunduh aplikasi dari toko aplikasi tidak resmi.
* Jangan lakukan itu kecuali Anda tahu apa yang Anda lakukan. Belum lagi banyak aplikasi palsu yang beredar di toko aplikasi resmi.
* Prasyarat untuk menggunakan fungsi sinkronisasi Cloud resmi adalah Anda harus memastikan akun Anda aman, jika tidak, jika akun Cloud disusupi, ponsel juga akan disusupi.

Secara pribadi saya lebih mengandalkan iPhone. Dan Anda memerlukan setidaknya dua akun iCloud: satu di China dan satu di luar negeri. Anda akan memerlukannya untuk menginstal aplikasi dengan batasan regional yang berbeda. (yang mungkin terdengar sangat aneh, tapi selamat datang di kenyataan)

### Jaringan

Keamanan jaringan Dulunya masalah ini sangat menyusahkan, namun sudah ada perbaikan yang signifikan dalam beberapa tahun terakhir, terutama sejak penerapan kebijakan HTTPS Everywhere secara massal.

Jika terjadi serangan pembajakan jaringan (serangan man-in-the-middle) yang sedang berlangsung, akan ada peringatan kesalahan sistem yang sesuai. Namun selalu ada pengecualian, jadi ketika Anda punya pilihan, gunakan opsi yang lebih aman. Misalnya, jangan menyambung ke jaringan Wi-Fi yang tidak dikenal kecuali jaringan 4G/5G yang lebih populer & aman tidak tersedia atau tidak stabil.

### Perambah

Browser yang paling populer adalah Chrome dan Firefox, di bidang kripto beberapa akan menggunakan Brave juga. Browser terkenal ini memiliki tim yang kuat dan akan ada pembaruan keamanan yang tepat waktu. Topik keamanan browser sangat luas. Berikut beberapa tips yang perlu Anda waspadai:

* Perbarui (update) secepat mungkin, jangan ambil risiko.
* Jangan gunakan ekstensi jika tidak diperlukan. Jika ya, buatlah keputusan berdasarkan ulasan pengguna, jumlah pengguna, perusahaan pengelola, dll, dan perhatikan izin yang diminta. Pastikan Anda mendapatkan ekstensi dari toko aplikasi resmi browser Anda.
* Beberapa browser dapat digunakan secara paralel, dan sangat disarankan agar Anda melakukan operasi penting di satu browser, dan menggunakan browser lain untuk operasi yang lebih rutin dan kurang penting.
* Berikut adalah beberapa ekstensi terkenal yang berfokus pada privasi (seperti uBlock Origin, HTTPS Everywhere, ClearURLs, dll.), silakan mencobanya.

Khususnya di Firefox, saya juga akan menggunakan ekstensi OG seperti NoScript, yang memiliki catatan terbukti dalam menangkis muatan JavaScript berbahaya. Saat ini browser menjadi semakin aman karena mereka menambahkan dukungan untuk hal-hal seperti kebijakan asal yang sama, CSP, kebijakan keamanan Cookie, header keamanan HTTP, kebijakan keamanan ekstensi, dll. Oleh karena itu, kebutuhan untuk menggunakan alat seperti NoScript menjadi lebih kecil dan lebih kecil, silakan melihatnya jika tertarik.

### Pengelola Kata Sandi (password manager)

Jika Anda belum pernah menggunakan pengelola kata sandi, mungkin Anda tidak tahu kenyamanan menggunakannya, atau Anda memiliki istana ingatan Anda sendiri yang kuat. Risiko gangguan memori otak juga telah disebutkan sebelumnya, salah satunya adalah waktu akan melemahkan atau mengganggu daya ingat Anda; yang lainnya adalah Anda mungkin mengalami kecelakaan. Apa pun kasusnya, saya tetap menyarankan Anda menggunakan pengelola kata sandi yang sesuai dengan memori otak Anda, gunakan yang terkenal seperti 1Password, Bitwarden, dll.

Saya tidak perlu membahas bagian ini terlalu banyak, ada begitu banyak tutorial terkait secara online, mudah untuk memulainya bahkan tanpa memerlukan tutorial.

Yang perlu saya ingatkan di sini adalah:

* Jangan pernah lupa kata sandi utama Anda, dan jaga keamanan informasi akun Anda, jika tidak semuanya akan hilang.
* Pastikan email Anda aman. Jika email Anda disusupi, informasi sensitif di pengelola kata sandi Anda mungkin tidak disusupi secara langsung, namun pelaku kejahatan mempunyai kemampuan untuk menghancurkannya.
* Saya telah memverifikasi keamanan alat yang saya sebutkan (seperti 1Password), dan telah mengamati dengan cermat insiden keamanan yang relevan, ulasan pengguna, berita, dll. Namun saya tidak dapat menjamin bahwa alat ini benar-benar aman, dan tidak ada peristiwa black swan yang terjadi. akan terjadi di masa depan pada mereka.
 
Satu hal yang saya kagumi adalah pengenalan dan deskripsi halaman keamanan 1Password, misalnya.
>https://1password.com/security/

Halaman ini berisi konsep desain keamanan, sertifikat privasi dan keamanan yang relevan, kertas putih desain keamanan, laporan audit keamanan, dll. Tingkat transparansi dan keterbukaan ini juga memfasilitasi validasi yang diperlukan dalam industri. Semua tim proyek harus belajar dari ini.

Bitwarden melangkah lebih jauh karena sepenuhnya open source, termasuk sisi server, sehingga siapa pun dapat memvalidasi, mengaudit, dan berkontribusi. Sekarang kamu paham? Maksud dari 1Password dan Bitwarden sangat jelas: 

>Saya sangat aman dan saya khawatir tentang privasi. Saya tidak hanya mengatakannya sendiri, otoritas pihak ketiga juga mengatakannya. Jangan ragu untuk mengaudit saya, dan untuk memudahkan audit Anda, saya menghabiskan banyak upaya untuk bersikap terbuka jika memungkinkan. Jika apa yang saya lakukan tidak sesuai dengan apa yang saya katakan, mudah untuk menantang saya. Dan ini disebut Keyakinan Keamanan.

### Otentikasi Dua Faktor (2FA)

Berbicara tentang keamanan identitas Anda di Internet, lapisan pertama bergantung pada kata sandi, lapisan kedua bergantung pada otentikasi dua faktor, dan lapisan ketiga bergantung pada kemampuan pengendalian risiko proyek target itu sendiri. Saya tidak bisa mengatakan bahwa otentikasi dua faktor adalah suatu keharusan. Misalnya, jika Anda menggunakan dompet terdesentralisasi, satu lapisan kata sandi sudah cukup mengganggu (sekarang pada dasarnya mendukung identifikasi biometrik seperti pengenalan wajah atau sidik jari untuk meningkatkan pengalaman pengguna), tidak ada yang mau menggunakan 2FA. Namun dalam platform terpusat, Anda harus menggunakan 2FA. Siapa pun dapat mengakses platform (CEX) terpusat, dan jika kredensial Anda dicuri, akun Anda akan dibobol dan dana Anda akan hilang. Sebaliknya, kata sandi untuk dompet terdesentralisasi Anda hanyalah otentikasi lokal, meskipun hacker mendapatkan kata sandinya, mereka masih perlu mendapatkan akses ke perangkat tempat dompet Anda berada.

Sekarang Anda melihat perbedaannya?Beberapa alat otentikasi dua faktor (2FA) yang terkenal meliputi: Google Authenticator, Microsoft Authenticator, dll. Tentu saja, jika Anda menggunakan pengelola kata sandi (seperti 1Password), alat tersebut juga dilengkapi dengan modul 2FA , yang sangat berguna. Ingatlah selalu untuk membuat cadangan, karena kehilangan 2FA bisa merepotkan.

Selain itu, otentikasi dua faktor juga bisa menjadi konsep yang lebih luas. Misalnya, ketika pengidentifikasi akun dan kata sandi digunakan untuk masuk ke platform target, pengidentifikasi akun kami biasanya berupa email atau nomor ponsel. Saat ini, kotak surat (SMS) atau nomor ponsel dapat digunakan sebagai 2FA untuk menerima kode verifikasi. Namun tingkat keamanan metode ini kurang baik. Misalnya, jika kotak surat disusupi atau kartu SIM dibajak, atau layanan pihak ketiga yang digunakan untuk mengirim email dan pesan teks diretas, maka kode verifikasi yang dikirim oleh platform juga akan terungkap.

### HATI-HATI Berinternet (selalu jaga keamananmu)

Untuk alasan kebijakan, saya tidak terlalu banyak membicarakan hal ini, cukup pilih salah satu solusi yang sudah diketahui. Segalanya akan lebih terkendali jika Anda dapat membuat solusi Anda sendiri. Bagaimanapun, titik awal kami adalah menjelajahi Internet secara nyaman dan aman.

Jika Anda tidak menggunakan solusi yang dibuat sendiri, Anda tidak dapat sepenuhnya mengesampingkan kemungkinan serangan man-in-the-middle. Seperti disebutkan sebelumnya, situasi keamanan Internet tidak seburuk dulu, terutama setelah penerapan kebijakan HTTPS Everywhere secara massal. Namun, sebagian dari rasa keamanan itu mungkin hanya tampak di permukaan saja, dan sudah ada arus bawah permukaan yang tidak mudah terlihat. Sejujurnya, saya tidak punya solusi jitu untuk ini. Membangun solusi Anda sendiri tidaklah mudah, namun hal ini pasti sepadan. Dan jika tidak bisa, pastikan Anda memeriksa menggunakan berbagai sumber dan memilih sumber yang memiliki reputasi baik dan sudah ada sejak lama.

### Email

Email adalah landasan identitas berbasis web kami. Kami menggunakan email untuk mendaftar ke banyak layanan. Hampir semua layanan email yang kami gunakan gratis. Tampaknya seperti udara, dan menurut Anda itu tidak akan hilang. Bagaimana jika suatu saat layanan Email Anda hilang, maka semua layanan lain yang bergantung padanya akan berada dalam situasi yang agak canggung. Situasi ekstrim ini sebenarnya bukan tidak mungkin terjadi jika terjadi perang, bencana alam, dll. Tentu saja, jika situasi ekstrim ini terjadi, Email tidak akan terlalu penting bagi Anda dibandingkan kelangsungan hidup.

Ketika berbicara tentang penyedia layanan Email, Anda harus memilih dari raksasa teknologi, seperti Gmail, Outlook, atau QQ Email. Kebetulan penelitian keamanan saya sebelumnya mencakup bidang ini. Overall keamanan kotak surat (Email) ini cukup baik. Namun tetap saja Anda harus berhati-hati terhadap serangan Email phishing. Anda tidak perlu berurusan dengan setiap Email, terutama tautan dan lampiran yang tertanam, tempat Trojan mungkin disembunyikan.

Jika Anda menemukan serangan yang sangat canggih terhadap penyedia layanan Email Anda, Anda sendirian.

Selain layanan email dari raksasa teknologi ini, jika Anda sangat mengkhawatirkan privasi, Anda dapat melihat dua layanan email terkenal yang ramah privasi ini: ProtonMail dan Tutanota. Saran saya adalah untuk memisahkan kotak surat ramah Privasi ini dari penggunaan sehari-hari, dan hanya menggunakannya untuk layanan yang memerlukan perhatian khusus terhadap privasi. Anda juga perlu secara rutin menggunakan layanan Email gratis untuk mencegah akun Anda ditangguhkan karena tidak aktif dalam waktu lama.

### Kartu SIM

Kartu SIM dan nomor ponsel juga merupakan identitas dasar yang sangat penting dalam banyak kasus, seperti halnya email. Dalam beberapa tahun terakhir, operator besar di negara kita telah melakukan pekerjaan yang sangat baik dalam melindungi keamanan nomor ponsel. Misalnya, terdapat protokol keamanan & proses verifikasi yang ketat untuk pembatalan dan penerbitan ulang kartu SIM, dan semuanya dilakukan di lokasi. Mengenai topik serangan kartu SIM, izinkan saya memberi Anda sebuah contoh:

Pada tahun 2019, akun Coinbase seseorang mengalami Serangan Port SIM (serangan intrusif via kartu SIM), dan sayangnya mengakibatkan kehilangan lebih dari 100.000 dolar AS mata uang kripto. Proses serangannya kira-kira sebagai berikut:

Penyerang memperoleh informasi privasi pengguna target melalui rekayasa sosial dan metode lainnya, dan menipu operator telepon seluler untuk memberinya kartu SIM baru, dan kemudian dia dengan mudah mengambil alih akun Coinbase pengguna target melalui nomor ponsel yang sama. SIM telah ditransfer, yang sangat merepotkan. Sangat merepotkan jika kartu SIM Anda ditransfer oleh penyerang, karena saat ini banyak layanan online yang menggunakan nomor ponsel kami sebagai faktor otentikasi langsung atau 2FA. Ini adalah mekanisme otentikasi yang sangat terpusat, dan nomor ponsel menjadi titik lemahnya.

Untuk analisis lebih rinci, silakan merujuk ke:
>https://medium.com/coinmonks/the-most-expensive-lesson-of-my-life-details-of-sim-port-hack-35de11517124

Saran pertahanan untuk ini sebenarnya sederhana: aktifkan solusi 2FA yang terkenal.

Kartu SIM mempunyai risiko lain: yaitu, jika ponsel hilang atau dicuri, akan sangat memalukan jika orang jahat dapat mengeluarkan kartu SIM tersebut dan menggunakannya. Inilah yang saya lakukan: Aktifkan kata sandi kartu SIM (kode PIN), jadi setiap kali saya menghidupkan telepon atau menggunakan kartu SIM di perangkat baru, saya harus memasukkan kata sandi yang benar. Silakan tanyakan pada Google untuk mengetahui detailnya. Ini pengingat dari saya: jangan lupa password ini, jika tidak maka akan sangat merepotkan.

### GPG

Banyak konten di bagian ini telah disebutkan di bagian sebelumnya, dan saya ingin menambahkan lebih banyak konsep dasar di sini. Terkadang Anda akan menemukan nama yang mirip seperti PGP, OpenPGP, dan GPG. Cukup bedakan saja sebagai berikut:

* PGP, kependekan dari Pretty Good Privacy, adalah perangkat lunak enkripsi komersial berusia 30 tahun yang kini berada di bawah payung Symantec.
* OpenPGP adalah standar enkripsi yang berasal dari PGP.
* GPG, nama lengkapnya GnuPG, adalah perangkat lunak enkripsi sumber terbuka berdasarkan standar OpenPGP.

Inti mereka serupa, dan dengan GPG Anda kompatibel dengan yang lain. Di sini saya sangat menyarankan sekali lagi: Dalam enkripsi keamanan, jangan coba ngide ; GPG, jika digunakan dengan cara yang benar, dapat meningkatkan tingkat keamanan secara signifikan!

### Pemisahan (segregation)

Nilai inti di balik prinsip keamanan segregasi adalah pola pikir nol kepercayaan. Anda harus memahami bahwa sekuat apa pun kita, cepat atau lambat kita akan terkena Hack, tidak peduli apakah itu oleh Hacker eksternal, orang dalam (insider), atau kecerobohan diri kita sendiri. Saat di Hack, stop loss harus menjadi langkah pertama. Kemampuan menghentikan kerugian diabaikan oleh banyak orang, dan itulah sebabnya mereka diretas berulang kali. Akar permasalahannya adalah tidak adanya desain keamanan, terutama metode langsung seperti segregasi

Praktik pemisahan yang baik dapat memastikan bahwa jika terjadi insiden keamanan, Anda hanya kehilangan aset yang terkait langsung dengan target yang disusupi, tanpa memengaruhi aset lainnya.

Misalnya:
* Jika praktik keamanan kata sandi Anda baik, ketika salah satu akun Anda diretas, kata sandi yang sama tidak akan membahayakan akun lainnya.
* Jika mata uang kripto Anda tidak disimpan dalam satu set seed phrase, Anda tidak akan kehilangan segalanya jika Anda masuk ke dalam jebakan.
* Jika komputer Anda terinfeksi, untungnya ini hanya komputer yang digunakan untuk aktivitas biasa, dan tidak ada hal penting di dalamnya. Jadi Anda tidak perlu panik, karena menginstal ulang komputer akan menyelesaikan sebagian besar masalah. Jika Anda pandai menggunakan mesin virtual, segalanya akan menjadi lebih baik, karena Anda cukup memulihkan snapshot. Peralatan mesin virtual yang bagus adalah: VMware, Parallels.
* Ringkasnya, Anda dapat memiliki setidaknya dua akun, dua alat, dua perangkat, dll. Bukan tidak mungkin untuk sepenuhnya membuat identitas virtual independen setelah Anda memahaminya.

Saya telah menyebutkan pendapat yang lebih ekstrim sebelumnya: privasi bukan untuk kita lindungi, privasi harus dikontrol.

Alasan sudut pandang ini adalah: dalam lingkungan Internet saat ini, privasi sebenarnya telah dibocorkan secara serius. Untungnya, peraturan terkait privasi telah semakin banyak diadopsi dalam beberapa tahun terakhir, dan masyarakat semakin memberikan perhatian. Segalanya memang berjalan ke arah yang benar. Namun sebelum itu, bagaimanapun juga, ketika Anda sudah menguasai poin-poin pengetahuan yang saya sebutkan, Anda akan dapat mengontrol privasi Anda dengan mudah. Di Internet, jika Anda terbiasa, Anda mungkin memiliki beberapa identitas virtual yang hampir tidak bergantung satu sama lain.

## Keamanan Sifat Manusia

Manusia selalu berada pada risiko tertinggi dan abadi. Ada kutipan dari *The Three-Body Problem*: "Kelemahan dan ketidaktahuan bukanlah penghalang untuk bertahan hidup, namun kesombongan adalah penghalang."

* Jangan sombong: Jika kamu berpikir kamu sudah kuat, kamu baik-baik saja dengan dirimu sendiri. Jangan meremehkan seluruh dunia. Secara khusus, jangan terlalu bangga dan berpikir Anda bisa menantang peretas global. Belajar tidak ada habisnya, dan masih banyak kendala.
* Jangan serakah: Keserakahan memang menjadi motivasi untuk maju dalam banyak hal, tapi coba pikirkan, mengapa kesempatan bagus ini hanya diperuntukkan bagi Anda?
* Jangan impulsif: impulsif adalah iblis yang akan membawa Anda ke perangkap. Tindakan gegabah adalah perjudian.
Ada banyak hal dalam sifat manusia yang perlu dibicarakan dan Anda harus lebih berhati-hati.

Harap memberikan perhatian khusus pada poin-poin diatas, dan lihat bagaimana pelaku kejahatan memanfaatkan kelemahan sifat manusia, dengan memanfaatkan berbagai platform yang nyaman.

### Telegram

Saya sudah katakan sebelumnya bahwa Telegram adalah web gelap terbesar. Saya harus mengatakan bahwa orang-orang menyukai Telegram karena keamanan, stabilitas, dan fitur desain terbukanya. Namun budaya terbuka Telegram juga menarik orang-orang jahat: sejumlah besar pengguna, fungsionalitas yang sangat dapat disesuaikan, cukup mudah untuk membangun semua jenis layanan Bot. Jika digabungkan dengan mata uang kripto, pengalaman perdagangan sebenarnya jauh melampaui pasar web gelap (dark web) di Tor.

Biasanya, pengenal unik akun media sosial hanya berupa nama pengguna, id pengguna, tetapi ini dapat sepenuhnya dikloning oleh pelaku kejahatan. Beberapa platform sosial memiliki mekanisme validasi akun, seperti menambahkan ikon "(checkmark) ✓ biru" atau semacamnya. Akun media sosial publik dapat divalidasi melalui beberapa indikator, seperti jumlah pengikut, konten yang diposting, interaksi dengan penggemar, dll. Akun media sosial non-publik sedikit lebih sulit. Sangat menyenangkan melihat Telegram merilis fungsi "Grup mana yang kita ikuti bersama".

Dimanapun ada celah yang bisa dieksploitasi dan keuntungannya besar, pasti ada sekumpulan penjahat, itu sifat manusia.

Akibatnya, platform media sosial penuh dengan jebakan phishing. Misalnya: Dalam obrolan grup, seseorang yang terlihat seperti layanan pelanggan resmi tiba-tiba muncul dan memulai obrolan pribadi (obrolan pribadi apa pun adalah fitur Telegram, tidak perlu permintaan pertemanan), dan kemudian keluar dari taktik klasik spam, "ikan akan menggigit satu demi satu".

Atau penyerang mungkin melangkah lebih jauh dan menambahkan Anda ke grup lain. Semua peserta yg membeli token di grup itu adalah akun palsu (bot), tetapi bagi Anda itu terlihat sangat realistis. Kami menyebut teknik ini sebagai Kloning Kelompok (Group Cloning) dalam komunitas underground.

Ini hanyalah metode dasar memanipulasi sifat manusia, teknik-teknik canggih akan dikombinasikan dengan kerentanan sehingga lebih sulit untuk dicegah.

### Discord

Discord adalah platform sosial/perangkat lunak IM baru dan populer yang muncul dalam dua tahun terakhir. Fungsi intinya adalah server komunitas (bukan konsep server tradisional), seperti yang tertulis dalam pernyataan resmi:

Discord adalah aplikasi obrolan suara, video, dan teks gratis yang digunakan oleh puluhan juta orang berusia 13+ tahun untuk berbicara dan berkumpul dengan komunitas dan teman mereka.

Orang-orang menggunakan Discord setiap hari untuk membicarakan banyak hal, mulai dari proyek seni dan perjalanan keluarga hingga pekerjaan rumah dan dukungan kesehatan mental. Ini adalah rumah bagi komunitas dari berbagai ukuran, namun paling banyak digunakan oleh kelompok kecil dan aktif yang terdiri dari orang-orang yang berbicara secara teratur.

Itu terlihat sangat bagus namun memerlukan standar desain keamanan yang cukup kuat. Discord memiliki aturan dan kebijakan keamanan khusus seperti pada:

>https://discord.com/safety

Sayangnya, kebanyakan orang tidak mau repot-repot membacanya dengan cermat. Terlebih lagi, Discord tidak selalu dapat menggambarkan masalah keamanan inti tertentu dengan jelas, karena mereka juga harus berperan sebagai penyerang yang tidak selalu dapat dilakukan.

Contohnya:

Dengan banyaknya pencurian NFT di Discord, apa metode serangan utama? Sebelum kita mengetahuinya, saran keamanan Discord tidak ada gunanya.

Alasan utama di balik banyak proyek Discord hacks sebenarnya adalah Discord Token, yang merupakan konten bidang otorisasi di header permintaan HTTP. Itu sudah ada di Discord sejak lama. Bagi para hacker, jika mereka dapat menemukan cara untuk mendapatkan Token Discord ini, mereka hampir dapat mengontrol semua hak istimewa dari server Discord target. Artinya, jika targetnya adalah administrator, akun dengan hak administratif, atau bot Discord, peretas dapat melakukan apa pun yang mereka inginkan. Misalnya dengan mengumumkan situs phishing NFT, mereka membuat orang mengira itu adalah pengumuman resmi, dan ikan akan terpancing.

Beberapa orang mungkin bertanya, bagaimana jika saya menambahkan otentikasi dua faktor (2FA) ke akun Discord saya? Itu adalah sebuah kebiasaan (web3 security) yang baik! Tapi Discord Token tidak ada hubungannya dengan status 2FA akun Anda. Setelah akun Anda dibobol, Anda harus segera mengubah kata sandi Discord Anda agar Token Discord asli menjadi tidak valid.

Untuk pertanyaan bagaimana hacker bisa mendapatkan Discord Token, kami telah menemukan setidaknya tiga teknik utama, dan kami akan mencoba menjelaskannya secara detail di masa mendatang. Bagi pengguna awam, banyak hal yang bisa dilakukan, namun poin intinya adalah: jangan terburu-buru, jangan serakah, dan verifikasi dari berbagai sumber.

### Phishing "Resmi"

Aktor jahat pandai memanfaatkan permainan peran, terutama peran resmi. Misalnya kami telah menyebutkan metode layanan pelanggan palsu sebelumnya. Selain itu, pada bulan April 2022, banyak pengguna dompet perangkat keras (Hardware wallet) terkenal Trezor, menerima email phishing dari trezor.us, yang bukan merupakan domain resmi Trezor trezor.io. Ada sedikit perbedaan pada akhiran nama domain. Terlebih lagi, domain berikut juga disebarkan melalui email phishing.

>https://suite.trẹzor.com

<img src="res/trezor_phishing.jpg" width="800">

Nama domain ini memiliki "sorotan", perhatikan baik-baik huruf "ẹ" di dalamnya, dan Anda akan menemukan bahwa itu bukan huruf "e". Membingungkan? Ini sebenarnya adalah Punycode, deskripsi standarnya seperti di bawah ini:

>Pengkodean Bootstring Unicode untuk Nama Domain Internasional dalam Aplikasi (IDNA)
>adalah pengkodean nama domain internasional yang mewakili sekumpulan karakter terbatas dalam kode Unicode dan ASCII.

Jika seseorang men decoding kode trezor, tampilannya seperti ini: xn-trzor-o51b, yang merupakan nama domain asli!

Hacker telah menggunakan Punycode untuk phishing selama bertahun-tahun, pada tahun 2018, beberapa pengguna Binance terkena hack oleh trik yang sama.

Situs phishing semacam ini sudah bisa membuat banyak orang terjerumus, belum lagi serangan yang lebih canggih seperti kotak surat (email) resmi yang terkompromi, atau serangan pemalsuan Email yang disebabkan oleh masalah konfigurasi SPF. Alhasil, sumber emailnya terlihat sama persis dengan yang resmi.

Jika itu adalah orang dalam (insider) yang jahat, pengguna tidak dapat berbuat apa-apa. tim proyek harus berupaya keras untuk mencegah ancaman dari dalam. Orang dalam (insider) adalah kuda Troya terbesar, namun mereka sering kali diabaikan.

### Masalah Privasi Web3

Dengan semakin populernya Web3, semakin banyak proyek menarik atau serupa bermunculan: seperti semua jenis infrastruktur Web3, platform sosial, dll. Beberapa di antaranya telah melakukan analisis data besar-besaran dan mengidentifikasi berbagai "potret perilaku target", tidak hanya di sisi blockchain, tetapi juga pada platform Web2 terkenal. Begitu data data terkumpul, target pada dasarnya seperti orang yang transparan. Dan kemunculan platform sosial Web3 juga dapat memperburuk masalah privasi tersebut.

Pikirkan tentang hal ini, ketika Anda bermain-main dengan semua hal yang berhubungan dengan Web3 ini, seperti binding tanda tangan (signature) , interaksi on-chain, dll., apakah Anda memberikan lebih banyak privasi Anda? Banyak yang mungkin tidak setuju, namun seiring dengan banyaknya bagian yang digabungkan, akan ada gambaran yang lebih akurat dan komprehensif: NFT mana yang ingin Anda kumpulkan, komunitas mana yang Anda ikuti, White list (WL) mana yang Anda ikuti, dengan siapa Anda terhubung, akun Web2 mana Anda terikat, periode waktu apa Anda aktif, dan sebagainya. Lihat, blockchain terkadang memperburuk privasi. Jika Anda peduli dengan privasi, Anda harus berhati-hati dengan segala hal yang baru muncul dan menjaga kebiasaan baik dalam memisahkan identitas Anda.

Pada titik ini, jika kunci pribadi dicuri secara tidak sengaja, kerugiannya tidak sesederhana hanya uang, tetapi semua hak dan kepentingan Web3 yang dijaga dengan hati-hati. Kami sering mengatakan bahwa kunci pribadi adalah identitas, dan sekarang Anda memiliki masalah ID yang sebenarnya.

Jangan pernah "menguji" sifat manusia.

# Kejahatan Blockchain

Teknologi Blockchain menciptakan industri yang benar-benar baru. Baik Anda menyebutnya BlockFi, DeFi, cryptocurrency, mata uang virtual, mata uang digital, Web3, dll, inti dari semuanya tetaplah blockchain. Kebanyakan hype berpusat pada aktivitas keuangan, seperti aset kripto, termasuk token yang tidak dapat dipertukarkan (atau NFT, koleksi digital).

Industri Blockchain sangat dinamis dan menarik, namun ada terlalu banyak cara untuk melakukan kejahatan. Karakteristik khusus dari blockchain memunculkan beberapa kejahatan yang cukup unik, termasuk dan tidak terbatas pada pencurian kripto, cryptojacking, ransomware, perdagangan dark web, serangan C2, pencucian uang, skema Ponzi, perjudian, dll. Saya membuat peta pikiran pada tahun 2019 sebagai referensi.

>https://github.com/slowmist/Knowledge-Base/blob/master/mindmaps/evil_blockchain.png

Sementara itu, tim SlowMist telah memelihara dan memperbarui SlowMist Hacked — database yang berkembang untuk aktivitas peretasan terkait blockchain.

>https://hacked.slowmist.io/

Buku pegangan (handbook) ini telah memperkenalkan banyak langkah keamanan, dan jika Anda dapat menerapkannya pada keamanan Anda sendiri, maka selamat untuk anda. Saya tidak akan menjelaskan terlalu banyak tentang kejahatan blockchain. Jika Anda tertarik, Anda dapat mempelajarinya sendiri, yang tentunya merupakan hal yang baik, terutama karena penipuan dan penipuan baru terus berkembang. Semakin banyak Anda belajar, semakin baik Anda dapat mempertahankan diri dan menjadikan industri ini lebih baik.

# Apa yang Harus Dilakukan Jika Komputer Anda "terkompromi"

Beberapa kelompok Hacker menggunakan peracunan komputer, sering kali tidak melalui teknik zero-day tingkat lanjut (seperti browser zero-days) tetapi melalui induksi rekayasa sosial. Contohnya termasuk menyamar sebagai investor, jurnalis, HRD, dll., untuk mengelabui pengguna agar memasang perangkat lunak konferensi palsu. Metode lain melibatkan menyamar sebagai "Telegram Safeguard" atau memerlukan "verifikasi manusia via Cloudflare" untuk mengelabui pengguna agar bisa menyisipkan kode berbahaya secara lokal (kedalam PC).

Contoh taktik semacam itu dapat ditemukan di sini:
> https://x.com/SlowMist_Team/status/1899713751625969997<br>
> https://x.com/SlowMist_Team/status/1880520294496104827<br>
> https://x.com/SlowMist_Team/status/1888879128172241000

Jika Anda menjadi korban dari serangan semacam itu, sebaiknya Anda bersikap hati-hati dan menghindari menempatkan diri Anda dalam posisi yang (lebih) berbahaya. Anda harus mengambil langkah-langkah berikut:

1. Jika Anda memiliki wallet yang digunakan di komputer Anda (termasuk kunci pribadi/file cadangan frasa mnemonik), Anda harus segera dan aman mentransfer dana dari wallet tersebut. Jangan berasumsi bahwa memiliki kata sandi sudah cukup.
2. Ubah kata sandi dan 2FA untuk akun penting di komputer Anda, seperti akun Telegram/X/email/exchange, dll. (termasuk kata sandi yang tersimpan/akun yang login di browser), dan periksa akun tersebut untuk login perangkat yang tidak dikenal. Jangan berandai andai anda terhindar dari kemalangan (selalu berpikir skenario terburuk).
3. Instal perangkat lunak antivirus yang bereputasi baik seperti AVG/Bitdefender/Kaspersky/Malwarebytes, dll., dan pindai komputer Anda secara menyeluruh. Putuskan mana yang akan digunakan, idealnya versi berbayar. Jika Anda masih khawatir, pertimbangkan untuk membeli dua dan menggunakannya secara bergantian.
4. Jika Anda masih khawatir, cadangkan file penting Anda, dll., lalu Anda dapat mengatur ulang komputer Anda… Setelah itu, kembali ke langkah sebelumnya (langkah 3) dan pindai file cadangan Anda dengan antivirus.

Perlu dicatat bahwa serangan peracunan ini tidak hanya menargetkan komputer Windows tetapi juga Mac, dan terkadang kompatibel dengan beberapa bagian Linux.

# Apa Yang Harus Dilakukan Ketika Anda Diretas

Hanya masalah waktu sebelum Anda akhirnya di hack. Jadi apa yang harus dilakukan? Saya akan langsung saja ke pokok permasalahannya. Langkah-langkah berikut ini tidak berurutan; ada kalanya Anda harus menyesuaikan keadaan, tetapi gambaran umumnya adalah ini.

## Hentikan Kerugian Terlebih Dahulu

Stop loss adalah tentang membatasi kerugian Anda. Ini dapat dipecah menjadi setidaknya dua fase.

* Fase Tindakan Segera. Segera bertindak! Jika Anda melihat Hacker mentransfer aset Anda, jangan terlalu banyak berpikir lagi. Buruan pindahkan sisa asetnya ke tempat yang aman. Jika Anda memiliki pengalaman dalam menjalankan Front runing, ambil saja dan jalankan. Jika itu adalah jenis aset yang dapat dibekukan di blockchain, harap hubungi platform terkait untuk membekukannya sesegera mungkin. Jika Anda dapat melakukan analisis on-chain dan menemukan aset Anda ditransfer ke centralized exchange (CEX), Anda dapat menghubungi departemen pengendalian risiko mereka.
* Fase Pasca kejadian. Setelah situasi stabil, fokus Anda harus pada memastikan tidak akan ada serangan berikutnya atau yang akan datang.

## Karantina Tempat Kejadian

Saat Anda menemukan ada sesuatu yang tidak beres, tetaplah tenang dan tarik napas dalam-dalam. Ingatlah untuk karantina tempat kejadian. Berikut beberapa saran:

* Jika Insiden terjadi pada komputer, server, atau perangkat lain yang terhubung ke Internet, segera putuskan sambungan jaringan (internet) sambil tetap menghidupkan perangkat dengan charger. Beberapa orang mungkin mengklaim bahwa jika itu adalah virus yang merusak, file sistem lokal akan dihancurkan oleh virus tersebut. Mereka benar, namun mematikan hanya membantu jika Anda dapat bereaksi lebih cepat daripada virus...
* Kecuali Anda mampu menanganinya sendiri, menunggu profesional keamanan turun tangan untuk melakukan analisis selalu merupakan pilihan yang lebih baik.

Hal ini sangat penting karena kami telah beberapa kali menjumpai lokasi insiden sudah berantakan pada saat kami turun tangan untuk melakukan analisis. Dan bahkan ada kasus ketika bukti penting (misalnya log, file virus) tampaknya telah dibersihkan. Tanpa TKP yang terpelihara dengan baik, hal ini akan sangat mengganggu analisis dan penelusuran selanjutnya.

## Analisis Akar Masalah

Tujuan menganalisis penyebabnya adalah untuk memahami siapa lawan anda dan "menampilkan potret" hacker. Pada titik ini, laporan kejadian yang disebut juga Post Mortem Report menjadi sangat penting. Laporan Insiden dan Laporan Post Mortem (Post mortem report) mengacu pada hal yang sama.

Kami telah bertemu begitu banyak orang yang datang kepada kami untuk meminta bantuan setelah token/koin mereka dicuri, dan sangat sulit bagi kebanyakan dari mereka untuk menceritakan dengan jelas apa yang terjadi. Lebih sulit lagi bagi mereka untuk menghasilkan laporan kejadian yang jelas. Tapi menurut saya ini bisa dipraktekkan dan akan membantu jika mengacu pada contoh. Berikut ini bisa menjadi titik awal yang baik:

* Rangkuman 1: Siapa saja yang terlibat, kapan kejadiannya, apa yang terjadi, dan berapa total kerugiannya?
* Rangkuman 2: Alamat dompet (wallet address) terkait dengan kehilangan, alamat dompet peretas, jenis koin, jumlah koin. Ini bisa menjadi lebih jelas hanya dengan bantuan satu tabel.
* Deskripsi proses: bagian ini adalah yang paling sulit. Anda perlu mendeskripsikan semua aspek kejadian dengan segala detailnya, yang berguna untuk menganalisis berbagai macam jejak yang terkait dengan peretas dan pada akhirnya "mendapatkan potret" Hacker dari mereka (termasuk motivasinya)

Jika menyangkut kasus tertentu, template nya akan jauh lebih kompleks. Terkadang ingatan manusia juga tidak dapat diandalkan, dan bahkan terdapat penyembunyian informasi penting yang disengaja yang menyebabkan waktu terbuang percuma atau waktu tertunda. Jadi dalam praktiknya, butuh upaya dan sumber daya yang besar (dari kami) dan kami perlu menggunakan pengalaman kami untuk memandu pekerjaan dengan baik. Terakhir, kami akan membuat laporan insiden dengan orang atau tim yang kehilangan koin, dan terus meng update laporan kejadian ini.

## Penelusuran Sumber (source tracing)

Menurut Hukum Rocca (Rocca’s Law), dimana ada invasi, disitu ada jejak. Jika kita menyelidikinya dengan cukup teliti, kita akan selalu menemukan beberapa petunjuk. Proses investigasi sebenarnya adalah analisis forensik dan penelusuran sumber. Kami akan menelusuri sumber berdasarkan "potret Hacker" dari analisis forensik, dan terus memperkayanya, yang merupakan proses dinamis dan berulang.

Penelusuran sumber terdiri dari dua bagian utama:

* Intel on-chain: Kami menganalisis aktivitas aset alamat dompet, seperti masuk ke centralized exchanges (CEX) , pencampur koin (coin mixers), dll., memantaunya, dan mendapatkan peringatan tentang transfer baru.
* Intel off-chain: Bagian ini mencakup IP peretas, informasi perangkat, alamat email, dan informasi lebih lanjut dari korelasi titik-titik terkait ini, termasuk informasi perilaku.

Ada banyak upaya penelusuran sumber berdasarkan informasi ini, dan bahkan memerlukan keterlibatan penegak hukum.

## Kesimpulan Kasus

Tentu saja kita semua menginginkan akhir yang bahagia, dan berikut adalah beberapa contoh peristiwa yang diungkapkan kepada publik yang telah kita ikuti dan memberikan hasil yang baik:

* Lendf.Me, Senilai $25 million
* SIL Finance, Senilai $12.15 million
* Poly Network, Senilai $610 million

Kami telah mengalami banyak kasus lain yang tidak dipublikasikan yang berakhir dengan hasil yang baik atau baik-baik saja. Namun sebagian besar dari mereka memiliki akhir yang buruk, yang sangat disayangkan. Kami telah memperoleh banyak pengalaman berharga dalam proses ini dan kami berharap dapat meningkatkan rasio hasil akhir yang baik di masa depan.

Bagian ini disebutkan secara singkat seperti di atas. Ada banyak sekali pengetahuan yang berkaitan dengan bidang ini dan saya tidak begitu paham dengan beberapa di antaranya. Oleh karena itu, saya tidak akan memberikan penjelasan detailnya di sini. Tergantung pada skenarionya, kemampuan yang perlu kita kuasai adalah:

* Analisis Dan Forensik Keamanan Kontrak Cerdas (smart contract)
* Analisis Dan Forensik Transfer Dana On-chain
* Analisis Keamanan Web Dan Forensik
* Analisis Dan Forensik Keamanan Server Linux
* Analisis Dan Forensik Keamanan Windows
* Analisis Keamanan Dan Forensik macOS
* Analisis Dan Forensik Keamanan Seluler (mobile security)
* Analisis Kode Berbahaya Dan Forensik
* Analisis Keamanan Dan Forensik Perangkat Atau Platform Jaringan
* Analisis Dan Forensik Keamanan Orang Dalam
* ...

Panduan ini mencakup hampir semua aspek keamanan, begitu pula buku panduan (handbook) ini. Namun, ipoin-poin penting hanya disebutkan secara singkat di sini sebagai panduan Pendahuluan.

# Kesalahpahaman (misconception)

Sejak awal, buku panduan ini memberitahu Anda untuk tetap skeptis! Ini mencakup semua yang disebutkan di sini. Ini adalah industri yang sangat dinamis dan menjanjikan, penuh dengan segala macam jebakan dan chaos. Di sini mari kita lihat beberapa kesalahpahaman, yang jika dianggap sebagai kebenaran, dapat dengan mudah membuat Anda jatuh ke dalam perangkap dan menjadi bagian dari kekacauan itu sendiri.

## Kode Adalah Hukum (code is law)

Kode adalah hukum. Namun, ketika sebuah proyek (terutama yang terkait dengan kontrak pintar) diretas atau dirusak, tidak ada satupun korban yang menginginkan "Code Is Law", dan ternyata mereka masih harus bergantung pada hukum di dunia nyata.

## Bukan Kunci Anda, Bukan Koin Anda

Jika Anda tidak memiliki kunci, Anda tidak memiliki koin Anda. Faktanya, banyak pengguna gagal mengelola kunci pribadi mereka dengan benar. Karena berbagai kesalahan praktik keamanan, mereka bahkan kehilangan aset kripto mereka. Terkadang Anda akan menyadari bahwa sebenarnya lebih aman menempatkan aset kripto Anda di platform besar dan bereputasi baik.

## Di Blockchain Kami Percaya (seluruhnya)

Kami mempercayainya karena ini adalah blockchain. Faktanya, blockchain sendiri memiliki kemampuan untuk memecahkan banyak masalah kepercayaan mendasar, karena blockchain tahan terhadap kerusakan, tahan terhadap sensor (negara, pemerintah), dan lain-lain; jika aset saya dan aktivitas terkait berada didalam (on-chain), secara default saya dapat percaya bahwa tidak ada orang lain yang dapat mengambil aset saya atau merusak aktivitas saya tanpa izin. Namun kenyataannya seringkali sulit, pertama tidak semua blockchain mampu mencapai poin fundamental ini, dan kedua sifat manusia selalu menjadi mata rantai terlemah. Banyak teknik hacking saat ini berada di luar imajinasi kebanyakan dari kita. Meskipun kami selalu mengatakan bahwa serangan dan pertahanan adalah keseimbangan antara biaya dan dampak, ketika Anda tidak memiliki aset besar, tidak ada peretas yang akan membuang waktu untuk menargetkan Anda. Namun bila ada banyak target seperti Anda, akan sangat menguntungkan bagi para Hacker untuk melancarkan serangan. 

Saran keamanan saya sangat sederhana: Tidak percaya secara default (yaitu mempertanyakan semuanya secara default), dan melakukan verifikasi berkelanjutan. Verifikasi adalah tindakan keamanan utama di sini, dan verifikasi berkelanjutan pada dasarnya berarti bahwa keamanan tidak pernah dalam keadaan statis, aman sekarang bukan berarti aman besok. Kemampuan untuk memverifikasi dengan benar merupakan tantangan terbesar bagi kita semua, namun ini cukup menarik, karena Anda akan menguasai banyak pengetahuan dalam prosesnya. Jika Anda cukup kuat, tidak ada yang bisa dengan mudah mencelakakan Anda.

## Keamanan Kriptografis Adalah Keamanan (pada umumnya)

Kriptografi sangat kuat dan penting. Tanpa semua kerja keras para kriptografer, semua algoritma kriptografi yang solid & implementasi rekayasa, tidak akan ada teknologi komunikasi modern, Internet, atau teknologi blockchain. Namun, beberapa orang menganggap keamanan kriptografi sebagai keamanan mutlak. Dan timbullah banyak pertanyaan aneh:

Bukankah blockchain sangat aman sehingga butuh triliunan tahun untuk memecahkan kunci pribadi? Kenapa FBI bisa mendekripsi Dark Web Bitcoin? Mengapa NFT Jay Chou bisa dicuri?

Saya dapat memaklumi pertanyaan-pertanyaan pemula ini… yang tidak dapat saya mengerti adalah kenyataan bahwa banyak yang disebut profesional keamanan menggunakan konsep keamanan kriptografi untuk "menipu" publik, mereka menyebutkan istilah-istilah seperti "enkripsi tingkat militer, enkripsi terbaik dunia , enkripsi tingkat kosmik, keamanan sistem absolut, tidak dapat diretas, dll."

Hacker? Mereka tidak peduli…

## Apakah Memalukan Saat (kau menyadari menjadi korban) Diretas?

Memang benar bahwa diretas dapat menimbulkan perasaan campur aduk, dan terkadang ada rasa malu. Namun perlu Anda pahami bahwa diretas hampir 100% akan terjadi (hanya kapan??) jadi tidak ada yang perlu malu.

Sekali diretas, tidak masalah jika Anda hanya bertanggung jawab pada diri sendiri. Namun, jika Anda bertanggung jawab terhadap banyak orang lain, Anda harus transparan dan terbuka ketika menangani insiden tersebut.

Meskipun orang mungkin mempertanyakan atau bahkan menuduh Anda melakukan peretasan sendiri, proses Update yang transparan dan terbuka akan selalu membawa hal baik dan pengertian (dari orang diluar).

Anggap saja seperti ini: jika proyek Anda tidak terkenal, tidak ada yang akan meretas Anda. Yang memalukan bukan karena diretas; rasa malunya adalah kesombonganmu.

Dari sudut pandang kemungkinan, Hacking adalah fenomena umum, biasanya sebagian besar masalah keamanan hanyalah masalah kecil, yang dapat membantu proyek Anda berkembang. Namun, masalah utamanya efek nya nanti itulah yang masih harus dihindari sebisa mungkin.

## Segera Perbarui (immediately update)

Seringkali buku pegangan (handbook) ini menyarankan untuk memperhatikan pembaruan. Jika ada pembaruan keamanan yang tersedia, segera terapkan. Sekarang pikirkan baik-baik, apakah ini solusi terbaik?

Sebenarnya, dalam banyak kasus, "perbarui sekarang" adalah hal yang benar untuk dilakukan. Namun, ada kalanya dalam sejarah ketika pembaruan menyelesaikan satu masalah namun menimbulkan masalah lain. Contohnya adalah iPhone dan Google Authenticator:

>Ada risiko pembaruan (di) iOS 15 terbaru, yaitu informasi di Google Authenticator mungkin terhapus atau digandakan setelah pembaruan iPhone. Dalam hal ini, jangan pernah menghapus entri duplikat jika ternyata entri tersebut digandakan, karena dapat menyebabkan hilangnya semua informasi di Google Authenticator setelah dibuka kembali. Bagi yang belum mengupgrade ke sistem iOS 15 dan menggunakan Google Authenticator, sangat disarankan untuk melakukan backup sebelum melakukan upgrade.

Belakangan, Google telah memperbarui aplikasi Authenticator, memecahkan masalah ini secara permanen.

Selain itu, saya tidak menyarankan memperbarui dompet secara sering, terutama untuk dompet dengan banyak aset, kecuali jika ada patch keamanan besar, atau fitur yang sangat penting yang menyebabkan pembaruan yang tidak dapat dihindari. dalam hal ini Anda harus melakukan penilaian risiko sendiri dan membuat keputusan sendiri.

# Kesimpulan

Ingatlah bahwa buku pegangan (handbook) ini dimulai dengan diagram ini :)

![](res/web3_hacking_map.jpg)

Pernahkah Anda memperhatikan bahwa saya telah menandai dengan "orang" (manusia) dalam diagram dengan warna merah?, Saya melakukannya untuk mengingatkan kembali semua orang bahwa manusia adalah dasar dari segalanya (disebut sebagai "prinsip antropik" dalam kosmologi). Tidak peduli apakah itu keamanan sifat manusia, atau kemampuan menguasai keterampilan keamanan, semuanya tergantung pada Anda. Ya, jika Anda cukup kuat, tidak ada yang bisa dengan mudah menyakiti Anda. 

Saya mulai memperluas berdasarkan diagram, dan menjelaskan banyak poin kunci keamanan dalam tiga proses, membuat dompet, membuat cadangan dompet, dan menggunakan dompet. Lalu saya memperkenalkan perlindungan privasi tradisional. Saya menyatakan bahwa hal-hal tradisional seperti itu adalah landasan dan landasan bagi kita untuk tetap aman dalam ekosistem blockchain. Bagian keamanan alam manusia tidak dapat diabaikan. Ada baiknya untuk memahami lebih banyak tentang berbagai cara melakukan kejahatan, terutama jika Anda pernah terjatuh kedalam lubang, kesadaran keamanan di atas kertas pada akhirnya dapat menjadi pengalaman keamanan Anda. Tidak ada keamanan mutlak, jadi saya menjelaskan apa yang harus dilakukan jika Anda diretas. Saya tidak ingin kejadian buruk menimpa Anda, namun jika hal itu terjadi, saya harap buku panduan (handbook) ini dapat membantu Anda. Hal terakhir adalah membicarakan beberapa kesalahpahaman (misconception). Niat saya sangat sederhana, saya harap Anda dapat membangun pemikiran kritis Anda sendiri, karena dunia ini indah (dan juga) sekaligus mengerikan. 

Saya sudah lama tidak menulis begitu banyak kata. Saya rasa terakhir kali adalah 10 tahun yang lalu ketika saya menulis buku *Web 前端黑客技术揭秘*. Rasanya cukup pahit. Setelah bertahun-tahun berkecimpung dalam keamanan web dan keamanan siber, saya memimpin tim untuk membuat ZoomEye, mesin pencari dunia maya. Dalam bidang keamanan siber, saya telah berkecimpung di banyak bidang, hanya beberapa di antaranya yang dapat saya katakan sebagai keahlian saya.

Sekarang dalam keamanan blockchain, SlowMist dan saya sendiri dianggap sebagai pionir. Ada begitu banyak kasus yang kami temui pada tahun-tahun ini sehingga Anda hampir dapat berpikir bahwa kami berada dalam kondisi trance setiap hari. Sangat disayangkan banyak wawasan yang tidak terekam dan dibagikan. Dan alhasil, atas desakan beberapa teman, lahirlah buku panduan ini.

Ketika Anda telah selesai membaca buku panduan ini, Anda harus berlatih, menjadi mahir dan menarik kesimpulan. Ketika Anda memiliki penemuan atau pengalaman sendiri setelahnya, saya harap Anda dapat berkontribusi. Jika Anda merasa ada informasi sensitif, Anda dapat menyembunyikannya, atau menganonimkan informasi tersebut.

Dan yang terakhir, berkat kematangan global dalam legislasi dan penegakan hukum terkait keamanan dan privasi; terima kasih atas upaya semua perintis kriptografer, insinyur, peretas etis, dan semua pihak yang terlibat dalam penciptaan dunia yang lebih baik, termasuk Satoshi Nakamoto.

# Lampiran

## Aturan Dan Prinsip Keamanan

Aturan dan prinsip keamanan yang disebutkan dalam buku panduan (handbook) ini dirangkum sebagai berikut. Cukup banyak aturan yang dimasukkan ke dalam teks di atas dan tidak akan dijelaskan secara khusus di sini.

Dua aturan keamanan utama:

* **Tidak ada kepercayaan mutlak (zero trust**. Sederhananya, tetaplah skeptis, dan selalu tetap demikian.
* **Validasi berkelanjutan**. Untuk memercayai sesuatu, Anda harus memvalidasi apa yang Anda ragukan, dan menjadikan memvalidasi sebagai kebiasaan.

Prinsip keamanan:

* Untuk semua pengetahuan yang anda temukan dari Internet, carilah refferensi setidaknya pada dua sumber, yang bisa menguatkan, dan selalu bersikap skeptis.
* Memisahkan. Jangan menaruh semua telur dalam satu keranjang.
* Untuk dompet dengan aset penting, jangan melakukan pembaruan yang tidak perlu.
* Apa yang Anda lihat adalah apa yang Anda tandatangani (be careful of blind signing). Anda perlu menyadari apa yang Anda tandatangani, dan hasil yang diharapkan setelah transaksi yang ditandatangani dikirimkan. Jangan melakukan hal-hal yang akan membuat Anda menyesal di kemudian hari.
* Perhatikan pembaruan keamanan sistem. Perbarui sesegera mungkin.
* Jangan mendownload & menginstal program sembarangan, hal itu dapat meminimalisir sebagian besar risiko.

## Kontributor

Terima kasih kepada seluruh kontributor, daftar ini akan terus diperbarui. Jika Anda punya ide, silakan hubungi:

>Cos, Twitter ([@evilcos](https://twitter.com/evilcos)), Jike App (@余弦.jpg)

Kontributor:
```
Istriku
SlowMist, Twitter (@SlowMist_Team), e.g. Pds | Johan | Kong | Kirk | Thinking | Blue | Lisa | Keywolf...
Penerjemah bahasa Inggris, misalnya Alphatu | C. | CJ | JZ | Lovepeace | Neethan | pseudoyu | SassyPanda | ss |
Penerjemah bahasa Jepang, misalnya Jack Jia | Mia
Penerjemah bahasa Korea, misalnya Sharon | Jeongmin
Penerjemah bahasa Arab, misalnya Ahmed Alsayadi | Gabr Alsayadi
Penerjemah bahasa Indonesia, misalnya Finball
Jike App
Beberapa teman Anonim ...
Info lebih lanjut: https://darkhandbook.io/contributors.html
```

**Sepanjang ada bantuan yang diadopsi dan dimasukkan dalam buku pegangan ini (handbook), seperti: memberikan saran dan kasus pembelaan yang spesifik (study case); pekerjaan penerjemahan; koreksi kesalahan besar, dll.**

## Alat2nya (tools)

Buku pegangan ini, yang biasa disebut sebagai "Dark Handbook", telah tersedia selama lebih dari dua tahun, dan saya senang melihat dampaknya yang bermanfaat bagi banyak orang. Pengaruhnya terus meluas, dengan semakin banyak pendukung yang [menganjurkan pembaruan](https://github.com/evilcos/darkhandbook). Biasanya, pembaruan pada "Dark Handbook" ini terutama terdiri dari bacaan tambahan. Tantangan dari bacaan tambahan ini adalah bahwa bacaan tersebut secara teknis rumit dan tidak mudah diakses oleh pemula. Selain itu, saya menyadari bahwa tidak semua orang ingin menginvestasikan banyak waktu untuk menguasai berbagai nuansa keamanan di blockchain. Awalnya, bagian ini bertujuan untuk merekomendasikan beberapa alat yang ramah bagi pemula, seperti dompet, ekstensi keamanan, dan alat skrip. Namun, setelah banyak pertimbangan, saya memutuskan untuk tidak mendukung produk tertentu karena cepatnya perubahan dalam industri. Meskipun manual ini telah menyoroti beberapa alat yang dapat diandalkan, masih belum pasti apakah alat tersebut akan tetap efektif atau relevan di masa depan. Mengingat tanggung jawab saya terhadap semua pembaca, harus saya akui, saya tidak yakin.

Seperti yang telah saya nyatakan sebelumnya, ketika merekomendasikan suatu alat, saya berusaha untuk mendeskripsikannya seobjektif dan senetral mungkin. Selain itu, untuk meningkatkan keamanan, setiap pembaca harus memperhatikan hal-hal berikut:

　* Keamanan mutlak (itu) tidak ada. Mengadopsi pendekatan zero-trust dengan verifikasi berkelanjutan sangat penting dalam menghadapi lanskap yang kompleks ini. Jika salah satu alat ini menimbulkan bug, mengalami masalah keamanan, atau, dalam skenario yang lebih buruk, menyertakan pintu belakang dalam pembaruan baru, risikonya ada pada Anda untuk dikelola. Saya mendorong Anda untuk berpikir mandiri dan kritis sebelum menggunakan alat ini.

　* Keterampilan penelitian saya terasah dengan baik, dan saya memiliki jaringan yang luas, jadi yakinlah bahwa saya akan merekomendasikan alat berkualitas jika dirasa tepat. Tidak perlu terburu-buru; jika suatu alat terbukti andal dan mendapat kepercayaan luas, saya tentu saja akan mendukungnya.
 
　* Setiap orang memiliki pendekatan uniknya masing-masing, dan ini pendekatan saya.
 
　* Jauhi (emosional) pengaruh harga koin.

　* Kepercayaan itu sulit dibangun, tapi dapat runtuh dalam sekejap, jadi mohon hargai halitu.

Meskipun saya tidak membuat rekomendasi alat khusus apa pun di bagian ini, saya ingin berbagi pola pikir yang berharga: pola pikir firewall. Konsep "zero trust" dan "verifikasi berkelanjutan" yang ditekankan sebelumnya sebenarnya adalah bagian dari pemikiran firewall ini.

Misalnya, dalam penggunaan dompet (wallet), penandatanganan (signing) merupakan masalah utama dalam hal keamanan dana, dengan berbagai metode phishing canggih terkait penandatanganan, seperti:

- Eksploitasi penandatanganan native (signing) dengan eth_sign/personal_sign/eth_signTypedData_*, di mana eth_sign semakin banyak diblokir oleh dompet (wallet).
- Eksploitasi fungsi otorisasi seperti menyetujui/mengizinkan Token/NFT.
- Pemanfaatan fungsi-fungsi canggih seperti swapExactTokensForTokens/permit2 Uniswap.
- Eksploitasi fungsi protokol dari OpenSea/Blur dan lainnya (yang sangat beragam).
- Eksploitasi TX data 4byte, seperti untuk Claim Rewards/Security Update.
- Menggunakan Create2 untuk membuat alamat penerima dana terlebih dahulu, dan men bypass pemeriksaan terkait.
- Satu tanda tangan (signing) di Solana melakukan phishing terhadap semua aset di alamat dompet target.
- Inscription Bitcoin untuk phishing massal (dengan) sekali klik, memanfaatkan mekanisme UTXO.
- Phishing switching di berbagai rantai EVM/Solana/Tron, dll.

Jika dompet (wallet) Anda, ketika meminta konfirmasi tanda tangan, mengirimkan tanda tangan tepat setelah satu klik — baik karena FOMO atau tangan gemetar — maka metode penggunaan dompet ini tidak mencerminkan pola pikir firewall. Praktik yang lebih baik adalah memerlukan setidaknya dua klik; setiap klik tambahan menambah lapisan keamanan (tentu saja, jangan terlalu banyak lapisan, karena orang bisa menjadi tidak peka…). Misalnya, saya menggunakan dompet ekstensi browser seperti Rabby, MetaMask, dan OKX Wallet, dan kecuali untuk dompet uji coba, saya selalu menyandingkannya dengan dompet perangkat keras (sebaiknya dompet dengan layar lebih besar agar mudah meninjau konten yang akan ditandatangani).

Pada titik ini, popup konfirmasi tanda tangan dompet ekstensi akan melakukan analisis keamanan lapisan pertama, seperti mengidentifikasi situs phishing, alamat dompet (wallet address) berisiko, "apa yang Anda lihat adalah apa yang Anda tandatangani", dan pengenalan tanda tangan berisiko tinggi. Ini sangat penting untuk keamanan interaksi pengguna. Dompet perangkat keras (hardware wallet) menyediakan analisis keamanan lapisan kedua. Jika Anda kemudian menambahkan ekstensi keamanan dompet browser seperti Scam Sniffer, Wallet Guard, atau Pocket Universe, Anda menambahkan lapisan lain ke firewall Anda. Namun, penting untuk diingat, meskipun tidak ada peringatan risiko atas tindakan yang Anda lakukan, Anda harus tetap waspada dan menyadari bahwa pada akhirnya, Anda adalah garis pertahanan terakhir Anda sendiri…

Itu saja dan terima kasih!

## Situs Resmi
```
SlowMist https://www.slowmist.com
CoinMarketCap https://coinmarketcap.com/
Sparrow Wallet https://sparrowwallet.com/
MetaMask https://metamask.io/
imToken https://token.im/
Trust Wallet https://trustwallet.com/
TokenPocket https://www.tokenpocket.pro/
Gnosis Safe https://gnosis-safe.io/
ZenGo https://zengo.com/
Fireblocks https://www.fireblocks.com/
Safeheron https://www.safeheron.com/
Keystone https://keyst.one/
Trezor https://trezor.io/
OneKey https://onekey.so/
imKey https://imkey.im/
Rabby https://rabby.io/
OKX Wallet https://www.okx.com/web3
EdgeWallet https://edge.app/
MyEtherWallet https://www.myetherwallet.com/
Phantom https://phantom.app/
Tornado Cash https://tornado.cash/
Binance https://www.binance.com/
Coinbase https://coinbase.com
Compound https://compound.finance/
SushiSwap https://www.sushi.com/
OpenSea https://opensea.io/
Revoke.cash https://revoke.cash/
Scam Sniffer https://www.scamsniffer.io/
Wallet Guard https://www.walletguard.app/
Pocket Universe https://www.pocketuniverse.app/

Jike App https://okjike.com/
Kaspersky https://www.kaspersky.com.cn/
Bitdefender https://www.bitdefender.com/
Cloudflare https://www.cloudflare.com/
Akamai https://www.akamai.com/
SURVEILLANCE SELF-DEFENSE https://ssd.eff.org/
Privacy Guide https://www.privacytools.io/
OpenPGP https://www.openpgp.org/
GPG https://gnupg.org/
GPG Suite https://gpgtools.org/
Gpg4win https://www.gpg4win.org/
1Password https://1password.com/
Bitwarden https://bitwarden.com/
Google Authenticator https://support.google.com/accounts/answer/1066447
Microsoft Authenticator https://www.microsoft.com/en-us/security/mobile-authenticator-app
ProtonMail https://protonmail.com/
Tutanota https://tutanota.com/
VMware Workstation https://www.vmware.com/products/workstation-pro.html
Parallels https://www.parallels.com/
```
