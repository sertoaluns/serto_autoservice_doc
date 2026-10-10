<div align="center">

# 🔧 Serto Auto Service

**Fully modular, metadata-driven workshop & mechanic ecosystem designed for FiveM / GTA V.**  
*FiveM / GTA V ekosistemi için tamamen modüler, metadata odaklı oto servis ve tamirhane sistemi.*

<br/>

![Stage](https://img.shields.io/badge/STAGE-CONCEPT%20%26%20DESIGN-orange?style=for-the-badge)
![Rockstar DMCA](https://img.shields.io/badge/ROCKSTAR%20DMCA-%25100%20SAFE-brightgreen?style=for-the-badge)

<br/>

### [English](#-english) | [Türkçe](#-türkçe)

</div>

---

## 🇬🇧 English

### Overview
**Serto Auto Service** is a comprehensive workshop management script designed to elevate automotive roleplay on FiveM servers. Featuring interactive mini-games, custom tablet interfaces, role hierarchy management, and modular shop configurations, it provides an all-in-one mechanic experience.

---

### 🚀 Key Features

* **Custom Mechanics & Tooling:** Dedicated repair pipelines, vehicle diagnostics, part assembly, and maintenance lifecycles.
* **Exclusive 3D Props:** High-fidelity workshop props, tools, engine components, and hand-held utility models.
* **Interactive Mini-Games:** Skill-check sequences and interactive task mini-games for component disassembly, repairs, and tuning.
* **Custom Workshop Items:** Unique inventory items representing spare parts, lubricants, mechanical toolkits, and diagnostic devices.
* **Dedicated Tablet Interface:** Built-in in-game tablet app to manage service tickets, invoices, stock inventory, and workshop tasks.
* **Modular Multi-Location & Blip System:** Fully adaptable coordinate and blip configuration. Set up unique work bays, tool benches, and interaction zones per mechanic shop.
* **Deep Hierarchy & Rank Progression:**
  * **Boss (Patron):** Full administrative control, employee management, and financial balance oversight.
  * **Master Mechanic (Usta):** Advanced repairs, dyno testing, and fine-tuning privileges.
  * **Journeyman (Kalfa):** Intermediate maintenance, tire changes, and routine service tasks.
  * **Apprentice (Çırak):** Basic cleaning, oil changes, part fetching, and training tasks.
* **Extensive `config.lua` & Discord Logging:**
  * Modular configuration allowing server owners to customize pricing, repair intervals, and job restrictions.
  * Real-time audit logs to track employee actions, stock usage, and cash flow.

---

### ⚙️ Installation & Configuration

1. Place `serto_autoservice` into your server's `resources` directory.
2. Import the required database tables (`sql/install.sql`) into your MySQL server.
3. Configure workshops, blips, discord webhooks, and ranks in `config.lua`:
   ```lua
   Config.Webhook = "YOUR_DISCORD_WEBHOOK_URL"
   Config.Mechanics = {
       ['bennys'] = {
           label = "Benny's Original Motor Works",
           blip = { id = 446, color = 5, scale = 0.8 },
           bossGrade = "boss"
       }
   }

Add ensure serto_autoservice to your server.cfg.

FiveM sunucuları için geliştirilmiş gelişmiş, etkileşimli ve tamamen özelleştirilebilir oto servis & mekanik altyapısı.

---

### 🚀 Öne Çıkan Özellikler

* **Özel Mekanik Sistemleri:** Ayrıntılı araç arıza tespiti, motor yenileme, parça sökme/takma ve bakım süreçleri.
* **Özel 3D Proplar:** Mekanik rolünü zenginleştiren yüksek kaliteli el aletleri, yedek parça modelleri, kaldırma liftleri ve atölye propları.
* **Etkileşimli Mini Oyunlar (Mini-Games):** Başarılı tamir, ayar ve parça montajı gerektiren beceri odaklı mini oyunlar (skill-check mekanikleri).
* **Özel Envanter İtemleri:** Servis süreçleriyle tam entegre çalışan yedek parçalar, motor yağları, alet çantaları ve arıza tespit cihazları.
* **Özel Mekanik Tablet Arayüzü:** İş emirlerini yönetme, fatura kesme, parça stoğu takip etme ve müşteri kayıtlarını tutma imkânı sunan modern tablet ekranı.
* **Özelleştirilebilir Mekan & Blip Sistemi:** Her tamirhane için bağımsız çalışma alanları, lift noktaları, tezgâhlar ve harita blipleri (istenen her mekanın içine özel olarak uyarlanabilir).

---

### 👥 Rütbe ve Yetki Hiyerarşisi

* **Patron:** Kasa yönetimi, çalışan alımı/çıkarımı, maaşlar ve tüm atölye ayarlarının tam kontrolü.
* **Usta:** İleri düzey motor/şanzıman tamirleri, performans ayarları ve kritik bakım işlemleri.
* **Kalfa:** Lastik, fren, yağ bakımları ve rutin onarım süreçleri.
* **Çırak:** Temel atölye düzeni, temizlik, parça taşıma ve çıraklık görevleri.

---

### ⚙️ Yapılandırma ve Log Takibi

* **`config.lua` ile Tam Özelleştirme:** Fiyatlandırmalar, tamir süreleri, mekan sınırları ve yetkiler sunucu sahibinin isteğine göre kolayca ayarlanabilir.
* **Çalışan Log Takibi:** Çalışanların yaptığı tüm işlemler, kullanılan yedek parçalar, faturalar ve kasa hareketleri Discord webhook üzerinden anlık olarak loglanır.

---

### 🛠️ Kurulum

1. Dosyaları sunucunuzun `resources` klasörüne ekleyin.
2. Gerekli veritabanı tablolarını (`sql/install.sql`) MySQL veritabanınıza içe aktarın.
3. `config.lua` üzerinden dükkan konumlarını, rütbeleri ve Discord webhook adresinizi tanımlayın.
4. `server.cfg` dosyanıza `ensure serto_autoservice` satırını ekleyin.
