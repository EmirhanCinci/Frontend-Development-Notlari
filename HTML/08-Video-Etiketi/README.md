# 08. Ders - Video Etiketi

HTML **`<video>`** etiketi, web sayfalarında video içeriğini görüntülemek için kullanılır. Bu etiket, videoyu tarayıcıda oynatırken kullanılacak video dosyasını belirtir. **`<video>`** etiketi, aşağıdaki gibi kullanılır:
`
~~~ HTML
<video src="video.mp4" controls></video>
~~~

* "**src**" özelliği, oynatılacak video dosyasının URL'sini veya yerel dosya yolunu belirtir.
* "**controls**" özelliği, tarayıcıda video oynatıcının kontrol düğmelerini görüntüler.

## Video Etiketi Kullanım Örnekleri

1. En basit haliyle, videoyu oynatmak için sadece "**src**" özelliği kullanılır:

~~~ HTML
<video src="video.mp4"></video>s
~~~

2. Kontrol düğmelerini görüntülemek için "**controls**" özelliği eklenir:

~~~ HTML
<video src="video.mp4" controls></video>
~~~ 

3. Sayfa yüklendiğinde video otomatik olarak başlaması için "**autoplay**" özelliği eklenir:

~~~ HTML
<video src="video.mp4" controls autoplay></video>
~~~ 

4. Video otomatik olarak tekrarlanması için "**loop**" özelliği kullanılır:

~~~ HTML
<video src="video.mp4" controls autoplay loop></video>
~~~ 

5. Videonun sessiz olarak başlaması için "**muted**" özelliği eklenir:

~~~ HTML
<video src="video.mp4" controls autoplay loop muted></video>
~~~ 

6. Video yüklenirken görüntülenecek bir önizleme resmi belirtmek için "**poster**" özniteliği kullanılır:

~~~ HTML
<video src="video.mp4" controls autoplay loop muted poster="onizleme.jpg"></video>
~~~

7. Video oynatıcının genişlik ve yükseklik değerlerini belirtmek için "**width**" ve "**height**" özelliği eklenir.

~~~ HTML
<video src="video.mp4" width="500" controls autoplay loop muted poster="onizleme.jpg"></video>
~~~