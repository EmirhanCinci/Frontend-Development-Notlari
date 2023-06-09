# 04. Ders - Paragraf ve Pre Etiketi 

Bir web sayfası metinden oluşur ve metinleri belirtmek için birçok etiket bulunur. Bu etiketler, tarayıcıya içeriği nasıl görüntüleyeceğini ve yorumlayacağını söyler. 

## Paragraf Etiketi

Paragraf etiketi, bir web sayfasında paragrafları belirtmek için kullanılır. **`<p>`** etiketi ile başlar ve **`</p>`** etiketi ile sona erer. İki etiket arasına yazılan her şey, bir paragraf olarak kabul edilir.

İşte bir örnek:

~~~ HTML
<p>
Bu bir paragraf örneğidir. Paragraf etiketi kullanarak metni paragraflara bölebiliriz. Tarayıcı, paragrafları otomatik olarak düzenler ve aralarında bir boşluk bırakır.
</p>
~~~

Bu örnekte, tarayıcı paragrafları otomatik olarak düzenleyecek ve her bir paragraf arasında bir boşluk bırakacaktır.

Paragraf etiketinin bazı özellikleri şunlardır:

* Metni otomatik olarak paragraflara böler.
* Her paragraf arasında bir boşluk bırakır.
* CSS (Cascading Style Sheets) kullanarak paragrafları biçimlendirebilirsiniz.

## Pre Etiketi

Pre etiketi, metni ön biçimlendirilmiş bir alan içinde görüntülemek için kullanılır. Bu etiket, metindeki boşlukları, satır sonlarını ve diğer boşlukları korur. Pre etiketi, **`<pre>`** ile başlar ve **`</pre>`**  ile sona erer. İşte bir örnek:

~~~ HTML
<pre>
Bu bir ön biçimlendirilmiş metin örneğidir. Pre etiketi kullanıldığında, metindeki boşluklar ve satır sonları korunur.
    Bu metin içindeki boşluklar ve satır sonları korunur.
</pre>
~~~

Bu örnekte, metindeki boşluklar, satır sonları ve diğer boşluklar orijinal şekliyle görüntülenecektir.

Pre etiketinin bazı özellikleri şunlardır:

* Metindeki boşlukları, satır sonlarını ve diğer boşlukları korur.
* Ön biçimlendirilmiş metinler için idealdir, örneğin kod bloklarını veya düz metin içeriğini göstermek için kullanılabilir.
* CSS kullanarak ön biçimlendirilmiş metinleri biçimlendirebilirsiniz.