# Gelişmiş Teknik Analiz İndikatörü

## Genel Bakış
Bu indikatör, teknik analiz ve yapı kırılımları (BOS/CHoCH), destek-direnç seviyeleri, trend olasılık hesaplamaları ve çeşitli bölge tanımlamaları gibi birçok özelliki bir arada sunan kapsamlı bir araçtır.

## Nasıl Kullanılır

### Kurulum
1. TradingView'da gösterge ekle (Add Indicator) butonuna tıklayın
2. "scriptim.pine" dosyasını içe aktarın veya kopyalayıp yeni bir Pine Script editörüne yapıştırın
3. Göstergeyi grafiğinize eklemek için "Add to Chart" butonuna tıklayın

### Temel Özellikler

#### 1. Trend Olasılık Gösterimi
- Mumun sağında trend yönü ve olasılık yüzdesi görüntülenir
- Yükseliş ve düşüş olasılıkları yüzde (%) olarak gösterilir
- Olasılık değeri ne kadar yüksekse trend o kadar güçlüdür

#### 2. Destek ve Direnç Seviyeleri
- Hesaplanan destek ve direnç seviyeleri grafik üzerinde çizgiler ve etiketler ile gösterilir
- Bu seviyeler ATR değeri ve trend olasılıklarına göre dinamik olarak hesaplanır

#### 3. Premium/Discount/Denge Bölgeleri
- Premium Bölge: Fiyatın yüksek olduğu, satış fırsatlarının oluşabileceği bölge
- İndirim Bölgesi: Fiyatın düşük olduğu, alım fırsatlarının oluşabileceği bölge
- Denge Bölgesi: Fiyatın orta seviyede olduğu bölge

#### 4. Yapı Kırılımları ve Karakter Değişimleri
- BOS (Yapı Kırılımı): Fiyatın önceki yüksek/düşükleri kırarak yeni bir yön belirlediğini gösterir
- CHoCH (Karakter Değişimi): Fiyatın davranışında önemli bir dönüşüm olduğunu gösterir

## Alım Satım İpuçları

### Trade Yaparken Dikkat Edilmesi Gerekenler

1. **Trend Yönünde İşlem Yapın**
   - %65 ve üzeri olasılıklar güçlü trend sinyali verir
   - %80 ve üzeri olasılıklar çok güçlü trend sinyali verir
   - Trend yönünde işlemler açmak her zaman daha avantajlıdır

2. **Destek ve Direnç Seviyelerini Kullanın**
   - Direnç seviyelerine yaklaşıldığında kâr alma veya pozisyon küçültme düşünülebilir
   - Destek seviyelerinde alım fırsatları değerlendirilebilir
   - Bu seviyeler stop-loss ve take-profit belirlemede rehber olabilir

3. **Bölgeleri Doğru Yorumlayın**
   - Premium Bölge: Satış fırsatları için takip edin
   - İndirim Bölgesi: Alım fırsatları için takip edin
   - Bu bölgeler tek başına alım-satım sinyali değildir, diğer göstergelerle birlikte kullanın

4. **Yapı Kırılımları ve Karakter Değişimleri**
   - Yapı kırılımları (BOS) yeni trend başlangıcını gösterebilir
   - Karakter değişimleri (CHoCH) trendin güçlendiğini gösterir
   - Bu sinyaller oluştuğunda alarmlar kurarak fırsatları kaçırmayın

5. **Zaman Dilimlerini Doğru Kullanın**
   - Günlük (D), Haftalık (W) ve Aylık (M) zaman dilimlerindeki destek-direnç seviyeleri daha güçlüdür
   - Kısa vadeli işlemlerde bile büyük zaman dilimlerindeki seviyelere dikkat edin

## Önemli Not
Bu gösterge, finansal tavsiye niteliği taşımaz. Her zaman kendi analiz ve risk yönetimi stratejinizi geliştirin. Gösterge, teknik analiz sürecinizi desteklemek için tasarlanmış bir araçtır.

## İpucu
* Başarılı trade'ler için sadece bir göstergeye bağlı kalmayın
* Risk yönetimi her zaman öncelikli olmalıdır
* Göstergeyi kendi stratejinize göre uyarlamaktan çekinmeyin
