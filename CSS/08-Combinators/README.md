# 08. Ders - Combinators Özellikleri

Kombinatörler, HTML öğelerini seçmek için kullanılan özel seçici notasyonlardır. Kombinatörler, öğelerin hiyerarşik ilişkilerini, konumlarını veya durumlarını temel alarak öğeleri seçmek için kullanılır. Bu, daha spesifik ve hedeflenmiş seçiciler oluşturmayı sağlar.

CSS'de yaygın olarak kullanılan kombinatörler şunlardır:

## 1. Boşluk (Whitespace) Kombinatörü (Descendant Combinator)

Boşluk kombinatörü, bir öğenin içinde yer alan diğer öğeleri seçmek için kullanılır. Yani, bir öğenin altındaki tüm alt öğeleri hedeflemek için kullanılır.

~~~ CSS
div p {
  /* div öğesi içindeki tüm p öğelerini seçer */
}
~~~

Yukarıdaki örnekte, div öğesi içinde yer alan tüm p öğeleri seçilir.

## 2. > Kombinatörü (Child Combinator)

**`>`** kombinatörü, bir öğenin doğrudan alt öğelerini seçmek için kullanılır. Yani, bir öğenin birinci seviye alt öğelerini hedeflemek için kullanılır.

~~~ CSS
div > p {
  /* div öğesinin doğrudan altındaki p öğelerini seçer */
}
~~~

Yukarıdaki örnekte, div öğesinin doğrudan altındaki p öğeleri seçilir.

## 3. + Kombinatörü (Adjacent Sibling Combinator)

**`+`** kombinatörü, bir öğeden hemen sonraki kardeş öğeyi seçmek için kullanılır. Yani, bir öğeden sonraki öğeyi hedeflemek için kullanılır.

~~~ CSS
h2 + p {
  /* h2 öğesinden hemen sonra gelen p öğesini seçer */
}
~~~

Yukarıdaki örnekte, h2 öğesinden hemen sonra gelen p öğesi seçilir.

## 4. ~ Kombinatörü (General Sibling Combinator)

**`~`** kombinatörü, bir öğeden sonraki tüm kardeş öğeleri seçmek için kullanılır. Yani, bir öğeden sonraki tüm öğeleri hedeflemek için kullanılır.

~~~ CSS
h2 ~ p {
  /* h2 öğesinden sonraki tüm p öğelerini seçer */
}
~~~

Yukarıdaki örnekte, h2 öğesinden sonraki tüm p öğeleri seçilir.