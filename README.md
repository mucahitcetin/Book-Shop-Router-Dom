﻿<h1> Book-Shop-Router-Dom </h1>

Bu proje, React, Vite ve React Router kullanılarak oluşturulmuş bir basit kitap uygulamasını içermektedir. Proje, farklı sayfalar arasında gezinme, ürünleri listeleyerek detaylarına ulaşma ve 404 hatası gibi durumları ele almak için React Router'ın kullanımını örneklemektedir.

Canlı:https://book-shops-react.netlify.app/

<h2>Proje Yapısı</h2>

- src/components/Header.js: Ana sayfa ve ürünler sayfasına yönlendiren başlık bileşeni.

- src/components/Footer.js: Sayfanın altında bulunan footer bileşeni.

- src/components/Card.js: Card yapsının içeren sayfa bileşeni.

- src/pages/MainPage.js: Ana sayfa içeriğini oluşturan bileşen.

- src/pages/ProductsPage.js: Tüm ürünleri listeleyen sayfa bileşeni.

- src/pages/ProductDetail.js: Bir ürünün detaylarını gösteren sayfa bileşeni.

- src/pages/NotFound.js: Geçersiz URL'lerde görüntülenecek 404 sayfası bileşeni.

- src/pages/CategoryPage.js: Kategorileri listeleyen sayfa bileşeni.

- src/pages/CategoryDetail.js: Kategorileri ayrıntılandırma sayfası bileşeni.

- src/App.js: Ana uygulama bileşeni, tüm sayfaları ve router'ı içerir.

<h2>Kullanılan Kütüphaneler</h2>

- Axios
- Bootstrap
- React Router Dom

<h2>Ekran Görüntüsü</h2>

![](ekran.gif)
