# Windows Açılış Süreci

## Amaç

Bu derste bilgisayarın güç düğmesine basıldıktan sonra Windows masaüstü gelene kadar gerçekleşen temel aşamaları öğrendim.

---

# Açılış Sırası

PSU
↓
BIOS / UEFI
↓
POST
↓
Boot Device
↓
Windows Boot Manager
↓
Kernel
↓
Driver'lar
↓
Servisler
↓
Kullanıcı Girişi
↓
Explorer.exe
↓
Masaüstü

---

# Öğrendiklerim

## PSU

Güç kaynağıdır.

Şebekeden gelen elektriği bilgisayar bileşenlerinin kullanabileceği voltajlara dönüştürür.

---

## BIOS / UEFI

Bilgisayar açıldığında ilk çalışan yazılımdır.

Donanımları kontrol eder ve işletim sistemini başlatır.

---

## POST

Power On Self Test.

RAM, işlemci ve diğer temel donanımların kontrol edildiği aşamadır.

---

## Boot Device

İşletim sisteminin bulunduğu disk veya cihazın bulunması aşamasıdır.

---

## Kernel

Windows'un çekirdeğidir.

Donanım ve yazılım arasındaki iletişimi sağlar.

---

## Driver

Windows ile donanım arasında tercüman görevi görür.

---

## Service

Arka planda çalışan ve sistem hizmeti sağlayan özel process'lerdir.

Örnek:

* DHCP Client
* DNS Client
* Print Spooler
* Windows Update

---

## Explorer.exe

Masaüstü, görev çubuğu ve Windows gezginini oluşturan process'tir.

---

# Troubleshooting Notları

Bilgisayar hiç açılmıyorsa:

* PSU
* Güç kablosu
* Anakart

kontrol edilir.

---

Windows bulunamıyorsa:

* SSD/HDD
* Boot sırası
* Boot kaydı

kontrol edilir.

---

Yazıcı çalışmıyorsa:

* Yazdırma Biriktiricisi (Print Spooler)

kontrol edilmelidir.

---

# Bu Dersten Çıkardığım Sonuç

Bir bilgisayarın açılması tek bir işlem değildir.

Her aşama ayrı ayrı incelenebilir ve arıza tespiti yapılırken sistemin hangi aşamada kaldığı belirlenmelidir.
