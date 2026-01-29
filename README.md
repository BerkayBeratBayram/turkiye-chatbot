# Türkiye Chatbot

Bu proje, Türkiye ile ilgili kısa bilgiler ve konu bazlı içerikler sunmak için hazırladığım bir sohbet yardımcısıdır. Amacım, elimdeki metin kaynaklarını düzenleyip sorgulara uygun bilgiyi hızlıca bulabilen bir yapı kurmaktı.

Ne yapıyor
- Verilen metin kaynaklarını parçalayıp indeksliyorum.
- Gelen soruları metin içinde arayıp en ilgili parça(ları) döndürüyorum.

Proje yapısı (kısa)
- `turkiye_chatbot.ipynb`: Projenin ana çalışma not defteri. Veri işleme, indeksleme ve örnek sorgular burada yer alıyor.
- `data/` klasörü: Projede kullanılan ham metin dosyaları.
  - `genel_bilgiler.txt`
  - `kultur.txt`
  - `sehirler.txt`
  - `tarih_ekonomi.txt`
  - `turizm.txt`
- `venv312/`: Projeyi geliştirdiğim sanal ortam dizini (Python ortamı).

Kullandığım temel araçlar ve kütüphaneler
- Python (geliştirme ortamı olarak sanal ortam kullandım).
- Jupyter Notebook (çalışmaların ve deneylerin kayıtlı olduğu yer).
- Chroma / `chromadb` — metinlerin vektör tabanlı indekslenmesi için.
- Embedding (cümle gömme) yöntemleri — metinlerin benzerlik hesapları için.
- Langchain benzeri metin bölme (ör. `RecursiveCharacterTextSplitter`) — uzun metinleri yönetilebilir parçalara ayırmak için.
- Gerekli olduğunda `numpy`, `pandas` ve benzeri temel Python kütüphanelerinden faydalandım.

Notlar
- Tüm ham veriler `data/` içinde tutuluyor; her dosya belirli bir konuya karşılık geliyor.
- Projeyi ben geliştirdim; not defterinde adım adım yaptığım işlemler ve denemeler bulunuyor.
- Eğer dosyada değişiklik veya ekleme isterseniz, not defterindeki ilgili hücreleri güncelleyerek ilerleyebiliriz.

İletişim
- Değişiklik isterseniz bildirin, düzenleyeyim.
