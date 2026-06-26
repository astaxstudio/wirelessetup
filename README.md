<div align="center">

```
__        ___          _                    
\ \      / (_)_ __ ___| | ___  ___ ___     
 \ \ /\ / /| | '__/ _ \ |/ _ \/ __/ __|    
  \ V  V / | | | |  __/ |  __/\__ \__ \    
   \_/\_/  |_|_|  \___|_|\___||___/___/    
                      _               
  ___  ___| |_ _   _ _ __             
 / __|/ _ \ __| | | | '_ \            
 \__ \  __/ |_| |_| | |_) |           
 |___/\___|\__|\__,_| .__/            
                    |_|               
```

# 📶 WirelessSetup

**WiFi Setup Tool for Termux — by ™Astax Studio**

[![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)](https://python.org)
[![Termux](https://img.shields.io/badge/Termux-Android-black?style=for-the-badge&logo=android)](https://termux.dev)
[![PHP](https://img.shields.io/badge/PHP-8.x-purple?style=for-the-badge&logo=php)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge&logo=mysql)](https://mysql.com)
[![Groq](https://img.shields.io/badge/Groq-AI-green?style=for-the-badge)](https://groq.com)
[![License](https://img.shields.io/badge/License-MIT-red?style=for-the-badge)](LICENSE)

🌐 [wirelessetup.xo.je](https://wirelessetup.xo.je)

</div>

---

## 🇬🇧 English

### What is WirelessSetup?
WirelessSetup is a powerful **WiFi configuration CLI tool** that runs on **Termux (Android)**. It automatically detects your router model, analyzes your network with **Groq AI**, and guides you through the full PPPoE/WiFi setup process.

### ✨ Features
- 🔐 **User Authentication** — Login via [wirelessetup.xo.je](https://wirelessetup.xo.je) (MySQL backend)
- 🤖 **AI Analysis** — Groq AI detects if setup is complete or missing
- 📡 **Auto Router Detection** — Supports TP-Link, ZTE, Huawei, Cudy, Technicolor, ASUS, D-Link and more
- ⚠️ **SETUP FAILED Alert** — Instantly shows if configuration is missing
- 💾 **Local Logging** — Saves all setups to `kurulum_kayit.txt`

### 🚀 Quick Start

```bash
# Install dependencies
pkg install python termux-api nano
pip install requests

# Run
python wirelessetup.py
```

### ⚙️ Configuration
1. Get a free Groq API key → [console.groq.com](https://console.groq.com)
2. Open `wirelessetup.py` and replace `YOUR_GROQ_API_KEY`
3. Register at [wirelessetup.xo.je](https://wirelessetup.xo.je)
4. Run and enjoy!

---

## 🇹🇷 Türkçe

### WirelessSetup Nedir?
WirelessSetup, **Android üzerinde Termux** ile çalışan güçlü bir **WiFi kurulum CLI aracıdır**. Router modelini otomatik tespit eder, **Groq AI** ile ağınızı analiz eder ve PPPoE/WiFi kurulum sürecinde sizi adım adım yönlendirir.

### ✨ Özellikler
- 🔐 **Kullanıcı Doğrulama** — [wirelessetup.xo.je](https://wirelessetup.xo.je) üzerinden giriş (MySQL)
- 🤖 **AI Analizi** — Groq AI kurulumun eksik mi tamamlanmış mı olduğunu tespit eder
- 📡 **Otomatik Modem Tespiti** — TP-Link, ZTE, Huawei, Cudy, Technicolor, ASUS, D-Link ve daha fazlası
- ⚠️ **KURULUM FAILED Uyarısı** — Yapılandırma eksikse anında gösterir
- 💾 **Yerel Kayıt** — Tüm kurulumları `kurulum_kayit.txt`'e kaydeder

### 🚀 Hızlı Başlangıç

```bash
# Gerekli paketleri yükle
pkg install python termux-api nano
pip install requests

# Çalıştır
python wirelessetup.py
```

### ⚙️ Yapılandırma
1. Ücretsiz Groq API key al → [console.groq.com](https://console.groq.com)
2. `wirelessetup.py` aç ve `YOUR_GROQ_API_KEY` yerine key'ini yaz
3. [wirelessetup.xo.je](https://wirelessetup.xo.je) adresinden kayıt ol
4. Çalıştır ve kullan!

---

## 🇩🇪 Deutsch

### Was ist WirelessSetup?
WirelessSetup ist ein leistungsstarkes **WiFi-Konfigurationstool für die Kommandozeile**, das auf **Termux (Android)** läuft. Es erkennt automatisch dein Router-Modell, analysiert dein Netzwerk mit **Groq AI** und führt dich durch die vollständige PPPoE/WiFi-Einrichtung.

### ✨ Funktionen
- 🔐 **Benutzerauthentifizierung** — Anmeldung über [wirelessetup.xo.je](https://wirelessetup.xo.je) (MySQL)
- 🤖 **KI-Analyse** — Groq AI erkennt ob die Einrichtung vollständig oder unvollständig ist
- 📡 **Automatische Router-Erkennung** — TP-Link, ZTE, Huawei, Cudy, Technicolor, ASUS, D-Link und mehr
- ⚠️ **SETUP FAILED Warnung** — Zeigt sofort an wenn die Konfiguration fehlt
- 💾 **Lokale Protokollierung** — Speichert alle Setups in `kurulum_kayit.txt`

### 🚀 Schnellstart

```bash
# Abhängigkeiten installieren
pkg install python termux-api nano
pip install requests

# Starten
python wirelessetup.py
```

### ⚙️ Konfiguration
1. Kostenlosen Groq API-Schlüssel holen → [console.groq.com](https://console.groq.com)
2. `wirelessetup.py` öffnen und `YOUR_GROQ_API_KEY` ersetzen
3. Registrieren auf [wirelessetup.xo.je](https://wirelessetup.xo.je)
4. Starten und genießen!

---

## 📁 Project Structure

```
wirelessetup/
├── python/
│   └── wirelessetup.py      ← Run this on Termux
└── api/
    ├── login.php             ← Upload to InfinityFree htdocs/api/
    └── database.sql          ← Import via phpMyAdmin
```

---

## 🖥️ Supported Routers

| Brand | Status |
|-------|--------|
| TP-Link | ✅ |
| ZTE | ✅ |
| Huawei | ✅ |
| Cudy | ✅ |
| Technicolor | ✅ |
| ASUS | ✅ |
| D-Link | ✅ |
| Tenda | ✅ |
| Netgear | ✅ |
| TTNet | ✅ |
| Superonline | ✅ |
| Others | ⚠️ Manual |

---

## 🔄 How It Works

```
[ Login ] → [ Detect Network ] → [ Detect Router ] → [ Groq AI Analysis ]
                                                              ↓
                                              ┌─────────────────────────────┐
                                              │  SETUP FAILED?              │
                                              │  → Enter AD, ŞİFRE,         │
                                              │    GÜVENLİK, PPPoE info     │
                                              │  → DEVAM → Apply Setup      │
                                              └─────────────────────────────┘
```

---

<div align="center">

**Made with ❤️ by ™Astax Studio**

🌐 [wirelessetup.xo.je](https://wirelessetup.xo.je)

</div>
