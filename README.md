<div align="center">
  <img src="https://img.icons8.com/color/96/000000/network-cable.png" alt="Logo">
  <h1>Ağ İzleme & Teşhis Aracı</h1>
  <p><b>LLDP ve CDP Paket Dinleyicisi (Portable)</b></p>
</div>

---

## 🚀 Proje Hakkında

**Ağ İzleme**, bir bilgisayarı bilmediğiniz bir ağ portuna veya switch'e bağladığınızda *"Ben şu an hangi switch'e ve hangi porta bağlıyım?"* sorusunu saniyeler içinde cevaplamak için geliştirilmiş taşınabilir bir Windows aracıdır.

Cisco Discovery Protocol (CDP) ve Link Layer Discovery Protocol (LLDP) paketlerini doğrudan ağ kartınız (Ethernet/Wi-Fi) üzerinden dinler, analiz eder ve şık bir arayüzle size sunar.

![Ekran Görüntüsü](https://img.shields.io/badge/Aray%C3%BCz-React-blue?style=for-the-badge&logo=react)
![Backend](https://img.shields.io/badge/Arka_Plan-Python-yellow?style=for-the-badge&logo=python)

### ✨ Özellikler

*   **Switch ve IP Tespiti:** Bağlı olduğunuz Switch'in adını ve yönetim IP adresini otomatik bulur.
*   **Port ve VLAN Bilgisi:** Hangi switch portuna (`Gi1/0/1`, `Fa0/1` vb.) ve hangi VLAN ID'sine üye olduğunuzu gösterir.
*   **Donanım Detayları:** Switch'in Chassis ID'sini (MAC adresi) ve tam işletim sistemi/model bilgisini analiz eder.
*   **Raporlama:** Tek tıkla "Ekran Görüntüsü Al" özelliği sayesinde o anki ağ raporunuzu resim (.png) olarak kaydeder.
*   **Taşınabilir (Portable):** Kurulum gerektirmeyen tek bir `AgIzleme.exe` dosyası ile anında çalışır.

---

## 🛠 Kurulum ve Kullanım

Yazılımın temel katmanda ağ trafiğini okuyabilmesi için sistemde **Npcap** sürücüsünün kurulu olması gerekmektedir. 

1. **Ön Hazırlık:** Eğer bilgisayarınızda daha önceden Wireshark vb. bir program kurulu değilse, bu depodaki `npcap-installer.exe` dosyasını çalıştırarak Npcap sürücüsünü kurun. (Bu işlem sadece ilk kullanımda gereklidir).
2. **Çalıştırma:** `AgIzleme.exe` dosyasına çift tıklayın.
3. **Dinleme:** Açılan arayüzden takılı olan Ağ Kartınızı seçin ve **Dinle** butonuna basın. (Kablo takılıysa veya switch cihazından paket geliyorsa saniyeler içinde veriler ekrana düşecektir.)

---

## 👨‍💻 Geliştirici

Bu araç, ağ analizi süreçlerini hızlandırmak ve pratikleştirmek amacıyla **Murat Erol** tarafından geliştirilmiştir.

🔗 [LinkedIn Profilim](https://www.linkedin.com/in/murat-erol1/) üzerinden benimle iletişime geçebilirsiniz. Geri bildirimleriniz ve fikirleriniz değerlidir!
