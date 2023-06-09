# 02. Ders - Meta Etiketleri

Web geliştirme sürecinde, web sayfalarının tarayıcılar ve arama motorları tarafından nasıl yorumlanacağını kontrol etmek önemlidir. Bu noktada HTML5 meta etiketleri devreye girer. Meta etiketleri, web sayfalarına ilişkin önemli bilgileri belirlemek ve doğru bir şekilde yorumlanmalarını sağlamak için kullanılan HTML etiketleridir.

## Nedir Meta Etiketleri?

Meta etiketleri, web sayfalarının başlık bilgileri, karakter kodlaması, tarayıcı uyumluluğu, açıklama metni, anahtar kelimeler gibi meta verilerini belirtmek için kullanılan etiketlerdir. Bu etiketler, tarayıcılar, arama motorları ve diğer web araçları tarafından kullanılır ve web sayfasının doğru bir şekilde yorumlanmasına yardımcı olur.

Meta etiketleri ayrıca sosyal medya paylaşımları sırasında sayfa başlığı, açıklama ve resim gibi önemli bilgilerin belirlenmesinde de kullanılabilir. Bu sayede, paylaşılan bir bağlantının daha etkili bir şekilde gösterilmesi ve ilgi çekici olması sağlanabilir.

## Örnek Kullanımlar

Aşağıda, bazı yaygın meta etiketlerinin örnek kullanımlarını bulabilirsiniz:

### "charset"

Bu etiket, web sayfasının karakter kodlamasını belirlemek için kullanılır. Örneğin, UTF-8 karakter kodlamasını kullanmak için aşağıdaki örneği kullanabilirsiniz:

~~~ HTML
<meta charset="UTF-8">
~~~

### "viewport"

Bu etiket, web sayfasının görüntülenme alanını belirlemek için kullanılır, özellikle mobil cihazlarda önemlidir. Örneğin, aşağıdaki örnekte sayfa genişliğini cihaz genişliğine ayarlamak için **"width=device-width"** ifadesini kullanabilirsiniz:

~~~ HTML
<meta name="viewport" content="width=device-width, initial-scale=1.0">
~~~

### "description"

Bu etiket, web sayfasının kısa bir açıklamasını belirtmek için kullanılır. Arama motorları, bu açıklamayı sayfa içeriğini anlamak ve kullanıcıların arama sonuçlarında daha iyi bir önizleme elde etmesini sağlamak için kullanır. Örneğin:

~~~ HTML
<meta name="description" content="Bu web sitesi, web geliştirme konularında bilgi ve ipuçları sunan bir kaynaktır.">
~~~

### "keywords"

Bu etiket, web sayfasının anahtar kelimelerini belirtmek için kullanılır. Anahtar kelimeler, arama motorlarına sayfanın içeriği hakkında bilgi verir ve kullanıcıların ilgili içeriği daha kolay bulmalarına yardımcı olur. Örneğin:

~~~ HTML
<meta name="keywords" content="web geliştirme, HTML, CSS, JavaScript, web tasarımı">
~~~

### "author"

Bu etiket, web sayfasının yazarını belirtmek için kullanılır. Örneğin:

~~~ HTML
<meta name="author" content="John Doe">
~~~

## Diğer Meta Etiketleri

Yukarıdaki örnekler, sık kullanılan meta etiketlerinden sadece birkaçını içermektedir. HTML5'de daha fazla meta etiketi bulunmaktadır ve belirli ihtiyaçlara göre kullanılabilir. Bu etiketler, web sayfalarının sosyal medya entegrasyonu, tarayıcı uyumluluğu, dil belirleme gibi konularda daha iyi bir kontrol sağlamak için kullanılabilir.