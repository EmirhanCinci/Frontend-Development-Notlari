# 09. Ders - Liste Etiketleri

HTML liste etiketleri, metin veya içeriği sıralı veya sırasız bir liste biçiminde görüntülemek için kullanılır. İki temel liste türü vardır:

* Sıralı Liste (**`<ol>`**): Numaralandırılmış bir liste oluşturur.
* Sırasız Liste (**`<ul>`**): İşaretlenmiş bir liste oluşturur.

## Sıralı Liste - **`<ol>`**

Sıralı liste etiketi olan **`<ol>`**, numaralandırılmış bir liste oluşturur. Her liste öğesi **`<li>`** etiketi ile belirtilir. İşte bir örnek:

~~~ HTML
<ol>
  <li>Liste öğesi 1</li>
  <li>Liste öğesi 2</li>
  <li>Liste öğesi 3</li>
</ol>
~~~

Bu kod, aşağıdaki gibi görünen bir sıralı liste oluşturur:

1. Liste öğesi 1
2. Liste öğesi 2
3. Liste öğesi 3

## Sırasız Liste - **`<ul>`**

Sırasız liste etiketi olan **`<ul>`**, işaretlenmiş bir liste oluşturur. Her liste öğesi **`<li>`** etiketi ile belirtilir. İşte bir örnek:

~~~ HTML
<ul>
  <li>Liste öğesi 1</li>
  <li>Liste öğesi 2</li>
  <li>Liste öğesi 3</li>
</ul>
~~~

Bu kod, aşağıdaki gibi görünen bir sırasız liste oluşturur:

* Liste öğesi 1
* Liste öğesi 2
* Liste öğesi 3

## İç İçe Liste

HTML listeleri iç içe kullanılabilir. İç içe liste oluşturmak için, iç liste öğelerini bir üst liste öğesinin <li> etiketi içine yerleştirin. İşte bir örnek:

~~~ HTML
<ol>
  <li>Liste öğesi 1</li>
  <li>Liste öğesi 2
    <ul>
      <li>İç liste öğesi 1</li>
      <li>İç liste öğesi 2</li>
    </ul>
  </li>
  <li>Liste öğesi 3</li>
</ol>
~~~

Bu kod, aşağıdaki gibi görünen bir iç içe sıralı liste oluşturur:

1. Liste öğesi 1
2. Liste öğesi 2
    * İç liste öğesi 1
    * İç liste öğesi 2
3. Liste öğesi 3

## Özel İşaretler

HTML listelerinde varsayılan işaretleri kullanmak zorunda değilsiniz. CSS kullanarak özel işaretler tanımlayabilirsiniz. İşte bir örnek:

~~~ HTML
<ul style="list-style-type: square;">
    <li>Liste öğesi 1</li>
    <li>Liste öğesi 2</li>
    <li>Liste öğesi 3</li>
</ul>
~~~

Bu kod ile madde imleri daire şeklinde değil, kare şeklinde olur.