# 02. Ders - Text Özellikleri

CSS, web sayfalarında metin görünümünü kontrol etmek için çeşitli metin özellikleri sağlar. Metin özellikleri, metnin fontu, boyutu, rengi, hizalaması, arka planı ve daha fazlasını kontrol etmek için kullanılır. Bu özellikler, metin içeriğinin daha okunabilir, estetik ve kullanıcı dostu olmasını sağlar.

İşte bazı yaygın CSS metin özellikleri:

## **`color`**

**color** özelliği, metin rengini belirlemek için kullanılır. Özelliğe bir renk değeri atanır. Örneğin:

~~~ CSS
p {
  color: blue;
}
~~~

Bu örnekte, **p** etiketlerindeki metin mavi renkte olacaktır.

## **`font-family`**

**font-family** özelliği, metnin kullanacağı yazı tipini belirlemek için kullanılır. Özelliğe bir veya birden fazla yazı tipi adı atanır. Örneğin:

~~~ CSS
body {
  font-family: Arial, sans-serif;
}
~~~

Bu örnekte, sayfadaki metin Arial yazı tipi veya alternatif olarak kullanılabilir bir sans-serif yazı tipi ile gösterilecektir.

## **`font-size`**

**font-size** özelliği, metin boyutunu belirlemek için kullanılır. Özelliğe bir boyut değeri atanır. Örneğin:

~~~ CSS
h1 {
  font-size: 24px;
}
~~~

Bu örnekte, **h1** başlıklarının metin boyutu 24 piksel olacaktır.

## **`font-weight`**

**font-weight** özelliği, metnin kalınlığını belirlemek için kullanılır. Özelliğe bir kalınlık değeri atanır. Örneğin:

~~~ CSS
p {
  font-weight: bold;
}
~~~

Bu örnekte, **p** etiketlerindeki metin kalın olarak gösterilecektir.

## **`text-align`**

**text-align** özelliği, metin hizalamasını belirlemek için kullanılır. Özelliğe bir hizalama değeri atanır. Örneğin:

~~~ CSS
p {
  text-align: center;
}
~~~

Bu örnekte, **p** öğelerindeki metin merkeze hizalanacaktır.

**text-align** özelliğinin diğer değerleri:

* **`text-align: right;`** özelliği ile metin sağa yaslanır.
* **`text-align: left;`** özelliği ile metin sola yaslanır.
* **`text-align: justify;`** özelliği ile metin iki yana yaslanır.

## **`text-decoration`**

**text-decoration** özelliği, metin süslemelerini belirlemek için kullanılır. Özelliğe bir veya birden fazla süsleme değeri atanır. Örneğin:

~~~ CSS
p {
  text-decoration: underline;
}
~~~

Bu örnekte, **p** etiketleri altı çizili olarak gösterilecektir.

**text-decoration** özelliğinin diğer değerleri:

* **`text-decoration: line-through;`** özelliği ile metnin üzeri çizilir.
* **`text-decoration: overline;`** özelliği ile metnin üstü çizilir.
* **`text-decoration: none;`** özelliği ile metinde çizilmiş yapılar kaldırılır. 

## Diğer Özellik ve Değerleri

* **`font-style`**: italic; özelliği ile metin italik olarak yazdırılır.

* **`text-align-last`** özelliği metinlerin son satırının nasıl konumlandırılacağı belirtilir. 

    * **`text-align-last: right;`** özelliği ile metnin son satırı sağa yaslanır.
    * **`text-align-last: left;`** özelliği ile metnin son satırı sola yaslanır.
    * **`text-align-last: center;`** özelliği ile metnin son satırı ortalanır.
    * **`text-align-last: justify;`** özelliği ile metnin son satırı iki yana yaslanır.

* **`text-transform`** özelliği ile metin içerisindeki harflerin büyük veya küçük olma durumu belirtilir.

    * **`text-transform: uppercase;`** özelliği ile metindeki bütün harfler büyük harfe dönüştürülür.
    * **`text-transform: lowercase;`** özelliği ile metindeki bütün harfler küçük harfe dönüştürülür.
    * **`text-transform: capitalize;`** özelliği ile metindeki kelimelerin baş harfleri büyük harfe dönüştürülür.

* **`text-indent: "..."`** özelliği ile ilk satırın girinitisi belirlenir.

* **`letter-spacing: "..."`** özelliği ile karakterler arası mesafeyi (boşluğu) ayarlar.

* **`word-spacing: "..."`** özelliği ile metindeki sözcükler arasındaki mesafeyi (boşluğu) ayarlar.

* **`line-height: "..."`** özelliği ile satır yüksekliği ayarlanır.

* **`text-shadow: "..."`** özelliği ile metinlere gölgelendirme yapılabilir.