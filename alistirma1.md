# Alıştırma 1 - Versiyon Kontrol Sistemi (Git)

### Yapılması istenenler aşağıdaki gibidir:

1. Bir tane dosya oluşturacaksınız.
2. Bu dosyanın içerisinde modern-web-gelistirme.txt ( bir dosya oluşturcaksınız.)
3. modern-web-gelistirme.txt içerisinde okul numaranız-ad-soyad yer alsın.
4. git versiyon kontrol sistemini bilgisayarlarınıza kurmanız gerekiyor.

Oluşturduğunuz dosya dizinine git'i entegre etmenizi istiyorum.

- git init ( boş bir local repo oluşturmak için )
- git status ( ne gibi değişiklikler yaptığınız görmek için )
- git add . , git add modern-web-gelistirme.txt
- git status (stage tarafına geçtiğini göstereceksiniz.)
- git commit -m kullanılırak commit mesajı attığını göstermenizi istiyorum.
- git status ( working tree clean ) mesajını almanızı bekliyorum.

---

### Çözüm aşağıdaki gibidir:

- C sürücüsü içinde dotnet_yuzuncuyil-alistirmalar klasörü oluşturuldu.
- modern-web-gelistirme.txt dosyası bu klasör içine istenilen bilgileri içerecek şekilde eklendi.

![1](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/fac4e63a-6c4f-41ec-8828-392e8ca6a85f)


- Dosyanın bulunduğu dizin adresi kopyalandı. Sonrasında açılan terminale (cmd ekranı) yapıştırıldı.

![][2.C:\Users\Lenovo\Desktop\Resimler]

- Oluşturduğumuz klasörün git ile ilgili herhangi bir bağlantısı yoktur. Dolayısıyla local bir repository oluşması için ilk adım git init komutunu çalıştırmaktır.

![][3.C:\Users\Lenovo\Desktop\Resimler]

- Yapılan değişiklikleri ya da hangi aşamada olduğumuzu görmek için kullandığımız komut git status komutudur. Aşağıda kırmızı renkte olan dosyaların working directory’de yer aldığını buradan anlayabiliriz.

![][5.C:\Users\Lenovo\Desktop\Resimler]

- Working directory’de yer alan dosyalarımızın Staging Area’ya aktarılmasını sağlamak amacıyla kullancağımız komut git add . komutudur. Bu komut ile çalışılan dizindeki dosyaların hepsini Staging Area’ya aktarırız. Aşağıda spesifik olarak bir dosyanın aktarılmasının görüntüsü vardır.

![][6.C:\Users\Lenovo\Desktop\Resimler]

- Working Directory’de yer alan tüm dosyalar Staging Area’ya aktarıldı.

![][7.C:\Users\Lenovo\Desktop\Resimler]

- Yapılan değişikliklerin yerel depomuza kaydedilme işleminin yapılabilmesi için commit atmamız gerekmektedir. İlk commitim aşağıdadır.

![][8.C:\Users\Lenovo\Desktop\Resimler]




