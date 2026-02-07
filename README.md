# Steam Kütüphane Yöneticisi

**Steam Kütüphane Yöneticisi**, Steam oyunlarınızın DLC (Ek İndirilebilir İçerik) paketlerini bulmanızı, yönetmenizi ve kütüphanenize kolayca eklemenizi sağlayan modern, taşınabilir (portable) bir Windows uygulamasıdır.

<p align="center">
  <img src="https://github.com/nyx47rd/steamkutuphaneyoneticisi/blob/4605fd3384119a59493a7b5521df65a2aaeda7e0/app_icon.png?raw=true" width="128" height="128" />
</p>

## 🌟 Özellikler

- **🔍 Hızlı Arama & Kurulum:** Oyun adı veya Steam AppID girerek saniyeler içinde DLC tespiti ve kurulumu.
- **🚀 Toplu Kurulum (Paralel):** Birden fazla oyunun AppID'sini veya adını listeleyerek aynı anda, hızlı bir şekilde kurulum yapabilme.
- **📂 Akıllı Dizin Yönetimi:** Steam kurulum yolunu otomatik tespit eder. İsterseniz ayarlardan manuel olarak (Gözat ile) belirleyebilirsiniz.
- **🗑️ Kütüphane Yönetimi:** Yüklü DLC dosyalarını görüntüleyebilir, seçilenleri veya tümünü tek tıkla silebilirsiniz.
- **⚡ Tek Dosya (Portable):** Kurulum gerektirmez. Tek bir `.exe` dosyası olarak çalışır.
- **🎨 Modern Arayüz:** Cyberpunk estetiğine sahip, Gold & Dark temalı, kullanıcı dostu tasarım.
- **🔄 Otomatik Güncellemeler:** Steam'i yeniden başlatma ve dosya doğrulama süreçlerini yönetir.

## 📥 Kullanım

1. **Uygulamayı İndirin:** `SteamLibraryManager.exe` dosyasını bilgisayarınıza indirin.
2. **Çalıştırın:** Dosyaya çift tıklayın. (Yönetici haklarına ihtiyaç duyabilir, gerekirse sağ tıklayıp "Yönetici olarak çalıştır" deyin).
3. **Kurulum Sihirbazı:** İlk açılışta uygulama Steam klasörünü otomatik bulur. Bulamazsa size soracaktır.
4. **DLC Ekleme:**
   - Arama kutusuna oyunun adını (örn: *Cyberpunk 2077*) veya AppID'sini (örn: *1091500*) yazın.
   - Listeden oyunu seçin veya doğrudan **KUR** butonuna basın.
   - İşlem bittiğinde Steam'i yeniden başlatmanız önerilecektir.

### Toplu Kurulum Nasıl Yapılır?
Sağ üst menüdeki **Toplu Kurulum** butonuna tıklayın. Açılan pencereye her satıra bir oyun gelecek şekilde listeyi yapıştırın:
```text
Cyberpunk 2077
Elden Ring
123456
Age of Empires IV
```
**Başlat** butonuna bastığınızda işlemler paralel olarak sırayla tamamlanacaktır.

## 🛠️ Teknik Gereksinimler

- **İşletim Sistemi:** Windows 10 veya Windows 11 (x64)
- **Gerekli Bileşen:** Microsoft Edge WebView2 Runtime (Windows'ta genellikle yüklüdür).

## ⚠️ Yasal Uyarı

Bu yazılım, Steam oyunları için 3. parti yapılandırma dosyalarını (`config/stplug-in`) yönetir. Yazılımın kullanımı tamamen kullanıcının sorumluluğundadır. Geliştirici, Steam hesabınızda oluşabilecek herhangi bir durumdan sorumlu tutulamaz.

---
*Keyifli oyunlar!*
