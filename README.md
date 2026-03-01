# Assignment: Books CRUD

Bu proje, ASP.NET Core MVC kullanılark yazdığım bir kitap yönetim sistemidir.
Tüm CRUD (Listeleme, Ekleme, Düzenleme, Silme) işlemleri manuel olarak koydum.

### Uygulanan Özellikler
- **Model & Validation**: Kitap adı, yazar, sayfa sayısı gibi alanlar için kurallar (Required, Range vb.) eklendim.
- **SQLite Geçişi**: Proje MacOS ortamında geliştirdiğim için veritabanı SQLite olarak yapılandırdım.
- **Views**: Tüm arayüz sayfaları Razor Views kullanılarak sıfırdan tasarladım.
- **Navigation**: Ana menüye "Books" linki entegre edildi..

### Nasıl Çalıştırılır? (Mac/SQLite)
1. Terminalden proje dizinine gidin hocam.
2. Bağımlılıkları yükleyin: `dotnet restore`
3. Veritabanını oluşturun: `dotnet ef database update`
4. Uygulamayı başlatın: `dotnet run`

![Kitap Listesi](Ekran Resmi 2026-03-01 20.18.27.png)


<img width="1796" height="954" alt="Ekran Resmi 2026-03-01 20 18 27" src="https://github.com/user-attachments/assets/765c5899-4adc-4249-a312-a0ea1feda0ac" />
<img width="1800" height="954" alt="Ekran Resmi 2026-03-02 01 45 57" src="https://github.com/user-attachments/assets/94373d4c-0349-4758-a5e1-db431ed2da79" />
<img width="1800" height="954" alt="Ekran Resmi 2026-03-02 01 46 58" src="https://github.com/user-attachments/assets/8b998cfd-9577-4d52-92b8-3345759da53d" />


