# 🛡️ ClamAV Test Süreci | ClamAV Testing Workflow

Bu repo, ClamAV antivirüs sisteminin izole bir VM ortamında test edilmesini belgelemektedir.  
Amaç, zararlı dosya simülasyonlarıyla ClamAV'ın tepki süresini, log çıktısını ve sistem etkisini gözlemlemektir.

This repository documents the testing of ClamAV antivirus in an isolated VM environment.  
The goal is to observe ClamAV’s response time, log output, and system impact using simulated malicious files.

---

## ⚙️ Kurulum | Installation

ClamAV'ı kurmak ve güncellemek için aşağıdaki komutları kullanın:  
Use the following commands to install and update ClamAV:
## 📁 Belgeler | Documents

- [ClamAV Test Süreci / Test Process](clamav-testleri.md)
- [ClamAV Log Analizi / Log Analysis](clamav-log-analizi_log-analysis.md)
- [ClamAV Karşılaştırma Süreci / Comparison Process](clamav-karsilastirma_comparison.md)
```bash
README güncellendi: Belgeler bölümü eklendi / README updated: Documents section added
Bu bölüm, ClamAV test sürecine ait belgeleri içerir.  
This section contains documents related to the ClamAV testing process.
sudo apt install clamav clamav-daemon
sudo freshclam
