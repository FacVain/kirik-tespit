# Kırık Tespit Projesi
Bil468 Dönem Projesi Grup No:3
Furkan Taşdemir
Mehmet Safa Öztürkoğlu

Project Report: [Bone Fracture Diagnosis.pdf](https://github.com/user-attachments/files/18656786/Bone.Fracture.Diagnosis.pdf)


Dijital radyografi, kemik kırıklarının teşhisi için en yaygın ve uygun maliyetli standartlardan biridir. 
Radyografi görüntüleri kullanılarak yapılacak kemik kırığı teşhisi süreci ise zaman alan ve görüntülerdeki çeşitli kusurlar sebebiyle hatalı tanıya imkân veren bir yapıdadır. Bilgisayarla görme algoritmalarının da gelişmesiyle birlikte, kemik kırığı tanı sürecini doktorlar için kolaylaştırmak adına radyografi görüntülerinden kemik kırığı sınıflandırması yapan bir sistem geliştirmekteyiz.

## Yöntem 1: 
method-2 altında implement edilmiştir. process-featureext klasörü altında iki ayrı veri seti için ayrı klasörlerde öznitelik çıkarım işlemleri yapılmakta. Classification klasörü altında iki ayrı veri seti için ayrı klasörlerde modellerin eğitim ve test scriptleri bulunmakta. 

## Yöntem 2: 
SIFT-BoW altında implement edilmiştir. SIFTextraction klasörü altında iki ayrı veri seti için SIFT öznitelik çıkarımı yapılmakta ve Bag of Word histogramları oluşturulmakta. Classification klasörü altında iki ayrı veri seti için modellerin eğitim ve test scriptleri bulunmakta. 

## Yöntem 3: 
glcmMethod altında implement edilmiştir. imageProcessing ve featureExtrction scriptleri altında önişleme ve öznitelik çıkarımı işlemleri yapılmakta. clasification scriptinde fracatlas veri seti için sınıflandırma ve test işlemleri, clasificationFibula scripti altında tibia ve fibula veriseti için  sınıflandırma ve test işlemleri yapılmakta.

## Yöntem 4: 
method-3 altında implement edilmiştir. Test scriptlerinin çalışması için fracatlas klasörü içine https://drive.google.com/drive/folders/19CExgdC9uaHp5WE6owGQUJTHwYVQfm1p?usp=drive_link linkinde bulunan klasörler ve h5 dosyaso kopyalanmalıdır. Github boyut limiti sebebiyle CNN modelleri drive'a yüklenmiştir.

Fracatlas klasörünün yapısı aşağıdaki gibi olmalıdır.

![image](https://github.com/FacVain/kirik-tespit/assets/78103291/60bdbb9d-2b03-49f1-aae2-bcf06d16d550)

Bu klasör içinde belirtilen modeller için eğitim ve test scriptleri bulunmaktadır.
