# Araştırma Ödevi


1. Solid Prensiplerini Öğren.
2. Microsoft Build 'den 2 etkinlik araştır.
3. Microsoft Build 2020 yeniliklerini Araştır.
4. Takip Ettiğin 2 yazılımcıyı araştır.
5. Devler Azure'da araştır [Eğitim-Workshop]
6. Yazılım ile ilgili Yarışmaları araştır (Örneğin: GGJ)

**1.Solid Prensipleri**

Solid bir yazılım geliştiricinin esnek ve gelişmeye açık object oriented programlama yaparken
uyması gereken kuralların bir araya getirildiği bir prensiptir. Dünya standartlarında yazılım
geliştirmek için uymamız gereken bu prensipler 5 başlıkta ele alınıyor.


S ingle Responsibility Principle
O pen/Closed Principle
L iskov ‘s Substitution Principle
I nterface Segregation Principle
D ependency Inversion Principle
Bu temel kuralların yanı sıra Kiss, Yangi, Dry, Reuse Release Equivalence, Common Closure
prensipleri de bulunmaktadır.

**1.1.Single Responsibility Principle**

Tek sorumluluk anlamına gelen bu kuralın amacı projede bir değişiklik yapılmak istendiğinde
buna bağlı olarak nelerin etkileneceği düşüncesinden kurtulmak ve özgürce isteğimiz
geliştirmeyi yapabilmemize olanak sağlamaktır. Her bir method sadece kendisine verilen işi
yapar aynı anda birden fazla modeli update etmez, örnek vermek gerekirse bir dizi işi yapan
bir fonksiyon yazmaktansa tüm gereksinimleri parçalara ayırıp bağımsız fonksiyonlar ile
yapmayı gerektiren bir kuraldır. Böylece zaman içerisinde geliştirme yaparken etkilenecek
diğer aşamaları gözden kaçırmanız gibi bir risk oluşmaz.

**1.2.Open/Closed Principle**

Açık kapalı prensibi projemizdeki nesnelerin geliştirmeye açık ama değişime kapalı olmaları
anlamına gelmektedir. Oluşturduğunuz nesneler zaman içerisinde ek özellikler kazanabilir
genişlemeye açık olurlar bu normal bir yazılım projesinde kaçınılmaz bir durumdur. Ama temel
nesne değişime kapalı tutulmalıdır.

**1.3.Liskov ‘s Substitution Principle**

Yerine geçme prensibi kalıtım alarak türeyen sınıfların kalıtım aldıkları nesnenin tüm özellikleri
kullanmalı ve sonrasında kendi özelliklerini barındırmasını hedefleyen bir prensiptir eğer
nesne kalıtım aldığı objenin tüm özelliklerini kullanmaz ise ortaya gereksiz kod yığınları oluşur
ve sonrasında kalıtım alınan objenin diğerlerinden ayrılması için if else bloklarına ihtiyaç olur
ve bu durum son derece verimsiz bir yazılıma sebep olur.

**1.4.Interface Segregation Principle**

Arayüz ayırım prensibi, bir arayüze gerektiğinden fazla yetenek eklenmemesi gerektiğini
söyler. Nesnelerin ihtiyaç duymadıkları fonksiyonların Interface’lerinden münkün olduğunca
ayrıştırılmasıdır.

**1.5.Dependency Inversion Principle**

Bağımlılığın ters çevirilmesi ilkesine göre üst seviye sınıflar, modüller, methodlar vs. alt seviyeli
sınıflara bağımlı olmamalıdır. Alt sınıflarda yapılan değişiklikler üst sınıfları etkilememelidir.
Yüksek seviyeli sınıflar, düşük seviyeli sınıflara bağlı olmamalı, her ikisi de soyut kavramlara
bağlı olmalıdır.

**2. Etkinlikler**

## ÇÖZÜMPARK

![çözümpark](https://user-images.githubusercontent.com/61011022/84431434-f4e24300-ac33-11ea-99e4-6de3897be78c.jpg)


## BİLİŞİM ZİRVESİ

![bilişimzirvesi](https://user-images.githubusercontent.com/61011022/84431919-c44ed900-ac34-11ea-958d-c1d9f846b6ed.jpg)


Etkinlik Tarihi

18 Haziran 2020 / Perşembe / 14:0 0

Konuşmacılar
Başak Berk, Sadi Abalı, Seçil Songür,
Servet Gözel, Tarcan Serdaroglu

**3. Microsoft Build 2020 Yenilikleri**

- Build 2020’de operasyonel veritabanı hizmetlerini ve analitiği gerçek zamanlı olarak bir
araya getiren Azure Synapse Link tanıtıldı. Maliyetleri düşüren ve zaman kazandıran
Azure Synapse Link, veri hareketlerini yönetmeye gerek kalmadan müşterilerin değerli
bilgiler elde etmesini sağlıyor.

- Geliştiricilerin Visual Studio ve Visual Studio Code’dan Teams uygulamaları oluşturmaları
ve yayınlamaları için Microsoft Teams’e, yenilikler sunuldu. Bu yeni yetenekler BT
yöneticilerinin Teams’teki kullanıcıların iş kollarını ve ISV uygulamalarını
değerlendirmesine ve iş dağılımı yapmasına olanak tanıyor.

- Yeni güncellemeler eklenen Fluid Framework, açık kaynak platformu olarak geliştiricilere
sunulmaya başlandı. Böylece Office.com ve Web için Outlook’taki Fluid bileşenleri de son
kullanıcılara sağlanmış oldu.

- Azure Machine Learning ve OSS araçlarına getirilen yeniliklerle müşterilerin yapay zekâ
modellerini daha sorumlu bir şekilde kullanmasına yardımcı olmak için yeni Responsible
ML (Sorumlu Makine Öğrenmesi) araçları sunuldu. Bu araç, model yorumlama yeteneğini
geliştirerek veri güvenliğini ve kullanıcı gizliliği garanti altına alacak, yapay zeka
sistemlerinin geliştirilmesinde sorumluluk anlayışını güçlendirecek.

- Etkinlikte, 1 milyar Windows 10 cihazında birlikte uygulama geliştirmeye yardımcı olmak
için Project Reunion girişimi de tanıtıldı. Project Reunion, Win32 ve UWP API’leri ile
entegrasyonu kolaylaştırmak ve Windows 10 sürümleri kullanılan tüm cihazlarda çalışan
kullanışlı uygulamalar geliştirmek üzere bir “Windows geliştirici platformu” olarak
oluşturuldu.

- Power Automate çözümüne kapsamlı düşük kodlu Robotik Proses Otomasyonu (RPA)
teknolojisini sunmak için yatırımlarını sürdüren Microsoft, düşük kodlu ve kullanımı kolay
RPA geliştirme ortamlarının lider sağlayıcısı Softomotive’i satın aldı. Softomotive’in
teknolojisi, Microsoft müşterilerinin işlerini kolaylaştırmak için kullanıcı arayüzü akışlarına
destek olan çözümler sunmaya başladı.

- Etkinlikte, Azure’da yer alan dünyanın en güçlü süper yapay zekâ bilgisayarları ndan birini
de duyuruldu. OpenAI ile işbirliğiyle özel olarak geliştirilen bu süper bilgisayar gücünü
Azure bulut altyapısından alıyor. Sistem, dağıtılmış devasa yapay zekâ modelleri
geliştirmek için özel olarak tasarlandı.

- Visual Studio ürün ailesiyle Microsoft, her geliştiriciye sınıfının en iyisi araçları
sağlanmaya devam ediyor. Build 2020’de, yeni bir geliştirici kutusu kurmak, yeni bir
projeye katılırken veya uzaktan çalışmaya geçerken ortak bir senaryo oluşturmak
için Visual Studio Codespaces de tanıtıldı. VS Codespaces, geliştiricilerin dakikalar içinde
tamamen yapılandırılmış geliştirme ortamları oluşturması için bulutun gücünden
faydalanıyor.

- Geliştiricilerin bulut deneyimine kesintisiz kod sağlamak için, GitHub Actions for Azure
(Azure için GitHub Eylemleri) platformuna yapılan yeni entegrasyonlar da duyuruldu.
Ekiplerin iş akışlarını kolayca oluşturmasına, test edip yayınlamasına, dağıtmasına ve
otomatikleştirmesine yardımcı olan 30’dan fazla GitHub Eylemi geliştiricilere sunuldu.

- Build 2020’de ayrıca Microsoft’un sağlık sektörüne özgü ilk bulut hizmeti olan Microsoft
Cloud for Healthcare (Sağlık için Microsoft Bulut) tanıtıldı. Hizmet, müşteriler ve iş
ortaklarının hasta bakımını güçlendiriyor, bakım ekiplerinin bağlantılı hizmet yürütmesini
sağlıyor; işbirliği, karar verme ve operasyonel verimliliği artırma yetenekleri sunuyor.
Microsoft Cloud for Healthcare, Teams’teki Bookings uygulaması gibi, sağlık
kurumlarındaki çevrimiçi randevuları zamanlamaya ve yönetmeye yarayan araçlara
destek sağlayacak.

**Platformlar uzaktan çalışmaya özel geliştiriliyor**

Bugün dünyanın en büyük 500 şirketinin %95’inin kullandığı Azure, geliştiricilerin emekleriyle
yeni özelliklere kavuştu. Yapay zekâ destekli botlarla güçlendirilen sağlık uygulamalarından
üretim alanındaki dijital ikizlere; e-ticaret, akıllı perakende ve satış işlemlerine kadar Azure
altyapısı, operasyonların uzaktan yapılabilmesini, simüle edilmesini ve otomatikleştirmesini
sağlıyor. Microsoft 365 ile dünyanın insan merkezli; çok hizmetli, çok yönlü üretkenlik
bulutunu geliştirmeye devam eden Microsoft, bu platform içinde sunduğu Teams ile günlük
75 milyon kullanıcıya ulaştı. Gerçek zamanlı gürültü kesme, parmak kaldıranı tespit etme,
izinsiz katılımları engelleme; düşük bant internette kesintisiz hizmet verme gibi yeni
özelliklerle Teams kullanımı önceki ayların 3 katına çıktı.

Yeni güncellemelerle birlikte Windows 10 işletim sisteminin aylık kullanıcı sayısı 1 milyarı
yakaladı. Bu da Window’u geliştiriciler için vazgeçilmez kılıyor. Bunların yanında, bugün,
uygulamalar, botlar, iş akışları, gösterge panoları oluşturmak için Power Platform’u kullanan
3,5 milyon kişi bulunuyor.

Platform ile kullanıcılar kod kullanmadan uygulamalar geliştirebiliyor, Microsoft 365 ve
Dynamics 365 verilerini özelleştirebiliyor.

**4.Takip Ettiğim Yazılımcılar**

**Engin Demiroğ**

**Hakkında**

Udemy'de 10.000 öğrenciyi geçmiş eğitmenler içerisinde en yüksek eğitmen ortalamasına
sahibim. (120.000+ öğrenci, 4.7 Puan)

Yazılım geliştirmeye lisede "yazılım" bölümünde okurken başladım.

Üniversite hayatıma ÖSS 2003 Türkiye derecesiyle başladım. Sırasıyla Başkent ve ODTÜ'de
Yönetim Bilişim Sistemleri (Lisans-Burslu) ve Tıp Bilişimi(Yüksek Lisans) okudum. Profesyonel
iş hayatıma ise henüz üniversite birinci sınıftayken başladım.

Ağırlıklı olarak Savunma Sanayisi, Bankacılık sektörlerine kurumsal yazılım geliştirme süreçleri
konusunda danışmanlık veriyorum.

Microsoft Certified Trainer (MCT) ,PMP ve ITIL sertifikalarına sahibim.

"Engin Demiroğ" YouTube kanalımda ücretsiz eğitim videoları ve içerikleri paylaşmaktayım.

Danışmanlık yaptığım kurumların bazıları : Merkez Bankası,TAI, Birleşmiş Milletler,NATO,İş
Bankası, Akbank, Halkbank, Vakıfbank, Yapı Kredi Bankası, Ziraat Bankası, Emniyet,
Başbakanlık, Cumhurbaşkanlığı, Hazine Müsteşarlığı, Maliye Bakanlığı, Tarım Bakanlığı,
Tübitak.

Danışmanlık veya eğitim verdiğim kurum sayısı son 10 yılda 300'ü geçmiştir.

DevFramework ismiyle geliştirdiğim altyapı projem birçok kurum ve firmada yazılım geliştirme
altyapısı olarak kullanılmaktadır.

**Selman Kahya**

**Hakkında**

Hem ön uç hem de arka uç sistemleri geliştirme konusunda deneyime sahip kıdemli bir yazılım
mühendisiyim. Birkaç başlangıçta ve Yahoo'da çalıştım, burada her gün milyonlarca
görüntüleme alan birçok kullanıcıyla yüz yüze ürün üzerinde çalışma şansı buldum! Uber'e
katıldım ve son zamanlarda orada çalışıyorum.

Olağanüstü bireysel katılımcı ve fantastik bir takım oyuncusu; ekip çalışmasının gerçek
anlamını gösterir, yol boyunca başkalarıyla iyi ve uzun süreli ilişkiler yaratır.
Stratejik düşünür / uyumsuz; her durumdan en iyi şekilde yararlanmak için çalışıyoruz.
Kendini starter / Bilinmeyenlerden enerji çeken içten motivasyonlu.
Mükemmel kalitede çok bağımsız olarak çalışabilir ve sürekli yeni beceriler geliştirmek için
doğal bir istek duyar.

**5. Devler Azure'da Eğitimler- Workshoplar**

- Yazılım Güvenliği – Bir uygulama nasıl hacklenir?

Etkinliğinin günü ve saati: 09.06.2020 saat 17.

- Mustafa El-Aliwat - Business Development Director , Enqura

- Emre Özer - Technology Director, Enqura

- Azure ile Uygulama Modernizasyonu, Mikroservis mimarileri ve

- Açık Kaynak Kod (Open Source) ışığında en iyi pratiklere sahip yazılım mimarisi

Etkinliğin günü ve saati: 11.06.2020 saat 17.

- Tayyip Osmanoglu - DevOps Engineer , Albarakaturk

- Pamir Erdem - Azure Specialist, Microsoft Türkiye Kubernetes Networking

Etkinliğin günü ve saati: 16.06.2020 saat 17.

- Oguz Yarımtepe - Site Reliability Engineer Team Lead , GittiGidiyor

- Pamir Erdem - Azure Specialist, Microsoft Türkiye

- Kubernetes Hybrid Monitoring

Etkinliğin günü ve saati: 18.06.2020 saat 17.

- Alper Hankendi - Director of Engineering , HepsiBurada TBD

Etkinliğin günü ve saati: 23.06.2020 saat 17.

- Mustafa Yağımlı - Big Data Development Manager, HepsiBurada TBD

Etkinliğin günü ve saati: 25.06.2020 saat 17.

**6.Yazılım ile ilgili Yarışmalar**

Hackhathon
