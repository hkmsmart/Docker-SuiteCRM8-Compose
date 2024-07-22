Klasorler oluşması için text.txt dosyası eklenmiştir, containerı ayağa kaldırmadan önce siliniz.

Github üzerinden docker projemizi indiriyoruz.

https://github.com/hkmsmart/Docker-SuiteCRM8-Compose
suitecrm8 versionumuzu aşağıdaki adresten indiriyoruz.

https://suitecrm.com/download/
Suitecrm projemizi docker projemiz içinde bulunan www klasörünün içine kopyalıyoruz.

kopyalama işlemi bittikten sonra docker-compose.yml klasörümüzü terminalde açıyoruz ve container ayağa kaldırıyoruz.

docker-compose up -d

contanier ayağa kalktıktan sonra localhost ile projemizin kurulumunu gerçekleştirebiliriz.

http://localhost/public/install.php
kurulum sayfasına geçip kurulumunuzu yapabilirsiniz.

Notlar:

suitecrm8 için gerekli php kütüphaneleri "extension" dockerfile içinde indirilmektedir.

suitecrm8 için gerekli dosya yetkileri "permissions" dockerfile içinde tanımlanmıştır.

php.ini içinde bulunan gerekli kütüphaneler "extension" açılmıştır.

blogger:https://hkmsmart.blogspot.com/2024/07/docker-suitecrm8-compose.html
