# Leukocytus

*leukocytus, i, m.* — akyuvar.

*Essential Medical Terminology* dersinin Caput I–IV konularını çalışmak için tarayıcıda oynanan bir arcade oyunu. Kan damarında devriye gezen bir akyuvarsın. Her patojen bir cevap taşıyor: doğru Latince formu taşıyanı vur, yanlışları bırak. Doğru patojen aşağı ulaşırsa enfeksiyon kaparsın.

**Oyna:** https://dionware1.github.io/leukocytus/

Telefonda tarayıcının "Ana ekrana ekle" seçeneğiyle uygulama gibi tam ekran açılır.

## Bölümler

| Bölüm | Konu | Boss |
|---|---|---|
| Caput I | Telaffuz kuralları, gramer kategorileri, sözlük formu | Haemorrhagia |
| Caput II | 1. çekim, edatlar (+ Acc. / + Abl.), isim + Genitivus | Pneumonia |
| Caput III | 2. çekim (-us, -er, -um), cinsiyet istisnaları | Icterus |
| Caput IV | 1. ve 2. çekim sıfatları, isim–sıfat uyumu | Morbus malignus |
| Examen | Dört bölüm karışık, sınav provası | Morbus chronicus complicatus |

Çekimler sabit bir soru listesinden gelmiyor; oyun hâl eklerini kurallardan kendisi üretiyor (`costarum`, `cancri`, `arteriae thoracicae internae`, `diameter transversa`). Bu sayede aynı soruyu ezberlemek yerine kuralı öğrenirsin.

## Öğrenme mekaniği

- Her yeni soru tipinden önce kısa bir kural kartı çıkar.
- Yanlış cevapta doğru form, açıklama ve kelimenin tam çekim tablosu gösterilir.
- Yanlış yapılan soru birkaç soru sonra tekrar gelir.
- Yanlışlar "Hatalarım" bankasına kaydedilir; sadece onları ayrıca çalışabilirsin.
- **Codex** menüsünde tüm kurallar ve bölüm bölüm kelime listesi var.

## Kontroller

| | Bilgisayar | Telefon |
|---|---|---|
| Patojene ateş | Patojene tıkla ya da `1`–`4` | Patojene dokun |
| Hareket | Fare, `←` `→` / `A` `D` | Boş yere dokunup sürükle |
| Düz ateş | Tık, `Space` | — |
| Duraklat | `P` / `Esc` | Sağ üstteki II |

## Teknik

Tek dosya: `index.html`. Kurulum ya da derleme yok; Google Fonts dışında dış bağımlılık yok. Rekorlar ve hata bankası tarayıcının `localStorage`'ında tutulur. Yerelde oynamak için `index.html` dosyasını tarayıcıda açman yeterli.
