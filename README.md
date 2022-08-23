# Project

## Django + HTML/CSS/Bootstrap
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
