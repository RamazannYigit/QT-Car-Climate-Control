PCAN Entegrasyonu ile QT Araç İklim Kontrolü

Türkçe
Bu proje, QT framework kullanarak gelişmiş bir araç klima kontrol sistemi uygulaması olup, aracın sistemleri ile gerçek zamanlı veri alışverişi için PCAN (CAN bus) iletişimini entegre etmektedir.

Proje Genel Bakış
QT Araç Klima Kontrol uygulaması, bir aracın klima sistemini izlemek ve kontrol etmek için gelişmiş bir arayüz sunar. Aracın CAN bus'ı ile çift yönlü iletişim için PCAN (Peak CAN) donanımını kullanarak, çeşitli klima parametrelerinin gerçek zamanlı veri alımını ve kontrolünü sağlar.

Özellikler
·Gerçek zamanlı sıcaklık kontrolü ve izleme
·Çoklu seviyeli fan hızı ayarı
·Hava yönü ayarları (yüz, ayak, buz çözme)
·Optimal klima yönetimi için otomatik mod
·PCAN aracılığıyla aracın CAN bus'ı ile entegrasyon
·Klima parametrelerinin veri kaydı ve görselleştirmesi
·QT ile tasarlanmış kullanıcı dostu arayüz

Teknik Detaylar

·PCAN İletişimi:
Araç sensörlerinden gerçek zamanlı veri alımı (sıcaklık, nem, vb.)
Klima ayarlarını düzenlemek için kontrol komutları gönderimi
Sağlam çalışma için hata yönetimi ve veri doğrulama uygulaması

·QT Framework:
Duyarlı ve sezgisel bir kullanıcı arayüzü oluşturmak için QT kullanımı
Veri işleme sırasında sorunsuz UI performansı için çoklu iş parçacığı uygulaması

·Veri İşleme:
CAN mesajlarının gerçek zamanlı ayrıştırılması ve yorumlanması
İstenilen klima koşullarını korumak için algoritmik kontrol

Teknolojiler ve Araçlar
·QT Framework
·C++
·PCAN-Basic API
·CAN bus protokolü
·Versiyon kontrolü için Git

Kurulum ve Yükleme
Projeyi kurmak ve çalıştırmak için aşağıdaki adımları izleyin:
1.Gerekli Yazılımlar:
·QT
·Git
·PCAN-Basic API
2.Bu yazılımları bilgisayarınıza yükleyin.
3.Projeyi indirin:
4.QT Creator'ı açın.
5.QT Creator içerisinden "Open Project" seçeneğine tıklayın.
6.İndirdiğiniz proje klasöründeki CMakeLists.txt dosyasını seçin ve açın.
7.QT Creator, tüm proje dosyalarını doğrulayıp ekranınıza getirecektir.
8.Artık projeyi derleyebilir ve çalıştırabilirsiniz.

Kullanım
1.PCAN cihazını araca bağlayın.
2.Uygulamayı başlatın.
3.Uygulama arayüzünde, yapmak istediğiniz işleme karşılık gelen butona veya seçeneğe tıklayın.
4.Seçilen işlem, PCAN cihazı üzerinden araca veri olarak gönderilecektir.

Not: PCAN cihazından gelen veya giden verilerin baytları ve ID'leri sizin aracınıza veya sisteminize göre farklılık gösterebilir. Bu nedenle, uygulamayı kendi sisteminize uyarlamak için kod içeriğini incelemeniz ve gerekli değişiklikleri yapmanız gerekebilir.
