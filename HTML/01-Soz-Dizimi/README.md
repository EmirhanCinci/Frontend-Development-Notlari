# 01. Ders - HTML5 Söz Dizimi

HTML5, web sayfalarını oluşturmak için kullanılan bir işaret dili olan HTML'nin en son sürümüdür. HTML, HyperText Markup Language'ın kısaltmasıdır ve web tarayıcıları tarafından anlaşılabilen yapısallaştırılmış içerikler oluşturmak için kullanılır. HTML5, önceki sürümlere göre yeni özellikler, geliştirmeler ve iyileştirmeler sunar.

## Dosya Yapısı

HTML5 dosyaları genellikle .html uzantısına sahip metin dosyalarıdır. Bir HTML5 belgesi genellikle aşağıdaki temel yapısına sahiptir:

~~~ HTML
<!DOCTYPE html>
<html>
    <head>
        <title>Web Sayfasının Başlığı</title>
    </head>
    <body>
        <!-- Sayfa içeriği buraya gelir -->
    </body>
</html>
~~~

* **`<!DOCTYPE html>`** : Bu ifade, belgenin HTML5 uyumlu olduğunu belirtir.
* **`<html>`** : HTML belgesinin kök öğesi olup, tüm diğer öğeleri içerir.
* **`<head>`** : Sayfa başlığı, stiller ve diğer meta veriler gibi belgeyle ilgili bilgileri içeren bölüm.
* **`<title>`** : Web sayfasının başlığını belirtir. Tarayıcı sekmesinde görünen metindir.
* **`<body>`** : Sayfa içeriğini içeren bölüm. Metin, resimler, bağlantılar ve diğer öğeler burada yer alır.

## Etiketler ve Öznitelikler

HTML5, web sayfalarını oluşturmak için bir dizi etiket ve öznitelik sağlar. Etiketler, içerikleri yapısallaştırmak ve belirli amaçlar için kullanmak için kullanılırken, öznitelikler ise etiketlerin davranışını veya görünümünü özelleştirmek için kullanılır.

Örnek bir etiket:

~~~ HTML
<h1>Başlık</h1>
~~~

Örnek bir etiket ve özniteliği:

~~~ HTML
<a href="https://www.example.com">Bağlantı Metni</a>
~~~

HTML5'de birçok etiket ve öznitelik bulunur ve her birinin belirli bir amacı vardır. Örneğin:

* **`<h1>`** ila **`<h6>`** : Başlıkları temsil eder, **`<h1>`** en yüksek seviyede başlığı temsil ederken, **`<h6>`** en düşük seviyede başlığı temsil eder.
* **`<p>`** : Paragrafı temsil eder.
* **`<a>`** : Bağlantıyı temsil eder.
* **`<img>`** : Resmi temsil eder.