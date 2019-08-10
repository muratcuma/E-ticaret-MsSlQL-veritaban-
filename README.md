# E ticaret Veritabanı diyagramı

SQL'de Tablo Birleştirme ve JOIN

SQL'de bazı durumlarda birden fazla tablodan veri çekme ihtiyacı duyabiliriz. Bunun için tablolar arasında bir ilişki kurulması gerekmektedir. Bu ilişki JOIN ile sağlanır. JOIN ifadesi birden fazla tabloyu birbirine bağlayıp  bu tablolar üzerinde işlem yapmamıza olanak sağlar.

JOIN ifadesi ile hangi tabloları ve nasıl birleştireceğimizi ON ifadesi ile tabloların hangi alanlar üzerinden birleşeceğini belirtiriz.

Tablolar genelde Birincil Anahtar ve Yabancı Anahtar alanları üzerinden birleştirilselerde, gerektiğinde diğer herhangi bir alan da bunun için kullanılabilir. Fakat bu alanların aynı tür veri içerdiğinden emin olmalısınız.

Birincil Anahtar (Primary key), her kayıt için benzersiz bir değer taşıyan alandır. 

Örneğin, öğrenci kayıtlarının tutulduğu bir tabloda, öğrenci numarasının saklandığı alan birincil anahtar olarak seçilebilir. Zira öğrenciyle ilgili tüm bilgiler gerçekte onun numarası ile kodlanmıştır ve her öğrencinin numarası bir birinden farklıdır.

Tablolar birleştirilirken Primary Key - Foreign Key ikilisi kullanılır. Tablolar arası ilişkiler aynı zamanda Unique Index kullanılarakta yapılabilir. Fakat yaygın olarak PK - FK kullanılır.

Primary Key (Birincil Anahtar) : Her satırı tekil bir şekilde tanımlayan benzersiz anahtardır. Primary Key sayesinde tablolarda bulunan satırlar birbirlerinden farklı olur ve her satırın Primary Key değeri farklı atanır. Primary Key tek bir sütun olduğu gibi birden fazla sütundan da oluşabilir.

Primary Key olacak sütun asla boş değer almamalıdır.
Primary Key olacak sütun tekrarı olmayan kayıtlardan oluşmalıdır...
Primary Key sütunu olabildiğince küçük ve basit veri tipinde tanımlanmalıdır.

Foreign Key (Yabancı Anahtar) : Bir tablodaki sütunun başka tablodaki anahtara olan referansını belirler. Primary Key'den farklı olarak bir tabloda birden fazla Foreign Key olabilir.



![alt text](https://user-images.githubusercontent.com/43292855/50606085-7b3e1580-0ed5-11e9-8300-1407cb8031ea.png)

