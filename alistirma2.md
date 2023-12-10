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

![git_staging_area](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/da6eb276-b965-4a7f-8279-e8405dd9b01f)

- Staging Area’dan Working Directory’e ilgili dosyayı geri çekmek için kullanacağımız komut 
    * git restore –-staged test.md şeklindedir. 

![gitrestore](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/39e362fe-097a-4c44-a982-7a46a8b91584)

- Working directory dizinindeki değişikliği de geri alarak herhangi bir değişiklik yapmadığınız duruma dönebilmek için kullanılacak komut /blabla/ şeklindedidir.

resim

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

![git_log](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/13cdaa64-04fa-45de-b58b-b83bfc2931b5)

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

![git-branch](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/4193dceb-4c24-4b77-9676-2ce240ca28f0)

--- 

### Dördüncü Kısım Aşamaları

- Github üzerinde (benim projelerim de olabilir,farklı projeler de olabilir.) bir repo seçin.
- Bu repoyu kendi localinize ( yani bilgisayarınıza) çekmek için uygun git komutunu kullanın.


### Dördüncü Kısım Çözümü

- Öncelikle github üzerinden uygun proje seçilir. Aşağıda ok ile göstererek belirttiğim şekilde de bilgisayarımıza indirebiliriz. Ancak git komutu ile bunu nasıl sağlayacağımıza bakacak olursak kırmızı kutu içerisine aldığım linki kopyalayarak işe başlarız.

![git-clone](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/1ab1119d-e02f-41c5-8a87-d165162008b9)

- Sonrasında istenilen bir yere klasör açılır. Masaüstünde test adında klasör oluşturuyorum.
- git clone url komutu ile repoyu kendi localimize çekmiş oluruz.

![git-clone-](https://github.com/beyzakuru/dotnet-yuzuncuyil-egitimi-alistirmalar/assets/88837400/a16ee5a0-4db8-4949-9934-7de67d5ef4a2)

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

