# Refleksi Modul 1

## Refleksi 1
Saya belajar untuk ngerapihin struktur biar gampang dibaca dan dikembangin. Saya jadi paham Impelemntasi Controller, Service, Repository itu  supaya logic nggak campur aduk, dan pentingnya penamaan variable yang jelas karena membantu waktu debugging. Saya juga belajar basic secure coding serta operasi yang mengubah data seperti edit/delete lebih tepat pakai POST. Dari sini saya belajar perlu membiasakan diri untuk validasi input dan handle error lebih baik lagi, dan juga clean code yang baru saya sadari pentingnya, yang dimana saya tidak belajar hal ini di PBP.

## Refleksi 2
Alhamdulillah saya senang telah menyelesaikan modul 1, walaupun di tengah-tengah ada error, saya dapat ngebenerinnya, thanks to discord adpro. Jujur saya gak tahu harus ada berapa unit test, yang menurut saya penting adalah mencakup skenario positive, negative, dan edge case. Code coverage 100% juga bukan jaminan tidak ada bug atau error, karena bisa saja ada logic error atau kasus yang tidak kepikiran.

Untuk functional test, kalau bikin test suite baru dengan copy paste setup yang sama itu kurang bagus karena banyak kode yang duplikat, yang dimana hal tersebut melanggar prinsip DRY (Dont Repeat Yourself). Kalau nanti ada perubahan setup, harus update di banyak tempat dan bakal rawan error. Seharusnya bisa dibikin lebih clean dengan extract setup yang sama ke base class atau satu tempat, jadi lebih gampang maintain dan nggak ada duplikasi.