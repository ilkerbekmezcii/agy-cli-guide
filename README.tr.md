🌍 [English](README.md) | [Türkçe](README.tr.md) | [Español](README.es.md)

# 🥧 Antigravity CLI (`agy`) — Genel Kullanım Kılavuzu

> **Google Antigravity yapay zeka iş akışları için klavye merkezli terminal arayüzü.**

<div align="center">

![Sürüm](https://img.shields.io/badge/version-1.0.16-blue)
![Lisans](https://img.shields.io/badge/license-Proprietary-red)

</div>

---

## 📚 İçindekiler

- [agy Nedir?](#agy-nedir)
- [Kurulum](#kurulum)
- [Hızlı Başlangıç](#hızlı-başlangıç)
- [Etkileşimli Mod (TUI)](#etkileşimli-mod-tui)
- [Yapılandırma](#yapılandırma)
- [Slash Komutları](#slash-komutları)
- [Temel Kısayollar](#temel-kısayollar)
- [İpuçları ve Hileler](#ipuçları-ve-hileler)
- [Kaynaklar](#kaynaklar)
- [Hızlı Başvuru Kartı](#hızlı-başvuru-kartı)

---

## agy Nedir?

**Antigravity CLI** (`agy`), Google Antigravity yapay zeka platformuyla terminal üzerinden hızlı ve verimli etkileşim kurmanızı sağlayan klavye merkezli bir arayüzdür.

---

## Kurulum

### 🪟 Windows (WinGet)
```powershell
winget install Google.AntigravityCLI
```

### 🪟 Windows (PowerShell)
```powershell
irm https://antigravity.google/cli/install.ps1 | iex
```

### 🍎 macOS / 🐧 Linux
```bash
curl -fsSL https://antigravity.google/cli/install.sh | bash
```

---

## Hızlı Başvuru Kartı

```
┌──────────────────────────────────────────────────────────┐
│                   🥧 agy Hızlı Başvuru                   │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  BAŞLAT                    YÖNET                         │
│  agy             .......  TUI Başlat      /resume        │
│  agy "prompt"    .......  Prompt ile      /fork          │
│  agy --help      .......  Yardım göster   /clear         │
│                                           /quit          │
│                                                          │
│  EDİTÖR                    İZLE                          │
│  @dosya          .......  Dosya referansı /agents        │
│  !komut          .......  Shell çalıştır  /tasks         │
│  Shift+Enter     .......  Yeni satır      /permissions   │
│  Escape          .......  Kes/Durdur                     │
│                                                          │
│  AYARLAR                   OTURUM                        │
│  /config         .......  Ayarlar Paneli  /rewind        │
│  /keybindings    .......  Kısayolları düzen /switch      │
│                                                          │
└──────────────────────────────────────────────────────────┘
```
