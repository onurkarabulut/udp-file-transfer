# udp-file-transfer
## Sunucu
* Sunucu bağlantıyı UDP üzerinden sağlayarak, 42. portu dinlemektedir.
## İstemci
* **istemci.py** çalıştırıldığında IP adresi olarak **sunucu.py**'nin IP adresi girilmelidir.
* Sunucuya bağlantı sağlandığında sunucu üzerindeki klasörde bulunan dosya isimlerini istemciye gönderir.
* İstemci bu klasörde bulunan dosyaları GET dosya_adı yazarak ilgili dosyayı indirebilir.
* İstemci kendi klasöründe bulunan dosyalarıda PUT dosya_adi yazarak sunucuya gönderebilir.
