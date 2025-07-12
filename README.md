# Human-Activity-Recognition-with-Smart-Devices
2 veri seti için train test yapılmıştır. 2 veri setinin de yöntem1 için dosyaları ayrı olarak hazırlanmıştır ve hepsinin modelleri kaydedilmiştir. Aynı zamanda yöntem dosyaları içinde hem train hem test yapılmıştır ve test sonuçları kaydedilmiştir. 2 veri seti için train+test toplamda yaklaşık 10-13dk sürmektedir.

Kuhar verisetinin veri dosyası büyük olduğu için verisetinin tamamı yüklenememiştir. Küçük bir parçası yüklenecektir ama yöntem1 adlı dosyalar tam veriseti ile çalıştırılıp kaydedilmiştir. Sonuçları kuhar yöntem1 dosyası içinde mevcuttur.

KUHAR verisetinin subseti ile test yapıldığında değerlerde değişim yaşanabilir ama tam veriseti ile elde edilen sonuçlar hem raporda belirtilmiştir hem de yöntem dosyası içinde kayıtlı bulunmaktadır.
Yöntem dosyaları veri setlerinin tamamı ile yazılmıştır. Test dosyaları ise sadece kuhar veriseti için subset kullanılarak yazılmıştır.

Kayıtlı modellerden bazılarının boyutları büyük olduğu için git lfs ile yüklenmiştir. Repo clone edilmeden önce git lfs install yapılmalıdır. Kuhar veri setinin subset hali de git lfs ile yüklenmiştir. 
verisetinin tamamı için link :https://drive.google.com/file/d/1irKuv7Kj7K8HN34uiEdZ-0UOA50wHvGu/view?usp=drive_link 

HOCAM TRAİN VE TEST DOSYALARINI AYRI TUTMAYA ÇALIŞTIM FAKAT PCA VE STANDARDİZASYON YAPMAYA ÇALIŞTIĞIMDA TEST DOSYALARI HATA VERDİ. BU DURUMU DA BİR TÜRLÜ ÇÖZEMEDİM. YÖNTEM1 İSİMLİ DOSYALARIN İÇİNDE HEM TRAİN HEM TEST YAPTIM. İKİ DOSYANIN TOPLAM ÇALIŞMA SÜRESİ YAKLAŞIK 10-13DK SÜRÜYOR. KU-HAR_YONTEM1 DOSYASINDA VERİSETİNİN TAM HALİNİN PATH İ BULUNMAKTA AMA BURAYA TAM HALİNİ ATAMADIĞIM İÇİN SUBSET HALİNİ ATTIM. 

KU-HAR_YONTEM1 DOSYASINDA SUBSET HALİNDE OKUDUĞUM KISMI DA YORUM SATIRI OLARAK EKLEDİM. BU SATIRI AÇIP DİĞER pd.read_csv SATIRINI YORUMA ALIRSANIZ SUBSET İÇİN TRAİN VE TEST YAPABİLİRSİNİZ
