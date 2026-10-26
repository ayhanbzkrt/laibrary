 
<div align="center">

# L’AI’brary: Evrenlerin Muhafızı

### Kitaptan ve portaldan doğan yapay zekâ macerası

**14 Evren · 14 Bekçi · 14 Muhafız · 14 Etkileşimli Bulmaca · 42 Kavram**

**2D Tarayıcı Oyunu | Yapay Zekâ Okuryazarlığı | Etkileşimli Öğrenme**

*Bir atlasın kayıp sayfalarını bulmak için yapay zekânın dünyasını oynayarak keşfet.*

![L’AI’brary: Evrenlerin Muhafızı — Oyun Tanıtım Afişi]([assets/afis.png](https://github.com/ayhanbzkrt/laibrary/blob/main/L%E2%80%99AI%E2%80%99BRARY_%20Evrenlerin%20Muhaf%C4%B1z%C4%B1.png))

**[L’AI’brary Öğrenme Portalı](https://ayhanbzkrt.github.io/yzevreni/)** · **[GitHub](https://github.com/ayhanbzkrt)** · **[Kitapyurdu](https://www.kitapyurdu.com/yazar/ayhan-bozkurt/260288.html)**

</div>

---

> **© 2026 Ayhan Bozkurt / AI’Han Academy — Tüm hakları saklıdır.**
>
> Bu projenin kaynak kodları, görselleri, karakterleri, tasarımı, oyun mekanikleri ve özgün içerikleri telif hakkıyla korunmaktadır. Açık kaynak lisansı verilmemiştir. İzinsiz kopyalama, çoğaltma, değiştirme, yeniden dağıtma veya ticari kullanım yasaktır.

---

# İçindekiler

1. Oyun Hakkında
2. Hikâye ve Karakterler
3. Oynanış ve Oyun Mekanikleri
4. Üç Bölüm, On Dört Evren
5. Kavramlar, Görevler ve İlerleme
6. Kontroller
7. Kurulum ve Çalıştırma
8. Teknik Mimari
9. Pedagojik Yaklaşım
10. Erişilebilirlik ve Teknik Notlar
11. L’AI’brary Ekosistemi ve Kaynakça
12. Telif Hakları ve Kullanım Koşulları
13. English Documentation
14. İletişim ve Bağlantılar

---

# 1. Oyun Hakkında

**L’AI’brary: Evrenlerin Muhafızı**, Ayhan Bozkurt tarafından geliştirilen L’AI’brary öğrenme dünyasını keşif, platform oyunu, karakter etkileşimi, mücadele ve uygulamalı yapay zekâ bulmacalarıyla birleştiren özgün bir tarayıcı oyunudur.

Oyun, yapay zekâ kavramlarını yalnızca tanımlamak yerine oyuncunun bir problemi deneyimlemesini amaçlar.

Oyuncu bir evreni keşfeder, bekçisiyle konuşur, hareketli platformlardan geçer, yapay zekâ kavramlarını toplar, muhafızla mücadele eder ve bilimsel bir fikri somutlaştıran etkileşimli bulmacayı çözerek atlasın kayıp sayfasına ulaşır.

## Temel Özellikler

- **3 ana bölüm ve 14 ayrı evren:** Yapay zekâ temellerinden ileri sistemlere, insan–yapay zekâ iş birliğine ve etik konularına uzanan öğrenme yolculuğu.
- **14 bekçi ve 14 muhafız:** Her evrene özgü karakter, hikâye ve mücadele.
- **14 oynanabilir öğrenme bulmacası:** Sayısal deneyler, sınıflandırma, arama, karar verme, sıralama, parametre ayarlama ve görselleştirme.
- **42 toplanabilir yapay zekâ kavramı:** Her evrende üç kavram ve açıklaması.
- **14 bilgi rünü ve 84 kıvılcım:** Keşif ve toplama hedefleri.
- **XP ve seviye sistemi:** Oyuncunun ilerlemesine bağlı unvanlar.
- **Rozet, görev ve teçhizat sistemi:** Keşif ve mücadele ilerlemesini destekleyen mekanikler.
- **Hikâye sahneleri ve karakter diyalogları:** Öğrenme evrenlerini birbirine bağlayan anlatım.
- **Web Audio API ses sistemi:** Tarayıcıda üretilen müzik ve ses efektleri.
- **Yerel kayıt:** Oyuncu ilerlemesinin tarayıcıda saklanması.
- **Tek HTML mimarisi:** Oyunun temel kodu, animasyonları, görselleri ve bulmacaları tek dosyada.

Bu proje, yalnızca bir tanıtım prototipi veya tıklanıp geçilen test uygulaması değildir. Karakter hareketi, savaş, evren içi platform bölümleri, ilerleme sistemi ve etkileşimli öğrenme etkinliklerini birleştiren oynanabilir bir deneyimdir.

---

# 2. Hikâye ve Karakterler

## Atlasın Kayıp Sayfaları

Bir kütüphanenin arka odasında bulunan eski, deri kaplı bir atlas açıldığında yapay zekâya ilişkin on dört sayfa evrenlere savrulur.

Her evrenin bilgeliğini koruyan bir bekçisi, aşılması gereken bir muhafızı ve çözülmeyi bekleyen bir bulmacası vardır.

Sayfalar toplanmadan atlas eski bütünlüğüne kavuşamaz.

Oyuncunun görevi, kayıp sayfaları bulmak ve evrenleri yeniden birbirine bağlamaktır.

## Elif — Ana Karakter

**Elif**, oyunun oynanabilir ana karakteridir.

Yolculuğunda:

- Yeni evrenleri keşfeder.
- Bekçilerle konuşur.
- Koşar, zıplar ve platformları aşar.
- Kıvılcımları ve bilgi rünlerini toplar.
- Yeni yetenekler kazanır.
- Muhafızlarla mücadele eder.
- Yapay zekâ bulmacalarını çözer.
- Atlasın kayıp sayfalarını geri getirir.

Elif'in yolculuğundaki temel ilerleme, yalnızca düşmanları yenmek değil, karşılaştığı sorunların arkasındaki bilimsel fikirleri anlamaktır.

## İbre — Yol Arkadaşı

**İbre**, Elif'e eşlik eden konuşan rehber karakteridir.

Oyuncuyu bir sonraki hedefe yönlendirir, evrenlerin hikâyelerini anlatır ve yolculuğun farklı aşamalarında rehberlik eder.

## Evren Bekçileri

Her evrenin bilimsel içeriği, kendine özgü bir karakter ve mekân üzerinden anlatılır.

Örneğin:

- **Gökbilimci Nur:** Verileri anlamlandırır.
- **Haritacı Leyla:** Öğrenme ve genellemeyi sorgular.
- **Masalcı Nine:** Dilin yapısını açıklar.
- **Dokumacı Saadet:** Sinir ağları ve öğrenme sürecini anlatır.
- **Arşivci Selim:** Kaynağa dayalı bilgi üretimini önemser.
- **Bilge Teyze:** Yapay zekânın fırsat ve risklerini birlikte değerlendirir.

Karakterler yalnızca görev veren kişiler değildir. Her biri temsil ettiği yapay zekâ alanının temel sorunlarını hikâye aracılığıyla anlaşılır kılar.

---

# 3. Oynanış ve Oyun Mekanikleri

## Temel Oynanış Döngüsü

**Keşfet → Bekçiyle Konuş → Evrene Gir → Kavramları Topla → Muhafızı Yen → Bulmacayı Çöz → Atlas Sayfasını Kazan**

## 3.1. Ana Atlas Dünyası

Elif, yan kaydırmalı iki boyutlu bir dünyada hareket eder.

Ana dünyada:

- Keşfedilebilir adalar
- Platformlar ve hareketli geçişler
- Evren kapıları
- Bekçi karakterler
- Bilgi rünleri
- Kıvılcımlar
- Tehlikeler
- Hikâye ve bölüm geçişleri

bulunur.

Tamamlanan evrenler, oyuncunun yeni bölgelere ulaşmasına yardımcı olur.

## 3.2. Evren İçleri

Her evrenin kendi platform bölümü vardır.

Oyuncu bu alanlarda hareket ederek üç ayrı kavram küresini toplar.

Her küre ilgili terimin:

- Türkçe adını
- İngilizce karşılığını
- Açıklamasını

gösterir.

Bu mekanik, konuların oyun içerisinde birbirinden kopuk bilgi kutularına dönüşmesini önler.

## 3.3. Muhafız Mücadeleleri

Her evrenin kendine özgü muhafızı bulunur.

Muhafızların davranışları farklı saldırı desenleriyle oluşturulmuştur.

Oyuncu:

- Saldırılardan kaçınır.
- Uygun zamanda karşılık verir.
- Kılıç ve ekipmanlarını kullanır.
- Muhafızın zayıf anlarını değerlendirir.

Her muhafız, ilgili yapay zekâ alanında karşılaşılan bir sorunu veya yanılgıyı temsil eder.

Örneğin **Aşırı Öğrenme Golemi**, yalnızca eğitim örneklerini ezberleyen bir modelin yeni verilerde başarısız olabileceği fikrine dayanır.

## 3.4. Etkileşimli Bilgi Bulmacaları

Muhafız karşılaşmasının ardından ilgili evrenin bilimsel bulmacası açılır.

Oyuncu:

1. Problemi inceler.
2. Girdileri veya parametreleri değiştirir.
3. Seçenekleri dener.
4. Sonuçları gözlemler.
5. Çözümü tamamlar.
6. Bilimsel açıklamayı okur.
7. Atlas sayfasını geri kazanır.

Bulmacalar, JavaScript ile tarayıcıda çalışan eğitimsel örnekler içerir.

---

# 4. Üç Bölüm, On Dört Evren

## BÖLÜM I — YAPAY ZEKÂ EVRENİNE GİRİŞ

### Evren 01 — Veri Akademisi

**Mekân:** Veri Gözlemevi

**Bekçi:** Gökbilimci Nur

**Muhafız:** Eksik Veri Avcısı

**Öğrenme konuları:**
- Veri analizi
- Ortalama
- Medyan
- Örneklem
- Veri yorumlama

**Etkileşimli deney:**

Oyuncu sayı taşlarını kullanarak ortalamayı dengeler. Ortalama ve medyan arasındaki farkı gözlemleyerek veri kümelerinin nasıl yorumlandığını öğrenir.

### Evren 02 — Arama Adaları

**Mekân:** Arama Feneri

**Bekçi:** Fenerci Kaptan Rıza

**Muhafız:** Labirent Bekçisi

**Öğrenme konuları:**
- Arama algoritmaları
- İkili arama
- Genişlik öncelikli arama
- Sezgisel arama

**Etkileşimli deney:**

Oyuncu 32 olasılık içindeki hedefi daha büyük veya daha küçük geri bildirimlerinden yararlanarak bulmaya çalışır.

İkili aramanın problem alanını nasıl daralttığını deneyimler.

### Evren 03 — Makine Öğrenmesi

**Mekân:** Haritacının Masası

**Bekçi:** Haritacı Leyla

**Muhafız:** Aşırı Öğrenme Golemi

**Öğrenme konuları:**
- Makine öğrenmesi
- Eğitim ve test verileri
- Genelleme
- Aşırı öğrenme
- Karar sınırları

**Etkileşimli deney:**

Oyuncu, iki sınıfı birbirinden ayıran karar sınırını değiştirir.

Eğitim verisindeki başarı ile daha önce görülmemiş verideki başarının neden farklı olabileceğini inceler.

### Evren 04 — Yapay Zekâ Atölyesi

**Mekân:** Çarkların Atölyesi

**Bekçi:** Usta Demirhan

**Muhafız:** Kural Canavarı

**Öğrenme konuları:**
- Yapay zekâ
- Kural tabanlı sistemler
- Makine öğrenmesi
- Sınıflandırma
- Model kavramı

**Etkileşimli deney:**

Oyuncu kedi ve köpek örneklerini ayırt etmek için özellik kuralları oluşturur.

Bu kuralları farklı örneklerde deneyerek sabit kuralların sınırlarını keşfeder.

### Evren 05 — Yapay Zekâ Ajanları

**Mekân:** Seyyah Girdabı

**Bekçi:** Seyyah Kerem

**Muhafız:** Kontrolsüz Ajan

**Öğrenme konuları:**
- Yapay zekâ ajanları
- Planlama
- Araç kullanımı
- Görev yürütme
- İnsan onayı

**Etkileşimli deney:**

Oyuncu bir toplantı planlama senaryosundaki ajan adımlarını doğru sıraya yerleştirir.

Hangi işlemin otomatik yürütülebileceğini ve hangi noktada insan onayı gerektiğini değerlendirir.

### Evren 06 — Doğal Dil İşleme

**Mekân:** Masalcı Ormanı

**Bekçi:** Masalcı Nine

**Muhafız:** Halüsinasyon Hayaleti

**Öğrenme konuları:**
- Doğal dil işleme
- Token
- Anlam vektörleri
- Büyük dil modelleri
- Sözcük parçalama

**Etkileşimli deney:**

Oyuncu Türkçe sözcükleri anlamlı parçalara ayırarak token kavramıyla ilişkili bir deney gerçekleştirir.

Dilin işlenebilir parçalara ayrılmasının neden önemli olduğunu öğrenir.

---

## BÖLÜM II — MODELLER VE AKILLI SİSTEMLER

### Evren 07 — Derin Öğrenme

**Mekân:** Dokumacının Tezgâhı

**Bekçi:** Dokumacı Saadet

**Muhafız:** Kaybolan Gradyan

**Öğrenme konuları:**
- Yapay sinir ağları
- Nöronlar
- Ağırlıklar
- Geri yayılım
- Öğrenme süreci

**Etkileşimli deney:**

Oyuncu tek bir nöronun ağırlıklarını değiştirir ve öğrenme adımları uygular.

Parametre değişimlerinin model çıktısını nasıl etkilediğini gözlemler.

### Evren 08 — MLOps

**Mekân:** Şelale Değirmeni

**Bekçi:** Değirmenci Hasan

**Muhafız:** Kayma Seli

**Öğrenme konuları:**
- MLOps
- Model izleme
- Veri kayması
- Model performansı
- Yeniden eğitim

**Etkileşimli deney:**

Oyuncu 60 günlük veri kayması senaryosunda model başarısını izler.

Sınırlı yeniden eğitim hakkını doğru zamanlarda kullanmaya çalışır.

### Evren 09 — Bilgisayarlı Görme

**Mekân:** Camcı Kulesi

**Bekçi:** Camcı Işıl

**Muhafız:** Piksel Sürüsü

**Öğrenme konuları:**
- Bilgisayarlı görme
- Pikseller
- Görüntü işleme
- Konvolüsyon
- Görüntü filtreleri

**Etkileşimli deney:**

Oyuncu piksel matrisine farklı süzgeçler uygular.

Konvolüsyon işleminin sayısal sonuçlarını gözlemleyerek görüntülerdeki yapıların nasıl ortaya çıkarıldığını öğrenir.

### Evren 10 — MCP ve Gelişmiş RAG

**Mekân:** Kayıp Belgeler Arşivi

**Bekçi:** Arşivci Selim

**Muhafız:** Kaynaksız Söylenti

**Öğrenme konuları:**
- RAG
- Bilgi erişim
- BM25
- Anlamsal arama
- MCP
- Kaynak doğrulama
- Erişim yetkileri

**Etkileşimli deney:**

Oyuncu belgeler arasından ilgili ve erişim izni bulunan kaynakları seçer.

Kaynağa dayalı bir yanıt oluşturmanın önemini deneyimler.

---

## BÖLÜM III — İNSAN, ÜRETİM VE GELECEK

### Evren 11 — Görünmez Yapay Zekâ ve Otonom İşletmeler

**Mekân:** Mühürlü Konak

**Bekçi:** Kâhya Zeynep

**Muhafız:** Kara Kutu

**Öğrenme konuları:**
- Görünmez yapay zekâ
- Otonom sistemler
- Dijital ikizler
- Tahmin
- Stok yönetimi

**Etkileşimli deney:**

Oyuncu güvenlik stoku parametresini ayarlar.

Karşılanan talep ile fazla stok arasındaki ilişkiyi grafik üzerinden inceler.

### Evren 12 — Hibrit Zekâ ve İnsan–AI İş Birliği

**Mekân:** Aşılı Bahçe

**Bekçi:** Bahçıvan Ömer

**Muhafız:** Otomasyon Yanlılığı

**Öğrenme konuları:**
- Hibrit zekâ
- İnsan–yapay zekâ iş birliği
- Otomasyon yanlılığı
- Güven eşikleri
- İnsan denetimi

**Etkileşimli deney:**

Oyuncu sistemin güven eşiğini değiştirir.

Otomatik karar hataları ile insan inceleme yükü arasındaki dengeyi gözlemler.

### Evren 13 — Prompt Mühendisliği ve Üretken Yapay Zekâ

**Mekân:** Hattatın Kubbesi

**Bekçi:** Hattat Melek

**Muhafız:** İstem Enjeksiyonu

**Öğrenme konuları:**
- Prompt mühendisliği
- Rol
- Görev
- Bağlam
- Kısıtlar
- Çıktı biçimi
- Sıcaklık parametresi

**Etkileşimli deney:**

Oyuncu iyi yapılandırılmış bir istem oluşturur.

Sıcaklık parametresinin token olasılıkları üzerindeki etkisini görselleştirir.

### Evren 14 — Yapay Zekâ Riskleri, Etik ve Gelecek

**Mekân:** Son Fener

**Bekçi:** Bilge Teyze

**Muhafız:** Önyargı Gölgesi

**Öğrenme konuları:**
- Yapay zekâ etiği
- Yanlılık
- Açıklanabilirlik
- Yapay zekâ güvenliği
- Risk temelli düzenleme
- AB Yapay Zekâ Yasası

**Etkileşimli deney:**

Oyuncu örnek yapay zekâ kullanım senaryolarını ilgili risk ve yükümlülük kategorileriyle eşleştirir.

Bu bölüm eğitim amaçlıdır ve hukuki danışmanlık yerine geçmez.

---

# 5. Kavramlar, Görevler ve İlerleme

## 5.1. Toplanabilir Unsurlar

| Unsur | Sayı | Açıklama |
|---|---:|---|
| Atlas Sayfası | 14 | Evren bulmacalarının tamamlanmasını gösterir. |
| Kavram Küresi | 42 | Her evrende üç yapay zekâ kavramı bulunur. |
| Bilgi Rünü | 14 | Ana dünyadaki keşif hedefleridir. |
| Kıvılcım | 84 | Puan ve toplama ilerlemesine katkıda bulunur. |
| Muhafız | 14 | Her evrene ait mücadele karşılaşması. |

## 5.2. Görev Sistemi

Her evrende dört temel görev aşaması bulunur:

1. Bekçiyle konuş.
2. Üç kavramı topla.
3. Muhafızı yen.
4. Atlas sayfasını bul.

Görev sistemi, oyuncunun keşif ve öğrenme ilerlemesini takip etmesini sağlar.

## 5.3. XP ve Seviye Sistemi

Oyuncu farklı eylemlerden deneyim puanı kazanır.

İlerleme unvanları:

**Çırak → Yolcu → Kâşif → Haritacı → Atlas Bilgesi**

## 5.4. Teçhizat ve Yetenekler

Oyunda farklı aşamalarda açılabilen ekipmanlar bulunmaktadır.

- Algoritma Kılıcı
- Yapay Zekâ Okuryazarlığı Kalkanı
- Veri Pelerini
- Gradyan Çizmeleri
- Hizalama Pusulası
- Optimize Edilmiş Kılıç

Ekipmanlar oyuncunun hareket, korunma ve mücadele yeteneklerini etkiler.

## 5.5. Kâşif Defteri

Oyun içindeki Kâşif Defteri şu bölümleri içerir:

- Görevler
- Teçhizat
- Rozetler
- İstatistikler

## 5.6. İlerleme Kaydı

Oyun, kayıt bilgilerini tarayıcının `localStorage` özelliğiyle saklar.

Bu sistem:

- Oyuncunun ilerlemesini korur.
- Tamamlanan bölümleri kaydeder.
- Toplanan nesneleri takip eder.
- XP, başarı ve ekipman bilgilerini saklar.
- Ses tercihlerini korur.

Sunucu tabanlı kullanıcı hesabı veya bulut senkronizasyonu bulunmamaktadır.

Tarayıcı verilerinin silinmesi, kayıtların kaybolmasına neden olabilir.

---

# 6. Kontroller

## Masaüstü

| Eylem | Kontrol |
|---|---|
| Sola hareket | ← veya A |
| Sağa hareket | → veya D |
| Zıpla | Boşluk, ↑ veya W |
| Konuş / Etkileşim | E veya Enter |
| Saldır | J veya F |
| Atılma | K veya Shift |
| Fareyle hedefe yönel | Oyun alanına tıkla |
| Bulmacayı kapat | Esc |
| Hikâye sahnesini ilerlet | Boşluk, Enter veya E |
| Hikâye sahnesini geç | Esc / Geç |

**Not:** Atılma yeteneği Gradyan Çizmeleri kazanıldıktan sonra açılır.

Zıplama yüksekliği tuşa basılı tutma süresine göre değişebilir.

Bazı bulmacalarda kendine özgü fare, sürükleme veya klavye kontrolleri bulunur.

## Mobil ve Dokunmatik Cihazlar

Dokunmatik cihazlarda ekranda şu kontroller görünür:

- Sol / sağ hareket
- Zıplama
- Saldırı
- Atılma
- Etkileşim

Karmaşık bulmacaların ve görsel ayrıntıların daha rahat incelenebilmesi için geniş ekran önerilir.

---

# 7. Kurulum ve Çalıştırma

## Proje Dosya Yapısı

```text
LAIbrary-Evrenlerin-Muhafizi/
│
├── index.html
│
├── README.md
│
└── assets/
    └── afis.png
```

Projenin oyun mantığı tek bir HTML dosyasındadır.

`index.html` içerisinde:

- HTML
- CSS
- JavaScript
- Gömülü görseller
- Karakter animasyonları
- Oyun sistemleri
- Öğrenme bulmacaları
- Ses motoru

yer almaktadır.

Haricî oyun motoru, Node.js derleme sistemi, veritabanı veya dış LLM API anahtarı gerektirmez.

## Yöntem 1 — HTML Dosyasını Açma

`index.html` dosyasını güncel bir web tarayıcısında açabilirsiniz.

Ancak yerel dosyalarda tarayıcıların veri saklama davranışları değişebildiği için HTTP sunucusu kullanılması önerilir.

## Yöntem 2 — Yerel Sunucu

Proje klasöründe terminal açın:

```bash
python3 -m http.server 8000
```

Ardından:

http://localhost:8000

adresine gidin.

## Yöntem 3 — GitHub Pages

1. GitHub üzerinde yeni bir depo oluşturun.
2. `index.html`, `README.md` ve `assets` klasörünü yükleyin.
3. Depodaki **Settings** bölümüne girin.
4. **Pages** ayarını açın.
5. **Deploy from a branch** seçeneğini belirleyin.
6. `main` dalını ve `/ (root)` klasörünü seçin.
7. GitHub Pages tarafından sağlanan bağlantıyı açın.

## README Afişi

Afişin GitHub README sayfasında görünmesi için:

```markdown
![L’AI’brary Oyun Afişi](assets/afis.png)
```

satırını kullanın.

Görselin `assets/afis.png` yolunda bulunması gerekir.

---

# 8. Teknik Mimari

## Kullanılan Teknolojiler

| Teknoloji | Kullanım |
|---|---|
| HTML5 | Uygulama yapısı |
| CSS3 | Arayüz, stiller ve responsive düzen |
| JavaScript | Oyun motoru ve etkileşimler |
| Canvas 2D | Oyun sahnesi, animasyon ve çizimler |
| Web Audio API | Müzik ve ses efektleri |
| localStorage | Yerel kayıt sistemi |
| WebP | Gömülü evren görselleri |
| Google Fonts | Fraunces ve Atkinson Hyperlegible |

## 8.1. Canvas Oyun Motoru

Oyun dünyası HTML5 Canvas 2D üzerinden çizilir.

Temel mekanikler:

- Karakter hareketi
- Yerçekimi
- Zıplama
- Platform çarpışmaları
- Kamera hareketi
- Karakter animasyonları
- Parçacık efektleri
- Mücadele ve hasar sistemi
- Sahne geçişleri

## 8.2. Karakter Animasyonları

Karakter sprite kareleri Canvas üzerinden hazırlanır.

Desteklenen hareketler:

- Boşta bekleme
- Yürüme
- Zıplama
- Mücadele hareketleri

## 8.3. Öğrenme Modülleri

Oyun kodunda her evren için ayrı JavaScript modülü bulunmaktadır.

```javascript
G.veri
G.arama
G.ml
G.atolye
G.ajan
G.dil

G.deep
G.mlops
G.gorme
G.rag

G.konak
G.hibrit
G.istem
G.etik
```

Bu modüller yapay zekâ alanlarının eğitimsel bulmacalarını içerir.

## 8.4. Ses Motoru

Müzik ve ses efektleri Web Audio API üzerinden tarayıcıda üretilir.

Sesler tarayıcının otomatik oynatma kısıtları nedeniyle ilk kullanıcı etkileşiminden sonra etkinleşebilir.

## 8.5. Yerel Depolama

Oyun ilerlemesi `localStorage` aracılığıyla saklanır.

Oyunun mevcut sürümünde haricî bulut veritabanı kullanılmamaktadır.

## 8.6. Tek HTML Yaklaşımı

Tasarımın temel teknik özelliklerinden biri, oyunun ana bileşenlerinin tek HTML dosyasında bir araya getirilmesidir.

Bu yaklaşım sayesinde:

- Ek derleme adımı gerekmez.
- Paket yöneticisi zorunlu değildir.
- Haricî oyun motoru kurulmaz.
- Dış LLM API anahtarı gerekmez.
- Oyun modern tarayıcıda çalışabilir.

Google Fonts ve dış bağlantılar internet erişimi gerektirebilir. Bu nedenle tamamen çevrimdışı kullanımda tipografi farklılıkları oluşabilir.

---

# 9. Pedagojik Yaklaşım

L’AI’brary: Evrenlerin Muhafızı, yapay zekâ okuryazarlığını oyun içerisinde deneyimletmeyi amaçlar.

## 9.1. Hikâyeleştirerek Öğretme

Soyut yapay zekâ kavramları karakterler, mekânlar ve problemler üzerinden somutlaştırılır.

Örneğin aşırı öğrenme, Haritacı Leyla'nın karşılaştığı bir model problemi üzerinden anlatılır.

## 9.2. Deneyimleyerek Öğrenme

Oyuncu yalnızca açıklama okumaz.

- Parametreleri değiştirir.
- Verileri karşılaştırır.
- Modelleri sınar.
- Karar verir.
- Sonuçları gözlemler.

## 9.3. Anında Geri Bildirim

Bulmacanın çözümü sonrasında:

- Doğru veya yanlış durumları
- Bilimsel açıklamalar
- İlgili kavramlar
- Kaynak bilgileri

oyuncuya sunulur.

## 9.4. Oyunlaştırma

Keşif, görev, XP, mücadele, rozet ve koleksiyon sistemleri öğrenme etkinlikleriyle birleştirilir.

## 9.5. Öğrenme Hedefi

Oyunun temel yaklaşımı:

**Konuyu anlamak → Denemek → Değiştirmek → Sonucu gözlemlemek → Öğrenilen bilgiyi pekiştirmek**

şeklinde özetlenebilir.

Bu yöntem, yapay zekâya yeni başlayan kullanıcıların teknik konularla etkileşime girmesini kolaylaştırmayı hedefler.

---

# 10. Erişilebilirlik ve Teknik Notlar

- Klavye, fare ve dokunmatik kontroller mevcuttur.
- Responsive arayüz düzenlemeleri bulunmaktadır.
- Bazı arayüz bileşenlerinde erişilebilirlik etiketleri kullanılır.
- `prefers-reduced-motion` terciğine yönelik hareket azaltma desteği bulunmaktadır.
- Oyun tarayıcı tabanlıdır.
- Haricî LLM hizmetine bağımlı değildir.
- Kayıtlar yerel cihazda tutulur.
- Tüm ekran okuyucu senaryolarında eksiksiz erişilebilirlik doğrulanmış değildir.
- Tüm tarayıcı ve cihaz kombinasyonlarında aynı performans garanti edilmez.
- Hukuki ve etik bulmacalar eğitim amaçlı örneklerdir.

---

# 11. L’AI’brary Ekosistemi ve Kaynakça

Bu oyun, L’AI’brary öğrenme ekosisteminin bir parçasıdır.

L’AI’brary, yapay zekâ kavramlarının kitap, portal ve etkileşimli uygulamalar aracılığıyla öğrenilmesini amaçlayan bir eğitim çalışmasıdır.

**Öğrenme Portalı:**

https://ayhanbzkrt.github.io/yzevreni/

Oyun içindeki bilimsel içerikler ve kaynakça sistemi, yapay zekâ literatüründeki çeşitli çalışmalardan yararlanır.

## Seçilmiş Kaynaklar

Russell, S., & Norvig, P. (2020). *Artificial Intelligence: A Modern Approach*. 4th Edition. Pearson.

Robertson, S., & Zaragoza, H. (2009). The Probabilistic Relevance Framework: BM25 and Beyond.

Lewis, P., et al. (2020). Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks.

LeCun, Y., Bengio, Y., & Hinton, G. (2015). Deep Learning. *Nature*.

Amershi, S., et al. (2019). Guidelines for Human-AI Interaction.

European Parliament and Council. (2024). Regulation (EU) 2024/1689 — Artificial Intelligence Act.

Daha ayrıntılı bibliyografik bilgiler oyunun **Kaynaklar** bölümünde yer almaktadır.

---

# 12. Telif Hakları ve Kullanım Koşulları

## © 2026 Ayhan Bozkurt — AI’Han Academy

**TÜM HAKLARI SAKLIDIR — ALL RIGHTS RESERVED**

L’AI’brary: Evrenlerin Muhafızı projesinin özgün yazılım kodları, oyun tasarımı, görsel kimliği, karakterleri, anlatısı, oyun mekanikleri, evren yapıları, etkileşimli öğrenme içerikleri, grafik ve animasyonları, tanıtım görselleri ve bütünsel sunumu üzerindeki ilgili fikrî mülkiyet hakları saklıdır.

Üçüncü taraf eserler, alıntılar, fontlar ve haricî kaynaklar kendi hak sahiplerinin lisans ve kullanım koşullarına tabidir.

## İzinsiz Kullanım Yasağı

Hak sahibinden önceden yazılı izin alınmadan aşağıdaki faaliyetlere kullanım izni verilmemektedir:

1. Projenin kaynak kodlarının tamamını veya özgün bölümlerini kopyalayarak başka bir projede yayımlamak.
2. Oyunun görsellerini, karakterlerini veya tasarım bileşenlerini izinsiz yeniden kullanmak.
3. Kaynak kod üzerinde değişiklik yaparak türev bir oyun veya dijital ürün olarak yeniden dağıtmak.
4. Oyunu başka marka veya isim altında yeniden yayımlamak.
5. Oyunu ticari faaliyetlerde kullanmak, satmak veya ücretli hizmete dönüştürmek.
6. Oyun içeriklerini izinsiz eğitim paketlerine, ticari kurslara veya başka dijital ürünlere aktarmak.
7. Projenin özgün görsel varlıklarını bağımsız grafik veya oyun varlığı paketleri olarak dağıtmak.
8. Telif hakkı ve eser sahipliği bildirimlerini kaldırmak veya değiştirmek.

## GitHub ve Açık Kaynak Durumu

Bu projenin GitHub üzerinde herkese açık olarak bulunması, otomatik biçimde açık kaynak lisansı verildiği anlamına gelmez.

Bu proje:

**MIT, Apache, GPL, Creative Commons veya başka bir açık kaynak lisansı altında yayımlanmamaktadır.**

Ayrı ve açık bir lisans verilmedikçe tüm hakları saklıdır.

Projenin resmî olarak erişime sunulan sürümünü kişisel amaçlarla oynama ve inceleme imkânı, kaynak kodları veya diğer özgün varlıkları yeniden yayımlama hakkı vermez.

Akademik, kurumsal veya ticari kullanım talepleri için önceden yazılı izin alınmalıdır.

**Kaynak gösterilmesi tek başına kullanım izni anlamına gelmez.**

---

# 13. English Documentation

## L’AI’brary: Guardian of the Universes

### An Artificial Intelligence Adventure Born from a Book and Learning Portal

**14 Universes · 14 Keepers · 14 Guardians · 14 Interactive Puzzles · 42 Concepts**

**2D Browser Game | AI Literacy | Interactive Learning**

## About the Game

**L’AI’brary: Guardian of the Universes** is an original browser-based educational adventure developed by **Ayhan Bozkurt**.

The game combines side-scrolling exploration, platforming, character interactions, guardian battles, and interactive artificial intelligence learning challenges.

The player controls **Elif**, who embarks on a journey to restore fourteen lost pages of a mysterious atlas.

Her companion **İbre** helps guide the adventure.

Each universe introduces a different artificial intelligence concept through its environment, keeper, guardian, and interactive puzzle.

## Core Gameplay

**Explore → Talk to the Keeper → Enter the Universe → Collect Concepts → Defeat the Guardian → Solve the Puzzle → Restore the Atlas Page**

## Main Features

- 3 chapters and 14 explorable universes
- 14 unique keeper characters
- 14 themed guardian encounters
- 14 interactive educational puzzles
- 42 collectible AI concepts
- 14 knowledge runes
- 84 collectible sparks
- Experience points and progression levels
- Equipment and unlockable abilities
- Quests and achievements
- Browser-generated audio
- Locally saved progress
- Keyboard, mouse, and touch controls
- HTML5 Canvas rendering
- Single-file browser architecture

## Chapter I — Introduction to AI Universes

### 1. Data Academy

Learn data analysis, mean, median, and sampling through an interactive numerical balancing challenge.

### 2. Search Islands

Explore binary search and problem-solving strategies by locating a hidden target among multiple possibilities.

### 3. Machine Learning

Experiment with decision boundaries and understand the difference between training performance and generalization.

### 4. AI Workshop

Explore rule-based classification and the challenges of generalizing to unseen examples.

### 5. AI Agents

Understand task planning, tool usage, and human approval through an agent workflow puzzle.

### 6. Natural Language Processing

Explore Turkish word segmentation and its relationship with tokenization.

## Chapter II — Models and Intelligent Systems

### 7. Deep Learning

Adjust neuron weights and observe how learning steps affect model outputs.

### 8. MLOps

Manage data drift and model retraining decisions in a simulated monitoring scenario.

### 9. Computer Vision

Apply image filters to pixel matrices and explore numerical convolution.

### 10. MCP & Advanced RAG

Select relevant and authorized information sources to construct a grounded response.

## Chapter III — Humans, Production and the Future

### 11. Invisible AI & Autonomous Businesses

Experiment with inventory planning and safety stock decisions.

### 12. Hybrid Intelligence

Balance automated decision-making with human oversight.

### 13. Prompt Engineering & Generative AI

Construct structured prompts and visualize the effects of temperature on token probabilities.

### 14. AI Risks, Ethics & the Future

Explore risk classification and responsible artificial intelligence through educational scenarios.

---

## Educational Philosophy

L’AI’brary aims to make artificial intelligence understandable through experimentation.

Its instructional approach combines:

**Storytelling:** Presenting abstract concepts through characters and meaningful situations.

**Experimentation:** Allowing users to change variables, test assumptions, and observe outcomes.

**Feedback:** Explaining results and connecting them with scientific concepts.

**Gamification:** Integrating quests, exploration, progression, battles, and collectible knowledge.

The interactive activities are educational implementations written in JavaScript.

They do not require an external language model and should not be confused with production-grade AI systems.

---

## Technical Architecture

| Component | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 |
| Application Logic | JavaScript |
| Rendering | Canvas 2D |
| Audio | Web Audio API |
| Storage | localStorage |
| Embedded Artwork | WebP Data URIs |
| Typography | Fraunces, Atkinson Hyperlegible |
| External AI API | Not required |
| Build Tools | Not required |

The main game implementation is contained in a single HTML document.

## Run Locally

Clone or download the repository.

Place the game file in the project directory as:

```text
index.html
```

Start a local server:

```bash
python3 -m http.server 8000
```

Open:

http://localhost:8000

The game can also be deployed using GitHub Pages.

No Node.js installation, external LLM API key, database, or build pipeline is required for the current game implementation.

---

## Copyright and Intellectual Property

**© 2026 Ayhan Bozkurt — AI’Han Academy**

**ALL RIGHTS RESERVED**

The original source code, game design, visual identity, characters, narrative, animations, educational content, interactive learning activities, promotional assets, and overall creative presentation of L’AI’brary: Guardian of the Universes are protected by applicable intellectual property laws.

Unless explicitly authorized in writing by the rights holder, no permission is granted to:

- Copy or redistribute original source code.
- Modify and republish the game.
- Rebrand or commercially exploit the project.
- Reuse original characters, graphics, or artistic assets.
- Incorporate protected content into other commercial products.
- Package or distribute original assets as standalone resources.
- Remove copyright notices or authorship information.

**Public availability on GitHub does not grant an open-source license.**

This project is not released under MIT, Apache, GPL, Creative Commons, or another open license.

Any educational, institutional, commercial, or redistribution use beyond the rights granted by applicable law requires prior written authorization.

Attribution alone does not constitute permission.

Third-party content remains subject to its respective rights and licensing terms.

---

# 14. İletişim ve Bağlantılar / Contact & Links

**Proje ve Eser Sahibi / Creator:** Ayhan Bozkurt

**Ekosistem / Ecosystem:** AI’Han Academy — L’AI’brary

### L’AI’brary Learning Portal
https://ayhanbzkrt.github.io/yzevreni/

### GitHub
https://github.com/ayhanbzkrt

### Kitapyurdu
https://www.kitapyurdu.com/yazar/ayhan-bozkurt/260288.html

### Medium
https://medium.com/@ayhanbzkrt

### LinkedIn
https://www.linkedin.com/in/ayhanbozkurt/

### YouTube
https://www.youtube.com/results?search_query=Ayhan+Bozkurt+AI%27Han+Academy

---

<div align="center">

**L’AI’brary: Evrenlerin Muhafızı**

*Kitaptan ve portaldan doğan yapay zekâ macerası.*

**© 2026 Ayhan Bozkurt / AI’Han Academy**

**All Rights Reserved.**

</div>
