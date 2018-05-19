
1. Gerekli Konsol Komutları

    * Bulunduğumuz dizinde hangi klasörler var onları listeler.
    > ls -l
    * Listelenen dizinlerdeki herhangi bir klasörün içine girmemize yarar.
    > cd dizin
    * Bir üst dizine geri dönmek için kullanılır.
    > cd ..
    * Ana dizine dönmek için kullanılır.
    > cd --


2. Rails Proje Oluşturma

    2.1 Öncelikle projeyi oluşturacağımız dizine geliriz.
    > cd Desktop
    
    2.2 Bulunduğumuz dizinde proje oluşturmak için aşağıdaki komutu çalıştırırız.
    > rails new newproje
	
	2.3 Ardından oluşturduğumuz proje dizininin içine girmeliyiz.
	>cd newproje
	
	2.4 Ardından projemizin çalışması için gerekli olan paketleri yüklememiz gerekmektedir.
	>bundle install
	
	2.5 Paketler yüklendikten sonra proje çalıştırıp test edilmedir.
	>rails s
	
	veya
	>rails server
	
	Proje default olarak aşağıdaki bağlantılarda çalışmaktadır.

		0.0.0.0:3000
		localhost:3000
