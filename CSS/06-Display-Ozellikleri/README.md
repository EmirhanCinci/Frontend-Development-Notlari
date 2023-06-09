# 06. Ders - Display Özellikleri

**`display`** özelliği, HTML öğelerinin görüntülenme davranışını kontrol etmek için kullanılır. Bu özellik, öğelerin blok, satır veya inline gibi farklı görüntülenme tiplerine sahip olmalarını sağlar. **`display`** özelliği, sayfa düzenini ve öğelerin yerleşimini kontrol etmek için önemli bir rol oynar.

## **`display`** Özelliği Değerleri

**`display`** özelliğine atanabilecek bazı değerler şunlardır:

* **`block`**: Öğenin bir blok öğesi gibi davranmasını sağlar. Blok öğeler, kendilerinden sonraki öğeleri yeni bir satırda başlatır ve genellikle diğer blok öğeleriyle aynı satırda yer almaz.

* **`inline`**: Öğenin bir inline öğesi gibi davranmasını sağlar. Inline öğeler, kendilerinden sonraki öğelerle aynı satırda yer alır ve içerdikleri içeriğin boyutunu otomatik olarak ayarlar.

* **`inline-block`**: Öğenin hem inline hem de blok öğesi gibi davranmasını sağlar. Inline-block öğeler, kendilerinden sonraki öğelerle aynı satırda yer alır ancak içerdikleri içeriğin boyutunu belirleyebilirler.

* **`none`**: Öğenin hiç görüntülenmemesini sağlar. Öğe yerine boşluk bırakılır ve diğer öğeler bu boşluğu doldurur.

## Örnek Kullanım

~~~ CSS
div {
  display: block;
}
~~~

Yukarıdaki örnekte, **div** etiketlerinin bir blok öğesi olarak görüntülenecektir. Bu, öğenin kendinden sonraki öğeleri yeni bir satırda başlatması anlamına gelir.

~~~ CSS
span {
  display: inline;
}
~~~

Bu örnekte, **span** etiketlerinin bir inline öğesi olarak görüntülenecektir. Bu, öğenin kendinden sonraki öğelerle aynı satırda yer alması anlamına gelir.