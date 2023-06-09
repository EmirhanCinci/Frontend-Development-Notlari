# 03. Ders - Başlık Etiketleri

Başlık etiketleri, web sayfalarında başlıkları tanımlamak için kullanılan HTML etiketleridir. Başlıklar, sayfanın hiyerarşik yapısını oluşturur ve içeriğin önem sırasını belirtir. Başlık etiketleri, arama motorları ve tarayıcılar gibi web araçları tarafından sayfanın anlaşılması ve yorumlanması için kullanılır.

HTML5'de başlık etiketleri **`<h1>`** ile **`<h6>`** arasında sıralanır. **`<h1>`** en yüksek öneme sahip başlığı temsil ederken, **`<h6>`** en düşük öneme sahip başlığı temsil eder. Örneğin:

~~~ HTML
<h1>Başlık 1</h1>
<h2>Başlık 2</h2>
<h3>Başlık 3</h3>
<h4>Başlık 4</h4>
<h5>Başlık 5</h5>
<h6>Başlık 6</h6>
~~~

## Başlık Etiketi Hiyerarşisi

Başlık etiketleri, sayfanın yapısını ve içeriğin önem sırasını belirlemek için bir hiyerarşi oluşturur. Bu hiyerarşi, sayfanın kullanıcılar tarafından daha iyi anlaşılmasını ve erişilebilirliğini sağlar. İşte başlık etiketi hiyerarşisinin temel özellikleri:

* **`<h1>`** en üst düzey başlığı temsil eder ve genellikle sayfanın ana başlığı olarak kullanılır.
* **`<h2>`** bir alt düzey başlığı temsil eder ve genellikle ana bölümleri tanımlamak için kullanılır.
* **`<h3>`** **`<h2>`** başlığının alt düzey başlığıdır ve alt bölümleri tanımlamak için kullanılabilir.
* **`<h4>`** - **`<h6>`** başlıkları, daha fazla alt düzey başlık için kullanılabilir.

Başlık etiketlerini hiyerarşik bir şekilde kullanmak, sayfanın yapısını ve içeriğini daha iyi organize etmek için önemlidir.

## Başlık Etiketleri Kullanılırken Dikkat Edilmesi Gereken Noktalar

* **Hiyerarşik Yapı**: Başlık etiketlerini, sayfanın yapısını yansıtacak şekilde kullanın. En önemli başlık **`<h1>`** olmalı ve sıralama **`<h1>`** ile başlayıp **`<h6>`** ile bitmelidir.

* **Başlık Anlamı**: Başlık etiketlerini, içeriğin anlamını yansıtacak şekilde kullanın. Başlık, sayfanın konusunu veya bölümünü özetleyen bir ifade olmalıdır.

* **Tekrarlanan Başlıklar**: Bir sayfada aynı düzeyde birden fazla aynı başlık etiketi kullanmaktan kaçının. Her başlık etiketi benzersiz olmalıdır.

* **Boyut ve Stil**: Başlık etiketlerinin boyutu ve stili, tarayıcılar tarafından varsayılan olarak belirlenen şekilde görüntülenir. CSS kullanarak başlık etiketlerini özelleştirebilirsiniz, ancak kullanıcı deneyimini olumsuz etkileyecek aşırı büyük veya küçük başlıklardan kaçınmalısınız.

* **Sayfa Başlığı**: Sayfanın genel başlığını tanımlamak için `<title>` etiketini kullanmalısınız. Bu etiket, tarayıcı sekmesinde veya arama sonuçlarında sayfanın başlığı olarak görüntülenir.

## Örnek Kullanımlar

İşte başlık etiketlerinin bazı örnek kullanımları:

~~~ HTML
<h1>Hoş Geldiniz!</h1>
    <h2>Web Tasarımına Giriş</h2>
        <h3>HTML Temelleri</h3>
            <h4>Etiketler</h4>
            <h4>Formlar</h4>
        <h3>CSS Özellikleri</h3>
            <h4>Renkler</h4>
            <h4>Yazı Stilleri</h4>
            <h4>Kenarlık</h4>
    <h2>Web Geliştirme İpuçları</h2>
        <h3>SEO Stratejileri</h3>
        <h3>Mobil Uyumluluk</h3>
~~~

Bu örneklerde başlık etiketlerini hiyerarşik bir şekilde kullanarak sayfanın yapısını belirledik.