# 11. Ders - Block ve Inline Etiketler

HTML'de, içerik öğelerini farklı düzenleme ve davranış kurallarına göre ayırmak için iki temel etiket tipi vardır: block ve inline.

## Block Etiketler

Block etiketler, içerdikleri içeriği blok halinde yerleştirir. Yani, varsayılan olarak bir satırın tam genişliğini kaplar ve alt satıra geçer. Block etiketlerinin en yaygın kullanılanları şunlardır:

* **`<div>`**: Genel amaçlı bir block etiketi olup, diğer içerikleri gruplamak veya stil uygulamak için kullanılır.
* **`<p>`**: Paragraf oluşturur ve otomatik olarak boş bir satır bırakır.
* **`<h1>`** - **`<h6>`**: Başlık etiketleri olup, farklı başlık düzeylerini temsil eder.

Örnek kullanım:

~~~ HTML
<div>
  <h1>Başlık</h1>
  <p>Paragraf metni...</p>
  <p>Başka bir paragraf metni...</p>
</div>
~~~

## Inline Etiketler

Inline etiketler, içerdikleri içeriği blok içine yerleştirmeden satırın aynı hizasında kalacak şekilde yerleştirir. Bu etiketler, içeriklerin bir arada görüntülenmesini sağlar. Inline etiketlerinin en yaygın kullanılanları şunlardır:

* **`<span>`**: Genel amaçlı bir inline etiketi olup, diğer içerikleri gruplamak veya stil uygulamak için kullanılır.
* **`<a>`**: Bir bağlantı oluşturur.
* **`<strong>`** veya **`<b>`**: Metni kalın yapar.
* **`<em>`** veya **`<i>`**: Metni italik yapar.

Örnek kullanım:

~~~ HTML
<p>
  Bu bir <strong>kalın</strong> metindir. Ayrıca, <a href="#">bir bağlantı</a> içerir.
</p>
~~~

## Block ve Inline Etiketlerin Karışımı

Block ve inline etiketleri gerektiğinde bir arada kullanabilirsiniz. Block etiketleri, içinde inline etiketler barındırabilir ve içeriklerini blok şeklinde yerleştirirken, inline etiketler inline olarak kalır. Örnek kullanım:

~~~ HTML
<div>
  <h2>Başlık</h2>
  <p>Paragraf metni ve <strong>kalın bir kelime</strong> içerir.</p>
</div>
~~~