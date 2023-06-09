# 03. Ders - Border Özellikleri

**`border`** özelliği, HTML öğelerinin kenarlarını çerçevelemek için kullanılır. Bu özellik, öğelerin görünümünü zenginleştirmek, vurgulamak veya sınırlamak için kullanışlıdır. **`border`** özelliği, kenarlar boyunca çizgilerin ve çerçevenin rengini, kalınlığını ve stilini belirlemenizi sağlar.

## **`border-style`**

**`border-style`** özelliği, kenarların stilini belirlemek için kullanılır. Bu özelliğe bir veya birden fazla stil değeri atanabilir. Bazı yaygın **`border-style`** değerleri şunlardır:

* **`none`**: Kenarlar çizilmez.
* **`solid`**: Tek çizgiyle düz bir kenar oluşturulur.
* **`dashed`**: Kesikli bir çizgiyle kenar oluşturulur.
* **`dotted`**: Noktalı bir çizgiyle kenar oluşturulur.
* **`double`**: İki çizgiyle kalın bir kenar oluşturulur.

Örnek kullanım:

~~~ CSS
div {
  border-style: solid;
}
~~~

Bu örnekte, **div** etiketlerinin kenarları tek çizgi stiliyle görüntülenecektir.

## **`border-width`**

**`border-width`** özelliği, kenar kalınlığını belirlemek için kullanılır. Bu özelliğe bir kalınlık değeri atanır. Örnek kullanım:

~~~ CSS
div {
  border-width: 2px;
}
~~~

Bu örnekte, **div** etiketlerinin kenarları 2 piksel kalınlığında olacaktır.

## **`border-color`**

**`border-color`** özelliği, kenar rengini belirlemek için kullanılır. Bu özelliğe bir renk değeri atanır. Örnek kullanım:

~~~ CSS
div {
  border-color: red;
}
~~~

Bu örnekte, **div** öğesinin kenarları kırmızı renkte olacaktır.

## **`border-radius`**

**`border-radius`** özelliği, kenar köşelerinin yuvarlaklığını belirlemek için kullanılır. Bu özelliğe bir yuvarlaklık değeri atanır. Örnek kullanım:

~~~ CSS
div {
  border-radius: 10px;
}
~~~

Bu örnekte, **div** öğesinin köşeleri 10 piksel yarıçaplı yuvarlatılmış olacaktır.

## **`border`**

**`border`** özelliği, **`border-width`**, **`border-style`** ve **`border-color`** özelliklerini birleştirerek kenarların stilini tek bir özellikle belirlemenizi sağlar. Örnek kullanım:

~~~ CSS
div {
  border: 1px solid red;
}
~~~

Bu örnekte, **div** öğesinin kenarları 1 piksel kalınlığında, tek çizgi stili ve kırmızı renkte olacaktır.