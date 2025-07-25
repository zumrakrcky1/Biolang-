# Biolang-
Python temelli biyoinformatik dili: genetik analiz, hastalık tahmini, sağlık verisi işleme.


🧬 Biolang - Python Tabanlı Sağlık ve Genetik Odaklı Programlama Dili
📌 Tanıtım
Biolang, genetik mühendisliği, biyoinformatik ve biyomedikal analizler için özel olarak geliştirilmiş Python tabanlı bir programlama dilidir. Sağlık alanındaki bilim insanlarına ve yazılımcılara genetik veriler üzerinde analiz yapma, hastalık teşhisi koyma ve sağlık risklerini değerlendirme konularında kullanıcı dostu bir dil ve hazır fonksiyonlar sunar.

Bu proje, Python'un esnek yapısını biyoloji temelli özel fonksiyonlarla genişleterek yeni bir niş programlama dili oluşturmayı amaçlamıştır.

🚀 Özellikler
🧪 Hastalık Tahminleme ve Risk Analizi: Kalp hastalıkları, diyabet, kanser ve X-kromozomu hastalıklarına yönelik risk tahminleri.

🧬 Genetik Fonksiyonlar: DNA replikasyonu, mRNA transkripsiyonu, protein sentezi, mutasyon tespiti, fenotip tahmini.

🧠 Farmakogenetik Modül: Genotip ve ilaç etkileşimlerine göre yan etki riski değerlendirmesi.

🩸 Kan Grubu ve Rh Faktörü Tahmini: Anne-baba verisine göre çocuk olasılıklarının hesaplanması.

📂 Veri Kaydetme ve Yükleme: JSON, CSV, Excel ve SQLite veri kaynaklarıyla tam uyum.

🔍 Veri Arama ve Analiz: DNA dizilerinde motif arama, genetik desen inceleme.

📚 Kullanılan Fonksiyonlardan Örnekler
Fonksiyon	Açıklama
dna_rep(dna_seq)	DNA'nın tamamlayıcı dizisini üretir.
med_side_effect_risk(genotype, drug)	Genotip-ilaç uyumuna göre yan etki riski tahmini yapar.
glucose_level_analysis(level, state)	Açlık/tokluk durumuna göre kan şekeri analiz eder.
calculate_cf_risk(parents)	Kistik fibrozis gibi hastalıklarda taşıyıcılık ve risk analizi yapar.
calc_cancer_risk(BRCA_status, family_history)	Meme kanseri riski hesaplar.
load_data_from_excel(file)	Excel dosyasından veri çeker ve işler.
mrna_to_protein(mrna_seq)	mRNA'dan aminoasit dizilimi üretir.

💡 Neden Biolang?
✅ Doğal dil benzeri anlaşılır syntax
✅ Tıp ve genetik odaklı yerleşik fonksiyonlar
✅ Kodlama bilgisi az olan sağlık profesyonelleri için bile erişilebilir yapı
✅ Etik ilkelerle geliştirilmiş: veri gizliliği, şeffaflık, güvenlik

🔧 Kurulum
bash
Kopyala
Düzenle
git clone https://github.com/kullanici-adi/biolang.git
cd biolang
pip install -r requirements.txt
Kütüphaneler (örnek):

text
Kopyala
Düzenle
pandas
numpy
openpyxl
requests
📂 Dosya Yapısı (örnek)
bash
Kopyala
Düzenle
biolang/
├── core/                  # Temel fonksiyonlar (genetik, risk analizleri vb.)
├── data/                  # Örnek veri setleri
├── utils/                 # Yardımcı işlevler (veri yükleme/kaydetme)
├── tests/                 # Test dosyaları
├── README.md              # Bu dosya
└── requirements.txt
🔐 Etik İlkeler
Gizlilik: Genetik veriler kullanıcı izni olmadan kullanılmaz.

Şeffaflık: Çıktılar yalnızca tahmin olarak sunulur, tıbbi karar destek sistemi değildir.

Erişim Adaleti: Açık kaynak kodludur, herkesin kullanımına açıktır.

📈 Gelecek Planları
Makine öğrenmesi algoritmalarının entegrasyonu

Görsel analiz modüllerinin (heatmap, risk dağılımı vs.) eklenmesi

Web tabanlı bir arayüzle doktorlar için kullanılabilir hale getirilmesi

🤝 Katkı Sağlayın
Projeye katkı sağlamak isteyenler için:

Fork'layın 🍴

Geliştirin 🛠

Pull request gönderin 📬

👨‍🔬 Geliştirici Ekibi
Bu proje 6 kişilik bir ekip tarafından geliştirilmiştir:
Sevda Sağlamtaş, Eylül Naz Çelik, Zeynep Karataş, Defne Çiftçi, Rana Sabiha Çevik, Sena Zeynep Görgün, Sude Başalan, Berfin Zümra Karacakaya
