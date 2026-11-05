# Veri Kartı (Data Card)

* **Kaynak:** Kaggle Hava Kalitesi ve PM2.5 Veri Setleri / Open-Meteo[cite: 41]
* **Lisans:** Açık Erişim / Creative Commons
* **İndirme Tarihi:** Kasım 2026
* **Boyut / Yapı:** 500+ ölçüm satırı, 200+ puan kaydı, 4 sayısal sütun, 1 zaman sütunu[cite: 7, 41].

## Beklenen Veri Sorunları ve Temizleme Adımları
1. **Uç Değerler:** PM2.5 ölçümlerinde negatif veya mantık dışı çok büyük değerler bulunabilir. Bu değerler sensör hatası olabileceğinden silinmemiş, ham veride (`data/raw/`) olduğu gibi bırakılmış, ancak veri kartında not edilmiştir[cite: 42].
2. **Eksik Puanlar:** Bazı uyarıların vatandaşlar tarafından puanlanmadığı (NULL) tespit edilmiştir. Bu durum analizlerde ayrıca ele alınacaktır[cite: 42].
3. **Zaman Uyuşmazlığı:** Ölçüm zamanı ile uyarı gönderim zamanı arasındaki farklar göz önünde bulundurulmuştur.
