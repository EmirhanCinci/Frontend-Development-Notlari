# 09. Ders - Pseudo Class Özellikleri

Pseudo class'lar, HTML öğelerinin belirli durumlarını veya belirli ilişkilerini seçmek için kullanılan seçici notasyonlardır. Pseudo class'lar, öğelerin durumuna veya kullanıcıyla olan etkileşimine göre stil uygulamak için kullanılır. Bu sayede, dinamik ve interaktif tasarımlar oluşturmak mümkün hale gelir.

CSS'de yaygın olarak kullanılan pseudo class'lar şunlardır:

## 1. **`:hover`** Pseudo Class'ı

**`:hover`** pseudo class'ı, bir öğenin üzerine gelindiğinde uygulanacak stilleri belirlemek için kullanılır. Kullanıcı bir öğenin üzerine geldiğinde, **`:hover`** pseudo class'ı ile tanımlanan stil kuralları uygulanır.

~~~ CSS
a:hover {
  /* Bir linkin üzerine gelindiğinde uygulanacak stil kuralları */
}
~~~

Yukarıdaki örnekte, bir linkin üzerine gelindiğinde uygulanacak stil kuralları belirtilmiştir.

## 2. **`:active`** Pseudo Class'ı

**`:active`** pseudo class'ı, bir öğe tıklandığında uygulanacak stilleri belirlemek için kullanılır. Kullanıcı bir öğeye tıkladığında, **`:active`** pseudo class'ı ile tanımlanan stil kuralları uygulanır.

~~~ CSS
button:active {
  /* Bir düğmeye tıklandığında uygulanacak stil kuralları */
}
~~~

Yukarıdaki örnekte, bir düğmeye tıklandığında uygulanacak stil kuralları belirtilmiştir.

## 3. **`:focus`** Pseudo Class'ı

**`:focus`** pseudo class'ı, bir öğenin odaklandığında uygulanacak stilleri belirlemek için kullanılır. Özellikle form öğeleri için kullanışlıdır. Kullanıcı bir öğeye odaklandığında, **`:focus`** pseudo class'ı ile tanımlanan stil kuralları uygulanır.

~~~ CSS
input:focus {
  /* Bir input öğesi odaklandığında uygulanacak stil kuralları */
}
~~~

Yukarıdaki örnekte, bir input öğesi odaklandığında uygulanacak stil kuralları belirtilmiştir.

## 4. **`:nth-child()`** Pseudo Class'ı,

**`:nth-child()`** pseudo class'ı, bir öğenin belirli bir sıradaki alt öğelerini seçmek için kullanılır. Sıralama, öğelerin konumuna göre yapılır.

~~~ CSS
ul li:nth-child(odd) {
  /* Bir ul öğesinin içindeki tek sıradaki li öğelerini seçer */
}
~~~

Yukarıdaki örnekte, bir ul öğesinin içindeki tek sıradaki li öğeleri seçilmiştir.

## 5. **`:not()`** Pseudo Class'ı

**`:not()`** pseudo class'ı, belirli bir öğe veya öğe grubunu hariç tutmak için kullanılır. Verilen bir seçiciye uyan öğeleri hariç tutar.

~~~ CSS
p:not(.highlight) {
  /* .highlight sınıfına sahip olmayan p öğelerini seçer */
}
~~~

Yukarıdaki örnekte, .highlight sınıfına sahip olmayan p öğeleri seçilmiştir.