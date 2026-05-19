# 🛡️ TryHackMe Comprehensive Learning Journal & Operations Vault

<p align="center">
  <img src="https://img.shields.io/github/stars/ZeroSamurai/thm-learning-journal?style=for-the-badge&color=gold" alt="Stars">
  <img src="https://img.shields.io/github/forks/ZeroSamurai/thm-learning-journal?style=for-the-badge&color=blue" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/ZeroSamurai/thm-learning-journal?style=for-the-badge&color=green" alt="Last Commit">
  <br>
  <a href="https://buymeacoffee.com/KULLANICI_ADIN"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" alt="Buy Me A Coffee"></a>
</p>

Anlık olarak güncellenen bu depo, **TryHackMe** platformundaki siber güvenlik serüvenimin eksiksiz bir haritasıdır. Burada sadece basit çözümler değil; teorik altyapılar, asistan destekli özel çalışma notları, metodolojiler ve sızma testi raporları yer almaktadır.

> 🌍 **Language Notice:** Tüm içerikler hem **Türkçe (🇹🇷)** hem de global topluluk için **İngilizce (🇬🇧)** standartlarında hazırlanmaktadır.

---

## 🔒 VIP Premium Vault Nedir?
Bu repoda göreceğiniz 🔒 (Kilit) simgeli ileri seviye içerikler, zorlu CTF çözümleri ve özel sömürü (exploitation) senaryoları **Private VIP Repo** içerisinde yer alır. 
Cebinizden servet çıkmadan, sadece aylık küçük bir kahve aboneliği ile tüm gizli arşive ve güncellenen `.md` dosyalarına anında erişim sağlayabilirsiniz.

👉 **[VIP Kasa Erişimi İçin Buraya Tıklayın](https://buymeacoffee.com/KULLANICI_ADIN)**

---

## 📊 Live Metrics & Dashboard
*TryHackMe platformundaki güncel sızma testi ve gelişim istatistiklerim:*

| Kategori | İlerleme Durumu | Tamamlanan / Toplam |
| :--- | :---: | :---: |
| 🚀 Total Challenges | `██░░░░░░░░░░░░░░░░░░` | **14** / 494 |
| 🟢 Easy Challenges | `███░░░░░░░░░░░░░░░░░` | **13** / 175 |
| 🟡 Medium Challenges | `█░░░░░░░░░░░░░░░░░░░` | **1** / 217 |
| 🔴 Hard Challenges | `░░░░░░░░░░░░░░░░░░░░` | **0** / 102 |

---

## 🗺️ 1. Paths (Eğitim Yol Haritaları)
Siber güvenlik disiplinlerine göre yapılandırılmış, teorik ve pratik bütünlük içeren devasa THM eğitim patikaları.

| Patika Adı | Seviye | Dil | Durum | Notlar & Raporlar |
| :--- | :---: | :---: | :---: | :--- |
| **Pre-Security** | `Beginner` | 🇹🇷 / 🇬🇧 | 🟢 Tamamlandı | [Network Fundamentals](https://github.com/ZeroSamurai/thm-learning-journal/tree/main/Pre%20Security/Network%20Fundamentals) [How To Web Works](https://github.com/ZeroSamurai/thm-learning-journal/tree/main/Pre%20Security/How%20The%20Web%20Works)|
| **Introduction to Cyber Security** | `Beginner` | 🇹🇷 / 🇬🇧 | 🟢 Tamamlandı | [Siber Güvenliğe Giriş Günlüğü](./paths/intro-cyber/) |
| **SOC Level 1** | `Intermediate` | 🇬🇧 | 🟡 Devam Ediyor | [Log Analizi & Tehdit Avcılığı](./paths/soc-lvl-1/) |
| **Jr. Penetration Tester** | `Intermediate` | 🇬🇧 | 🔒 VIP | [Sızma Testi Metodolojileri (VIP)](https://buymeacoffee.com/KULLANICI_ADIN) |
| **Red Team Capstone** | `Advanced` | 🇬🇧 | 🔒 VIP | [İleri Seviye Active Directory Aktarımları (VIP)](https://buymeacoffee.com/KULLANICI_ADIN) |

---

## 📚 2. Modules (Uzmanlık Modülleri)
Konu bazlı kategorize edilmiş, her bir odanın teknik detayını ve arka plandaki çalışma mantığını açıklayan asistan destekli derinlemesine notlar.

### 🌐 Network Fundamentals (Ağ Temelleri)
- [x] 🟢 `Network Theory` | [İletişim Protokolleri & OSI Katmanları](./modules/networking/osi-model.md)
- [x] 🟢 `Packets & Frames` | [Wireshark ile Canlı Paket Analiz Teknikleri](./modules/networking/packet-analysis.md)

### 💻 Operating Systems (İşletim Sistemi Güvenliği)
- [x] 🟢 `Linux Fundamentals` | [Linux Dosya Sistemleri, İzinler & Ssh Sıkılaştırma](./modules/os/linux-fundamentals.md)
- [x] 🟢 `Windows Fundamentals` | [Windows Kayıt Defteri (Registry) & Yetki Yönetimi](./modules/os/windows-fundamentals.md)
- [ ] 🟡 `Active Directory Basics` | Active Directory Mimarisi ve Keşif Aşamaları *(Hazırlanıyor)*

### 🕵️‍♂️ Information Gathering & Recon (Keşif ve İstihbarat)
- [x] 🟢 `Nmap passive/active` | [Gelişmiş Port Tarama ve Firewall Atlama Betikleri](./modules/recon/nmap-deepdive.md)
- [ ] 🔒 `Subdomain Brute-Forcing` | Amass ve Gobuster ile Atak Yüzeyi Genişletme (VIP)
- [ ] 🔒 `OSINT Operations` | Açık Kaynak İstihbaratı ve Dijital Ayak İzi Takibi (VIP)

---

## 🎛️ 3. Networks (Büyük Ağ Simülasyonları)
TryHackMe üzerindeki kurumsal ağ yapılarının sızma testi operasyon analizleri.

| Ağ Adı | Zorluk | Hedef Sistem Sayısı | Durum | Operasyon Raporu |
| :--- | :---: | :---: | :---: | :--- |
| **Wreath** | `Medium` | 3 Pivot Host | 🔒 VIP | [Pivoting & Tünelleme Stratejileri](https://buymeacoffee.com/KULLANICI_ADIN) |
| **Hololo** | `Hard` | 5 Active Host | 🔒 VIP | [AD Domain Kompromizasyonu](https://buymeacoffee.com/KULLANICI_ADIN) |
| **Throwback** | `Enterprise` | 15+ Active Host | 🔒 VIP | [Kurumsal Ağ Sızma Testi Raporu](https://buymeacoffee.com/KULLANICI_ADIN) |

---

## 🎯 4. Challenges & Walkthroughs (CTF Makine Çözümleri)
Bağımsız sızma testi makinelerinin (Boot-to-Root) aşama aşama (Recon -> Foothold -> PrivEsc) çözümleri.

### 🟢 Easy Challenges (13 / 175)
- [x] `Pickle Rick` | Web Sızma Testi & Komut Çalıştırma (RCE) zafiyeti. -> [Raporu Oku](./challenges/easy/pickle-rick.md)
- [x] `Basic Pentesting` | Kaba kuvvet (Brute Force) ve zayıf kimlik doğrulama. -> [Raporu Oku](./challenges/easy/basic-pentesting.md)
- [x] `RootMe` | Dosya yükleme (File Upload) açıklığı üzerinden reverse shell. -> [Raporu Oku](./challenges/easy/rootme.md)

### 🟡 Medium Challenges (1 / 217)
- [x] `Kenobi` | Samba paylaşımı manipülasyonu ve SUID yetki yükseltme. -> [Raporu Oku](./challenges/medium/kenobi.md)
- [ ] `Vulnversity` | Özel form manipülasyonu ve Systemctl yetki yükseltme. *(Hazırlanıyor)*
- [ ] `Daily Bugle` | Joomla CMS sömürüsü ve SQL Injection adımları. 🔒 [VIP Sürüm](https://buymeacoffee.com/KULLANICI_ADIN)

### 🔴 Hard & Insane Challenges (0 / 102)
- [ ] `Brainpan` | Buffer Overflow (Bellek Taşması) ve Tersine Mühendislik. 🔒 [VIP Sürüm](https://buymeacoffee.com/KULLANICI_ADIN)
- [ ] `Game Zone` | SQLi üzerinden Jenkins sömürüsü ve SSH tünelleme. 🔒 [VIP Sürüm](https://buymeacoffee.com/KULLANICI_ADIN)

---

## 🛠️ Kullanılan Siber Güvenlik Cephaneliği
*Notlar ve çözümler esnasında aktif olarak kullanılan ve konfigüre edilen araçlar:*
`Kali Linux` | `Nmap` | `Burp Suite` | `Metasploit` | `Wireshark` | `Gobuster` | `John the Ripper` | `Hydra`

---
<p align="center">
  <i>Bu depo tamamen siber güvenlik topluluğuna bilgi sağlama amacı taşır. Buradaki tekniklerin izinsiz sistemlerde kullanılması yasal sorumluluk doğurur.</i>
</p>
