# 07. Ders - Resim Etiketi

"**img**" etiketi, web sayfalarında görüntüleri göstermek için kullanılır. **img** etiketi, **`<img>`** olarak kullanılır ve kendini kapatan bir etikettir. Bir görüntüyü görüntülemek için src özniteliği kullanılır. İşte bir örnek kullanım:

~~~ HTML
<img src="image.jpg" alt="Resim Açıklaması">
~~~

Bu örnekte, "image.jpg" adlı bir görüntü görüntülenecek ve "Resim Açıklaması" olarak tanımlanacaktır.

"**img**" etiketinin bazı özellikleri şunlardır:

* Görüntüleri web sayfalarında görüntülemek için kullanılır.
* src özniteliği, görüntünün dosya yolunu veya URL'sini belirtir.
* alt özniteliği, görüntü açıklamasını belirtir ve görüntü yüklenemezse veya okunamazsa metin olarak görüntülenir.
* width ve height öznitelikleri, görüntünün genişlik ve yüksekliğini belirleyebilir (piksel cinsinden veya yüzde olarak).

Aşağıda, **img** etiketinin nasıl kullanılabileceğine dair bazı örnekler bulunmaktadır:

~~~ HTML
<img src="image.jpg" alt="Resim Açıklaması">
~~~

~~~ HTML
<img src="path/to/image.png" alt="Başka Bir Resim" width="300" height="200">
~~~

~~~ HTML
<img src="https://www.example.com/image.jpg" alt="Uzaktan Bir Resim">
~~~