# Alıştırma 2 - Versiyon Kontrol Sistemi (Git)

### Birinci Kısım Aşamaları

- Working Directory'de bir dosya oluşturun.
- Bu dosyada herhangi bir değişiklik yapın.
- Bu değişikliği Working Directory'den -> Staging Area'ya doğru aktarın.
- Sonrasında Stage'ye eklenmiş değişikliği geri alarak tekrar Working Directory dizinine dönün.
- Sonrasında da Working Directory dizinindeki değişikliği de tekrar geri alarak, herhangi bir değişiklik yapmadığınız duruma dönün.



### Birinci Kısım Çözümü

- Working Directory’de test adında bir txt uzantılı dosya oluşturdum.
- Bu dosya içerisinde test verisi vardır.
- Bu dosyayı Working Directory’den Staging Area’ya doğru aktarmak için izleyeceğimiz yol sırasıyla;
    * git status ile durum kontrolü yapılır.
    * Rengi kırmızı olarak gözüken dosya henüz Staging Area’ya aktarılmadığını ifade eder.
    * git add . komutunu yazarak ilgili dosyanın Staging Area’ya aktarılmasını sağlarız.
    * Git status komutunu tekrar çalıştırdığımızda işlemin doğru gerçekleşmesinden ötürü dosya rengi kırmızıdan yeşile dönecektir.

![git_staging_area](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/e66f0273-e5a6-4e63-9f0b-be7cb4c818ec)

- Staging Area’dan Working Directory’e ilgili dosyayı geri çekmek için kullanacağımız komut 
    * git restore –-staged test.md şeklindedir. 

![gitrestore](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/c5f35067-f692-4492-8d8f-7643ddf26f07)

- Working directory dizinindeki değişikliği de geri alarak herhangi bir değişiklik yapmadığınız duruma dönebilmek için kullanılacak komut git restore test.txt şeklindedidir.

---

### İkinci Kısım Aşamaları

- Repository üzerinden son üç logu getirecek git komutunu yazınız.
- Repository üzerinden son 15 dakika içerisindeki logu getirecek git komutunu yazınız.
- Logları tek satırda gösterebileceğiniz komutu yazınız.

### İkinci Kısım Çözümü

- git log -3 komutu ile son 3 log getirilir.
- git log –-since=15minutes komutu ile son 15 dakika içerisindeki logları görebiliriz. Ancak son 15 dakika içerisinde bir log olmamasından kaynaklı görüntüleme olmamıştır.
- git log –-oneline komutu ile tüm logları tek satırda görüntüleyebiliriz.   

CMD ekranında sırasıyla gösterimi aşağıdaki gibidir:

![git_log](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/a0b8ca21-a8f8-4bad-bf91-929858d47ce2)

---

### Üçüncü Kısım Aşamaları

- Local ortamınızdaki branchleri listeleyin.
- Kendi branchinizi oluşturun.
- Kendi branchinize git komut satırıyla geçiş yapın.

### Üçüncü Kısım Çözümü

- Brancleri listelemek için kullanacağımız komut git branch –a şeklindedir.
- Kendi branch’imizi oluşturmak için git branch dev-beyza komutunu kullanırız.
- Kendi branch’imize geçiş yapmak için git checkout dev-beyza komutunu kullanırız.

Aşağıda işlemleri sırasıyla gösteriyorum.

![git-branch](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/ff59947d-eb42-4d96-b30b-ee48906bafd9)

--- 

### Dördüncü Kısım Aşamaları

- Github üzerinde (benim projelerim de olabilir,farklı projeler de olabilir.) bir repo seçin.
- Bu repoyu kendi localinize ( yani bilgisayarınıza) çekmek için uygun git komutunu kullanın.


### Dördüncü Kısım Çözümü

- Öncelikle github üzerinden uygun proje seçilir. Aşağıda ok ile göstererek belirttiğim şekilde de bilgisayarımıza indirebiliriz. Ancak git komutu ile bunu nasıl sağlayacağımıza bakacak olursak kırmızı kutu içerisine aldığım linki kopyalayarak işe başlarız.

![git-clone](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/6c82c589-363f-4cbb-9d9a-0b6d7b74bf7d)

- Sonrasında istenilen bir yere klasör açılır. Masaüstünde test adında klasör oluşturuyorum.
- git clone url komutu ile repoyu kendi localimize çekmiş oluruz.

![git-clone-](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/1f07ca9c-377a-4366-8122-ae796cfa0bcf)

---

### Beşinci Kısım Aşamaları

- Boş bir klasör oluşturunuz.
- Bu klasör içerisinde github.txt bir dosya ekleyiniz. Bu dosya içerisine "test" yazabilirsiniz.
- Bu projeyi git ile izlemeye alın.
- Gerekli işlemleri yaptıktan sonra github repository oluşturun.
- Localinizdeki bu değişilkleri uzak repoya aktarın.
- Bu çalışmaları yaptıktan ve ekran görüntülerini aldıktan sonra repository'i silebilirsiniz.


### Beşinci Kısım Çözümü

- Tekrardan boş bir klasör oluşturmak yerine aynı işlemleri bu oluşturduğum alistirma2.md dosyası için gerçekleştireceğim.
- Komutlar sırasıyla;
    * git status
    * git add .
    * git status
    * git commit -m "Alıştırma 2 gönderildi."
    * git pull origin master
    * git push origin master
- Sonrasında merge işlemleri yapılarak işlem sonlandırılır.
