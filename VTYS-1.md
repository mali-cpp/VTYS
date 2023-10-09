Öğrenci İsim-Soyisim: **Mehmet Ali Emiroğlu**
Öğrenci No: **223010710022**

**VTYS-ODEV-1**

					

## Veri Tabanı Ve Tarihçesi

Bilgiye ve bilginin saklanmasına farklı sebeplerden dolayı geçmişte ve günümüzde büyük oranda ihtiyaç duyulmuştur. Bunun doğrultusunda veritabanına ihtiyaç duyulmuştur.

**Veritabanı Nedir?**
Veritabanı, (database) herhangi bir konuda birbiriyle ilişkili olan ve amaca uygun olarak düzenlenmiş, mantıksal ve fiziksel olarak tanımlanmış veriler bütünüdür. Bununla birlikte her düzenli veri topluluğunu veritabanı olarak tanımlamak da doğru değildir.


**Veritabanının Özellikleri**

 - Veritabanı herhangi bir kurumda birden fazla uygulamada ortak olarak kullanılabilen verilerden oluşur.
 - Veritabanında sürekli niteliği olan veriler bulunur. Buna göre, girdi ya da çıktı verisi olan ya da kurum için sürekli bir anlam ifade etmeyen geçici veriler veritabanında yer almaz.
 - Veritabanı, ortak kullanılan verilerin tekrarlanmasına izin vermeden çok amaçlı kullanılmasına olanak verir.
 - Veritabanında saklanan veriler durağan nitelikte değişmez veriler değildir. Ekleme, silme ya da güncelleme işlemleri ile veritabanındaki veriler değiştirilebilir
 
 **

**NOT**:Veritabanı Yönetim Sistemi (VTYS-Database Management System); veritabanı tanımlamak, veritabanı oluşturmak, veritabanında işlem yapmak, veritabanının farklı kullanıcı yetkilerini belirlemek, veritabanının bakımını ve yedeklemesini yapmak için geliştirilmiş programlar bütünüdür.


## Veritabanı Kullanımının Bazı Avantajları

 - Gereksiz veri tekrarı ve veri tutarsızlığının önlenmesi
 - Veri bütünlüğünün sağlanması
 - Veri paylaşımının sağlanması
 - Kullanımda üst düzey uzmanlık gerektirmemesi
 - Verilerin gizliliğinin ve güvenliğinin sağlanması
 - Standart yapı ve kuralların uygulanabilir olması
 

## Veritabanı Kullanıcıları
Veritabanı ile herhangi bir şekilde etkileşimde olan kişi ya da kişiler veritabanı kullanıcısı olup aşağıdaki gibi sınıflandırılabilirler:

 - **Veritabanı Sorumluları**
*Veritabanı sorumluları, veritabanının tasarlanması, oluşturulması ve veritabanının işletim faaliyetlerinden birinci derecede sorumlu olan ve veritabanı üzerinde en fazla yetkiye sahip olan kullanıcılardır. Veritabanı sorumluları, veritabanı yöneticisi ve veritabanı tasarımcısı olarak iki başlık altında incelenebilir.
		**Veritabanı Yöneticisi**
			Veritabanı yöneticisinin (database administrator) veritabanına erişim yetkilerini belirleme, veritabanı kullanımının düzenlenmesi ve izlenmesini sağlama, ihtiyaç duyulan yazılım ve donanım kaynaklarını edinme biçiminde sıralanan sorumlulukları vardır. Ayrıca güvenlik ihlalleri ve kötü sistem yanıt süresi gibi sorunların çözümünden de sorumludur. Büyük işletmelerde bu sorumluluklar için yardımcı personele de ihtiyaç duyulur.
			**Veritabanı Tasarımcısı**
			Veritabanı tasarımcısı (database designer) veritabanında saklanacak olan verilerin tanımlanmasından ve bu verilerin depolanması ve gösterilmesi için gerekli olan uygun yapıların seçilmesinden sorumludur.
				**Veritabanı Tasarımcısının Bazı Sorumlulukları:**
			
	- Veritabanı tasarımını yapma
	- Bütünlük kısıtlamalarını belirleyip tanımlama
	- Veritabanı kullanım yetkilerini tanımlama
	- Veritabanı güvenliğini sağlama
	- Güncelleme ihtiyaçlarına cevap verebilme
	- Veritabanından beklenen performansı sağlama
	
**Son Kullanıcılar**
 - Standart Son Kullanıcılar:
		 - Veritabanına nadiren erişim yapan fakat her seferinde farklı bilgi ihtiyacı olabilen kullanıcılardır. Bu tür kullanıcılar isteklerini belirtmek için gelişmiş veritabanı sorgu dili kullanırlar. Orta ya da üst düzey yöneticiler bu gruba örnek verilebilir.
	
-	Sıradan Ya Da Parametrik Son Kullanıcılar:
		Son kullanıcıların önemli bir bölümünü bu tür kullanıcılar oluşturur. Bu kullanıcıların temel iş fonksiyonları, veritabanı üzerinde sürekli bir sorgulama ve güncelleme yapmalarını gerektirir. Standart (önceden belirlenmiş) sorgu ve güncelleme yaparlar. Bu gruba giren kullanıcılar çok çeşitli konum ve görevlerde olabilirler

-	Gelişmiş Son Kullanıcılar:
			VTYS’nin sağladığı özellikler yardımıyla ayrıntılı olarak belirledikleri karmaşık gereksinimlerini karşılamak amacıyla veritabanını kullanan gruptur. Mühendisler, bilim adamları, işletme analistleri vb. bu gruptaki kullanıcılara örnek olarak verilebilir.
		
-	Bağımsız Son Kullanıcılar
		Bu kullanıcılar menü kullanımı ya da araç çubukları gibi grafiksel ögeler yardımıyla kullanım kolaylığı sağlayan hazır paket programlarını kullanarak kişisel veritabanlarının sürekliliğini sağlar. Vergilere ilişkin olarak hazırlanan ve kişisel finansal verileri depolayan vergi paketi kullanıcıları bu tür kullanıcılara verilebilecek bir örnektir.



**Sistem Analistleri ve Uygulama Programcıları**
Sistem analisti son kullanıcıların, özellikle de sıradan son kullanıcıların gereksinimlerini belirleyen ve standart işlemler yoluyla bu gereksinimleri karşılayabilecek ayrıntıları belirleyen kişi ya da kişilerdir. Uygulama programcıları ise sistem analisti tarafından belirlenen ayrıntıları program hâline getiren ve daha sonra test eden, hataları ayıklayan, belgeleyen ve kaydedilmiş işlemler olarak sürekliliğini sağlayan kişilerdir. Yaygın olarak yazılım geliştiriciler ya da yazılım mühendisleri olarak da anılan analistler ve programcıların yukarıda sıralanan görevlerini yerine getirebilmeleri için VTYS’nin sağladığı tüm özellikleri bilmeleri gerekir.


**

## VERİTABANI YÖNETİM SİSTEMLERİNİN MİMARİSİ

**VTYS’lerinin mimarisi geçmişten günümüze incelendiğinde, ilk veritabanı sistemlerinde, VTYS’nin tüm yazılım paketlerinin tek bir sisteme entegre edildiği, modern VTYS’lerinde ise istemci/sunucu mimarisi ile modüler bir yapılanmanın sözkonusu olduğu görülmektedir

**Veri Modelleri**
Veritabanı yaklaşımının temel karakteristiklerinden biri, veritabanının bazı veri soyutlama düzeyleri sağlamasıdır. Veri soyutlama (data abstraction), verilerin düzenlenmesi ve depolanmasına ilişkin ayrıntıların gizlenmesi ve verinin daha iyi anlaşılmasını sağlamak için veriye ilişkin temel özelliklerin vurgulanması anlamına gelir. Veri modeli ise söz konusu bu soyutlamaları gerçekleştirebilmek için gerekli olan araçları sağlar. Veri modeli (data model), bir veritabanının mantıksal yapısını tanımlamada kullanılacak kavramlar, işlemler ve kurallar bütünüdür. Veritabanının mantıksal yapısı; veri tipleri, veriler arasındaki ilişkiler, veri üzerinde uygulanacak kısıtlamalar vb. dir.

**Veri Modellerinin Sınıflandırılması**

Yüksek düzeyli ya da kavramsal veri modelleri (conceptual data models), kullanıcıların veri algılama biçimiyle ilişkili kavramları kapsar. Düşük düzeyli ya da fiziksel veri modelleri (physical data models), verinin bilgisayar ortamında nasıl depolanacağına ilişkin ayrıntıları tanımlayan kavramları kapsar. Fiziksel veri modelleri kavramları genellikle son kullanıcılar için değil, bilgisayar uzmanları için geliştirilir.


**Şemalar, Örnekler ve Veritabanının Durumu**

Veritabanının herhangi bir veri modeliyle tanımlanması veritabanı şeması (database schema) olarak adlandırılır. Sözkonusu bu şema veritabanının tasarlanması sürecinde oluşturulur ve sık sık değişiklik göstermez. Veri modellerinin çoğunda şemaların bir diyagram olarak gösterilebilmesi amacıyla kullanılan belirli kuralları vardır.


**

## Üç Şema Mimarisi

Veritabanı yaklaşımının önemli karakteristikleri aşağıdaki biçimde sıralanabilir:

 - Veritabanı tanımlarını (şema) depolamak için kendi kendine tanım yapabilmeyi sağlayan bir katalog kullanır.
 - Veri ve program izolasyonunu sağlar (program – veri bağımsızlığı; program – işlem bağımsızlığı)
 - Çoklu kullanıcıyı destekler

Üç şema mimarisinin amacı kullanıcı uygulamalarını fiziksel veritabanından ayırt etmektir. Bu mimaride şemalar izleyen üç düzeyde tanımlanır:

 1. **İçsel (fiziksel) düzey**: (internal level), veritabanının fiziksel depolama yapısını tanımlayan içsel şemayı içerir. İçsel şema, veriyi depolama ayrıntılarının tamamını ve veritabanına erişim yollarını tanımlayan fiziksel veri modelini kullanır.
 2. **Kavramsal düzey**: (conceptual level), kullanıcı topluluğu için tüm veritabanının yapısını tanımlayan kavramsal şemayı içerir. Kavramsal şema fiziksel depolama yapısının ayrıntılarını gizler ve veritabanında yer alan verilerin tipine, veriler arası ilişkilere, kullanıcı işlemlerine ve kısıtlara ilişkin tanımlara yoğunlaşır.
 3. **Dışsal (görünüm) düzey**: (external level), bir dizi dışsal şema ya da kullanıcı görünümü içerir. Her dışsal şema bir grup kullanıcının ilgilendiği bazı veritabanı bölümlerini tanımlar. Böylece veritabanının diğer kısmı bu kullanıcı grubundan gizlenir.



**

## VERİ BAĞIMSIZLIĞI

**Şema düzeyleri arasındaki dönüştürme kapasitesi olarak tanımlanabilen veri bağımsızlığı (data independence) yine üç şema mimarisi ile açıklanabilir. Veri bağımsızlığı iki başlıkta ele alınır:

 1. **Mantıksal veri bağımsızlığı (logical data independence)**:Kavramsal şemanın dışsal şemalarda ya da uygulama programlarında değişiklik yapılmaksızın değiştirilebilmesi anlamına gelir.
 2. **Fiziksel veri bağımsızlığı (physical data independence)**:Kavramsal şemada bir değişiklik yapılmaksızın içsel şemada değişiklik yapma kapasitesidir. Buna bağlı olarak içsel şemada yapılan değişiklik dışsal şemalarda da bir değişiklik yapılmasını gerektirmez.



**

## VERİTABANI TÜRLERİ

**Her veritabanı yönetim sistemi bir veri modeli kullanır.Veritabanında yer alacak veriler ve veriler arasında kurulacak ilişkiler mantıksal olarak ilgili veri modeline göre yapılandırılır ve veritabanları da buna göre sınıflandırılır.Geçmişten günümüze kadar geliştirilmiş olan çok sayıda veri modeli, kullandıkları teknikler açısından dört temel başlıkta incelenir. Bu dört veri modelinden hangisini kullandığına bağlı olarak veritabanları da aşağıda verilen dört başlık altında sınıflandırılabilir:

 1. **Hiyerarşik veritabanı (Hierarchical database)**:
		-	Bu yapı, başlangıç noktası ağacın kökü, bağlantılı kılınacak noktalar dallar ve ana dallara bağlı alt dallar olarak düşünülebilen bir yapı biçimindedir. Buna göre veriler arasındaki ilişkilerde hiyerarşinin üst bölümünde olan dallar alt bölümde birden çok dal ile bağlantılı olabilirken alt bölümünde olan dallar üstte kalan dallara yalnızca tek bir noktadan bağlantılı olabilirler.
 2. **Ağ veritabanı (Network database)**:
		 -	Ağ veritabanı modeline göre her bağlantı noktası düğüm olarak ifade edilirse hiyerarşik yapıdan farklı olarak ağ veri modelinde, her düğümün birden fazla ebeveyn ve birden fazla çocuk düğümü ile bağlantısı olabilir.
 3. **İlişkisel veritabanı (Relational database)**:
		-	Bu yapıda ilk iki veri modelinden farklı olarak birden çok ilişki biçimi kullanılabilir. Günümüzde kullanılan veritabanı yönetim sistemlerinin hemen hemen hepsinde tercih edilen model ilişkisel veri modelidir.
 4. **Nesneye yönelik veritabanı (Object oriented database)**:
		 -	Yalnızca harf, rakam ya da çeşitli karakterler kullanılarak yapılandırılmış verileri değil aynı zamanda multimedya (çeşitli çizim, fotoğraf, görüntü, ses ya da video gibi nesneleri) de içeren veritabanı yönetim sistemidir.


**

## VERİTABANI YÖNETİM SİSTEMİ YAZILIMLARI

 1. MS SQL Server
 2. Oracle
 3. MySQL
 4. Sybase
 5. PostgreSQL
 6. MS Access
 7. DB2
