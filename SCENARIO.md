# Proje Senaryosu ve Planı (Kura #30)

## Hikâye
Bir belediye şehirdeki hava kalitesi sensörlerinden gelen veriyi vatandaşlara uyarı olarak sunuyor. Vatandaşlar uyarıların ne kadar yerinde olduğunu puanlıyor. Belediye, sensör uyarısının sınır değerle mi, yoksa örüntüyle mi ilişkili olduğunu öğrenmek istiyor[cite: 41].

## Ana Soru
Vatandaşların "accurate" dediği uyarılar hangi sensör değeri aralığında yoğunlaşıyor?[cite: 41]

## Hedef Kullanıcı
Belediye karar vericileri, çevre kontrol mühendisleri ve şehir sakinleri.

## YZ Bileşeni ve Dönem Sonu Hedefi
Sistem uyarısının doğruluğunu ve vatandaş geri bildirim puanlarını eşleştirerek eşik değerlerinin optimize edilmesi. Dönem sonunda bu akış bir değerlendirme yapısı ile izlenecektir[cite: 42].

## Veri Kaynağı Adayları
* Kaggle "air quality", "PM2.5", "sensor" veri setleri[cite: 41].
* Open-Meteo saatlik rüzgâr ve hava verileri[cite: 41].
* Vatandaş geri bildirimleri için açık lisanslı anket veya derecelendirme verileri[cite: 41].
* *Asgari Gereksinim:* En az 500 ölçüm ve 200 puan kaydı[cite: 41].

## Tablo Adayları
1. **sensors** (id, region, type)[cite: 41]
2. **measurements** (id, sensor_id, pm25, measured_at)[cite: 41]
3. **alerts** (id, measurement_id, alert_type, sent_at)[cite: 41]
4. **ratings** (id, alert_id, accuracy_1_5)[cite: 41]
