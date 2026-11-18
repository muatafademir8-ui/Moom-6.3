MOOM 6.3 - YENI SILAH SESLERI

Bu paket MOOM 6.2 kaynak kodunu temel alir.
Kullanicinin gonderdigi uc ekran kaydindan (video) silah sesleri cikarilmis,
sessizlik kirpilmis, normalize edilmis ve 22050 Hz mono PCM olarak main.c icine gomulmustur.

SILAH SESLERI (yeni)
- Pompalı tüfek  : 1. video (pompalı görseli) sesi
- Çift tabanca   : 2. video (USP tabanca) sesi
- M249           : 3. video (sarı/mor tüfek) sesi

NASIL CALISIR
- X veya Kare ile ates edildiginde secili silahin kendi sesi calar.
- R1 ile silah degistirme duzeni: Pompalı -> Cift Tabanca -> M249.
- Zombi olum sesi korunmustur.
- Ayri ses dosyasi gerekmez, her sey main.c icinde.

DIGER OZELLIKLER
- 7 bolum.
- Zombi dusme animasyonu ve yerde siyah ceset gorunumu.
- Cift tabanca ve M249 icin 3D silah modelleri.
- Ortak mermi sayaci.

DERLEME
main.c ve Makefile dosyalarini PSP SDK projenize koyup PSPSDK / GitHub Actions ile EBOOT.PBP derleyin.

Makefile icindeki baslik da guncellenebilir:
PSP_EBOOT_TITLE = MOOM 6.3

DOGRULAMA NOTU
Bu ortamda PSP SDK bulunmadigindan derleme ve PPSSPP testi yapilmadi.
Sesler kirpilmis ve normalize edilmistir; PPSSPP uzerinde test edilmesi tavsiye edilir.
