# 01. Ders - CSS Söz Dizimi ve Kullanımı

CSS (Cascading Style Sheets), web sayfalarının görünümünü ve düzenini kontrol etmek için kullanılan bir stil dilidir.

CSS söz dizimi, CSS kodunu doğru bir şekilde yazmanızı sağlayan belirli kurallar ve yapılar içerir. İşte CSS söz diziminin temel unsurları:

## CSS Kuralları

CSS kuralları, bir veya daha fazla öğenin belirli bir stilini tanımlar. Her bir CSS kuralı aşağıdaki şekilde görünür:

~~~ CSS
selector {
  property: value;
  property: value;
  /* diğer özellikler */
}
~~~

* "**selector**": CSS kurallarının uygulanacağı HTML öğesini seçer.
* "**property**": Öğenin stil özelliklerini belirtir.
* "**value**": Özelliğin değerini belirtir.

## CSS Seçicileri

CSS seçicileri, hangi HTML öğelerine stil kurallarının uygulanacağını belirler. İşte bazı yaygın CSS seçici örnekleri:

* "**element**": Belirli bir HTML öğesini seçer (örneğin, h1, p, div).
* "**.class**": Belirli bir sınıfa sahip olan HTML öğelerini seçer.
* "**#id**": Belirli bir kimliğe sahip olan HTML öğesini seçer.
* "**selector1**", "**selector2**": Birden fazla seçiciyi birleştirerek stil kurallarını birden fazla öğeye uygular.

## CSS Özellikleri ve Değerleri

CSS, bir dizi özellik ve değer sağlar. Bu özellikler, HTML öğelerinin görünümünü kontrol etmek için kullanılır. İşte bazı örnekler:

* "**color**": Metin rengini belirler (örneğin, **`color: red;`**).
* "**font-size**": Metin boyutunu belirler (örneğin, **`font-size: 16px;`**).
* "**background-color**": Arka plan rengini belirler (örneğin, **`background-color: #f1f1f1;`**).
* "**margin**": Öğenin dış boşluklarını belirler (örneğin, **`margin: 10px;`**).
* "**padding**": Öğenin iç boşluklarını belirler (örneğin, **`padding: 5px;`**).

## CSS Kullanımı

CSS kullanımının temel adımları:

1. HTML belgesinde **`<style>`** etiketi içinde CSS kodu oluşturun veya harici bir CSS dosyası oluşturun ve HTML belgesine bağlayın.
2. CSS kodu içinde seçiciler ve stil kuralları tanımlayın.
3. Stil kurallarını seçilen HTML öğelerine uygulayarak görünümünü değiştirin.

Örnek bir CSS3 kullanımı:

~~~ HTML
<!DOCTYPE html>
<html>
<head>
  <style>
    h1 {
      color: blue;
      font-size: 24px;
    }

    .my-class {
      background-color: yellow;
      padding: 10px;
    }
  </style>
</head>
<body>
    <h1>Merhaba, Dünya!</h1>
    <p class="my-class">Bu bir örnek paragraftır.</p>
</body>
</html>
~~~

Bu örnekte, **`<style>`** etiketi içinde CSS kodu oluşturduk. "**h1**" seçici ile başlık etiketine mavi renk ve 24 piksel font boyutu uyguladık. "**.my-class**" sınıfını kullanarak paragraf öğesine sarı arka plan ve 10 piksel iç boşluk uyguladık.