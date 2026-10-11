<div align="center">

# TruckersMP Mod

### TruckersMP Mod Manager Bypass

Local mods and vehicle compatibility for Euro Truck Simulator 2.

Euro Truck Simulator 2 için yerel modlar ve araç uyumluluğu.

![Version](https://img.shields.io/badge/version-1.0.17-27c8bb)
![Platform](https://img.shields.io/badge/platform-Windows_x64-0078d4)
![Distribution](https://img.shields.io/badge/distribution-single_EXE-555555)

**[Download v1.0.17 / v1.0.17 indir](https://github.com/dmryasin-95/tmp-bypass-mod-manager/releases/download/v1.0.17/TMP.Mod.exe)**

[English](#english) · [Türkçe](#turkce)

</div>

---

<a id="english"></a>

## English

TruckersMP Mod is a desktop launcher for using local ETS2 mods with TruckersMP and accessing the in-game Mod Manager.

This repository distributes the compiled application. Download **v1.0.17** from [Releases](https://github.com/dmryasin-95/tmp-bypass-mod-manager/releases/latest) and save `TMP.Mod.exe` as `TMP Mod.exe`. A [repository copy](TMP%20Mod.exe) is also available.

### Changes in v1.0.17

- Compatible accessory database (ADB) updates are detected automatically. Each new session rebuilds its part indices and uses the current record count.
- If the database changes during or after preparation, prepare a new session before playing.
- Routine updates that keep the supported database format do not require manual hash edits or a rebuilt EXE. A changed database format or game/DLL signatures may still need an application update.

Validation passed: 24 Python ADB/policy tests, 30 controller tests, 36 native C++ scenarios, and two database revisions with the same compiled EXE. Live multiplayer server acceptance was not tested.

### Requirements

| Component | Requirement |
| --- | --- |
| Operating system | 64-bit Windows |
| Game | Installed ETS2; current test target: **1.61.1.1** |
| Multiplayer | Installed official TruckersMP launcher; current test target: **0.7.7.14** |
| Permissions | Administrator permission when starting the watchers |
| Extra installation | No additional runtime installation required |

### Install and start

1. Close ETS2 before preparing a new session.
2. Download `TMP Mod.exe` and place it in `%APPDATA%\TruckersMP`.
3. Open the EXE and click **İzleyicileri başlat** (Start watchers). Approve the Windows administrator prompt.
4. Wait until the launcher shows **OYNA için hazır** (Ready to play).
5. Click **TruckersMP'yi aç**, then press **PLAY / OYNA** in the official TruckersMP launcher.
6. Select your mods and vehicle in the game.

> **Note:** Do not add bus mods or similar vehicle mods. Other players will see these vehicles as vanilla trucks in the game.

Closing the TruckersMP Mod window leaves an active adaptation running. To end that session, exit the game. **Beklemeyi iptal et** cancels preparation before the game starts. Use **Günlükleri aç** to inspect a failed run.

### Troubleshooting

| Symptom | Next step |
| --- | --- |
| The game is already running | Close ETS2, start the watchers, then launch a new session. |
| Administrator permission is required | Approve the elevation prompt when starting the watchers. |
| Preparation fails or configuration is rejected | Confirm **v1.0.17**, start a fresh session, and open the logs if the failure repeats. |
| The database changed after preparation | Prepare a new session; compatible database updates are handled automatically. |
| The game or TruckersMP update changes the database format or code signatures | Check for a newer application version and report the error message. |
| The window still shows a previous failure | Start a new preparation. The last run's status remains visible until a new run is recorded. |

---

<a id="turkce"></a>

## Türkçe

TruckersMP Mod, yerel ETS2 modlarını TruckersMP ile kullanmak ve oyun içindeki Mod Yöneticisi'ne erişmek için hazırlanmış bir masaüstü başlatıcısıdır.

Bu depoda derlenmiş uygulama yayınlanır. **v1.0.17** EXE'sini [Releases](https://github.com/dmryasin-95/tmp-bypass-mod-manager/releases/latest) bölümünden indir; `TMP.Mod.exe` dosyasını `TMP Mod.exe` adıyla kaydet. [Depodaki kopya](TMP%20Mod.exe) da kullanılabilir.

### v1.0.17 değişiklikleri

- Uyumlu aksesuar veri tabanı (ADB) güncellemeleri otomatik algılanır. Her yeni oturum parça indekslerini yeniden üretir ve güncel kayıt sayısını kullanır.
- Veri tabanı hazırlama sırasında veya sonrasında değişirse oyuna girmeden yeni oturum hazırla.
- Desteklenen veri tabanı biçimini koruyan normal güncellemelerde elle hash değiştirmek veya EXE'yi yeniden derlemek gerekmez. Veri tabanı biçimi ya da oyun/DLL imzaları değişirse uygulama güncellemesi gerekebilir.

Doğrulama başarılı: 24 Python ADB/politika testi, 30 denetleyici testi, 36 yerel C++ senaryosu ve aynı derlenmiş EXE ile iki veri tabanı sürümü. Canlı çok oyunculu sunucu kabulü test edilmedi.

### Gereksinimler

| Bileşen | Gereksinim |
| --- | --- |
| İşletim sistemi | 64-bit Windows |
| Oyun | Kurulu ETS2; güncel test hedefi: **1.61.1.1** |
| Çok oyunculu | Kurulu resmî TruckersMP başlatıcısı; güncel test hedefi: **0.7.7.14** |
| Yetki | İzleyiciler başlatılırken yönetici izni |
| Ek kurulum | Ek çalışma ortamı kurulumu gerekmez |

### Kurulum ve kullanım

1. Yeni oturum hazırlamadan önce ETS2'yi kapat.
2. `TMP Mod.exe` dosyasını indir ve `%APPDATA%\TruckersMP` klasörüne yerleştir.
3. EXE'yi aç, **İzleyicileri başlat** düğmesine bas ve Windows yönetici iznini onayla.
4. **OYNA için hazır** durumunu bekle.
5. **TruckersMP'yi aç** düğmesine bas, ardından resmî başlatıcıda **OYNA** seçeneğini kullan.
6. Modlarını ve aracını oyundan seç.

> **Not:** Otobüs gibi araç modlarını eklemeyin. Bu araçlar oyunda diğer oyunculara vanilla tır olarak görünür.

TruckersMP Mod penceresini kapatmak etkin uyarlamayı durdurmaz. Oturumu bitirmek için oyundan çık. **Beklemeyi iptal et**, oyun başlamadan önce hazırlığı iptal eder. Başarısız bir çalıştırmayı incelemek için **Günlükleri aç** düğmesini kullan.

### Sorun giderme

| Durum | Yapılacak işlem |
| --- | --- |
| Oyun zaten açık | ETS2'yi kapat, izleyicileri başlat ve yeni bir oyun oturumu aç. |
| Yönetici yetkisi gerekiyor | İzleyicileri başlatırken gelen yetki isteğini onayla. |
| Hazırlık veya yapılandırma başarısız | **v1.0.17** kullandığını kontrol et, yeni oturum aç; hata tekrarlanırsa günlükleri incele. |
| Hazırlıktan sonra veri tabanı değişti | Yeni oturum hazırla; uyumlu veri tabanı güncellemeleri otomatik işlenir. |
| Oyun veya TruckersMP güncellemesi veri tabanı biçimini ya da kod imzalarını değiştirdi | Yeni uygulama sürümünü kontrol et ve hata mesajını bildir. |
| Pencerede önceki hata hâlâ görünüyor | Yeni hazırlığı başlat. Son çalıştırmanın durumu, yeni kayıt oluşana kadar görünür. |

---

## File integrity / Dosya bütünlüğü

**TruckersMP Mod 1.0.17** · **9,639,424 bytes / bayt**

SHA-256:

```text
8cfdf8965dc007406a03178e8ddbd6bb8067532c9821149be291c912e9b374bc
```

```powershell
Get-FileHash -LiteralPath '.\TMP Mod.exe' -Algorithm SHA256
```

**Contact / İletişim:** Discord: **yasindemir**
