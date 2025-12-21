🏋️ Spor Salonu Otomasyonu
Bu proje, bir spor salonunun üye yönetim süreçlerini (kayıt, silme, güncelleme) ve operasyonel takibini kolaylaştırmak için geliştirilmiş, C# tabanlı bir masaüstü uygulamasıdır. Yazılım mimarisi olarak N-Tier (Katmanlı) Mimari prensipleri benimsenmiş, bu sayede sürdürülebilir ve modüler bir yapı hedeflenmiştir.

🛠 Teknik Mimari ve Teknolojiler
Core Stack
Language: C#
UI Framework: Windows Forms (WinForms)
Database: MS Access (OleDb Connection)
Architecture: N-Tier (Katmanlı Mimari)
Kullanılan Kütüphaneler & Toollar
iTextSharp: Üyelik formları veya raporlar için PDF doküman oluşturma desteği.
ZedGraph: Salon verimliliği ve üye istatistiklerini grafiksel olarak sunmak için kullanılmıştır.
BouncyCastle: Veri güvenliği ve kriptografi işlemleri için entegre edilmiştir.
Mimari Kararlar ve Seçimler
Katmanlı Mimari (N-Tier): Proje; Presentation, Business, DataAccess ve Entity katmanlarına ayrılmıştır.
Trade-off: Küçük bir proje için daha fazla dosya yapısı gerektirse de, kodun okunabilirliğini artırır ve ileride farklı bir veritabanına (örn: SQL Server) geçişi kolaylaştırır.
MS Access Kullanımı: Düşük konfigürasyonlu bilgisayarlarda ek bir veritabanı sunucusu kurulumu gerektirmeden çalışabilmesi için tercih edilmiştir.
Trade-off: Çok kullanıcılı ve büyük veri setlerinde SQL Server kadar ölçeklenebilir değildir.

🚀 Öne Çıkan Özellikler
Üye Yönetimi: Yeni üye ekleme, mevcut bilgileri güncelleme ve üyelik sonlandırma işlemleri.
Gelişmiş Raporlama: iTextSharp entegrasyonu ile üye bilgilerinin PDF formatında dışa aktarılması.
Grafiksel Analiz: ZedGraph ile salon doluluk veya kayıt trendlerinin görselleştirilmesi.
Modüler Yapı: Her katmanın kendi sorumluluğuna sahip olması (Separation of Concerns).

📂 Proje Klasör Yapısı
BusinessLayer: İş mantığı ve validasyon kontrolleri.
DataAccessLayer: Veritabanı (CRUD) işlemleri.
EntityLayer: Veritabanı tablolarını temsil eden sınıflar.
Fitness_Club (UI): Kullanıcının etkileşime girdiği WinForms arayüzü.

📦 Kurulum
Repo'yu klonlayın:
git clone https://github.com/aslanbaris13/Spor_Salonu_Otomasyonu.git

Fitness_Club.sln dosyasını Visual Studio ile açın.
System.Data.OleDb bağımlılığının yüklü olduğundan emin olun.
Projeyi derleyin ve çalıştırın.

📄 Lisans
Bu proje MIT Lisansı ile lisanslanmıştır.
Developed by Barış Aslan
