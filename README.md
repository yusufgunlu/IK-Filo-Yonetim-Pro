# İK ve Filo Yönetim Pro (v2.5.3)

<p align="center">
  <img src="assets/logo.png" alt="İK ve Filo Yönetim Pro" width="96" />
</p>

Kurumsal düzeyde **İnsan Kaynakları (İK)**, **Özlük & Çalışma İzni Takibi**, **1–31 Günlük Puantaj / Bordro (ÜHP)**, **Kurumsal Kaşe Stüdyosu** ve **Filo & Akaryakıt Yönetimi** sunan **Hibrit Masaüstü (Edge WebView2 + FastAPI)** Windows yazılımıdır.

---

## 📥 İndirme ve Kurulum (v2.5.3)

Programı kurmak için aşağıdaki doğrudan indirme bağlantısından veya **Releases** bölümünden kurulum dosyasını indirip çalıştırmanız yeterlidir:

- **Doğrudan İndir (Son Sürüm v2.5.3):** [**IK_Filo_Yonetim_Pro_Setup_v2.5.3.exe İndir**](https://github.com/yusufgunlu/IK-Filo-Yonetim-Pro/releases/download/v2.5.3/IK_Filo_Yonetim_Pro_Setup_v2.5.3.exe)
- **Sürüm Notları ve Tüm Yayınlar:** [GitHub Releases Sayfası](https://github.com/yusufgunlu/IK-Filo-Yonetim-Pro/releases/latest)
- **İşletim Sistemi:** Windows 10 / Windows 11 (64-bit)
- **Ek Gereksinim:** Yoktur (Python veya ek kütüphane kurulumu gerektirmez; tek tıkla kurulur).
- **Yönetici İzni:** Standart kullanıcı hesaplarında dahi yönetici yetkisi gerektirmeden kurulabilir; mevcut veritabanınız ve lisansınız korunur.

### Kurulum Adımları

1. **`IK_Filo_Yonetim_Pro_Setup_v2.5.3.exe`** dosyasını indirin ve çift tıklayarak çalıştırın.
2. Windows SmartScreen bilgi ekranı görünürse **Ek bilgi (More info) -> Yine de çalıştır (Run anyway)** seçeneğine tıklayın.
3. Kurulum sihirbazında **İleri -> Kur** adımlarını tamamlayın. Masaüstünüzde **İK ve Filo Yönetim Pro** kısayolu otomatik oluşturulur.
4. Mevcut kullanıcılar daha sonraki tüm sürümleri uygulama içindeki **Hakkında -> Güncellemeleri Denetle** ekranından tek tıkla indirip kurabilir.

---

## ⏳ 1 Aylık (30 Gün) Ücretsiz Deneme Sürümü ve Lisanslama

- **Otomatik Deneme Sürümü:** Program yeni bir bilgisayara kurulduğunda herhangi bir anahtar girmenize gerek kalmadan **30 günlük (1 ay) tam kapsamlı deneme sürümü** otomatik olarak başlar.
- Kalan deneme süresi giriş ekranında ve uygulama içi **Hakkında** bölümünde gösterilir.
- **Lisans Etkinleştirme:** Deneme süresi sonunda (veya dilediğiniz zaman) **Hakkında** ekranında görünen **Donanım Kimliği (`HWID`)** kodunuzu geliştiriciye ileterek cihazınıza özel süresiz veya süreli lisans anahtarınızı alabilirsiniz.

---

## 📌 Başlıca Özellikler (v2.5.3)

### 1. ⚡ Hibrit Masaüstü Mimarisi & Çoklu Firma Güvenliği
- **Edge WebView2 + FastAPI SPA** mimarisiyle sekme ve menü geçişlerinde sıfır donma, anlık tepki hızı.
- Birden fazla firmayı tek program üzerinden birbirinden izole şekilde yönetme; **Admin** ve **İK Temsilcisi** kullanıcı rolleri.

### 2. 👥 Personel Yönetimi, SGDP, 4/b Huzur Hakkı & Çalışma İzni Takibi
- Resmi **T.C. Kimlik No doğrulaması**, **7.765 kayıtlı resmi ISCO-08 / SGK meslek kodu kataloğu**, GVK m.31 engellilik indirimi, **Emekli (`02 - SGDP`)** ve **4/b Şirket Ortağı (`00 - SGK Muaf` Huzur Hakkı)** statüleri.
- **6735 s.K. Yabancı Çalışma İzni** bitiş takibi ve bitişe 30 gün kala otomatik Genel Bakış uyarısı.
- Excel/CSV aktarımlarında ve manuel kayıtlarda aylık asgari ücret tutarlarının otomatik **Asgari Ücret** olarak algılanması.

### 3. ⚖️ 1–31 Günlük Puantaj & SMMM Uyumlu Bordro (ÜHP) Motoru
- 28/29/30/31 çeken aylarda **SGK 30 gün / eksik gün kuralı**, kıst gün veya **319 Seri No.lu GVK tam istisna modu**, takvim günü / 30 gün saatlik mesai esası, `%150` Fazla Mesai, `%125` Fazla Sürelerle Çalışma ve `%200` Tatil/Özel Mesai hesabı.
- Brüt ↔ Net maaş çözücü, kümülatif GV dilimi takibi, **4857 m.30 engelli işveren SGK teşviki (%100)**, BES tam TL / kuruşlu yuvarlama, avans ve icra/kesinti takibi.
- Logolu **Ücret Hesap Pusulası (PDF)**, **Bordro İcmali (Excel)**, toplu **SMTP E-Posta** ve **WhatsApp (`Ctrl + V` otomatik PDF pano kopyalama)** gönderim desteği.

### 4. 🗂️ Masaüstü `İK PRO` Kurumsal Klasörleme & 30 Resmi Rapor
- Alınan tüm PDF ve Excel çıktılarının `Masaüstü\İK PRO\<Firma Adı>\Personel\<Ad Soyad>\{Bordro, Ücret Hesap Pusulası, Raporlar, Özlük Evrakları}` ve `<Firma Adı>\Raporlar` hiyerarşisinde dönem adıyla otomatik arşivlenmesi ve ilgili klasörde seçili gösterilmesi.
- **WhatsApp İhtar & Savunma İstemi (4857 m.25/II)**, **Şeffaf Kurumsal Kaşe Çıkarma & PDF Belge Kaşeleme Stüdyosu**, APHB, MUHSGK, İŞKUR, BES, Banka Maaş Ödeme Listesi ve Kıdem/İhbar tazminatı modülü.

### 5. 🚗 Filo ve Akaryakıt Yönetimi
- Araç ve UTTS kartları, muayene/sigorta/kasko uyarıları, KM bazlı yakıt alım takibi ve **Lt / 100 km tüketim analizi**.

---

## 👨‍💻 Geliştirici & Lisans İletişim

- **Geliştirici:** Yusuf Alperen Günlü
- **GitHub:** [github.com/yusufgunlu](https://github.com/yusufgunlu)
- **LinkedIn:** [linkedin.com/in/yusuf-alperen-günlü-856844165](https://www.linkedin.com/in/yusuf-alperen-g%C3%BCnl%C3%BC-856844165/)
