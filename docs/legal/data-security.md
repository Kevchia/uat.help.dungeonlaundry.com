---
title: Data Security
description: 咖米漾專業洗衣店 Data Security Policy
---

# 🔐 Data Security  
## 咖米漾專業洗衣店資料安全政策

品牌：**咖米漾專業洗衣店**  
公司：**被神眷顧的股份有限公司**

---

## 🛡️ 傳輸加密（Data in Transit）

所有透過咖米漾專業洗衣店電腦版網站與手機 Web View 進行的資料傳輸，均採用：

> **TLS 1.3 高強度加密技術**

TLS 1.3 是目前業界廣泛採用的安全傳輸協定，可有效降低資料在傳輸過程中遭攔截、竄改或竊取的風險，確保使用者與系統之間的通訊安全。

---

## ☁️ 雲端基礎架構（Cloud Infrastructure）

為確保服務穩定性、資料安全性與系統可用性，咖米漾專業洗衣店採用位於日本東京的雲端基礎架構。

我們的主要服務部署於：

- **Linode by Akamai**
- **Tokyo, Japan**
- **Equinix Data Center Service Provider**

此外，我們亦採用 **Cloudflare R2 Object Storage** 作為備份資料與物件儲存服務。

我們所採用或參考之雲端與基礎架構服務供應商，包括 **Linode by Akamai**、**Amazon Web Services (AWS)** 及 **Cloudflare**，均具備多項國際安全與隱私管理認證，包括：

- **SOC 2**
- **ISO/IEC 27001**
- **ISO/IEC 27017**
- **ISO/IEC 27018**
- **ISO/IEC 27701**

上述認證涵蓋資訊安全管理、雲端服務安全、個人資料保護、雲端隱私保護與隱私資訊管理等面向，有助於確保我們採用的基礎架構與雲端服務符合國際資安與隱私保護標準。

---

## 💾 資料備份與物件儲存（Backup & Object Storage）

為降低資料遺失風險並提升災難復原能力，咖米漾專業洗衣店定期進行資料備份。

備份資料儲存於：

- **Cloudflare R2 Object Storage**
- **Tokyo, Japan**

Cloudflare R2 作為雲端物件儲存服務，用於保存系統備份資料，協助我們在系統異常、設備故障或不可預期事件發生時，能夠進行資料還原與服務恢復。

---

## 🌏 災難復原與備援設計（Disaster Recovery & Redundancy）

為提升服務可靠性，我們採取以下措施：

- 定期備份系統與用戶資料
- 將備份資料儲存於獨立物件儲存服務
- 主要服務與備份儲存皆位於日本東京區域
- 定期檢視備份與復原流程

### 主要服務位置

- 🇯🇵 **日本東京（Tokyo, Japan）**

### 備份儲存位置

- 🇯🇵 **日本東京（Tokyo, Japan）**

此設計可降低單一系統故障造成的資料遺失風險，並協助咖米漾專業洗衣店在異常情況下盡快恢復服務。

---

## 🤝 合約服務商（Sub-Processors）

| 服務商 | 用途 | 地區 |
|--------|------|------|
| Linode by Akamai | 主要系統主機與雲端運算服務 | 日本東京 |
| Equinix | 資料中心服務供應商 | 日本東京 |
| Cloudflare R2 Object Storage | 備份資料與物件儲存 | 日本東京 |
| Amazon Web Services (AWS) | 雲端基礎服務 / 可能之備援或系統服務 | 依實際服務區域 |
| LINE Taiwan | 訊息通知與用戶溝通 | 台灣 / 日本 |

---

## 🏢 主要資料中心位置

- **Linode by Akamai**
  - Tokyo, Japan
  - Service Provider: Equinix

---

## 🔎 安全承諾

咖米漾專業洗衣店重視每一位使用者的資料安全與隱私保護。  
被神眷顧的股份有限公司作為營運公司，承諾：

- 採用業界標準加密技術保護資料傳輸
- 使用具備國際資安認證之雲端服務供應商
- 定期備份重要系統與用戶資料
- 將備份資料儲存於獨立雲端物件儲存服務
- 持續檢視並強化系統安全措施
- 僅在提供服務所需範圍內處理使用者資料

---

_Last updated: {{ git_revision_date_localized }}_