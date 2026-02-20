☕ Starbucks Satış ve Operasyon Analizi Dashboard
Bu proje, bir kahve zincirinin (Starbucks konseptli) ham satış verilerini kullanarak operasyonel verimliliği, satış trendlerini ve müşteri tercihlerini analiz etmek amacıyla geliştirilmiştir.

Veri Kaynağı: Kaggle - Coffee Shop Sales Dataset

Kapsam: İşlem tarihleri, ürün kategorileri (Beverage, Food, Merch), mağaza lokasyonları ve satış miktarları.

✨ Temel Analizler ve Özellikler
📈 Satış Performansı: Aylık ve günlük bazda ciro trendleri ve hedeflerin takibi.

⏰ Yoğun Saat Analizi (Peak Hours): Günün hangi saatlerinde mağaza trafiğinin arttığının saptanması (Personel planlaması için kritik içgörü).

🥐 Ürün Miksi: Kahve (Beverage) ve yan ürün (Food/Merch) satışlarının korelasyonu.

📍 Mağaza Bazlı Kıyaslama: Farklı lokasyonların satış hacmi ve ortalama sipariş tutarı (AOV) bazında karşılaştırılması.


🛠 Teknik Detaylar
Veri Temizleme (ETL): Power Query kullanılarak tarih formatları düzenlendi ve "Date Table" oluşturuldu.

Veri Modelleme: Verimli bir raporlama için Star Schema mimarisi uygulandı.

DAX Ölçüleri: - Total Sales, Total Transactions, Average Order Value (AOV)

Month-over-Month (MoM) Growth (Önceki aya göre büyüme oranları)
