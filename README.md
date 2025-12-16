# 📺 YTNK TV - Akıllı Eğitim Asistanı (Smart Education Bot)

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)
![Tampermonkey](https://img.shields.io/badge/Platform-Tampermonkey-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Durum-Stabil%20(V31)-blue?style=for-the-badge)

Bu proje, **YTNK TV** platformundaki zorunlu eğitim videolarını izleme sürecini optimize etmek, arka planda kesintisiz oynatma sağlamak ve sadece zorunlu olan dersleri otomatik olarak tamamlamak için geliştirdiğim bir kullanıcı betiğidir (UserScript).

---

## 🚀 Projenin Amacı

Eğitim platformlarındaki uzun süreli videoları bilgisayar başında beklemeden tamamlamak ve sürekli çıkan "Devam Et" uyarılarıyla uğraşmamak için bu otomasyonu geliştirdim. Sistem, sunucu taraflı hız korumalarına takılmadan **%100 güvenli** bir şekilde çalışır.

## ✨ Temel Özellikler

### 🛡️ Tam Arka Plan Koruması (Focus Guard)
Tarayıcı sekmesini değiştirdiğinizde veya başka bir pencereye geçtiğinizde video **asla durmaz**. Script, siteye sürekli "Kullanıcı hala burada" sinyalleri gönderir.

### ⭐ Akıllı Yıldız Avcısı (Smart Star Hunter)
Sıradaki tüm videoları körü körüne izlemek yerine, listedeki **zorunlu (*)** işaretli dersleri tarar ve sadece onları izler. Gereksiz içerikleri atlar.

### 🔇 Konfor Modu
* **Otomatik Sessize Alma:** Video başladığında sesi otomatik kısar.
* **PiP (Picture-in-Picture):** Tek tuşla videoyu yüzen pencereye alır.
* **Sayaç:** Videonun gerçek bitiş saatini panelde gösterir.

### 🤖 Gelişmiş Otopilot
* "Lütfen notunuzu yazınız" gibi açılır pencereleri (popup) otomatik kapatır.
* Video bittiğinde otomatik olarak bir sonraki zorunlu derse geçer.
* Sunucu ile senkronize çalışarak "Hile tespit edildi" hatalarını önler (1.0x Hız Koruması).

---

## 🛠️ Kurulum

Bu scripti kullanmak için tarayıcınızda bir script yöneticisine ihtiyacınız var.

1. **Tampermonkey** eklentisini tarayıcınıza kurun ([Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) / [Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)).
2. Tampermonkey simgesine tıklayın ve **"Yeni Script Ekle"** deyin.
3. Bu repodaki `script.js` dosyasının içeriğini kopyalayın ve editöre yapıştırın.
4. `Ctrl + S` ile kaydedin.
5. YTNK TV'ye girin, panel otomatik olarak açılacaktır.

---

## 🖥️ Ekran Görüntüleri

| Kontrol Paneli | Çalışma Mantığı |
|----------------|-----------------|
| *Panelin ekran görüntüsünü buraya ekleyebilirsin* | Script, sağ menüdeki (*) işaretli dersleri hedef alır ve video bitince otomatik geçiş yapar. |

---

## ⚠️ Yasal Uyarı & Sorumluluk Reddi

Bu proje tamamen **eğitim ve kişisel kullanım amaçlı** geliştirilmiştir.
* Bu scripti kullanarak platformun kullanım koşullarını ihlal ediyor olabilirsiniz.
* Oluşabilecek herhangi bir hesap erişim sorunundan veya yasal durumdan geliştirici sorumlu değildir.
* Script, sunucuya zarar verecek veya sistemi manipüle edecek (hızlandırma hilesi vb.) zararlı kodlar içermez; sadece kullanıcı etkileşimini simüle eder.

---

## 👨‍💻 Geliştirici

**[Emirhan Bıçakcı & AeroDLL]**

*Bu projeyi geliştirmemdeki motivasyon, tekrarlayan görevleri otomatize ederek zaman verimliliği sağlamaktır.*

---

<div align="center">
  <sub>Made with ❤️ and ☕ by [AeroDLL]</sub>
</div>
