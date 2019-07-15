# ozPanel directadmin teması
## daha tanıdık bir görüntüde directAdmin teması (sadece user hesapları için)

Dil seçeneği var gibi görünsede çoğu yerde türkçe olarak sabit metinler var. pratikte ingilizce desteği yok

Geliştirilmesi ve Kullanılması Serbesttir.
FakatKopyaların ücretli dağıtılması yasaktır


## Kurulum 
```
cd /usr/local/directadmin/data/skins/
git clone https://github.com/ozkula-internet-hizmetleri/ozPanel.git
```

- Bu işlem ile klasörü oluşturduktan sonra panelinize admin girişi yapın
- <sunucuip>/reseller/skins adresine girip ozpanel temasını seçin.
- Listenin üstünde çıkan Apply to All Users'ı tuşuna basın. 
- Böylece Tema tüm user seviyesi kullanıcılara uygulanır. 

## Tema dizin yapısı (özelleştirme)
- üst kısım logosu: assets/logo-beyaz.png
- giriş sayfası logosu: assets/logo-siyah.png
- alt kısım logosu: assets/ozpanel.png
- ana menu simgeleri: assets/anasayfamenusu
- favicon simgeleri: assets/fav
- alt sayfalardaki yardım bağlantısının tanımlandığı dosya: header.html

## Ekran görüntüsü
![alt text](https://raw.githubusercontent.com/ozkula-internet-hizmetleri/ozPanel/master/assets/img/screenshot.png)

## Kullanılan Kütüphaneler
- Bootstrap v4.3.1 (https://getbootstrap.com/)
- jQuery JavaScript Library v3.4.1 (https://jquery.com/)
- Fuse.js v3.4.5 - Lightweight fuzzy-search (http://fusejs.io)
- Font Awesome Free 5.9.0 by @fontawesome - (https://fontawesome.com)