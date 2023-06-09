# 06. Ders - Bağlantı Etiketi

"**a**" etiketi, bir bağlantı oluşturmak için kullanılır ve web sayfalarında diğer sayfalara veya kaynaklara yönlendirme yapar.

"**a**" etiketi, **`<a>`** ile başlar ve **`</a>`** ile sona erer. Bağlantıyı oluşturmak için href özniteliği kullanılır. İşte bir örnek kullanım:

~~~ HTML
<a href="https://www.example.com">Örnek Web Sitesi</a>
~~~

Bu örnekte, "Örnek Web Sitesi" metni bir bağlantı olarak görüntülenecek ve kullanıcı tıkladığında **href** özniteliğinde belirtilen URL'ye yönlendirilecektir.

**a** etiketinin bazı özellikleri şunlardır:

* Kullanıcıyı başka bir sayfaya veya kaynağa yönlendirmek için kullanılır.
* href özniteliği, hedef URL'yi belirtir.
* Tarayıcılar, genellikle bağlantıları mavi renkte ve altı çizili olarak gösterir.
* target özniteliğiyle bağlantının nasıl açılacağı (aynı pencere, yeni pencere, vb.) belirtilebilir.

Aşağıda, **a** etiketinin nasıl kullanılabileceğine dair bazı örnekler bulunmaktadır:

~~~ HTML
<a href="https://www.example.com">Örnek Web Sitesi</a>
~~~

~~~ HTML
<a href="page.html">Diğer Sayfa</a>
~~~

~~~ HTML
<a href="#section">Sayfanın Bir Bölümüne Git</a>
~~~

~~~ HTML
<a href="https://www.example.com" target="_blank">Yeni Sekmede Aç</a>
~~~

## Notlar

* **a** etiketi, içeriğini tıklanabilir bir bağlantı olarak kullanır. Dolayısıyla, yalnızca metin değil, içinde herhangi bir HTML öğesi de kullanılabilir.
* **a** etiketi aynı zamanda, "**name**" veya "**id**" öznitelikleriyle hedeflenen bölümlere de bağlantı oluşturmak için kullanılabilir.