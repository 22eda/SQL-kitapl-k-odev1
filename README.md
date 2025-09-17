Books Database SQL Project
📚 Proje Açıklaması

Bu proje, bir kitap envanteri veri tabanını SQL Server üzerinde oluşturmayı ve çeşitli sorgular ile analiz etmeyi amaçlamaktadır.

Tablo adı: books

Kitaplar hakkında temel bilgiler: başlık, yazar, tür, fiyat, stok miktarı, yayın yılı ve envantere eklenme tarihi.

Otomatik artan birincil anahtar (book_id) kullanılmıştır.

Mantıksal kısıtlar (CHECK) ile veri bütünlüğü sağlanmıştır:

Fiyat (price) negatif olamaz.

Stok (stock) negatif olamaz.

Yayın yılı (published_year) 1900–2025 arasında olmalıdır.

--Proje Notları

SQL Server üzerinde çalışmak üzere optimize edilmiştir.

IDENTITY kullanımı ile book_id otomatik artmaktadır.

CHECK kısıtları ile veri bütünlüğü sağlanmıştır.

Bu proje, SQL sorguları ile veri analizi ve filtreleme becerilerini geliştirmek için uygundur.
