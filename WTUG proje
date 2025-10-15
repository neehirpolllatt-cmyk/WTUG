✅ Görev Takip Uygulaması (ToDoApp)
🎯 Proje Amacı

Bu proje, kullanıcıların günlük işlerini veya yapılacaklar listesini daha düzenli bir şekilde takip edebilmelerini sağlamak amacıyla geliştirilmiş basit bir görev yönetim uygulamasıdır.
Proje, hem ön uç (frontend) hem de arka uç (backend) geliştirmeye yönelik temel kavramları uygulamalı olarak öğrenmek için tasarlanmıştır.

Kullanıcı, bu uygulama sayesinde görevlerini kolayca:

Ekleyebilir,

Listeleyebilir,

Tamamlandı olarak işaretleyebilir,

Gerekirse silebilir.

Ayrıca proje, ASP.NET Core MVC mimarisinin nasıl çalıştığını, katmanlı mimari yapısını, Entity Framework ile veritabanı işlemlerini ve dinamik sayfa yönetimini öğrenmek için iyi bir örnek niteliğindedir.

🛠️ Kullanılan Teknolojiler ve Araçlar
Teknoloji	Açıklama
HTML5 / CSS3	Sayfa yapısı ve temel stil vermek için kullanıldı
JavaScript	Bazı etkileşimli arayüz işlevleri için kullanıldı
ASP.NET Core MVC	Uygulama iskeleti ve sunucu tarafı işlemler için
C#	Tüm sunucu taraflı kodlama bu dil ile yazıldı
Entity Framework Core	ORM (Object Relational Mapping) olarak veritabanı işlemleri için
SQLite	Hafif ve kurulumsuz veritabanı tercihi olarak
📦 Uygulama Özellikleri

Bu proje, görev yönetimini kolaylaştırmak amacıyla aşağıdaki temel özellikleri sunmaktadır:

🔹 Görev Ekleme: Yeni bir görev başlığı girilerek listeye yeni bir görev eklenebilir.

🔹 Görev Listeleme: Sisteme eklenen tüm görevler liste halinde görüntülenir.

🔹 Görev Silme: İstenmeyen görevler tek tıklama ile silinebilir.

🔹 Görev Tamamlama: Bir görevin tamamlandığı işaretlenerek durum bilgisi güncellenebilir.

Her görev, tamamlanma durumuna göre farklı şekilde görselleştirilebilir (örn: üzeri çizili, renkli vb.).

🧩 Proje Klasör Yapısı

Aşağıda, projenin temel klasör ve dosya yapısı gösterilmiştir:

ToDoApp/
│
├── Controllers/
│   └── TaskController.cs        → Görevlerle ilgili tüm işlemleri (CRUD) yöneten controller
│
├── Models/
│   └── TaskItem.cs              → Görev modelini temsil eden sınıf (Id, Title, IsCompleted vs.)
│
├── Views/
│   └── Task/
│       ├── Index.cshtml         → Tüm görevlerin listelendiği ana sayfa
│       ├── Create.cshtml        → Yeni görev ekleme sayfası
│       └── (Gerekiyorsa diğer görünümler)
│
├── wwwroot/
│   └── css/
│       └── style.css            → Sayfaların görünümünü güzelleştiren stil dosyası
│
├── appsettings.json            → Veritabanı ve genel uygulama ayarları
├── Program.cs                  → Uygulama giriş noktası
├── Startup.cs                  → Servislerin tanımlandığı ve middleware’lerin ayarlandığı yer
├── ToDoApp.csproj              → Proje konfigürasyon dosyası (NuGet bağımlılıkları vb.)

🗃️ Veritabanı Bilgisi

Uygulama, basit ve taşınabilir bir veritabanı çözümü olan SQLite kullanır.
Veritabanı, proje çalıştırıldığında otomatik olarak oluşturulur (Code-First yaklaşımı).

TaskItem.cs modeli şu alanları içerir:

public class TaskItem
{
    public int Id { get; set; }
    public string Title { get; set; }
    public bool IsCompleted { get; set; }
}

🧪 Projeyi Çalıştırmak İçin
1. Gerekli Araçlar

.NET 6.0 SDK veya üzeri

(İsteğe bağlı) Visual Studio 2022 veya Visual Studio Code

2. Çalıştırma Adımları

Projeyi klonlayın veya indirin:

git clone https://github.com/kullanici-adi/ToDoApp.git


Terminal veya komut satırından proje dizinine geçin:

cd ToDoApp


Gerekli NuGet paketlerini indirin ve projeyi çalıştırın:

dotnet restore
dotnet ef database update
dotnet run


Tarayıcıdan uygulamayı açın:
http://localhost:5000

🚀 Geliştirme Önerileri

Uygulama şu anda temel işlevleri yerine getirmektedir. Ancak istenirse aşağıdaki geliştirmeler eklenebilir:

Kullanıcı giriş sistemi (authentication)

Görevler için tarih ve saat bilgisi

Kategorilere ayırma (kişisel, iş, okul vb.)

Responsive tasarım (mobil uyumlu görünüm)

Görevleri sürükle-bırak ile sıralama

Tamamlanan görevleri gizleme seçeneği
