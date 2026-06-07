# Process ve Service Mantığı

## Amaç

Bu derste Windows'ta çalışan process ve service kavramlarını öğrendim.

---

# Process Nedir?

Windows tarafından çalıştırılan herhangi bir program veya işlemdir.

Örnek:

* chrome.exe
* outlook.exe
* teams.exe
* notepad.exe

Process'lerin arayüzü olmak zorunda değildir.

---

# Service Nedir?

Arka planda çalışan ve belirli bir hizmet sağlayan özel process türüdür.

Özellikleri:

* Kullanıcı giriş yapmadan çalışabilir.
* Otomatik başlayabilir.
* Arka planda çalışır.

---

# Örnek Servisler

## DHCP Client

Bilgisayarın DHCP sunucusundan IP adresi almasını sağlar.

---

## DNS Client

DNS sorgularını önbellekte tutar ve isim çözümlemesine yardımcı olur.

---

## Print Spooler

Yazdırma kuyruğunu yönetir.

Yazıcı problemlerinde ilk kontrol edilecek servislerden biridir.

---

## Windows Update

Windows güncellemelerini yönetir.

---

# Önemli Bilgi

Her service bir process'tir.

Ancak her process bir service değildir.

---

# Troubleshooting

## Yazıcı Çalışmıyor

Kontrol:

Print Spooler servisi

---

## IP Alınamıyor

Kontrol:

DHCP Client servisi

---

## DNS Problemleri

Kontrol:

DNS Client servisi

---

# Bu Dersten Çıkardığım Sonuç

Windows'taki birçok problem sadece uygulama kaynaklı değildir. Arka planda çalışan servislerin durumu da mutlaka kontrol edilmelidir.
