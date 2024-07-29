# Futbol Takımları Performans Analizi ve Görselleştirme

Bu projede, futbol takımlarının performansını analiz etmek ve görselleştirmek amacıyla çeşitli makine öğrenmesi teknikleri kullanılmıştır. Özellikle Türkiye'nin gol atma ve gol yeme performansı, diğer ülkelerle karşılaştırılarak değerlendirilecektir. Proje, performans analizi, görselleştirme ve performans iyileştirme önerileri sunmaktadır.

## İçindekiler

- [Proje Açıklaması ve Adımlar](#proje-açıklaması-ve-adımlar)
- [Kullanılan Kütüphaneler](#kullanılan-kütüphaneler)
- [Veri Seti](#veri-seti)
- [Kurulum ve Çalıştırma](#kurulum-ve-çalıştırma)
- [Sonuçlar](#sonuçlar)
- [Performans İyileştirme Önerileri](#performans-iyileştirme-önerileri)
- [Yazar](#yazar)
- [Lisans](#lisans)

## Proje Açıklaması ve Adımlar

Bu proje futbol takımlarının performansını analiz etmek için aşağıdaki adımları içermektedir:

1. **Veri Hazırlığı**
   - Veri Yükleme: Performans verilerini içeren veri kümesi yüklenir.
   - Veri Temizleme: Eksik veya hatalı veriler temizlenir ve gerekli ön işlemler yapılır.

2. **Performans Analizi**
   - Ortalama Hesaplama: Türkiye'nin ve tüm ülkelerin ortalama gol atma ve gol yeme verileri hesaplanır.
   - Performans Karşılaştırması: Türkiye'nin performansı ortalama değerlerle karşılaştırılarak değerlendirilir.

3. **Görselleştirme**
   - Bar Grafiği: Türkiye'nin gol atma ve gol yeme performansı, tüm ülkelerin ortalaması ile kıyaslanarak bar grafiği şeklinde gösterilecektir.

4. **Performans İyileştirme Önerileri**
   - Gol Atma Stratejileri: Türkiye'nin gol atma stratejilerinin gözden geçirilmesi ve hücum gücünün artırılması önerilecektir.
   - Savunma Stratejileri: Türkiye'nin savunma stratejilerinin iyileştirilmesi ve defans oyuncularının performansının artırılması önerilecektir.

5. **Sonuçların Sunumu**
   - Sonuçlar, grafikler ve önerilerle birlikte sunulacaktır. Performans değerlendirmeleri ve iyileştirme önerileri, ilgili görselleştirmelerle desteklenerek açıklanacaktır.

## Kullanılan Kütüphaneler

- `pandas` - Veri işleme ve analiz için
- `numpy` - Sayısal hesaplamalar için
- `matplotlib` - Veri görselleştirme için
- `seaborn` - İleri düzey görselleştirme için
- `scikit-learn` - Makine öğrenmesi modelleri için

## Veri Seti

Veri seti, futbol takımlarının performans metriklerini içermektedir ve aşağıdaki sütunları içermektedir:

- `Team`: Takım adı
- `Matches Played`: Oynanan maç sayısı
- `Won`: Kazanılan maç sayısı
- `Drawn`: Beraberlik sayısı
- `Lost`: Kaybedilen maç sayısı
- `Total Goals`: Toplam gol sayısı
- `Right Foot Goals`: Sağ ayakla atılan goller
- `Left Foot Goals`: Sol ayakla atılan goller
- `Head Goals`: Başla atılan goller
- `Other Goals`: Diğer tür goller
- `Goals Inside Area`: Ceza sahasında atılan goller
- `Goals Outside Area`: Ceza sahası dışında atılan goller
- `Penalties Scored`: Penaltı golleri

## Gerekli kütüphaneleri yükleyin:

pip install pandas numpy matplotlib seaborn scikit-learn

##  Jupyter Notebook veya Python dosyasını çalıştırın:

jupyter notebook

## Sonuçlar
Proje sonuçları, Türkiye'nin gol atma ve gol yeme performansını diğer ülkelerle kıyaslamaktadır. Türkiye'nin performansını görselleştiren bar grafikler ve performans iyileştirme önerileri sunulmuştur.

## Performans İyileştirme Önerileri
Gol Atma Stratejileri: Türkiye'nin gol atma stratejilerinin gözden geçirilmesi ve hücum gücünün artırılması önerilmektedir.
Savunma Stratejileri: Türkiye'nin savunma stratejilerinin iyileştirilmesi ve defans oyuncularının performansının artırılması önerilmektedir.
## Yazar
Enke-bit (İbrahim Püsküllü) - GitHub Profiliniz
## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.



