Titanic Veri Seti Analizi
Bu çalışmada, Titanic veri seti üzerinde veri ön işleme ve analiz işlemleri gerçekleştirilmiştir. Veri seti, yolcu bilgilerini içerdiğinden eksik verilerin doldurulması, aykırı değerlerin kontrolü ve kategorik değişkenlerin işlenmesi gibi temel veri ön işleme adımları titizlikle uygulanmıştır.

Çalışmada Yer Alan Adımlar
1. Veri Keşfi (Exploratory Data Analysis - EDA)
Veri setinin genel yapısı incelendi.
Eksik veri analizi yapılarak eksik değerlerin doldurulması için uygun stratejiler belirlendi.
Hedef değişken olan "Survived" ile diğer değişkenler arasındaki ilişkiler analiz edildi.
2. Veri Ön İşleme
Eksik değerler, ortalama/mode gibi yöntemlerle veya belirli mantık çerçevesinde dolduruldu.
Aykırı değerlerin tespiti için görselleştirme ve istatistiksel yöntemler kullanıldı.
Kategorik değişkenler, One-Hot Encoding ve Label Encoding gibi yöntemlerle modellenmeye uygun hale getirildi.
Sürekli değişkenler standardize edildi veya ölçeklendirildi.
3. Analiz ve Görselleştirme
Veri dağılımları görselleştirildi ve anlamlı istatistiksel bulgular raporlandı.
Yaş, cinsiyet, bilet sınıfı gibi değişkenlerin, hayatta kalma oranı üzerindeki etkileri incelendi.
Görselleştirmelerde matplotlib ve seaborn kütüphaneleri kullanıldı.
Çıktılar ve Sonuçlar
Yapılan analizler sonucunda, Titanic kazasında hayatta kalmayı etkileyen temel faktörler tespit edilmiştir. Örneğin:

Kadınların hayatta kalma oranı, erkeklere göre belirgin şekilde daha yüksek çıkmıştır.
Birinci sınıf yolcuların hayatta kalma oranı diğer sınıflara kıyasla daha yüksektir.
Çocuk yolcuların hayatta kalma şansı, yetişkinlere göre daha fazladır.
Kullanılan Araçlar ve Teknolojiler
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Bu analiz, hem veri bilimi öğrenimine katkı sağlamak hem de Titanic veri seti üzerinde yapılan çalışmalara bir örnek teşkil etmek amacıyla gerçekleştirilmiştir. Daha fazla detaya GitHub üzerindeki kod ve dokümantasyondan ulaşabilirsiniz.
