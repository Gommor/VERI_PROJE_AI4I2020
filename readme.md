# BLM308 Veri Madenciliği Final Projesi: Donanım Anomali Tespiti ve Kestirimci Bakım

Bu depo, endüstriyel üretim hatlarında faaliyet gösteren kesme ve frezeleme makinelerinin anlık sensör verilerini analiz ederek olası donanım arızalarını ve yapısal anomalileri önceden tahmin etmeyi amaçlayan uçtan uca bir veri madenciliği projesidir. Proje kapsamında iş anlayışından model canlıya almaya kadar olan tüm süreçlerde uluslararası standart dalı olan **CRISP-DM (CRoss Industry Standard Process for Data Mining)** metodolojisi adım adım takip edilmiştir.

Bu projeyi kendi bilgisayarınızda sıfır hata ile kurup çalıştırmak için aşağıdaki adımları sırasıyla takip etmeniz yeterlidir.

---


## Kurulum ve Çalıştırma Adımları

Terminalinizi (veya Git Bash) açın, projeyi bilgisayarınıza indirin ve proje klasörünün içine geçiş yapın:
```bash
1. Depoyu Klonlayın
git clone <github-repo-linkiniz>
cd <klonlanan-klasör-adı>

2. Sanal ortam oluşturma
python -m venv .venv 

# Windows kullanıyorsanız aktif etme komutu:
.venv\Scripts\activate

# macOS veya Linux kullanıyorsanız aktif etme komutu:
source .venv/bin/activate
 

## .env

3. .env dosyasi oluşturun içine api key girin.
GOOGLE_API_KEY=SizinGeminiApiKeyDeğeriniz

# 4. Gerekli Kütüphaneleri Yükleyin
pip install -r requirements.txt

# 5. Projeyi Çalıştırın
VS Code veya Jupyter Lab üzerinden proje_analiz.ipynb ana kod dosyasını açın. Sağ üst köşeden kernel (çekirdek) olarak oluşturduğumuz .venv ortamını seçip tüm hücreleri yukarıdan aşağıya sırayla çalıştırabilirsiniz


