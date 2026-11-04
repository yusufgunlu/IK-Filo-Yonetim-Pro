# İK ve Filo Yönetim Pro (v2.5.0)

<p align="center">
  <img src="assets/logo.png" alt="İK ve Filo Yönetim Pro" width="96" />
</p>

Kurumsal düzeyde **İnsan Kaynakları (İK)**, **Özlük & Mevzuat Uyumluluğu**, **1–31 Günlük Puantaj / Bordro (ÜHP)** ve **Filo & Akaryakıt Yönetimi** sunan Windows masaüstü yazılımıdır.

---

## 📥 İndirme ve Kurulum (v2.5.0)

Programı kurmak için bu depodaki veya **Releases** bölümündeki kurulum dosyasını indirip çalıştırmanız yeterlidir:

- **Doğrudan İndir (Kurulum Paketi):** [**IK_Filo_Yonetim_Pro_Setup_v2.5.0.exe İndir**](https://github.com/yusufgunlu/IK-Filo-Yonetim-Pro/releases/download/v2.5.0/IK_Filo_Yonetim_Pro_Setup_v2.5.0.exe)
- **İşletim Sistemi:** Windows 10 / Windows 11 (64-bit)
- **Ek Gereksinim:** Yoktur (Python veya ek kütüphane kurulumu gerektirmez; tek tıkla kurulur).
- **Yönetici İzni:** Standart kullanıcı hesaplarında dahi yönetici yetkisi gerektirmeden kurulabilir.

### Kurulum Adımları

1. **`IK_Filo_Yonetim_Pro_Setup_v2.5.0.exe`** dosyasını indirin ve çift tıklayarak çalıştırın.
2. Windows SmartScreen bilgi ekranı görünürse **Ek bilgi (More info) -> Yine de çalıştır (Run anyway)** seçeneğine tıklayın.
3. Kurulum sihirbazında **İleri -> Kur** adımlarını tamamlayın. Masaüstünüzde **İK ve Filo Yönetim Pro** kısayolu otomatik oluşturulur.
4. Programı ilk kez açtığınızda kendi firmanızı ve yönetici (`Admin`) hesabınızı tanımlayarak hemen kullanmaya başlayabilirsiniz.

---

## ⏳ 1 Aylık (30 Gün) Ücretsiz Deneme Sürümü ve Lisanslama

- **Otomatik Deneme Sürümü:** Program yeni bir bilgisayara kurulduğunda herhangi bir anahtar girmenize gerek kalmadan **30 günlük (1 ay) tam kapsamlı deneme sürümü** otomatik olarak başlar.
- Kalan deneme süresi giriş ekranında ve uygulama içi **Hakkında** bölümünde gösterilir.
- **Lisans Etkinleştirme:** Deneme süresi sonunda (veya dilediğiniz zaman) giriş ekranındaki **🔑 Lisans Gir** ya da **Hakkında -> 🔑 Lisans Anahtarı Gir / Güncelle** bölümünde görünen **Donanım Kimliği (`HWID`)** kodunuzu geliştiriciye ileterek cihazınıza özel süresiz veya süreli lisans anahtarınızı alabilirsiniz.

---

## 📌 Başlıca Özellikler

### 1. 🏢 Çoklu Firma Desteği ve Rol Bazlı Güvenlik

- Birden fazla firmayı tek program üzerinden birbirinden izole şekilde yönetme.
- **Admin** ve **İK Temsilcisi** kullanıcı rolleri, güvenli parola saklama ve isteğe bağlı oturum hatırlama.

### 2. 👥 Personel Yönetimi, Emekli (SGDP) Statüsü ve Excel Aktarımı

- Resmi **T.C. Kimlik No doğrulaması**, **7.765 kayıtlı resmi ISCO-08 / SGK meslek kodu kataloğu**, GVK m.31 engellilik indirimi dereceleri ve **Emekli (`02 - SGDP`)** çalışan işaretlemesi.
- İşten ayrılış kodları (SGK 01–50), yeniden işe alımda geçmiş hizmet dönemlerini koruma ve 30 günlük geri dönüşüm kutusu.
- Matbu Excel şablonu ile toplu personel içe/dışa aktarma.

### 3. 📝 İzin Yönetimi ve Resmi Tatil (UBGT) Takvimi

- Firma çalışma düzenine (**6 gün / Pazar tatil** veya **5 iş günü / Cumartesi-Pazar tatil**) ve resmi/dini bayram takvimine göre otomatik net izin günü ve işe dönüş tarihi hesabı.
- Kıdem ve yaş kurallarına (18 yaş altı / 50 yaş üstü en az 20 gün) uyumlu canlı yıllık izin bakiyesi ve 3 imzalı resmi PDF izin formu.

### 4. ⏱️ 1–31 Günlük Puantaj & Mevzuata Uygun Bordro Motoru

- 28/29/30/31 çeken aylarda **SGK 30 gün / eksik gün kuralına** tam uyum.
- Normal (`01 - 4/a`) ve **Emekli (`02 - SGDP`: %7,5 işçi + %24,75 işveren, %0 işsizlik)** bordro hesaplaması.
- Brüt ↔ Net maaş çözücü, kümülatif gelir vergisi dilimi takibi, asgari ücret GV/DV istisnası, fazla mesai, eksik saat, yol/yemek, prim, avans, BES ve icra/diğer kesinti kalemleri.
- Logolu **Ücret Hesap Pusulası (PDF)**, **Bordro İcmali (Excel)**, **E-Posta (SMTP)** ve **WhatsApp** gönderim desteği.

### 5. 📁 Özlük Dosyası Takibi, Otomatik Klasörleme & Rapor Merkezi

- 4857 s.K. m.75 kapsamında özlük belgesi kontrolü, geçerlilik süresi uyarıları, uygunluk PDF/Excel raporları.
- Alınan tüm PDF ve Excel çıktılarının `Masaüstü\İK PRO\<Firma Adı>\...` altında personel ve dönem bazında otomatik klasörlenmesi.
- APHB kontrol listesi, Eksik Gün, İŞKUR İşgücü Çizelgesi, İşyeri Bilgi Formu ve **Kıdem / İhbar / Yıllık İzin Ücreti** hesaplama modülü.

### 6. 🚗 Filo ve Akaryakıt Yönetimi

- Araç ve UTTS kartları, KM bazlı yakıt alım takibi, **Lt / 100 km tüketim analizi** ve grafikli Excel akaryakıt gider raporu.

---

## 👨‍💻 Geliştirici & Lisans İletişim

- **Geliştirici:** Yusuf Alperen Günlü
- **LinkedIn:** [linkedin.com/in/yusuf-alperen-günlü-856844165](https://www.linkedin.com/in/yusuf-alperen-g%C3%BCnl%C3%BC-856844165/)
