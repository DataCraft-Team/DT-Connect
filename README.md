<p align="center">
<img src="assets/logo.png" alt="DT Connect" width="120">
</p>

<h1 align="center">DT Connect</h1>

<p align="center">
<a href="https://github.com/DataCraft-Team/DT-Connect/releases/latest"><img src="https://img.shields.io/github/v/release/DataCraft-Team/DT-Connect?label=version&color=14b8a6" alt="version"></a>
<a href="https://github.com/DataCraft-Team/DT-Connect/releases"><img src="https://img.shields.io/github/downloads/DataCraft-Team/DT-Connect/total?color=14b8a6" alt="downloads"></a>
</p>

<div dir="rtl">

<p align="center"><b>اپ رسمی دیتاکرفت</b> برای ویندوز، اندروید، مک و لینوکس<br>فقط با لینک اشتراک‌تان وارد شوید و با یک لمس به سریع‌ترین سرور وصل شوید.</p>

## ⬇️ دانلود — نسخه‌ی 1.2.1

| سیستم | دانلود | برای چه کسی |
| --- | --- | --- |
| 🪟 **ویندوز ۱۰ و ۱۱** (۶۴ بیتی) | [**DT-Connect-Setup.exe**](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-Setup-1.2.1.exe) | همه‌ی کامپیوترهای ویندوزی |
| 🤖 **اندروید ۵ به بالا** | [**DT-Connect.apk**](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-android-universal.apk) | همه‌ی گوشی‌ها و تبلت‌های اندرویدی (یک فایل برای همه) |
| 🍎 **مک** با تراشه‌ی Apple (M1 و جدیدتر) | [**mac-arm64.pkg**](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-mac-arm64.pkg) | macOS 12 به بالا |
| 🍎 **مک** اینتل | [mac-x64.pkg](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-mac-x64.pkg) | macOS 12 به بالا |
| 🐧 **اوبونتو، دبیان، مینت، Pop!_OS** | [amd64.deb](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-linux-amd64.deb) · [arm64.deb](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-linux-arm64.deb) | |
| 🐧 **فدورا، RHEL، Rocky، AlmaLinux، openSUSE** | [x86_64.rpm](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-linux-x86_64.rpm) · [aarch64.rpm](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-linux-aarch64.rpm) | |
| 🐧 **آرچ، مانجارو، EndeavourOS** | [x64.pacman](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-linux-x64.pacman) · [aarch64.pacman](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-linux-aarch64.pacman) | |
| 📱 **آیفون و آیپد** | — | فعلاً نسخه‌ی iOS نداریم: لینک اشتراک را در **Streisand** یا **Happ** وارد کنید. |

**مک من کدام است؟** در منوی Apple گزینه‌ی **About This Mac** را بزنید: اگر جلوی Chip نوشته Apple M1 (یا M2، M3 و…)، فایل arm64 را بگیرید؛ اگر جلوی Processor نوشته Intel، فایل x64 را.

همه‌ی نسخه‌های قبلی در [صفحه‌ی Releases](https://github.com/DataCraft-Team/DT-Connect/releases) هستند.

## 🛠 نصب

**ویندوز:** فایل را اجرا کنید. اگر ویندوز پیام «Windows protected your PC» داد، روی **More info** و بعد **Run anyway** بزنید (فقط بار اول).

**اندروید:** فایل APK را باز کنید و اجازه‌ی نصب از این منبع را یک بار بدهید. اگر Play Protect هشدار داد، اول **More details** و بعد **Install anyway** را بزنید.

**مک:** فایل pkg را باز کنید. بار اول macOS جلوی آن را می‌گیرد: در **System Settings** بخش **Privacy & Security** را باز کنید و دکمه‌ی **Open Anyway** را بزنید. برای پروتکل OpenVPN روی مک، OpenVPN را با Homebrew نصب کنید.

**لینوکس:** در ترمینال، در پوشه‌ای که فایل را دانلود کرده‌اید:

</div>

```bash
# Ubuntu / Debian / Mint
sudo apt install ./DT-Connect-1.2.1-linux-amd64.deb
# Fedora / RHEL   (openSUSE: sudo zypper install ...)
sudo dnf install ./DT-Connect-1.2.1-linux-x86_64.rpm
# Arch / Manjaro
sudo pacman -U ./DT-Connect-1.2.1-linux-x64.pacman
# macOS, OpenVPN only
brew install openvpn
```

<div dir="rtl">

## 🔑 ورود

پیام تحویل سرویس در ربات [@DataCraftBot](https://t.me/DataCraftBot) یک **کد QR ورود** و یک **لینک ورود** دارد.

- **اندروید:** در صفحه‌ی اول «اسکن کد QR ورود» را بزنید. اگر QR روی همین گوشی است، «انتخاب عکس QR» و عکس را از گالری انتخاب کنید. یا روی لینک ورود بزنید.
- **ویندوز، مک، لینوکس:** روی لینک ورود کلیک کنید تا اپ باز شود و وارد شوید، یا فقط لینک اشتراک را در کادر لینک بچسبانید.

هر پلنی که خریده‌اید با همان اکانت در اپ کار می‌کند. هر دستگاه یکی از جاهای «تعداد دستگاه» اشتراک شما را می‌گیرد.


## 📸 تصاویر اندروید

<p align="center">
<img src="screenshots/android/01-welcome.png" alt="welcome" width="190">
<img src="screenshots/android/02-home.png" alt="home" width="190">
<img src="screenshots/android/03-connected.png" alt="connected" width="190">
<img src="screenshots/android/04-locations.png" alt="locations" width="190">
</p>
<p align="center">
<img src="screenshots/android/05-protection.png" alt="protection" width="190">
<img src="screenshots/android/06-account.png" alt="account" width="190">
<img src="screenshots/android/07-notices.png" alt="notices" width="190">
<img src="screenshots/android/08-connected-light.png" alt="connected light" width="190">
</p>

## 🛡 دانلود امن

- فقط از **همین صفحه** یا لینکی که ربات می‌فرستد دانلود کنید. فایلی که کسی در گروه یا کانال دیگری فرستاده ممکن است دستکاری شده باشد.
- کنار هر نسخه فایل [SHA256SUMS.txt](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/SHA256SUMS.txt) هست. عددی که دستور زیر برای فایل شما می‌دهد باید با عدد همان فایل در SHA256SUMS.txt یکی باشد.
- آدرس هیچ سروری داخل خود اپ نیست: سرورها، پروتکل‌ها و اطلاعیه‌ها فقط با لینک اشتراک خودتان می‌آیند.

</div>

```powershell
# Windows (PowerShell)
Get-FileHash .\DT-Connect-Setup-1.2.1.exe -Algorithm SHA256
```

```bash
# Linux
sha256sum DT-Connect-1.2.1-linux-amd64.deb
# macOS
shasum -a 256 DT-Connect-1.2.1-mac-arm64.pkg
```

<div dir="rtl">

## 🔒 حریم خصوصی

اپ برای ورود فقط نام کاربری، شناسه‌ی دستگاه، نام و نسخه‌ی سیستم عامل و نسخه‌ی اپ را می‌فرستد تا سقف دستگاه‌های اشتراک رعایت شود. گزارش خطا (لاگ) فقط وقتی فرستاده می‌شود که خودتان «گزارش مشکل» را بزنید، و رمزها، کلیدها و لینک‌ها پیش از ارسال از آن حذف می‌شوند.

## 💬 پشتیبانی

از داخل ربات [@DataCraftBot](https://t.me/DataCraftBot) یا از «تماس با پشتیبانی» در خود اپ.

</div>

---

### English

DT Connect is DataCraft's VPN app. Sign in with your subscription link alone, or scan the sign-in QR code from [@DataCraftBot](https://t.me/DataCraftBot).

| System | Download |
| --- | --- |
| Windows 10 / 11 (64-bit) | [DT-Connect-Setup-1.2.1.exe](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-Setup-1.2.1.exe) |
| Android 5.0+ | [DT-Connect.apk](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-android-universal.apk) (one file for every phone and tablet) |
| macOS 12+ | [Apple silicon](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-mac-arm64.pkg) · [Intel](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-mac-x64.pkg) |
| Debian / Ubuntu | [amd64](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-linux-amd64.deb) · [arm64](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-linux-arm64.deb) |
| Fedora / RHEL / openSUSE | [x86_64](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-linux-x86_64.rpm) · [aarch64](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-linux-aarch64.rpm) |
| Arch / Manjaro | [x64](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-linux-x64.pacman) · [aarch64](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/DT-Connect-1.2.1-linux-aarch64.pacman) |
| iPhone / iPad | Not available: use your subscription link in Streisand or Happ. |

Checksums: [SHA256SUMS.txt](https://github.com/DataCraft-Team/DT-Connect/releases/download/v1.2.1/SHA256SUMS.txt) · Older versions: [Releases](https://github.com/DataCraft-Team/DT-Connect/releases) · Open-source components: [THIRD-PARTY.md](THIRD-PARTY.md)

<p align="center"><sub>© DataCraft</sub></p>
