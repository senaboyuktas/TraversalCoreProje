# TraversalCoreProje
Traversal Rezervasyon Asp.Net Core 5.0 Mini Proje 

[![Kurs Linki](https://img.shields.io/badge/Kurs%20Linki%20-izlemek%20için%20tıklayın-purple)](https://www.youtube.com/playlist?list=PLKnjBHu2xXNMK5MBogdXmsXVi3K_eEZT5)

## Proje Hakkında: 
Veri tabanı olarak SQL Server kullanılarak, BusinessLayer, DataAccessLayer, DTOLayer, EntityLayer, PresentationLayer, SignalRApiForSQL ve SingalRConsume katmanlarından oluşan N Tier Architecture mimarisi, ASP.Net Core 5.0 ve Entity Framework Core teknolojileri kullanılarak Codefirst yaklaşımı ile API'lerle desteklenmiş ve kodlanmıştır. Ayrıca MSSQL ve Postgre SQL veri tabanları da kullanılmıştır.

Bu proje, tatil rezervasyonu alanında faaliyet gösteren bir web sitesini temsil etmektedir. Sitede, çeşitli tatil seçeneklerinin listelendiği, kullanıcıların kişisel hesabına ve siteye ait bilgilere erişebildiği ve admin kullanıcısının da site içerisinde CRUD işlemleri gerçekleştirebildiği üç farklı tasarıma sahip bir projedir.

## Aşağıda, proje geliştirme aşamaları sunulmaktadır:

* Katmanlar oluşturuldu ve projenin genel yapısı belirlendi.
* Veritabanı işlemleri için Context sınıfı tanımlandı ve migration işlemi gerçekleştirildi.
* DataAccesLayer ve BusinessLayer Generic Interface'leri kullanılarak veri erişimi yapıldı.
* Repository Design Pattern yaklaşımı kullanılarak veritabanı işlemleri gerçekleştirildi.
* Fluent Validation kütüphanesi kullanılarak giriş yapılan verilerin doğruluğu kontrol edildi.
* Partial Async ve View Component yapıları kullanılarak performans artırımı sağlandı.
* MSSQL veritabanı kullanılarak CRUD işlemleri yapıldı.
* Yorumları ait olduğu rotaya göre listeleme ve yaptırma işlemleri gerçekleştirildi.
* Identity kullanılarak kullanıcı girişi yapıldı ve kullanıcının profil bilgileri getirildi.
* Login ve Register sayfaları oluşturuldu.
* Custom Identity Validator işlemleri gerçekleştirildi.
* Identity ile kullanıcı profil ve resim bilgisi güncellemesi yapıldı.
* Giriş yapmış kullanıcıya ait aktif, onay bekleyen, geçmiş ve yeni rezervasyon sayfaları oluşturuldu.
* Include metodu ve Ef bağımlılığının kaldırıldı.
* Container dependencies ve startup yapıları refactoring edildi.
* 404 not found sayfası oluşturuldu.
* Hem dinamik hem de statik excel ve pdf raporları sayfaları oluşturuldu.
* Mail gönderme işlemi yapıldı.
* Ajax işlemleri yapıldı.
* Data Transfer Object (DTO) katmanı oluşturuldu ve AutoMapper kullanılarak veri transferi işlemleri optimize edildi.
* Api Projesi ana projede kullanıldı.
* Rapid Api Booking üzerinden otel listesi çekildi.
* CQRS Design Pattern kullanılarak veri işlemleri ayrıştırıldı.
* MediatR kütüphanesi kullanılarak işlemler daha düzenli bir şekilde yapıldı.
* Unit Of Work implementasyonu yapıldı ve veritabanı işlemleri daha yönetilebilir hale getirildi.
* Api üzerinden ziyaretçi veri seti oluşturuldu.
* CrossTab kullanılarak ziyaretçiler için pivot tablosu oluşturuldu.
* SignalR kullanılarak grafikte anlık veri görüntüleme yapıldı.
* Rol CRUD işlemleri gerçekleştirildi.
* Çoklu dil desteği ve şifremi unuttum sayfaları ile kampı tamamladık.

## Proje Görselleri

![Traversal](https://github.com/SenaBoyuktas/TraversalCoreProje/blob/master/Proje/1.jpg)

![Traversal](https://github.com/SenaBoyuktas/TraversalCoreProje/blob/master/Proje/4.jpg)

![Traversal](https://github.com/SenaBoyuktas/TraversalCoreProje/blob/master/Proje/6.jpg)

![Member](https://github.com/SenaBoyuktas/TraversalCoreProje/blob/master/Proje/8.jpg)

![Member](https://github.com/SenaBoyuktas/TraversalCoreProje/blob/master/Proje/9.jpg)

![Member](https://github.com/SenaBoyuktas/TraversalCoreProje/blob/master/Proje/10.jpg)

![Member](https://github.com/SenaBoyuktas/TraversalCoreProje/blob/master/Proje/11.jpg)

![Member](https://github.com/SenaBoyuktas/TraversalCoreProje/blob/master/Proje/12.jpg)

![Admin](https://github.com/SenaBoyuktas/TraversalCoreProje/blob/master/Proje/13.jpg)

![Admin](https://github.com/SenaBoyuktas/TraversalCoreProje/blob/master/Proje/15.jpg)

![Admin](https://github.com/SenaBoyuktas/TraversalCoreProje/blob/master/Proje/16.jpg)

![Admin](https://github.com/SenaBoyuktas/TraversalCoreProje/blob/master/Proje/17.jpg)

![Admin](https://github.com/SenaBoyuktas/TraversalCoreProje/blob/master/Proje/18.jpg)

![APİ](https://raw.githubusercontent.com/senaboyuktas/TraversalCoreProje/master/Proje/19.png)

![KUR](https://raw.githubusercontent.com/senaboyuktas/TraversalCoreProje/master/Proje/20.png)

![KUR](https://raw.githubusercontent.com/senaboyuktas/TraversalCoreProje/master/Proje/21.png)
