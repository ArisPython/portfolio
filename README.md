# Project


## Monolith
1. BlogApp-Antonio --> [Source](https://github.com/ArisDjango/BlogAntonio)
   <details>
      <summary>Details</summary>

        - Fungsi    : Blog Sederhana
        - Tech      : Django, HTML/CSS/JS, postgresql
        - Fitur     : Tag, Comment, Total Post, Latest Post, Most Commented Post, Similiar post, Search, feed, sitemap(xml)
        - Problem   : belum otentifikasi, Form belum handle image, send email by django masih bermasalah

    </details>
2. Bookmarks ( social media ) --> [Source](https://github.com/ArisDjango/SosmedAntonio)

    <details>
       <summary>Details</summary>
    
        - Fungsi    : Aplikasi bookmarks/capture image dari web lain dan menyimpannya ke app, mirip pinterest addon
        - Tech      : Django, HTML/CSS/JS, AJAX, Redis, postgresql
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
    
    </details
 3. Online Shop Antonio --> [source](https://github.com/ArisDjango/OnlineShopAntonioReborn2)

    <details>
        <summary>Details</summary>
    
        - Fungsi        : Online Shop Sederhana
        - Tech          : Django, HTML/CSS/JS, celery-rabbitMQ, Redis, Django-rosetta, postgresql, docker
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
            - Multilanguage system menggunakan Django rosetta
    </details>
 4. Educa E-Learning --> [source](https://github.com/ArisDjango/EducaAntonio)

    <details>
        <summary>Details</summary>
   
        - Fungsi        : Content Management System E-Learning
        - Tech          : Django, HTML/CSS/JS, memcached, DRF, django-channels & redis, websocket-jquery, postgresql, docker
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
            - Deploy dengan docker
      </details>
  5. Simple E-commerce --> [source](https://github.com/ArisDjango/ecomVery)
  
     <details>
          <summary>Details</summary>

           - Fungsi       : Ecommerce sederhana
           - Tech         : Django, Bootstrap5, sqlite, AJAX
           - Fitur        :
              - manajemen akun
              - keranjang belanja
              - payment: paypal
     </details>
  
  ## API
  1. Blog simple very --> [Source Backend](https://github.com/ArisDjango/CrudVeryAcademy) -- [Source Frontend](https://github.com/ArisDjango/CrudVeryAcademyReact2)
  
     <details>
          <summary>Details</summary>

           - Fungsi       : Blog sederhana
           - Tech         : Django, DRF, React
     </details>
     
  2. Todo sederhana (CRUD) --> [Source](https://github.com/ArisPython/fastapi/tree/planner-sql/todos)
  
     <details>
          <summary>Details</summary>
   
           - Fungsi       : fungsionalitas CRUD
           - Tech         : FastAPI
     </details>
     
  3. Planner app (CRUD) --> [Source](https://github.com/ArisPython/fastapi/tree/planner-sql/planner)
  
     <details>
          <summary>Details</summary>
   
            - Fungsi       : CRUD
           - Tech         : FastAPI, MongoDB
           - Fitur        : Otentikasi, OAuth2 dan JWT, dependency Injection, CORS
     </details>
