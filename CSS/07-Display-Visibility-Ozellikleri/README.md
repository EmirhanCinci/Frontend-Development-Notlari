# 07. Ders - Display Visibility Özellikleri

**`display`** ve **`visibility`** özellikleri, HTML öğelerinin görünürlüğünü kontrol etmek için kullanılır. Her iki özellik de öğelerin görünümünü değiştirmek için kullanılabilir, ancak farklı şekillerde davranırlar.

**`visibility`** özelliği, bir öğenin görünürlüğünü kontrol etmek için kullanılır. Bu özellik, öğenin tamamen gizlenip görünmez hale gelip gelmeyeceğini belirler. Bazı visibility özelliği değerleri şunlardır:

* **`visible`**: Öğe görünürdür.
* **`hidden`**: Öğe görünmez hale getirilir, ancak yine de yer kaplar.
* **`collapse`**: Sadece tablo öğelerinde kullanılır. Öğe gizlenir ve tablo hücrelerini düzenler.

Örneğin, **span** öğesini görünmez hale getirmek için şu şekilde kullanabiliriz:

~~~ CSS
span {
  visibility: hidden;
}
~~~

## **`display`** ve **`visibility`** Özellikleri Arasındaki Farklar

* **`display: none`**; kullanıldığında, öğe tamamen kaldırılır ve yerini alan diğer öğeleri etkilemez. **`visibility: hidden;`** kullanıldığında ise öğe görünmez hale gelir, ancak hala yer kaplar ve yerini alan diğer öğeleri etkiler.

* **`display: none;`** ile gizlenen bir öğe, CSS seçicileri veya JavaScript kullanılarak hedeflenemezken, **`visibility: hidden;`** ile gizlenen bir öğe hala hedeflenebilir.

* **`display: none;`** kullanıldığında, öğenin içeriği ve boyutları da kaldırılır. **`visibility: hidden;`** kullanıldığında ise öğenin içeriği ve boyutları korunur, sadece görünürlük değişir.