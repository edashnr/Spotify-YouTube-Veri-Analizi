# SPOTIFY vs YOUTUBE Veri Analizi
Spotify &amp; YouTube Keşifsel Veri Analizi ve Sınıflama Modeli


Bu proje, Spotify ve YouTube platformlarına ait verileri analiz ederek bu platformlar arasındaki farkları ve benzerlikleri incelemeyi amaçlamaktadır. Python kullanılarak yapılan veri analizi ve görselleştirme çalışmalarıyla çeşitli içgörüler elde edilmiştir.

## Kullanılan Veri Seti

Spotify ve YouTube'dan alınan veriler, şarkıların ve videoların özelliklerini karşılaştırmaktadır. Veri setine aşağıdaki bağlantıdan ulaşabilirsiniz:

- **Veri Seti:** [Kaggle]([https://www.kaggle.com](https://www.kaggle.com/datasets/salvatorerastelli/spotify-and-youtube))

### Değişkenler

- **Title:** Şarkı veya video adı.
- **Artist/Channel:** Şarkıcı adı veya video kanalı.
- **Popularity:** Şarkı/video popülerlik puanı.
- **Duration:** Şarkı/video süresi.
- **Release Date:** Yayın tarihi.
- **Views:** İzlenme sayısı (YouTube için).
- **Streams:** Dinlenme sayısı (Spotify için).

## Temel Bulgular ve İşlemler

1. Veri seti toplamda **X sütun** ve **Y kayıt** içermektedir.
2. **Spotify** ve **YouTube** platformları için veriler arasında belirgin farklılıklar gözlenmiştir:
   - Spotify'da en popüler şarkılar genellikle 3-4 dakika uzunluğunda iken, YouTube'da en çok izlenen videolar daha geniş bir süre aralığına sahiptir.
   - YouTube videoları genel olarak daha fazla izlenme sayısına sahiptir, ancak Spotify dinlenme oranları, video izlenme oranlarından daha kararlı bir dağılım göstermektedir.
3. Eksik veriler kontrol edilmiş ve gerekirse uygun yöntemlerle doldurulmuştur.
4. Spotify ve YouTube'daki en popüler şarkı ve videolar karşılaştırılmıştır.
5. Görselleştirme sonuçları, platformlar arasındaki kullanıcı davranışlarındaki farkları ortaya koymuştur.

## Kullanılan Teknolojiler

- **Python 3.10**
- **Jupyter Notebook**
- **Kütüphaneler:**
  - Pandas: Veri işleme.
  - NumPy: Sayısal hesaplama.
  - Matplotlib & Seaborn: Veri görselleştirme.

## Nasıl Çalıştırılır?

1. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Jupyter Notebook'u çalıştırın:
   ```bash
   jupyter notebook spotify-vs-youtube.ipynb
   ```
3. Hücreleri sırayla çalıştırarak analiz sürecini takip edin.
   
## Öne Çıkan Analizler

- Spotify'daki en uzun ve en kısa süreli şarkılar.
- YouTube'daki en çok ve en az izlenen videolar.
- Her iki platformda da popülerlik puanlarının dağılımı.
- Platformlar arasındaki içerik sürelerinin karşılaştırılması.

## Öneriler

- Veri setinin daha fazla özellik eklenerek genişletilmesi, modelin doğruluğunu artırabilir.
- Popülerlik ve diğer metrikler arasında güçlü bir korelasyon bulunmamıştır, ancak kullanıcı davranışlarını anlamak için daha fazla veri analizi yapılabilir.

## Uyarılar

- Model ve analiz sonuçları, kullanılan veri setine ve işleme tekniklerine bağlıdır. Yeni verilerle sonuçlar değişebilir.
- Her analiz çalıştırıldığında küçük farklar gözlenebilir, çünkü bazı işlemler rastgelelik içerebilir.
