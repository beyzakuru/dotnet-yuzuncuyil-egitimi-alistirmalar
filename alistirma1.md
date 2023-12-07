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

![2](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/6fc02b6f-0d4f-4aaf-ad60-ba249f959503)

- Oluşturduğumuz klasörün git ile ilgili herhangi bir bağlantısı yoktur. Dolayısıyla local bir repository oluşması için ilk adım git init komutunu çalıştırmaktır.

![3](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/5ad27ee4-b7b2-49d2-953c-644e99251fca)

- Yapılan değişiklikleri ya da hangi aşamada olduğumuzu görmek için kullandığımız komut git status komutudur. Aşağıda kırmızı renkte olan dosyaların working directory’de yer aldığını buradan anlayabiliriz.

![5](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/e7d58d7b-dae5-4f1d-984e-3d80af0d4620)

- Working directory’de yer alan dosyalarımızın Staging Area’ya aktarılmasını sağlamak amacıyla kullancağımız komut git add . komutudur. Bu komut ile çalışılan dizindeki dosyaların hepsini Staging Area’ya aktarırız. Aşağıda spesifik olarak bir dosyanın aktarılmasının görüntüsü vardır.

![6](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/b33d208f-339b-4a3b-965d-4df13f2529bd)

- Working Directory’de yer alan tüm dosyalar Staging Area’ya aktarıldı.

![7](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/de8c2960-0295-41ce-bf44-841294c1346f)


- Yapılan değişikliklerin yerel depomuza kaydedilme işleminin yapılabilmesi için commit atmamız gerekmektedir. İlk commitim aşağıdadır.

![9](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/75af3bc6-f528-4a16-b85e-89f9b1928b41)




