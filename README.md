------------------------------------------------------------------------

## Dönem Projesi Hakkında

**Bir veri seti (herhangi bir veri seti) seçerek RStudio’da RMarkdown
ile bir rapor hazırlayın.**

-   Dönem projesi sizin seçtiğiniz bir veri setinin analizinden
    oluşacaktır.

-   Veri seti halihazırda var olan bir veri olabileceği gibi anket
    yaparak da veri toplayabilirsiniz. Eğer anket yolu ile veri
    toplamayı seçerseniz sorduğunuz soruların farklı veri türlerini elde
    etmek için yeterli olduğundan emin olunuz.

-   Kullanacağınız veri setini kendi ilgi alanlarınızdan veya diğer
    derslerde kullandığınız verilerden seçebilirsiniz.

-   Dönem projesinin amacı derste işlediğimiz tekniklerin
    uygulanmasıdır.

-   Projenin amacı detaylı bir analiz gerçekleştirmek değildir. Bu
    yüzden her değişken için her istatistiği hesaplamanıza veya her
    türlü grafiği çizdirmenize gerek yoktur.

-   Projenin amacı elinizdeki veri seti ile alakalı anlamlı sorular
    sormak ve veri analizi ile bu sorulara anlamlı cevaplar vermek
    olmalıdır.

-   Derste öğrendiğimiz tüm istatistiksel yöntemleri uygulamanıza gerek
    yoktur. Analiziniz için en uygun yöntemin ne olduğuna siz karar
    vermelisiniz. İsterseniz derste öğrenmediğimiz ama kullanmak
    istediğiniz yöntemleri de kullanabilirsiniz, yani derste
    öğrendiğimiz konularla sınırlı kalmak zorunda değilsiniz.

-   Kullandığınız yöntemlerin eksik yanlarını ve analizin nasıl
    geliştirileceğini tartışmanız da faydalı olacaktır.

-   Veriniz ile alakalı güvenirlik ve geçerlilik konuları yanında
    istatistiki analizinizin bu veriye uygunluğunu tartışmanız
    gerekmektedir.

-   Verinizin tümünü tek bir grafik ile görselleştirmeyin. Veriniz ile
    çeşitli görseller oluşturmanız gerekmektedir.

-   İyi hazırlanmış ve detaylara dikkat edilen tek bir grafiğin kötü
    hazırlanmış çok fazla grafikten daha iyi olduğunu unutmayınız.

-   Hangi ek paketleri kullandığınız önemli değildir fakat `tidyverse`
    paketlerini kullanmanız gerekmektedir. [Tidyverse
    Paketleri](https://www.tidyverse.org/packages/). Bu paketlerin
    hepsini kullanmanız gerekmemektedir. Örneğin, Web API ile alakalı
    işler yapmıyorsanız `httr` paketini kullanmanıza gerek yok fakat
    verinizi Excel dosyasından RStudio’ya aktarıyorsanız `readxl`
    paketini kullanmanız gerekiyor.

-   Metin yazımına ve imla kurallarına mümkün olduğunca dikkat ediniz.

-   Tüm analizlerin RStudio’da yapılması gerekmektedir.

## Veri

-   Projede başarılı olmak için veri setinin nispeten küçük fakat
    verilerin kolayca erişilebilir ve birden çok ilişkinin
    keşfedilebilmesi için yeterince büyük olması önemlidir.

-   Veri setinizde en az 50 gözlem ve 10 ila 20 değişken bulunması
    tavsiye edilir. 10’dan az değişken sayısı ile analizinizin zor
    olacağını düşünüyorum. 20’den fazla değişken ise çok fazla
    olacağından üstesinden gelmek zor olabilir. Tavsiyem minimum 10
    maksimum 20 değişken bulmanız. Lütfen “hocam ben 15 değişken buldum
    uygun mu?” tarzı mesajlar atmayınız. 10-20 arası değişken sayıları
    uygundur.

-   Veri setinin kategorik değişkenleri, kesikli sayısal değişkenleri ve
    sürekli sayısal değişkenleri içermesi tavsiye edilir.

-   Dersteki örneklerde veya ödevlerde kullanılan veri setlerini
    projenizde yeniden kullanmayınız.

-   Eğer sorun yaşıyorsanız, çok geç olmadan yardım isteyiniz.

-   **Kaggle sitesinden bulduğunuz veriler kabul edilmeyecektir.**

-   Aşağıda, ilginizi çekebilecek bazı sitelerin linklerini
    bulabilirsiniz:

<table>
<colgroup>
<col style="width: 34%" />
<col style="width: 32%" />
<col style="width: 32%" />
</colgroup>
<tbody>
<tr class="odd">
<td><a href="https://www.aeaweb.org/rfe/showCat.php?cat_id=6">AEA
Resources</a></td>
<td><a href="https://data.ibb.gov.tr/">İBB Açık Veri Portalı</a></td>
<td><a href="http://sanayi.tobb.org.tr/index.php">TOBB Sanayi
Veritabanı</a></td>
</tr>
<tr class="even">
<td><a
href="https://github.com/awesomedata/awesome-public-datasets">Awesome
Public Datasets</a></td>
<td><a href=""></a></td>
<td><a href="http://www.tuik.gov.tr/">TUIK</a></td>
</tr>
<tr class="odd">
<td><a
href="https://cran.r-project.org/web/views/OfficialStatistics.html">CRAN
Official Statistics Task View</a></td>
<td><a href="https://stats.oecd.org/">OECD</a></td>
<td><a href="https://www.census.gov/">US Census</a></td>
</tr>
<tr class="even">
<td><a href="https://ec.europa.eu/eurostat">Eurostat</a></td>
<td><a href="http://openintrostat.github.io/openintro/">OpenIntro
datasets</a></td>
<td><a
href="https://www.nass.usda.gov/Surveys/Guide_to_NASS_Surveys/Ag_Resource_Management/">USDA
ARMS</a></td>
</tr>
<tr class="odd">
<td><a href="http://www.fao.org/faostat/en/#home">FAO</a></td>
<td><a href="https://www.rug.nl/ggdc/productivity/pwt/">Penn World
Tables</a></td>
<td><a href="https://www.nass.usda.gov/Data_and_Statistics/">USDA
NASS</a></td>
</tr>
<tr class="even">
<td><a href="https://fred.stlouisfed.org/">FRED</a></td>
<td><a
href="https://www.icpsr.umich.edu/icpsrweb/content/ICPSR/fenway.html">PRISM
Data Archive Project</a></td>
<td><a href="https://data.worldbank.org/">World Bank</a></td>
</tr>
<tr class="odd">
<td><a href="https://dataverse.harvard.edu/">Harvard Dataverse</a></td>
<td><a href="http://www.sbb.gov.tr/ekonomik-veriler/">SBB</a></td>
<td><a href="https://data.wto.org/">WTO</a></td>
</tr>
<tr class="even">
<td><a href="https://ilostat.ilo.org/">ILO</a></td>
<td><a href="https://evds2.tcmb.gov.tr/">TCMB EVDS</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a
href="https://data.imf.org/?sk=388DFA60-1D26-4ADE-B505-A05A558D9A42&amp;sId=1479329132316">IMF</a></td>
<td><a
href="https://thelittledataset.com/data_code/">thelittledataset.com</a></td>
<td></td>
</tr>
<tr class="even">
<td><a href="https://ipums.org/">IPUMS</a></td>
<td><a
href="https://github.com/rfordatascience/tidytuesday">TidyTuesday</a></td>
<td></td>
</tr>
</tbody>
</table>

## Önemli Tarihler ve Uyarılar

**Proje Önerisi ve Nihai Proje teslimi ekampus sisteminden zip dosyası
yüklenmesi şeklinde gerçekleştirilecektir. Sisteme zip dosyası
yüklemezseniz ara sınav ve finale girmemiş sayılacaksınız.**

**Mazeret (Bütünleme) Sınavınız hem Proje Önerisi (Proje) teslimi hem de
ek bir Sınav şeklinde olacak.**

1.  **Ara Sınav - Proje Önerisi Teslimi:** 28 Nisan 2024, 23:59
2.  **Final Sınavı - Proje Teslimi:** İlan Edilecek

## Proje Önerisi

-   **Proje önerinizi (`ÖğrenciNo.zip` dosyası) İlan Edilecek kadar
    *ekampus.ankara.edu.tr* sistemine yüklemeniz gerekmektedir.**

-   Projede kullanmayı planladığınız veri setini `/data/` klasörüne
    eklemeniz beklenmektedir.

-   Projede kullanmayı planladığınız literatüre ait kaynakça bilgilerini
    `biblio.bib` dosyasına eklemeniz beklenmektedir.

-   Proje önerinizde veri analizi planınızı ve veri setinizi açıklamanız
    beklenmektedir.

-   Proje öneriniz, projenizin giriş bölümü olmalıdır. Projenin nihai
    teslimine, yani dönem sonuna, kadar giriş bölümü üzerinde değişiklik
    yapmaya devam edebilirsiniz.

-   **Bölüm 1 - Giriş:** Bu kısımda aşağıdaki noktaları açıklamanız
    beklenmektedir.

    -   Araştırma sorunuz ve veri setinizi nereden ve nasıl bulduğunuz,

    -   Veride yer alan gözlemler, değişkenler, vs.

    -   Araştırma sorunuz ile alakalı literatür. Okuduğunuz makaleleri
        (makale kelimesi **akademik** makaleler anlamına gelmektedir.
        Blog yazıları, reddit postları veya gazete makaleleri gibi
        makaleleri değil akademik dergilerde basılmış akademik
        makaleleri ifade etmektedir) referans vererek kısaca tartışınız.
        **Her makaleyi ayrı başlık altında tek tek özetlemeyiniz.**
        Literatür taramasında **en az dört** makaleye atıf yapılması ve
        bu makalelerden **en az ikisinin İngilizce** olması
        beklenmektedir.

-   Proje öneriniz **2 sayfadan fazla olmamalıdır (Kaynakça hariç)**.

#### Notlandırma

<table>
<colgroup>
<col style="width: 81%" />
<col style="width: 18%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Veri</td>
<td>30 puan</td>
</tr>
<tr class="even">
<td>Proje Önerisi</td>
<td>40 puan</td>
</tr>
<tr class="odd">
<td>Kaynaklar, organizasyon, kod kalitesi, imla</td>
<td>30 puan</td>
</tr>
<tr class="even">
<td><strong>Toplam</strong></td>
<td><strong>100 puan</strong></td>
</tr>
</tbody>
</table>

## Proje

-   **Projenizin son halini (`ÖğrenciNo.zip` dosyası) İlan Edilecek
    kadar *ekampus.ankara.edu.tr* sistemine yüklemeniz gerekmektedir.**

-   Projenizin son halinde proje önerinizde yapmayı vaat ettiğiniz
    analizi yapmış olmanız beklenmektedir.

    -   **Bölüm 2 - Veri:** Verinizin içeriğini bir özet istatistik
        tablosu ile özetleyiniz ve veride yer alan değişkenler hakkında
        bilgi veriniz.

    -   **Bölüm 3 - Yöntem ve Veri Analizi:**

        -   Araştırma sorunuzu yanıtlamak için kullanacağınız sonuç
            (bağımlı, *Y*) değişkeni ve öngörücü (açıklayıcı, *X*)
            değişkenler hakkında bilgi veriniz.

        -   Varsa kullanacağınız karşılaştırma grupları hakkında bilgi
            veriniz.

        -   Verileriniz hakkında daha fazla bilgi edinmenize yardımcı
            olacak açıklamaların yanı sıra özet istatistikler ve
            görselleştirmeler (grafikler) de dahil olmak üzere ön keşif
            niteliğinde veri analizi gerçekleştiriniz.

        -   Sorularınızı cevaplarken faydalı olacağına inandığınız
            yöntem(ler) hakkında bilgi veriniz.

        -   Kullandığınız yöntemlerin sonuçları (örn. regresyon analizi
            yapmışsanız regresyon sonucu) hakkında bilgi veriniz ve
            gerekli tabloları ekleyiniz.

    -   **Bölüm 4 - Sonuç:** Bu bölümde çalışmanızın sonuçlarını
        özetleyiniz. Sonuçlarınızın başlangıçta belirlediğiniz araştırma
        sorusuna ne derece cevap verdiğini ve ileride bu çalışmanın
        nasıl geliştirilebileceğini tartışınız.

-   Projenizin son halinde bir sayfalık bir özet yazmanız
    beklenmektedir. Bu özet, kullandığınız veri seti, araştırma
    sorularınız, metodolojiniz ve bulgularınız hakkında bilgi
    vermelidir.

-   Özet 10 puan değerindedir, yukarıda yer alan yönlendirmeyi takip
    edip etmediğine ve özlü ancak yeterince ayrıntılı olup olmadığına
    göre değerlendirilecektir.

-   **Her bölüm 2 sayfadan fazla olmamalıdır (Kaynakça, tablolar ve
    şekiller hariç).**

-   **Projede sunulan tüm sonuçların `R` kodu ile türetilmiş olması
    gerekmektedir.** Sonucu oluşturan `R` kodu olmadan verilen
    yanıtlar/sonuçlar eksik kabul edilecektir. `R` kullanmak yerine elle
    hesaplamalar yaparsanız ve ardından hesaplamalardan sonuçları
    bildirirseniz, bu hesaplamalar için puan alamayacaksınız. Nihai
    proje belgenizde bildirilen tüm kodlar düzgün çalışmalıdır. Lütfen
    hata mesajlarına neden olan veya analiz ile ilgili olmayan kodları
    nihai belgeye eklemeyin.

#### Notlandırma

<table>
<colgroup>
<col style="width: 81%" />
<col style="width: 18%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Proje</td>
<td>50 puan</td>
</tr>
<tr class="even">
<td>Özet</td>
<td>10 puan</td>
</tr>
<tr class="odd">
<td>Yeniden Türetilebilirlik</td>
<td>20 puan</td>
</tr>
<tr class="even">
<td>Kaynaklar, organizasyon, kod kalitesi, imla</td>
<td>20 puan</td>
</tr>
<tr class="odd">
<td><strong>Toplam</strong></td>
<td><strong>100 puan</strong></td>
</tr>
</tbody>
</table>

#### Notlandırma Kriterleri

Projeniz aşağıdaki kriterlere göre değerlendirilecektir:

-   *İçerik* - Araştırma ve/veya politika sorusunun kalitesi ve
    verilerin bu sorularla ilgisi nedir?
-   *Doğruluk* - İstatistiksel prosedürler doğru bir şekilde uygulanıyor
    ve açıklanıyor mu?
-   *Yazma ve Sunum* - İstatistiksel sunum, yazı ve açıklamaların
    kalitesi nedir?
-   *Yaratıcılık ve Eleştirel Düşünce* - Proje dikkatlice düşünülmüş mü?
    Sınırlamalar dikkatlice değerlendiriliyor mu? Görünüşe göre projenin
    planlanması ve uygulanması için zaman ve çaba harcanmış mı?

## Klasör Organizasyonu

Proje reponuzda aşağıdaki klasörler ve dosyalar olmalıdır:

-   `/bibliography/`: Kaynakça Klasörü
-   `/bibliography/biblio.bib`: Kaynakça Dosyası
-   `/csl/`: Kaynakça Stil Klasörü
-   `/data/`: CSV, RDS, vs. Formatındaki Veri Setinin Yer aldığı Klasör
-   `/arasinav/`: Proje Önerisi Klasörü
-   `/arasinav/arasinav.Rmd` + `/arasinav/arasinav.pdf`: Proje Önerisi
    Metni
-   `README.Rmd` + `README.md`: README Dosyaları
-   `arasinav.Rproj`: RStudio Proposal Dosyası

Bu projede stil ve biçim önemli olduğundan, lütfen her şeyin iyi
göründüğünden, verilerinizin ve kodunuzun doğru biçimlendirildiğinden
emin olunuz.
