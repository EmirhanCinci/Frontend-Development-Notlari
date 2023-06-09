# 04. Ders - Margin ve Padding Özellikleri

**`margin`** ve **`padding`** özellikleri, HTML öğelerinin dış boşluklarını ve iç boşluklarını kontrol etmek için kullanılır. Bu özellikler, öğelerin birbirlerinden uzaklığını ve içerikleriyle aralarındaki boşluğu ayarlamak için kullanışlıdır. margin ve padding özellikleri, sayfa düzenini oluştururken ve öğeler arasındaki mesafeyi ayarlarken önemli bir rol oynar.

## **`margin`**

**`margin`** özelliği, öğelerin dış boşluklarını belirlemek için kullanılır. Bu özelliğe bir veya dört değer atanabilir. Değerler, öğenin dört kenarına (üst, sağ, alt, sol) sırasıyla uygulanır. Örnek kullanım:

~~~ CSS
div {
  margin: 10px;
}
~~~

Bu örnekte, **div** etiketlerinin dört kenarı da 10 piksel dış boşlukla çevrelenmiş olacaktır.

## **`padding`**

**`padding`** özelliği, öğelerin iç boşluklarını belirlemek için kullanılır. Bu özelliğe bir veya dört değer atanabilir. Değerler, öğenin dört kenarına (üst, sağ, alt, sol) sırasıyla uygulanır. Örnek kullanım:

~~~ CSS
div {
  padding: 20px;
}
~~~

Bu örnekte, **div** öğesinin içeriğinin etrafında 20 piksel iç boşluk olacaktır.

## **`margin`** ve **`padding`** Özellikleriyle İlgili Özel Durumlar

* Eğer dört değer kullanıyorsanız (örneğin **`margin: 10px 20px 10px 20px;`**), değerler sırasıyla üst, sağ, alt ve sol kenarlar için geçerlidir.

* Eğer üç değer kullanıyorsanız (örneğin **`margin: 10px 20px 30px;`**), değerler sırasıyla üst, sağ-sol ve alt kenarlar için geçerlidir.

* Eğer iki değer kullanıyorsanız (örneğin **`margin: 10px 20px;`**), değerler sırasıyla üst-alt ve sağ-sol kenarlar için geçerlidir.