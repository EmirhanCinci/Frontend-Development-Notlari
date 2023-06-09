# 12. Ders - Id ve Class Yapısı

HTML'de "**id**" ve "**class**" yapıları, belirli öğelere özel kimlik veya özellikler atamak ve CSS veya JavaScript gibi diğer teknolojilerle bu öğelere erişmek için kullanılır.

## ID (Kimlik)

"**id**" özelliği, bir HTML öğesine benzersiz bir kimlik atamak için kullanılır. Her bir "**id**" değeri belirli bir HTML belgesi içinde yalnızca bir kez kullanılmalıdır. "**id**" özelliği, CSS ve JavaScript gibi teknolojilerle belirli bir öğeye doğrudan erişmek için kullanılabilir.

Örnek bir ID kullanımı:

~~~ HTML
<h1 id="baslik">Merhaba Dünya!</h1>
~~~

Bu örnekte, **`<h1>`** başlık öğesine baslik adında bir ID atandı. Bu ID, CSS ile stil uygulamak veya JavaScript ile öğeye erişmek için kullanılabilir.

## Class (Sınıf)

"**class**" özelliği, belirli bir veya birden fazla HTML öğesine aynı sınıfı atamak için kullanılır. Bir HTML belgesinde birden çok öğe aynı sınıfa sahip olabilir. "**class**" özelliği, CSS ile stil uygulamak veya JavaScript ile belirli bir sınıfa ait öğelere erişmek için kullanılabilir.

Örnek bir Class kullanımı:

~~~ HTML
<p class="yazi">Bu bir paragraf örneğidir.</p>
~~~

Bu örnekte, **`<p>`** paragraf öğesine yazi adında bir sınıf atandı. Bu sınıf, CSS ile stil uygulamak veya JavaScript ile belirli bir sınıfa ait öğelere erişmek için kullanılabilir.

## ID ve Class'ın Karşılaştırması

* "**id**", benzersiz ve yalnızca bir kez kullanılabilen bir kimlik sağlar. "**class**" ise birden fazla öğeye aynı sınıfı atamak için kullanılır.

* "**id**", CSS veya JavaScript gibi teknolojilerle belirli bir öğeye doğrudan erişim sağlamak için kullanılabilir. "**class**" ise birden fazla öğeyi gruplamak veya benzer özellikleri paylaşan öğelere stil uygulamak için kullanılabilir.

* "**id**" ve "**class**" özellikleri, bir öğeye hem id hem de class atanarak birlikte kullanılabilir.