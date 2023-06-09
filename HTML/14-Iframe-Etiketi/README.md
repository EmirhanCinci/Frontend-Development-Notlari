# 14. Ders - Iframe Etiketi

**`<iframe>`** etiketi, başka bir HTML belgesini veya dışarıdan bir içeriği (örneğin, bir web sitesi veya video) içe aktarmak ve mevcut belgeye eklemek için kullanılır. **`<iframe>`** etiketi, içeriklerin farklı kaynaklardan (farklı alan adları, farklı sunucular) alınmasını sağlar.

## **`<iframe>`** Etiketi Kullanımı
**`<iframe>`** etiketi, src özelliği ile içe aktarılacak içeriğin kaynağını belirtir. Ayrıca, width ve height özellikleri ile **`<iframe>`**'in genişliğini ve yüksekliğini belirleyebilirsiniz.

Örnek bir **`<iframe>`** kullanımı:

~~~ HTML
<iframe src="https://www.example.com" width="500" height="300"></iframe>
~~~

Bu örnekte, src özelliği https://www.example.com olarak belirtilmiş ve **`<iframe>`** ile bu web sitesi içe aktarılmıştır. **`<iframe>`**'in genişliği 500 piksel ve yüksekliği 300 piksel olarak belirtilmiştir.