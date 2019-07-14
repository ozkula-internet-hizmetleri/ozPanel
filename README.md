# ozPanel directadmin teması
## daha tanıdık bir görüntüde directAdmin teması (sadece user hesapları için)

indirip /usr/local/directadmin/data/skins/ klasörüne kopyalayın. 

admin kullanıcısı olarak girip skins kısmından set global ve apply to all users'ı seçerseniz kullanıcılara uygulanır. 
reseller hesapları kullanıcılara özel olarak tema belirleyebilir. 

dil seçeneği var gibi görünsede çoğu yerde türkçe olarak sabit metinler var. pratikte ingilizce desteği yok

geliştirilmesi serbest ama kopyaların ücretli dağıtılması yasaktır


## örnek kurulum 
```
cd /usr/local/directadmin/data/skins/
git clone https://github.com/ozkula-internet-hizmetleri/ozPanel.git
```

## tema dizin yapısı 
- header logosu: assets/logo-beyaz.png
- footer logosu: assets/ozpanel.png
- ana menu simgeleri: assets/anasayfamenusu
- favicon simgeleri: assets/fav
- alt sayfalardaki yardım bağlantısının tanımlandığı dosya: header.html

## ekran görüntüsü
![alt text](https://raw.githubusercontent.com/ozkula-internet-hizmetleri/ozPanel/master/assets/img/screenshot.png)

## Henüz düzenlenmemiş sayfalar
- [ ] Hata Sayfaları Sayfası
- [ ] Mime Tipleri sayfası
- [ ] Cron Sayfası
- [ ] SSL Sertifikası Sayfası
