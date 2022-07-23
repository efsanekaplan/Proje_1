# Global-AI-Hub-Project-1

## Proje Hakkında
 Kullanıcı tarafından verilen öğrencilerin ders notlarını hesaplayan ve sonuçları pandas yardımıyla excel tablosu oluşturan uygulama.
 
## Projede istenenler

Bu projede bir öğrenci not sistemi oluşturacaksınız. Sizden istenilenler:
Kendinize bir ders belirleyiniz. (Matematik,Fizik, Lineer Cebir vb.) Not aralığınızı oluşturunuz (100-80 ⇒ A, 79-70 ⇒ B vb.) Öğrenci Bilgilerini (Ad, Soyad, Okul No, sınav puanı) girebileceğiniz ve bu bilgilerin tutulabileceği bir sistem oluşturunuz. Girilen bilgilerden yola çıkarak öğrencinin dersi geçip geçmediğini göstermesi gerekmektedir. Öğrenci dersi geçti ise öğrencinin bilgilerinin tutulduğu alana “Geçti” yazısı, öğrenci dersi geçemedi ise “kaldı” yazısını göstermesi gerekmektedir. Notları girilen öğrencilerden dersi geçenleri ve geçmeyenleri gösteren bir Dataframe oluşturunuz. Oluşturulan Dataframe’i Excel tablosuna dönüştürünüz.

## Proje içindeki dosyalar
* proje 1


##  Uygulamanın akışı

Kullanıcının verdiği öğrenci listesini okur.

![image](https://user-images.githubusercontent.com/93267352/180608636-b21d98ed-d3c9-4bdb-8fe7-17da981cbf02.png)

Grade_file (yazılacak txt) dosyası oluşturulur.

![image](https://user-images.githubusercontent.com/93267352/180608666-8803b7e7-a8b7-4df5-90b4-6ada03a8d037.png)

for döngüsü içinde compute_grade ile notlar belirlendi ve Grade_file a kaydedildi.

![image](https://user-images.githubusercontent.com/93267352/180609170-637db6c2-6ec8-4980-9d1e-c1d841a99467.png)


Pandas yardımıyla oluşturalacak excel dosyası için Sütun değerli listesi girilir.
![image](https://user-images.githubusercontent.com/93267352/180609186-2b41b07b-dbd7-41a4-b6fc-52e8fafa7bfa.png)


