# 🛡️ ClamAV Test Süreci Belgesi | ClamAV Testing Document

Bu belge, ClamAV antivirüs sisteminin izole VM ortamında test edilmesini adım adım belgelemektedir.  
This document outlines the step-by-step testing of ClamAV antivirus in an isolated VM environment.

---

## ⚙️ Kurulum Komutları | Installation Commands

```bash
sudo apt install clamav clamav-daemon
sudo freshclam
