# Web Scraping Projesi

Bu proje, Python kullanarak web scraping işlemini göstermektedir. Amaç, bir kitap e-ticaret sitesinden veri çekmek ve bu bilgileri görüntülemektir.

## Kullanılan Kütüphaneler
- beautifulsoup4==4.12.3
- pandas==2.2.2
- regex==2024.7.24
- requests==2.32.3
- selenium==4.23.1

## Nasıl Çalıştırılır

1. Depoyu klonlayın:
   ```bash
   git clone https://github.com/ibrahmkocaa/Web-Scraping-Project
   ```
2. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install -r requirements.txt
   ```
3. Jupyter Notebook dosyasını açın ve hücreleri çalıştırın:
   ```bash
   jupyter notebook app.ipynb
   ```

## Dosyalar

- `app.ipynb`: Ana notebook dosyası
- `requirements.txt`: Gerekli kütüphanelerin listesi

## Proje Adımları

1. Gerekli kütüphanelerin import edilmesi
2. Web sayfası içeriğinin alınması
3. HTML içeriğinin parse edilmesi
4. İlgili verilerin çıkarılması
5. Verilerin yapılandırılmış bir formata kaydedilmesi

## Açıklama

Bu proje, Selenium , BeautifulSoup ve requests kütüphanelerini kullanarak web scraping işlemlerini detaylandırmaktadır. Örnek olarak, bir kitap e-ticaret sitesinden kitap detayları çekilmekte ve bu bilgiler görüntülenmektedir.
```
