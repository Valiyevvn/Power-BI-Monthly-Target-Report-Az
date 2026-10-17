# **Power BI \- Aylıq Hədəf və İcraat Hesabatı**

Bu layihədə şirkətlərdə satış komandasının və əməkdaşların aylıq performansını, hədəf icraatlarını (H/G faizi) daha rahat və vizual izləmək üçün interaktiv bir dashboard hazırlamışam.

Məqsəd idarəçilərin həm fərdi işçi bazında, həm də ümumi komanda üzrə göstəriciləri bir neçə kliklə rahatlıqla analiz edə bilməsidir.

# **Dashboard-da Nələr Var?**

* **İnteraktiv İşçi Profili:** Yuxarı hissədən istənilən əməkdaşı seçdikdə onun vəzifəsi, işə başlama tarixi, fotosu və ümumi H/G faizi anında yenilənir.  
* **3 Fərqli Analiz Paneli (Tabs):**  
  * **İşçinin hədəfi:** Seçilmiş şəxsin hədəfə nə qədər yaxınlaşdığını göstərən spidometr (Gauge) vizualı.  
  * **H/G faizi:** Əməkdaşın aylar üzrə performans artımını/düşüşünü göstərən dinamik qrafik.  
  * **Ümumi cədvəl:** Bütün heyətin satış, hədəf və faiz göstəricilərinin detallı siyahısı.  
* **Top 8 Performans Liderləri:** Şirkət üzrə H/G faizi ən yüksək olan ilk 8 işçinin vizual kartlar şəklində xüsusi sıralaması.

# **Nələrdən İstifadə Etmişəm?**

* **Power BI Desktop** — Məlumatların vizuallaşdırılması və hesabatın qurulması üçün.  
* **DAX** — H/G faizlərinin, dinamik KPI-ların və Top 8 sıralamasının dəqiq hesablanması üçün mürəkkəb ölçülər (measures) yazılıb.  
* **Power Query** — Data təmizlənməsi və cədvəllər arası əlaqələrin (Data Model) düzgün qurulması üçün.  
* **UI/UX Dizayn** — Dashboard-un göz yormayan, tünd və qızılı tonlarda (Dark/Gold theme) müasir görünüşü üçün özel konsept seçilib.

# **Layihəni Necə Açmaq Olar?**

1. Repozitoriyanı kopyalayın.  
2. `.pbix` faylını Power BI Desktop proqramında açaraq daxili model və DAX düsturlarını araşdıra bilərsiniz.

