# Etiklik Kontrol Lisansı

![Logo](https://cdn.discordapp.com/attachments/814960684705513482/973973135122661406/ART.png)

> Merhaba ben Magdalena Sude. Uzun zamandır Discord Botları ve sistemleriyle uğraşıyordum. Birçok insan yazılım dillerine ve dahasına Discord.JS sayesinde başladı. Çat pat sistemler yaparak, kopyalayarak ve araştırarak yeni özelllikler keşfetti. Bunu devam ettirebilenler ise gelecekte bu işin ustaları olarak yer alacaklar. Bundan dolayı hala Discord Botları ile uğraşan kişiler mevcutsa çoğu yerde geçerliliği olan bir lisans yaratmaya karar verdim. Herhangi bir Legal karşılığı bulunmasa da Etiklik Kontrol Lisansı bulunan herhangi bir botun kaliteli olacağına emin olabilirsiniz.

### İşbu Lisansı (ECL) Nasıl Elde Ederim?
> Etiklik Kontrol Lisansını alabilmek için Discord üzerinden **Luzia#0001** ile iletişim kurabilirsin. Aşağıda belirtlen kurallar bütününe uyuyorsan ve bu lisansı almak istiyorsan (*ücretsiz*) başvuru yapmayı unutma.

### Tanımlamalar
> Yeni bir Discord Botu yapmaya karar vermişseniz doğru noktadasınız. Şu zamana geldiğimizde birçok Discord Botu fikrinin oluştuğunu görmüşsünüzdür. Her türden ve her amaca hizmet eden botları keşfedebilir onlarla sunucunuzdaki deneyimi arttırabilirsiniz. Yeni bir Public Bot (Halka Açık) yapmak istiyorsanız mutlaka yeni fikirleriniz olmalı. Eski çağdan kalma bir Moderasyon botu, basit komutları bulunduran bir Ekonomi Botu, Türkiye'de bulunan ve sadece Public sunuculara hizmet edebilecek Kayıt Botları, Gereksiz veya işlevsiz Botlar ve Çok Kompleks botlar yapmamalısınız. Her zaman yeni fikirli olup eskiden gelse bile ileriye dönük geliştirilebilir içeriği olan botları yaratmalısınız.

 - **Yenilikçi** ve **ileriye dönük** komutlar,
 - En **yeni** Discord.JS veya Discord.PY (vs.) sürümlerini kullanması,
 - **Eğik çizgi** komutları (Esnetilebilir),
 - Yeni gelen **özellikleri** kullanması (butonlar ve menüler gibi),
 -  Gereksiz **gömülü mesajlar** veya **mesajlar** içermemesi,
 - **Çalma** veya **kopyalama** yapılmaması,
 - **MongoDB** veya **MySQL** gibi güçlü veritabanlarından birisini kullanması,
 - Gerçek para ile satılan özelliklerin **güçlü** olması,
 - **Yasaklı komutları** bulundurmaması.

Bir Bot üstteki listeye uyuyorsa Etiklik Kontrol Lisansını alabilir ve bu Github'da sergilenir.

## Yenilikçi ve İleriye Dönük Komutlar
> Her zaman en iyi ve farklı komutları yazmanız gerekiyor. Botunuz her yönden eşsiz olmalı. Başka bir bota ihtiyaç duyulmadan sadece sizin botunuza ihtiyaç duyarak bir kısım gerekliliği tamamen üstlenmelisiniz. Yani şunu diyorum, sunucuda Moderasyon ihtiyacı varsa sizin botunuz tek başına bütün sunucunun Moderasyon ihtiyacını karşılayabilmeli. (İstisnalar: Birçok aynı botu gerektiren Public Sunuculardaki Moderasyon Botları vb.)

## En Yeni DJS veya DPY Sürümlerini Kullanması
> Sadece DJS veya DPY değil, herhangi başka bir framework kullanıyorsanız bu durum onlar için geçerli. Discord.JS için kabul edilebilir sürüm ise şu anlık V13.

## Eğik Çizgi Komutları
> Yeni olan çoğu bot artık eğik çizgi komutlarına geçiş yapıyor. Discord.JS V13'te de artık desteklenen Eğik Çizgi komutlarına geçme vakti geldi. Bütün bot komutlarını Eğik çizgi halinde yapmaktan bahsetmiyoruz birkaç normal komut kullanabilirsiniz fakat çoğunluk Eğik Çizgi komutlarını oluşturmalı. (*Yine de son zamanlara kadar Eğik Çizgi komutlarını kullanma zorunluluğu yoktur.*)

> Eğik Çizgilerle ilgili konuşmak gerekirse bir eğik çizgi bütün komutu olabildiğince sade şekilde anlatmalı. Her kısımda yardımcı olmalı ve ona göre önermeler yapmalı. Hiçbir zaman anlamsız Eğik Çizgi açıklamalarınız olmamalı. Örnek komutlar aşağıda yer alacak.

![Fotoğraf 12](https://kayra.pls-fuck.me/3XLQS7F.png)

Üstte belirtilen hesap oluşturma komutunda bilgiler yer alıyor.

![Fotoğraf 13](https://kayra.pls-fuck.me/xQbW3iF.png)

Burada ise e-postayı ne amaçla istediğimiz gibi bilgileri yazabiliyoruz.

![Fotoğraf 14](https://kayra.pls-fuck.me/7eubL8W.png)

Gerekiyorsa ek olarak açıklama belirtmelisiniz. Hangi süre formatına uymalı? Nasıl kullanılmalı? Gibi belirtimler şarttır.

![Fotoğraf 15](https://kayra.pls-fuck.me/8BvpjnW.png)

Sade eğik çizgi komutları yaratmaktan kaçınmayın.

## Yeni Gelen Özellikleri Kullanması.
> Artık yeni sayılmasa da Discord'a yeni gelen özellikleri botunuzda kullanmaya başlamalısınız. Buna örnek olarak verilebilecek Butonlar, menüler, Form gönderme vb. örnek verilebilir

## Gereksiz Gömülü Mesajlar (Embeds) ve Mesajlar İçermemesi
> Botunuzu inşa ederken gözünüze Embed'lerin çok hoş geldiğini biliyorum. İlk başladığımda ben de bütün mesajlarımı Embed şeklinde yapıyordum fakat bu oldukça yanlış. Her yerde Embed kullanmak yerine normal Mesajı tercih etmelisiniz. Hadi nerede Embed kullanabilirsiniz göz atalım.

- Fazlasıyla bilgi verdiğiniz bir yerde. (Mesela hesap durumunuzu kontrol ediyorsunuz.)
- Bazı komutlarda işlevsellik katmak için. (Yani normal mesajlar Embedler kadar özelleştirilemeyebilir. Bundan dolayı normal mesaj ile yapamayacağınız komutları Embed ile yapmalısınız.)
- Çoğunlukla Buton veya Menüleri kullanırken. (Eğer Embed içeriği küçük olacaksa bu işe de girişmeyin.)
- Zorunlu olarak `.setAuthor()` veya `.setFooter()` kullanımlarında.
- Genel olarak Masaüstü PC'lerde veya Mac'lerde çalıştırılacak komut kullanımlarında. (Yani Mobil kullanım dışı komutlar için.)
- Yanlış noktalama işaretleri içermemeli. (Şunun gibi: "`Selam Dünya !`" ünlem işareti bitişik yazılır.)
- Çok fazla Emoji içermemesi gerekir. İçerdiği Emojiler ise `default` emojiler olursa daha iyi olur.

### Doğru Gömülü Mesajlar

![Fotoğraf 1](https://cdn.discordapp.com/attachments/814960684705513482/973969869718568990/Ekran_Resmi_2022-05-11_17.28.10.png)

Üstteki Gömülü Mesaj bir kanalın tek mesajı olacağı için ufak mesaj barındırsa dahi Gömülü Mesaj olarak atıldı. Gereksiz görüldüğü için `footer` ve `title` kullanılmadı. Gri renkli buton kullanıldı. (Sadelik açısından.)

![Fotoğraf 4](https://kayra.pls-fuck.me/65DcvSN.png)

Üstteki fotoğraf bir Log görüntüsü. Log görüntülerinde `author` ve `footer` gereksiz kullanımlarına fazla dikkat edilmeyebilir. Sadelikten daha çok burada aranan şey ne kadar işlevli olduğu oluyor. İki tarih belirtilmiş bu tarihlerden birincisi cezanın uygulandığı tarih iken diğer tarih cezanın bitişini net olarak gösteren diğer tarih. İşlevsellikten ve sadelikten ödün vermemek için log numarası `#8` olarak en başta belirtilmiş. Ekstra olarak kopyalamalar ve diğer içerikler için orta kısımda daha geniş bilgi veriliyor.

![Fotoğraf 5](https://kayra.pls-fuck.me/8dmjRhz.png)

Üstteki doğru kullanım ise diğer bir Log görüntüsü ise mesaj raporlama ile alakalı. Bu raporlama örneği direk mesajın raporlandığını belirtiyor.

![Fotoğraf 6](https://kayra.pls-fuck.me/3Q5VeTf.png)

Üstteki fotoğrafta ise basit susturma mesajını görebilirsiniz. Bu mesaj kanala atılıyor ve log ile alakası yok. Oldukça sade ve normal mesaj kullanılmış.

![Fotoğraf 7](https://kayra.pls-fuck.me/6rSDTz8.png)

Burada ise bir sicil komutunu görüntüleyebilirsiniz. Sicil komutlarını normal mesajlarla yapmanızı **önermiyoruz**. Bunun sebebi birçok bilgi yer alması gereken komutlarda Embed büyüse bile (*istisnai durumlar genelde gömülü mesajlar büyük olmamalı.*) sicil gibi komutlarda zorunlu olarak alta doğru genişlemeli. 

**İPUCU:** Sicil komutunu iki komuta bölebilirsiniz. Normal sicil ve genişletilmiş olarak. Normal sicil en son alınan beş cezayı lanse ederken genişletilmiş sicil gömülü mesaj sayfaları ile yapılabilir veya kod blokları kullanılabilir.

![Fotoğraf 9](https://kayra.pls-fuck.me/3A21VZb.png)

Oldukça hoş duran bir anlaşma kabul mesajıyla karşınızdayız. Gömülü mesaj kullanılmadan başka bir yere aktarım suretiyle anlaşmayı kabul etmenize olanak sağlıyor. Belki bu anlaşma kabulünü görünmez mesaj olarak lanse edebilirsiniz.

![Fotoğraf 11](https://kayra.pls-fuck.me/SMpCg2Z.png)

Çok basit ve gömülü mesaja ihtiyaç duyulmadan oluşturulmuş bir hesap bilgi komutu.

### Yanlış Gömülü Mesajlar

![Fotoğraf 2](https://cdn.discordapp.com/attachments/814960684705513482/973970497761050664/Ekran_Resmi_2022-05-11_17.30.43.png)

Üstteki gömülü mesajda birçok etiklik ve sadelik problemi mevcut. İlk olarak `footer` ve `author` aynı amaca hizmet etmiş. Ya `footer`'dan ya da `author`'dan vazgeçilmeli. Aynı zamanda `timestamp` eklemek saçma çünkü Bot yazısının hemen yanında zaten zamanı görebilirsin. (İpucu: `XX | bugün saat 15:20` gibi kullanımlar artık eskidi.) Bir Gömülü Mesajın içerisinde fazla etiket bulunmamalı. Bundan dolayı  `@Yiğit` kullanımı yerine `Yiğit#0001` veya sadece `Yiğit` kişisi kullanılabilir.

![Fotoğraf 3](https://cdn.discordapp.com/attachments/902302627767918602/973891836861112320/IMG_1354.png)

Üstteki fotoğrafta ise yine `footer` kullanımı görüyoruz. Bu `footer` kullanımı çok saçma çünkü Bot zaten cevabını verdiği kişi belli. Noktalama işaretlerinde hata yapmış ve bir sürü emoji kullanılmış.

![Fotoğraf 8](https://kayra.pls-fuck.me/9pwY4VH.png)

Üstteki fotoğrafta gömülü mesaj yanlış kullanılmış. Bir gömülü mesajın boşluklu şekilde alta genişlemesi hoş durmaz. Bunun yerine alabilecek en büyük işlevsellik, sadelik denkleminde az büyümesidir. Yani bir gömülü mesaj olabildiğince işlevsel olmalı, sade olmalı, büyük olmamalı ve karışık olmamalı. Ek olarak buradaki `author` kullanımı gereksiz kaçmış olabilir. O bölüme komutu kullanan kişi yerine başka bilgilendirmeler yazabilirdi.

![Fotoğraf 10](https://kayra.pls-fuck.me/3cVG1QC.png)

Oldukça doğru gözüken bir yardım komutu ile karşılaştık. Bu yardım komutunda iki kısım hatalı. Birincisi zaten botun hangi bot olduğunu biliyoruz ekstra `author`'a ihtiyacımız yok. En sonda belirtilen komut linkleri ise en üstte yinelenmiş. Onun dışında emoji kullanımları doğru ve güzel dille yazılmış.

### Çalma veya Kopylama Yapılmaması
> Herkes farklı komutlardan esinlenebilir veya yeni bir komut yaratmak istediğiniz zaman farklı botlardan özellikleri ekleyebilirsiniz. Bu çok normal ve gerekli. Fakat kırmızı çizgiyi aşmamanız gerekiyor. 35%'den fazla çalıntı veya kopyalama kodlar bulunan hiçbir botu veya içeriği kabul etmiyoruz. 

### MongoDB veya MySQL gibi Veritabanlarını Kullanması
> Eski moda olan ve hiçbir şekilde iyi tecrübeler yaşatmayan `quick.db` ve türevlerini kabul etmiyoruz. İyi bir bot için kesinlikle Cloud veya Local anlamda öncü veritabanları kullanılmalı.

### Gerçek Para İle Satılan Özelliklerin Güçlü Olması
> Botunuz üzerinde bir Premium veya VIP üyelik sisteminin olduğunu farzedecek olursak bu özelliklerin yersiz olmaması gerektiğini söylemeliyiz. Botlarda bu tür sistemler tasarlayan ekibi güçlendirse ve destek olsa bile dilencilik adı altında hiçbir satış yapmamalısınız.

### Yasaklı Komutları Bulundurmamalı
> Bütün komutlarınız Discord ve bizim belirlediğimiz kurallara (*Discord'da Terms of Service*) uymalı. Bu tespit edilirse botunuz onay alamaz.

## Etiklik Kontrol Lisansı Alındıktan Sonra
> Herhangi bir EC-Lisansı aldıktan sonra o bot için altı haneli (`TR0001` veya `PL0002` cinsinden) kod oluşturulur. Bu kod sadece bota özgüdür ve botun kimliğini oluşturur. Bot kimliğini kontrol etmek için [bu adresten](https://google.com) kontrol kısmına ulaşabilirsiniz.

Her lisanslı bot ayın 15'inde kontrole tabii tutulur. Bu kontrolün aşamaları şunlardır;

- Bot lisans aldıktan sonra herhangi bir kurala riayetsizlik etmiş mi?
- Bot içerisinde lisans aleyhinde herhangi bir durum ilan etmiş mi?
- Bot sitesinde, Top.GG veya türevi sitelerinde EC-Lisans bildirisini silmiş mi?
- Bot ECL üzerinden herhangi bir şikayet almış mı?

## Neden Bu Lisansa İhtiyaç Duyalım?
> Üstte de bahsettiğim gibi hiçbir ihtiyacınız yok veya buna ihtiyaç duymuyorsunuz. EC-Lisans ailesine katılarak şu özellikleri kazanma şansı sunuyoruz;

- Herhangi bir muhalefette EC-Lisans ekibi sizin yerinize botunuzu koruyabilir. (*Diyelim ki bir hırsızlık yaşandı veya bot kullanıcıları bot geliştiricileri ile muhalefete düştüler. Resmi açıklamalar ve insan ilişkileri koruması açısından yardımcı oluruz. Bunu şunun gibi yapabiliriz; "X Botu EC-Lisans kapsamında bütün kurallara riayet ediyor. Bundan dolayı herhangi bir negativite söz konusu olamaz."*)
- EC-Lisans sahipli botlar gelişerek aileyi büyütüyor. Bu bir çok arkadaşlık ve çevre imkanı sağlayabilir.
- EC-Lisans Github sayfasında botlarınızın isimleri ve reklamları yer alıyor.
- EC-Lisans özgün ve eşi benzeri olmayan bir proje.

> Sizden istediğimiz talepler nedir?

- EC-Lisans ailesinde bulunduğunuz süre boyunca belirlediğimiz kurallara riayet etmeniz. (*Etiklik kuralları.*)
- Herhangi bir muhalefette ana çözücü olarak bir yetkilimizi görevlendirmenizi istiyoruz. (*Diyelim ki bir problem çıktı ve SOS ekibi kurmak zorunda kaldınız. EC-Lisans'tan bir yetkilimiz size yardımcı olmak ve işlerinizi yoluna sokmak için yanınızda olacak.*)
- EC-Lisans birçok tarafı birbiriyle bağlayan bir köprü görevi görüyor. Bundan dolayı yeni arkadaşlık ilişkilerine hazır olmalısınız.
- EC-Lisans ailesinden veya çalıştığımız partnerlerimizden birisi herhangi bir sorun yaşarsa onlara yardım etmeye **mükellef değilsiniz** fakat yardımcı olursanız bu iki taraf için de iyi olur.
- Her ayın 15'inde yaptığımız uygunluk testlerinde zorluk çıkmasını istemeyiz.
