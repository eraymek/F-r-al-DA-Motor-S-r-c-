# 🚀 STM32 Tabanlı Özel Geliştirme Kartı ve Fırçalı DC Motor Sürücü

Bu proje, güç elektroniği ve gömülü sistemler disiplinlerini bir araya getirerek sıfırdan tasarlanmış bir **Fırçalı DC Motor Sürücü** ve **STM32F373RCT Geliştirme Kartı** projesidir. 

Proje kapsamında, endüstriyel standartlara uygun donanım tasarımı (Altium Designer) ve alt seviye donanım kontrolünü sağlayan C tabanlı gömülü yazılım geliştirme süreçleri yürütülmüştür.Tasarlanan sürücü kartına önceden tasarladığımız stm32f3 geliştirme kartı entegre edilerek kontrol sinyali harici karttan alınmıştır.Amaç pid kontrol yapmak olmasına rağmen meydana gelen overshootları bastırmak için yeterli pid tuning zamanı bulunmamış bu sebeple sadece p kontrol yapılmıştır.


---

## 🛠️ Teknik Özellikler ve Kazanımlar

### Donanım Tasarımı (Hardware)
* **Mikrodenetleyici:** STM32F373RCT (ARM Cortex-M4)
* **Tasarım Aracı:** Altium Designer
* **PCB Mimarisi:** Çok katmanlı (Multilayer) tasarım ve IPC standartlarına uygun özel kütüphane (footprint) oluşturma süreçleri.
* **Sürücü Topolojisi:** Güç elektroniği prensiplerine dayalı çift yönlü motor kontrolü sağlayan opamp kontrol devresi devresi.

### Gömülü Yazılım (Software)
* **Geliştirme Ortamı:** STM32CubeIDE
* **Dil:** C

---

## 📂 Depo (Repo) İçeriği

Bu repo, sistemin çalışması için gereken tüm donanım ve yazılım dosyalarını düzenli bir mimaride sunar:
