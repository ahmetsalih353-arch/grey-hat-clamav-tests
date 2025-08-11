# ClamAV Comparison Process / ClamAV Karşılaştırma Süreci

This document contains comparisons and observations made during the ClamAV testing process.  
Bu belge, ClamAV test sürecinde yapılan karşılaştırmaları ve gözlemleri içerir.

---

## 📦 Test Environment / Test Ortamı

- VM: Debian 12 (XFCE)
- ClamAV version: 1.2.0
- Tools used: `clamscan`, `freshclam`, `sigtool`

---

## 🔍 Compared Features / Karşılaştırılan Özellikler

| Feature / Özellik       | Description / Açıklama                                      | Notes / Notlar |
|------------------------|-------------------------------------------------------------|----------------|
| `clamscan`             | Manual scan command / Manuel tarama komutu                  | Fast but limited / Hızlı ama sınırlı |
| `clamd` + `clamdscan`  | Daemon-based scanning / Daemon tabanlı tarama               | Faster, RAM-friendly / Daha hızlı, RAM dostu |
| `sigtool`              | Signature analysis and creation / İmza analizi ve üretimi   | For advanced use / Gelişmiş kullanım için |

---

## 🧪 Test Findings / Test Bulguları

- `clamscan` showed high CPU usage but consistent results.  
  `clamscan` ile yapılan taramalarda CPU kullanımı yüksek, ancak sonuçlar tutarlıydı.

- `clamdscan` reduced system load thanks to daemon usage.  
  `clamdscan` ile daemon kullanımı sayesinde daha düşük sistem yükü gözlendi.

- `sigtool` successfully tested for custom signature creation.  
  `sigtool` ile özel imza üretimi başarılı şekilde test edildi.

---

## 📁 Archive Notes / Arşiv Notları

This document is part of the technical archive of ClamAV testing.  
Bu belge, ClamAV test sürecinin teknik arşiv parçasıdır.

Open to community contributions and feedback.  
Topluluk katkısı ve geri bildirimler için açıktır.
