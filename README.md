# 🚀 AddAngularProject

![License](https://img.shields.io/github/license/umutbarancicek/AddAngularProject?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/umutbarancicek/AddAngularProject?style=for-the-badge)
![Stars](https://img.shields.io/github/stars/umutbarancicek/AddAngularProject?style=for-the-badge)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

Enterprise-ready Full-stack Web Application template integrating a modern **Angular** frontend with a robust **C# .NET** backend. Designed for scalability, maintainability, and high performance.

---

### 📝 Hakkında (About)

**AddAngularProject**, kurumsal seviyede projeler için bir temel (boilerplate) görevi görür. Frontend ve backend arasındaki entegrasyonu en iyi uygulamalarla (best practices) sağlar. Bu şablon, geliştiricilerin altyapı kurulumuyla vakit kaybetmeden doğrudan iş mantığına (business logic) odaklanmasına olanak tanır.

---

### ✨ Özellikler (Features)

- 🏗 **Clean Architecture**: Katmanlı mimari yapısı ile sürdürülebilir kod temeli.
- 🔐 **Authentication & Authorization**: JWT tabanlı güvenli kimlik doğrulama sistemi.
- ⚡ **Single Page Application (SPA)**: Angular'ın gücüyle hızlı ve dinamik kullanıcı deneyimi.
- 🛠 **Dependency Injection**: Esnek ve test edilebilir bir yapı için yerleşik DI desteği.
- 📊 **Entity Framework Core**: Veritabanı işlemleri için modern ORM kullanımı.
- 📱 **Responsive Design**: Tüm cihazlarla uyumlu kullanıcı arayüzü.
- 🌐 **RESTful API**: Standartlara uygun, dokümante edilebilir API uç noktaları.

---

### 🛠 Teknolojiler (Technologies)

- **Backend:** .NET Core / C#
- **Frontend:** Angular (v16+)
- **ORM:** Entity Framework Core
- **Database:** MS SQL Server / PostgreSQL / SQLite Support
- **UI Framework:** Angular Material / Bootstrap
- **API Documentation:** Swagger / OpenAPI

---

### ⚙️ Kurulum (Installation)

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları takip edin.

#### 1. Projeyi Klonlayın
git clone https://github.com/umutbarancicek/AddAngularProject.git
cd AddAngularProject

#### 2. Backend Kurulumu
cd Backend
dotnet restore
dotnet ef database update
dotnet run

#### 3. Frontend Kurulumu
cd ../Frontend
npm install
ng serve --open

---

### 🚀 Kullanım (Usage)

- **API Adresi:** Uygulama ayağa kalktığında `https://localhost:5001/swagger` adresinden API dökümantasyonuna erişebilirsiniz.
- **Frontend Adresi:** Uygulama arayüzüne varsayılan olarak `http://localhost:4200` adresinden ulaşabilirsiniz.

Backend yapılandırmasını değiştirmek için `appsettings.json` dosyasındaki bağlantı dizelerini (connection strings) güncelleyebilirsiniz.

---

### 🤝 Katkıda Bulunma (Contributing)

Katkılarınızı bekliyoruz! 

1. Bu depoyu çatallayın (Fork).
2. Yeni bir özellik dalı oluşturun (`git checkout -b feature/YeniOzellik`).
3. Değişikliklerinizi kaydedin (`git commit -m 'Yeni özellik eklendi'`).
4. Dalınıza gönderin (`git push origin feature/YeniOzellik`).
5. Bir Çekme İsteği (Pull Request) oluşturun.

---

### 📜 Lisans (License)

Bu proje **MIT Lisansı** ile lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına göz atabilirsiniz.

---

### 📬 İletişim (Contact)

**Umut Baran Çiçek**
- GitHub: [@umutbarancicek](https://github.com/umutbarancicek)
- LinkedIn: [Umut Baran Çiçek](https://linkedin.com/in/umutbarancicek)

---
*Developed with ❤️ by Umut Baran Çiçek*
