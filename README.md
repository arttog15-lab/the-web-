# 🌍 The Web - Orijinal TOEFL Sınaq İmtahanı Platforması

Bu layihə, istifadəçilərə real imtahan mühiti təcrübəsi bəxş edən, tam ekran interfeysinə və dinamik test sisteminə malik fərdiləşdirilmiş bir **TOEFL Sınaq İmtahanı** platformasıdır.

🔗 **Canlı Layihəni İzləyin:** [The Web - TOEFL İmtahanı](https://artogrulx.github.io/the-web-/)

---

## ✨ Özəlliklər

- **Orijinal YouTube İnteqrasiyası:** `Listening Section` (Dinləmə bölməsi) üçün birbaşa sual daxilinə yerləşdirilmiş, brauzer tərəfindən bloklanmayan xüsusi iFrame video pleyeri.
- **60 Dəqiqəlik Geri Sayım Taymeri:** Real imtahan şəraitini simulyasiya edən vizual zaman idarəetmə qutusu.
- **Təkmil Ötürmə (Skip) Sistemi:** 
  - `Skip (1 Sual Ötür)`: Cari sualı cavablandırmadan növbəti suala keçid.
  - `Skip All (Hamısını Ötür)`: Birbaşa imtahanın sonuna və yekun nəticə səhifəsinə keçid imkanı.
- **300,000 Dinamik Sual:** Alqoritmik olaraq generasiya edilən və brauzeri dondurmayan böyük akademik lüğət (`Vocabulary`) və qrammatika (`Grammar`) sual bazası.
- **CSS Əsaslı Tam Ekran Rejimi:** YouTube təhlükəsizlik alqoritmlərinin videonu bloklamasının (`Refused to connect`) qarşısını alan, bütün pəncərəni əhatə edən xüsusi dizayn mühiti.

---

## 🛠️ İstifadə Olunan Texnologiyalar

Bu layihə heç bir xarici kitabxana (library) və ya freymvork (framework) istifadə edilmədən, tamamilə **Pure (Vanilla) Web** texnologiyaları ilə yığılmışdır:

- **HTML5:** Struktur və media (iFrame) inteqrasiyası üçün.
- **CSS3:** Tam ekran təcrübəsi, adaptiv dizayn (responsive) və vizual effektlər üçün.
- **JavaScript (ES6):** Sual generasiyası, taymer idarəetməsi, "Skip" məntiqləri və performans optimizasiyası üçün.

---

## 🚀 Repozitoriyanın Strukturu

```bash
the-web-/
│
├── index.html     # İmtahan platformasının əsas kod quruluşu (HTML, CSS, JS birlikdə)
└── README.md      # Layihə haqqında ümumi məlumat sənədi
```

---

## 💻 Yerli Kompüterdə İşlətmək

Layihəni öz kompüterinizdə yoxlamaq üçün aşağıdakı addımları yerinə yetirin:

1. Repozitoriyanı klonlayın:
   ```bash
   git clone https://github.com
   ```
2. Layihə qovluğuna keçid edin:
   ```bash
   cd the-web-
   ```
3. `index.html` faylını istənilən müasir brauzerdə (Chrome, Edge, Firefox) açın.

---
📝 *Qeyd: Bu layihə davamlı olaraq inkişaf etdirilir və yeni TOEFL strukturları əlavə olunur.*
