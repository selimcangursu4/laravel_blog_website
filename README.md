**************************************************************   TURKİSH TRANSLATİON   *********************************************************************************

BLOG WEB SİTESİ VE ADMİN PANELİ 
Bu proje, kullanıcıların blog yazılarını okuyabileceği, yorum yapabileceği ve yazıların yönetimi için admin paneli sunan bir blog sitesini temsil etmektedir. Hem client tarafı hem de admin paneli için ücretsiz template'ler kullanılmış olup, tasarımlar ve içerikler tamamen özgün bir şekilde düzenlenmiştir.
Temel Özellikler
1. Client Tarafı Özellikleri

    Blog Yazılarını Görüntüleme: Ziyaretçiler, siteye erişim sağladığında, yazıların başlıklarını ve özetlerini görüntüleyebilir ve detaylı yazıya ulaşabilir.
    Yorum Yapma: Kullanıcılar, yazılara yorum yaparak görüşlerini paylaşabilirler. (Yorumlar onaya tabidir ve yönetici tarafından kontrol edilir.)
    Kategoriler: Blog yazıları, belirli kategorilere ayrılarak kullanıcıların ilgisini çeken yazıları daha hızlı bulmalarını sağlar.
    Arama Özelliği: Kullanıcılar, blog yazıları arasında anahtar kelime ile arama yaparak istedikleri içeriğe hızlıca ulaşabilirler.

2. Admin Paneli Özellikleri

    Kullanıcı ve Yazar Yönetimi: Admin paneline erişim yetkisi olan kullanıcılar, yeni yazarlar ekleyebilir, mevcut kullanıcıları yönetebilir ve silme işlemleri yapabilirler.
    Blog Yazı Yönetimi: Admin, blog yazıları ekleyebilir, güncelleyebilir veya silebilir. Yazılar için başlık, içerik, kategori, etiket ve görsel ekleyebilir.
    Yorum Yönetimi: Admin, kullanıcıların yazdığı yorumları yönetebilir; onaylayabilir veya silebilir.
    Statistikler ve Raporlar: Admin, siteye ait çeşitli istatistiklere erişebilir, kullanıcı etkileşimlerini, yorum sayısını ve en popüler yazıları inceleyebilir.

Teknolojik Altyapı
    Frontend (Client Tarafı):
    Proje, kullanıcı dostu bir arayüz için Newsroom Template kullanılarak hazırlanmıştır. Template, modern ve mobil uyumlu bir tasarıma sahiptir.
    Backend (Admin Paneli):
    Admin paneli, PHP programlama dili ve Laravel Framework kullanılarak geliştirilmiştir. Laravel'in sağladığı MVC yapısı ile güvenli, ölçeklenebilir ve bakımı kolay bir        sistem oluşturulmuştur.
    Veritabanı:
    Proje, tüm verileri saklamak için MySQL veritabanı kullanmaktadır. Yazılar, kullanıcılar, yorumlar ve diğer tüm içerik veritabanında saklanmaktadır.
    Authentication (Kimlik Doğrulama):
    Laravel'in sunduğu yerleşik kimlik doğrulama özellikleri kullanılarak, kullanıcılar sisteme güvenli bir şekilde giriş yapabilir ve admin paneline erişim sağlanabilir.

Proje Yapısı:
    app/: Uygulama mantığının bulunduğu klasör. Model, Controller ve diğer uygulama sınıfları burada yer alır.
    resources/views/: Frontend tarafındaki HTML şablonlarının bulunduğu klasördür.
    database/migrations/: Veritabanı şemalarının yer aldığı migration dosyaları burada bulunur.
    public/: Uygulamanın halka açık kaynaklarının bulunduğu klasördür (CSS, JS, görseller).
    routes/web.php: Uygulamanın web yönlendirmelerinin yapılandırıldığı dosya.


B.KURULUM VE BAŞLATMA

1.Gerekli Bağımlılıkları Yükleyin : Composer ve npm yüklü olduğundan emin olun.
  
   composer install 
   npm install

2.env Dosyasını Yapılandırın: ENV dosyasında yer alan veritabanı bağlantı ayarlarını yapın.

3.Veritabanını Yaratın ve Migrations'i Çalıştırın: Veritabanını oluşturun ve Laravel'in migration işlemlerini çalıştırarak gerekli tabloları oluşturun.
  
  php artisan migrate

4.Uygulamayı Başlatın : Laravel'in yerel sunucusunda uygulamayı başlatın.

  php artisan serve


Kullanıcı Erişimi

  Misafir Kullanıcılar: Yalnızca blog yazılarını okuyabilir ve yorum yapabilir.
  Admin Paneli: Admin, kullanıcı ekleme, yazı yönetimi ve yorum denetimi gibi tüm yönetim işlemlerini gerçekleştirebilir.

  Kullanıcı ve Admin Giriş

  Admin Girişi için:

  Kullanıcı adı: admin@example.com
  Şifre: password

  Ekstra Özellikler

  Mobil Uyumlu Tasarım: Temel template, mobil cihazlara uyumlu olacak şekilde tasarlanmış olup, kullanıcı deneyimini her cihazda optimize eder.
  SEO Uyumlu: Blog yazıları, SEO uyumlu olacak şekilde başlıklar, etiketler ve meta açıklamalar içerir.
  Veritabanı Yedekleme ve Geri Yükleme: Admin paneli üzerinden kolayca veritabanı yedeklemesi yapılabilir ve gerektiğinde geri yüklenebilir.

*************************************************************     ENGLİSH TRANSLATİON    ********************************************************************************

BLOG WEBSITE AND ADMIN PANEL
This project represents a blog site where users can read blog posts, comment on them and provide an admin panel for managing posts. Free templates have been used for both the client side and the admin panel, and the designs and contents have been completely uniquely organized.

Basic Features
1. Client Side Features

Viewing Blog Posts: When visitors access the site, they can view the titles and summaries of the posts and access the detailed post.
Commenting: Users can share their opinions by commenting on posts. (Comments are subject to approval and are controlled by the administrator.)
Categories: Blog posts are divided into certain categories, allowing users to find posts that interest them faster.
Search Feature: Users can quickly access the content they want by searching through blog posts with keywords.

2. Admin Panel Features

User and Author Management: Users who have access to the admin panel can add new authors, manage existing users and perform deletion operations.
Blog Post Management: Admin can add, update or delete blog posts. Can add titles, content, categories, tags and images for posts.

Comment Management: Admin can manage comments written by users; approve or delete them.

Statistics and Reports: Admin can access various statistics about the site, examine user interactions, number of comments and most popular posts.

Technological Infrastructure
Frontend (Client Side):
The project was prepared using Newsroom Template for a user-friendly interface. The template has a modern and mobile-friendly design.
Backend (Admin Panel):
The admin panel was developed using PHP programming language and Laravel Framework. A secure, scalable and easy-to-maintain system was created with the MVC structure provided by Laravel.
Database:
The project uses MySQL database to store all data. Posts, users, comments and all other content are stored in the database.
Authentication:
Using the built-in authentication features offered by Laravel, users can log in to the system securely and access the admin panel.

Project Structure:
app/: Folder containing application logic. Model, Controller and other application classes are located here.
resources/views/: Folder containing HTML templates on the frontend side.
database/migrations/: Migration files containing database schemas are located here.
public/: Folder containing public resources of the application (CSS, JS, images).
routes/web.php: File where the web redirects of the application are configured.

B. INSTALLATION AND STARTING

1. Install Necessary Dependencies: Make sure that Composer and npm are installed.

composer install
npm install

2. Configure the env File: Make the database connection settings in the ENV file.

3. Create Database and Run Migrations: Create the database and create the necessary tables by running Laravel's migration operations.

php artisan migrate

4. Start the Application: Start the application on Laravel's local server.

php artisan serve

User Access

Guest Users: Can only read and comment on blog posts.
Admin Panel: Admin can perform all administrative operations such as adding users, managing posts, and moderating comments.

User and Admin Login

For Admin Login:

Username: admin@example.com
Password: password

Extra Features

Mobile-Friendly Design: The basic template is designed to be compatible with mobile devices, optimizing the user experience on every device.
SEO-Friendly: Blog posts include SEO-friendly titles, tags, and meta descriptions.
Database Backup and Restore: Database backup can be easily done via the admin panel and restored when necessary.

