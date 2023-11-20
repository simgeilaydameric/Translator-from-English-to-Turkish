# CSV Türkçe Çevirici

Bu Python script'i, verilen bir CSV dosyasındaki İngilizce metinleri Türkçe'ye çevirir ve çevirilen metinleri içeren yeni bir CSV dosyası oluşturur. 

## Kullanım

1. `pandas` ve `googletrans==3.1.0a0` kütüphanelerini yükleyin: `pip install pandas googletrans==3.1.0a0`
2. "ornek.csv" adlı CSV dosyanızı hazırlayın ve kodu çalıştırarak Türkçe çevirisini alın.
3. Çevrilen veriyi "Turkce.csv" adlı yeni bir CSV dosyasında kaydedin.
4. Yeni yazılan csv dosyasında şu şekilde görünecektir:
  ![CSV İlk Görüntü](https://github.com/simgeilaydameric/Translator-from-English-to-Turkish/blob/main/csv_ilk%20_goruntu.png)
5. csv dosyasındaki tüm veriyi CTRL+A ile kopyalayın.
6. Kopyaladığınız veriyi not defterine yapıştırın. Not defterinde farklı kaydete tıklayın ve ANSI formatını seçin. Yazılar düzelmiş olacaktır.
  ![Not Defteri Görüntüsü](https://github.com/simgeilaydameric/Translator-from-English-to-Turkish/blob/main/not_defteri.png)

## Açıklama

- İngilizce sütun isimleri düzenlenir ve "_" karakterleri boşlukla değiştirilir.
- `googletrans` kütüphanesi kullanılarak her bir sütunun adı Türkçe'ye çevrilir.
- Veri çerçevesindeki metinler Türkçe'ye çevrilir ve yeni bir CSV dosyasına kaydedilir.

Bu script, metin verilerini Türkçe'ye çevirmek isteyenler için kullanışlı bir araçtır.
