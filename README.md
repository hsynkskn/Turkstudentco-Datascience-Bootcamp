# Turkstudentco-Datascience-Bootcamp-Pseudo Code Çalışması

1-) İki  sayının toplamını bulma
Basla

Lütfen ilk sayiyi giriniz! 
Sayi_1 =
Lütfen ikinci sayiyi giriniz! 
Sayi_2 =
Toplam = Sayi_1 + Sayi_2
Yaz (Toplam) 

Bitir

2-)  1'den 100 'e kadar olan sayıların toplamı
Basla

Toplam = 0
Döngü başlat i = 1'den 100'e kadar
    Toplam = Toplam + i
Döngü bitir
Yaz(Toplam)

Bitir

3-)  Kullanıcıdan alınan bir sayının  asal olup olmadığını bulma
Basla

Lütfen birbsayınhiriniz! \n
Sayi =
Eğer Sayı <= 1 ise
    Yaz("Asal değil")
    Bitir
Asal = Doğru
Döngü başlat i = 2'den Sayı'nın kareköküne kadar
    Eğer Sayı % i == 0 ise
        Asal = Yanlış
        Döngüden çık
Döngü bitir
Eğer Asal == Doğru ise
    Yaz("Asal")
Aksi takdirde
    Yaz("Asal değil")

Bitir

4-) Bir dizideki elemanların tekrar edip etmediğini kontrol eden programın puseido kodu

Basla

Diziyi kullanıcıdan al
Dizi = input()

Boş bir liste oluştur
Görülenler = []

TekrarEden = Yanlış

Her eleman için Döngü başlat Dizi içinde
    Eğer eleman Görülenler listesinde ise
        TekrarEden = Doğru
        Döngüden çık
    Aksi takdirde
        Elemanı Görülenler listesine ekle
Döngü bitir

Eğer TekrarEden == Doğru ise
    Yaz("Dizide tekrar eden eleman var")
Aksi takdirde
    Yaz("Dizide tekrar eden eleman yok")

Bitir
