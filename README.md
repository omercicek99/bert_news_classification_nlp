<img width="1361" height="686" alt="huff-post web picture" src="https://github.com/user-attachments/assets/6880ce5a-3422-41d8-8840-2c243ae9161b" />


🧠 BERT Tabanlı Haber Kategorisi Sınıflandırma

Bu projede, haber başlıklarını ve metinlerini önceden tanımlı kategorilere ayırmak için fine-tune edilmiş BERT modeli kullanılmıştır. Model, çok sınıflı metin sınıflandırma problemi üzerinde eğitilmiş ve güçlü genelleme performansı göstermiştir.

🚀 Proje Özeti

Model: BERT (Transformer)

Problem: Çok sınıflı metin sınıflandırma

Framework: PyTorch + HuggingFace Transformers

Değerlendirme Metrikleri: Accuracy, F1-score, Training/Validation Loss

📊 Model Performansı
🔹 Epoch Bazlı Sonuçlar
Epoch	Training Loss	Validation Loss	Accuracy	F1

1	1.1581	1.0687	0.6905	0.6780

2	0.9086	0.9883	0.7103	0.7036

3	0.7618	0.9840	0.7125	0.7066

✔ Stabil öğrenme
✔ Overfitting gözlemlenmedi
✔ Güçlü genelleme performansı

🔹 En Başarılı Kategoriler (F1 Skoru)

STYLE & BEAUTY → 0.872

WEDDINGS → 0.867

TRAVEL → 0.851

DIVORCE → 0.843

POLITICS → 0.827

HOME & LIVING → 0.826

QUEER VOICES → 0.789

SPORTS → 0.788

FOOD & DRINK → 0.787

WELLNESS → 0.781

🛠 Kurulum
git clone https://github.com/kullaniciadi/proje-adi.git
cd proje-adi
pip install -r requirements.txt

▶️ Kullanım
Modeli eğitmek:
python train.py

Modeli değerlendirmek:
python evaluate.py

Yeni metinle tahmin yapmak:
python predict.py --text "Yeni teknolojiler sağlık sektörünü dönüştürüyor"

🧠 Eğitim Süreci

Metin ön işleme ve tokenization

Batch bazlı forward pass

Loss hesaplama

Backpropagation ve ağırlık güncelleme

Epoch sonunda validation değerlendirmesi

Accuracy ve F1 takibi

🔍 Overfitting Analizi

Training ve validation loss birlikte düşmüştür

Epoch’lar boyunca metrikler stabil artmıştır

Model ezberleme yapmadan öğrenmiştir

➡️ Bu durum modelin iyi genelleme yaptığını göstermektedir.

🎯 Sonuç

BERT modeli bağlamsal metin anlamada güçlüdür

Çok sınıflı haber sınıflandırma problemleri için uygundur

Gerçek dünya NLP uygulamalarına entegre edilebilir
