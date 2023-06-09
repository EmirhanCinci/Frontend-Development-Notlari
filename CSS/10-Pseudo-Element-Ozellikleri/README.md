# 10. Ders - Pseudo Element Özellikleri

Pseudo element'ler, HTML öğelerinin belirli parçalarını seçmek ve bu parçalara stil uygulamak için kullanılan seçici notasyonlardır. Pseudo element'ler, öğelerin içerikleri veya konumlarına dayalı olarak stil uygulamak için kullanılır. Bu sayede, öğelerin belirli parçalarını daha ayrıntılı şekilde tasarlamak mümkün hale gelir.

CSS'de yaygın olarak kullanılan pseudo element'ler şunlardır:

## 1. **`::before`** Pseudo Element'i

**`::before`** pseudo element'i, bir öğenin içeriğinin önüne eklenen bir içerik parçasını seçmek için kullanılır. Bu içerik parçası, CSS ile oluşturulan ve öğenin içeriğinden önce yerleştirilen bir öğedir.

~~~ CSS
p::before {
  /* Bir p öğesinin içeriğinin önüne eklenen stil uygulanacak öğe */
  content: "Önünde yer alan içerik";
}
~~~

Yukarıdaki örnekte, bir p öğesinin içeriğinin önüne eklenen ve "Önünde yer alan içerik" metnini içeren bir öğe seçilmiştir.

## 2. **`::after`** Pseudo Element'i

**`::after`** pseudo element'i, bir öğenin içeriğinin sonuna eklenen bir içerik parçasını seçmek için kullanılır. Bu içerik parçası, CSS ile oluşturulan ve öğenin içeriğinden sonra yerleştirilen bir öğedir.

~~~ CSS
p::after {
  /* Bir p öğesinin içeriğinin sonuna eklenen stil uygulanacak öğe */
  content: "Sonuna eklenen içerik";
}
~~~

Yukarıdaki örnekte, bir p öğesinin içeriğinin sonuna eklenen ve "Sonuna eklenen içerik" metnini içeren bir öğe seçilmiştir.

## 3. **`::first-line`** Pseudo Element'i

**`::first-line`** pseudo element'i, bir öğenin içeriğinin ilk satırını seçmek için kullanılır. Bu sayede, öğenin ilk satırına özel stil uygulamak mümkün hale gelir.

~~~ CSS
p::first-line {
  /* Bir p öğesinin ilk satırına uygulanacak stil kuralları */
  font-weight: bold;
  text-transform: uppercase;
}
~~~

Yukarıdaki örnekte, bir p öğesinin ilk satırına kalın bir yazı tipi ve büyük harf dönüşümü uygulanmıştır.