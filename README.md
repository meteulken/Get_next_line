<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">

</head>
<body>
	<h1>get_next_line</h1>
	<p><em>get_next_line</em>, özellikle okuma işleminin yapıldığı C dilinde yazılmış bir fonksiyondur. Bu fonksiyon, bir dosyadan veya standart girdiden (STDIN) satır satır okuma işlemi gerçekleştirir.</p>
	<h2>Kullanımı</h2>
	<p><em>get_next_line</em> fonksiyonunu kullanarak bir dosyadan veya standart girdiden okuma işlemi gerçekleştirebilirsiniz. Fonksiyon, her çağrıldığında bir sonraki satırı okur. Fonksiyonun dönüş değeri, okunan satırın bir kopyasıdır ve bellek yönetimi kullanıcı tarafından gerçekleştirilmelidir.</p>
	<h3>Fonksiyon Adı</h3>
	<p>Aşağıdaki şekilde, <em>get_next_line</em> fonksiyonunun imzası yer almaktadır:</p>
	<pre>char	*get_next_line(int fd);</pre>
	<h3>Parametreler</h3>
	<ul>
		<li><code>fd</code>: Okunacak dosyanın dosya tanımlayıcısı (file descriptor).</li>
	</ul>
	<h3>Dönüş Değeri</h3>
	<p>Fonksiyon, okunan satırın bir kopyasını (string) döndürür. Okuma işlemi bittiğinde, fonksiyon NULL değeri döndürür.</p>
	<h2>Kurulum</h2>
	<p>Projenin kök dizininde, aşağıdaki şekilde bir komut çalıştırın:</p>
	<pre>make</pre>
	<p>Bu, derlenmiş kütüphaneyi oluşturacak ve libft.a dosyasını proje klasörüne ekleyecektir. Ardından, kaynak kodunuzda <em>get_next_line</em> fonksiyonunu kullanabilirsiniz.</p>
	<h2>Lisans</h2>
	<p>Bu proje, MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına bakabilirsiniz.</p>
</body>
</html>
