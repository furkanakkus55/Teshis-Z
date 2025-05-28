#  TEŞHİS-Z: Yapay Zeka Destekli Hastalık Teşhis Sistemi

**TEŞHİS-Z**, kullanıcıların semptomlarını girerek en olası hastalıkları öğrenebileceği, yapay zeka mantığıyla çalışan, Python ve Tkinter tabanlı grafik arayüzlü bir teşhis uygulamasıdır.

##  Özellikler

- ** Kişisel Bilgi Girişi**  
  Ad, soyad, yaş ve cinsiyet bilgilerine dayalı kişiselleştirilmiş teşhis.

- ** Kategorize Semptom Seçimi**  
  Semptomlar; solunum, nörolojik, kardiyovasküler gibi 14 kategoriye ayrılmıştır.

- ** Arama Özelliği**  
  Semptom listesi içinde hızlı arama yapabilirsiniz.

- ** Ağırlık Tabanlı Teşhis**  
  Her semptomun hastalıkla eşleşme düzeyine göre en olası **ilk 3 hastalık** listelenir.

- ** Kayıt Yönetimi**  
  Tüm teşhisler `kayitlar.json` dosyasında saklanır. Kayıtları görüntüleyebilir veya silebilirsiniz.

- ** Kullanıcı Dostu Arayüz**  
  Tkinter ile oluşturulmuş şık ve sezgisel bir kullanıcı arayüzü.

---

##  Gereksinimler

- Python 3.6 veya üzeri
- Tkinter (Python ile birlikte gelir)
- Dahili modüller: `json`, `os`, `datetime`, `collections`

--- 

## Kurulum

```bash
git clone https://github.com/kullanici_adiniz/teshis-z.git
cd teshis-z
python teshis_z.py
