# Project

## APP
1. BlogApp-Antonio --> [Source](https://github.com/ArisDjango/BlogAntonio) 
    - Fungsi    : Blog Sederhana
    - Fitur     : Tag, Comment, Total Post, Latest Post, Most Commented Post, Similiar post, Search, feed, sitemap(xml)
    - Database  : postgresql
    - Template  : HTML/CSS/JS
    - Problem   : belum otentifikasi, Form belum handle image, send email by django masih bermasalah
2. Bookmarks ( social media ) --> [Source](https://github.com/ArisDjango/SosmedAntonio)
    - Fungsi    : Aplikasi bookmarks/capture image dari web lain dan menyimpannya ke app, mirip pinterest addon
    - Fitur     :
        - User management (Otentikasi, Registrasi user, Login, logout, rubah password, reset password/lupa password)
        - Messages framework : pesan highlight pada halaman atas ketika suatu operasi sukses/error
        - Social authentication : otentikasi user melalui facebook/twitter/google
        - Bookmarklet menggunakan jquery 
        - Like/unlike function , menggunakan AJAX-jquery
        - Pagination Lazy-load menggunakan AJAX
        - Follow System menggunakan AJAX
        - Activity Stream : stream aktivitas user yang kita follow (upload, bookmarks, like, follow dll)
        - Menampilkan Jumlah view menggunakan REDIS
        - Menampilkan Ranking menggunakan REDIS
     - Database   : postgresql
     - template   : HTML/CSS/JS/AJAX
 3. Online Shop Antonio --> [source](https://github.com/ArisDjango/OnlineShopAntonioReborn2)
    - Fungsi        : Online Shop Sederhana
    - Fitur         :
        - Product catalog
        - shoping cart menggunakan django sessions
        - manajemen pesanan/order customer
        - Async notifikasi menggunakan celery dan rabbitMQ sebagai message broker
        - Monitor celery menggunakan flower
        - Integrasi payment gateway menggunakan braintree payment
        - Export order kedalam file csv
        - Invoice PDF menggunakan WeasyPrint
        - Sistem Kupon : mengaplikasikan diskon ke shoping cart dan order
        - Sistem rekomendasi produk emnggunakan Redis
        - Multilangage system menggunakan Django rosetta
 4. Educa E-Learning --> [source](https://github.com/ArisDjango/EducaAntonio)
    - Fungsi        : Content Management System E-Learning
    - Fitur         : 
        - Otentikasi instruktur (registrasi, Login/logout)
        - list semua course / single course yang dibuat oleh instruktur, difilter berdasarkan subject, 
        - CRUD materi
        - Tiap materi terdapat modul, tiap modul terdapat konten, konten bisa dalam berbagai type (Text, PDF, Image, Video embed ) 
        - Student Registration System ( Sign up, login/logout )
        - Enroll System
        - Django cache framework dan memcached
        - RestFul API menggunakan Django Rest Framework
        - Chat server menggunakan django-channels dan redis
        - Implementasi Web Socket Clients menggunakan jquery
