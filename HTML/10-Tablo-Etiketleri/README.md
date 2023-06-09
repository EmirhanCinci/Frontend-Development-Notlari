# 10. Ders - Tablo Etiketleri

HTML tablo etiketleri, verileri tablo formatında düzenlemek ve görsel olarak sunmak için kullanılır. Tablolar, satırlardan ve sütunlardan oluşur. HTML'de kullanılan temel tablo etiketleri şunlardır:

* **`<table>`**: Tabloyu tanımlar.
* **`<tr>`**: Tablo satırını tanımlar.
* **`<td>`**: Tablo hücresini tanımlar.
* **`<th>`**: Başlık hücresini tanımlar.

## Tablo Oluşturma

Bir tablo oluşturmak için **`<table>`** etiketi kullanılır. Tablonun içindeki verileri **`<tr>`** etiketi ile satırlara ve **`<td>`** etiketi ile hücrelere yerleştiririz. İşte bir örnek:

~~~ HTML
<table>
  <tr>
    <td>Hücre 1</td>
    <td>Hücre 2</td>
    <td>Hücre 3</td>
  </tr>
  <tr>
    <td>Hücre 4</td>
    <td>Hücre 5</td>
    <td>Hücre 6</td>
  </tr>
</table>
~~~

Bu kod, aşağıdaki gibi görünen bir tablo oluşturur:

| Hücre 1 | Hücre 2 | Hücre 3 |
| ----------- | ----------- | ----------- |
| Hücre 4 | Hücre 5 | Hücre 6 |