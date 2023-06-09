# 13. Ders - Form Etiketleri

HTML form etiketleri, kullanıcıların veri girişi yapabildiği ve sunucuya gönderilebilen interaktif form alanları oluşturmak için kullanılır. Form etiketleri, kullanıcının veri girişi yapabilmesini sağlar ve bu verilerin sunucuya gönderilmesini kolaylaştırır.

## Form Etiketleri

HTML'de kullanılan bazı temel form etiketleri şunlardır:

* **`<form>`**: Formu tanımlar ve içine form elemanlarını yerleştirir.
* **`<input>`**: Kullanıcının veri girişi yapmasını sağlayan bir giriş alanı oluşturur.
* **`<select>`**: Bir açılır menü oluşturur ve kullanıcının seçim yapmasına olanak tanır.
* **`<textarea>`**: Çok satırlı bir metin giriş alanı oluşturur.
* **`<button>`**: Bir düğme oluşturur.

Örnek bir form yapısı:

~~~ HTML
<form action="/sunucu-yolu" method="POST">
  <label for="isim">İsim:</label>
  <input type="text" id="isim" name="isim" required>

  <label for="email">E-posta:</label>
  <input type="email" id="email" name="email" required>

  <label for="mesaj">Mesaj:</label>
  <textarea id="mesaj" name="mesaj" rows="4" cols="30"></textarea>

  <button type="submit">Gönder</button>
</form>
~~~

Bu örnekte, bir form oluşturuldu ve action özelliği ile form verilerinin gönderileceği sunucu yolunu belirttik. method özelliği ile form verilerinin hangi HTTP metodunu kullanarak gönderileceğini belirledik. label etiketleri, giriş alanlarına bir etiket eklememizi sağlar ve for özelliği ile ilişkilendirdiğimiz giriş alanını belirtir. input etiketleri, kullanıcının veri girişi yapmasını sağlar ve type özelliği ile giriş alanının türünü belirler.