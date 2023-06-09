# 05. Ders - Metin Biçimlendirme Etiketleri

Bu etiketler, web sayfalarında metni vurgulamak, biçimlendirmek veya stillemek için kullanılır.

## Kalın ve İtalik

Metinde vurgulama yapmak için **`<strong>`** ve **`<em>`** etiketleri kullanılır. **`<strong>`** etiketi metni kalın olarak vurgularken, **`<em>`** etiketi metni italik olarak vurgular. İşte örnek bir kullanım:

~~~ HTML
<p>
Bu bir <strong>kalın</strong> ve <em>italik</em> metin örneğidir.
</p>
~~~

Bu örnekte, "kalın" kelimesi kalın olarak vurgulanacak ve "italik" kelimesi italik olarak vurgulanacaktır.

## Mark Etiketi

"**mark**" etiketi, metindeki belirli bir kısmı vurgulamak veya işaretlemek için kullanılır. **mark** etiketi, **`<mark>`** ile başlar ve **`</mark>`** ile sona erer. İşte bir örnek kullanım:

~~~ HTML
<p>
Bu bir <mark>vurgulanmış</mark> metin örneğidir.
</p>
~~~

Bu örnekte, "vurgulanmış" kelimesi sarı renkle arka planıyla birlikte vurgulanmış olarak görüntülenecektir.

## Del ve Ins Etiketleri

Bu etiketler, metindeki silinmiş veya eklenmiş kısımları göstermek için kullanılır. 

"**del**" etiketi, metindeki silinmiş veya çıkarılmış kısımları belirtmek için kullanılır. Bu etiket, **`<del>`** ile başlar ve **`</del>`** ile sona erer. İşte örnek bir kullanım:

~~~ HTML
<p>
Bu bir <del>silinmiş</del> metin örneğidir.
</p>
~~~

Bu örnekte, "silinmiş" kelimesi metinden çıkarılmış olarak görüntülenecektir.

"**del**" etiketinin bazı özellikleri şunlardır:

* Metindeki silinmiş veya çıkarılmış kısımları gösterir.
* Tarayıcılar, genellikle silinmiş metni üstü çizili olarak veya gri renkte gösterir.
* CSS kullanarak del etiketini biçimlendirebilirsiniz.

"**ins**" etiketi, metindeki eklenmiş veya eklendiği kısımları belirtmek için kullanılır. Bu etiket, **`<ins>`** ile başlar ve **`</ins>`** ile sona erer. İşte örnek bir kullanım:

~~~ HTML
<p>
Bu bir <ins>eklenmiş</ins> metin örneğidir.
</p>
~~~

Bu örnekte, "eklenmiş" kelimesi metne eklenmiş olarak görüntülenecektir.

"**ins**" etiketinin bazı özellikleri şunlardır:

* Metindeki eklenmiş veya eklenen kısımları gösterir.
* Tarayıcılar, genellikle eklenmiş metni altı çizili olarak veya yeşil renkte gösterir.
* CSS kullanarak ins etiketini biçimlendirebilirsiniz.

## Alt Başlık ve Betik Yazısı

Alt başlıklar veya betik yazıları için **`<sub>`** ve **`<sup>`** etiketleri kullanılır. **`<sub>`** etiketi metni altındaki küçük harfler olarak görüntülerken, **`<sup>`** etiketi metni üstündeki küçük harfler olarak görüntüler. İşte örnek bir kullanım:

~~~ HTML
<p>
H<sub>2</sub>O: Su molekülünde hidrojen atomları küçük harflerle altında görüntülenir.
</p>
~~~

Bu örnekte, "H2O" metni, "2" sayısı küçük harflerle altında görüntülenecektir.