<div align="center">
  <a href="#english">🇺🇸 English</a>
  <span> | </span>
  <a href="#turkish">🇹🇷 Türkçe</a>
</div>

<br />

<div id="english" align="center">

# 🛒 ORAGE: E-Commerce & Order Analysis System

[![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![Entity Framework](https://img.shields.io/badge/Entity_Framework_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://learn.microsoft.com/en-us/ef/core/)
[![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)](https://www.microsoft.com/sql-server)
[![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

<br />

> **ORAGE** is a comprehensive **Order Management and Analysis Software** developed using ASP.NET Core MVC and Entity Framework Core. It features a robust Admin Dashboard for tracking sales statistics and managing products, alongside a user-friendly e-commerce interface.


<br />
<br />

</div>

<div id="english">

### 🎯 Project Overview & Purpose

This project aims to digitize the product management, stock tracking, and order processes for businesses. Unlike standard e-commerce templates, ORAGE focuses on **backend analysis and management**, allowing administrators to visualize sales data and manage order lifecycles effectively.

The system implements **Role-Based Authorization** (Admin/User) to ensure secure access to sensitive management features.

---

### 🛠️ Tech Stack & Architecture

* **Framework:** ASP.NET Core 8.0 MVC
* **Database:** MS SQL Server (Code-First Approach)
* **ORM:** Entity Framework Core
* **Authentication:** ASP.NET Core Identity (Role-Based) 
* **Frontend:** HTML5, CSS3, Bootstrap 5.3, jQuery 
* **Architecture:** N-Layered Architecture, MVC Design Pattern

---

### ✨ Key Features

#### 📊 1. Admin Dashboard & Analysis
* **Statistical Cards:** Visual display of Total Sales, Total Orders, and Total Product Count instantly on the dashboard.
* **Order Management:** View recent orders, track status (Pending/Approved), and manage workflow.
* **Product & Category Management:** Full CRUD operations with image upload support using `IFormFile`.
* **User Management:** Admins can view, edit, or delete users and assign roles.

#### 🛍️ 2. User Interface
* **Dynamic Homepage:** Features an auto-sliding carousel (Slider) and "New Arrivals" section managed from the backend.
* **Filtering & Search:** Users can filter products by category or search by keywords.
* **Secure Auth:** Registration and Login system with validation (Data Annotations).

---

### 🗄️ Database Schema

The project uses a relational database model designed with normalization rules. Key entities include:
* **Users & Roles:** Identity management.
* **Products & Categories:** Inventory classification.
* **Orders & OrderDetails:** Transactional data.
* **Cart:** Temporary storage for purchasing.

---


### 📸 Screenshots

![Anasayfa](https://i.hizliresim.com/ok60hns.png)
![Admin-Index](https://i.hizliresim.com/qf7qlmi.png)
![Admin-Kategori](https://i.hizliresim.com/78u52o8.png)
![Admin-Urun](https://i.hizliresim.com/5i3doob.png)
![Admin-Kullanicilar](https://i.hizliresim.com/qni3iro.png)
![Admin-Urun-Update](https://i.hizliresim.com/haf8kph.png)

---



</div>

<br />
<br />
<hr />
<div align="center">
  <h2>🇹🇷 🇹🇷 🇹🇷</h2>
</div>
<br />

<div id="turkish" align="center">

# 🛒 ORAGE: Sipariş Yönetim ve Analiz Yazılımı

<br />

> **ORAGE**, ASP.NET Core MVC ve Entity Framework Core kullanılarak geliştirilmiş kapsamlı bir **Ürün Yönetim ve Analiz Sistemidir**. Proje, satış istatistiklerinin takip edildiği güçlü bir Yönetici Paneli ve kullanıcı dostu bir E-Ticaret arayüzü sunar.


<br />
<br />

</div>

<div id="turkish">

### 🎯 Proje Hakkında ve Amaç

Bu proje, işletmelerin ürün yönetimi, stok takibi ve sipariş süreçlerini dijitalleştirmeyi amaçlamaktadır. Sıradan e-ticaret sitelerinden farklı olarak ORAGE, **arka plan yönetimi ve veri analizine** odaklanır. Yöneticilerin satış verilerini görselleştirmesine ve sipariş yaşam döngüsünü yönetmesine olanak tanır.
Sistem, hassas yönetim özelliklerine güvenli erişim sağlamak için **Rol Bazlı Yetkilendirme** (Admin/User) kullanır.

---

### 🛠️ Teknolojiler ve Mimari

* **Framework:** ASP.NET Core 8.0 MVC
* **Veritabanı:** MS SQL Server (Code-First Yaklaşımı)
* **ORM:** Entity Framework Core
* **Kimlik Doğrulama:** ASP.NET Core Identity (Rol Bazlı)
* **Frontend:** HTML5, CSS3, Bootstrap 5.3, jQuery
* **Mimari:** Katmanlı Mimari, MVC Tasarım Deseni

---

### ✨ Temel Özellikler

#### 📊 1. Yönetici Paneli ve Analiz
* **İstatistiksel Kartlar:** Toplam Satış, Toplam Sipariş ve Toplam Ürün sayısının anlık olarak hesaplanıp görsel kartlarla sunulması.
* **Sipariş Yönetimi:** Son siparişleri listeleme, durum takibi (Onay Bekliyor/Onaylandı) ve iş akışı yönetimi.
* **Ürün ve Kategori Yönetimi:** `IFormFile` ile resim yükleme destekli tam CRUD (Ekle/Sil/Güncelle) işlemleri.
* **Kullanıcı Yönetimi:** Yöneticiler kayıtlı kullanıcıları görüntüleyebilir, düzenleyebilir ve rol atayabilir.

#### 🛍️ 2. Kullanıcı Arayüzü
* **Dinamik Anasayfa:** Admin panelinden yönetilebilen Slider (Manşet) alanı ve "Son Eklenenler" vitrini.
* **Filtreleme ve Arama:** Kullanıcılar ürünleri kategorilere göre filtreleyebilir veya anahtar kelime ile arama yapabilir.
* **Güvenli Üyelik:** Data Annotations ile validasyon kuralları sağlanmış Kayıt ve Giriş sistemi.

---

### 🗄️ Veritabanı Şeması

Proje, normalizasyon kurallarına uygun ilişkisel bir veritabanı modeli üzerine inşa edilmiştir. [cite_start]Temel tablolar şunlardır:
* **Users & Roles (Kullanıcılar ve Roller):** Kimlik yönetimi.
* **Products & Categories (Ürünler ve Kategoriler):** Envanter sınıflandırması.
* **Orders & OrderDetails (Siparişler):** Satış işlemleri verisi.
* **Cart (Sepet):** Geçici satın alma depolama alanı.

---


### 📸 Ekran Görüntüleri

![Anasayfa](https://i.hizliresim.com/ok60hns.png)
![Admin-Index](https://i.hizliresim.com/qf7qlmi.png)
![Admin-Kategori](https://i.hizliresim.com/78u52o8.png)
![Admin-Urun](https://i.hizliresim.com/5i3doob.png)
![Admin-Kullanicilar](https://i.hizliresim.com/qni3iro.png)
![Admin-Urun-Update](https://i.hizliresim.com/haf8kph.png)



---




</div>
