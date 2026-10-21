<h1>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/brand/logo-dark.png">
    <img src=".github/brand/logo-light.png" alt="Duvisto" width="206">
  </picture>
</h1>

Web sitelerini gerçek Chromium görünümlerinde, gerçek cihaz emülasyonuyla yan yana açıp canlı kıyaslayan masaüstü uygulaması.

- Aynı siteyi telefon, tablet ve masaüstü ölçülerinde aynı anda izleyin; ya da farklı siteleri yan yana kıyaslayın.
- Panelleri bölün, her panele kendi koşullarını verin: koyu tema, yavaş ağ, konum, saat dilimi, dil, engellenen istekler.
- Konsol, ağ ve erişilebilirlik denetimi; PNG, PDF ve rapor çıktısı; görsel fark.

## İndir

En son sürüm: **[Releases](https://github.com/duvisto/duvisto/releases/latest)**

| Bilgisayar                         | Dosya                                 |
| ---------------------------------- | ------------------------------------- |
| Mac, Apple Silicon (M1 ve sonrası) | `Duvisto-X.Y.Z-arm64.dmg`             |
| Mac, Intel                         | `Duvisto-X.Y.Z-x64.dmg`               |
| Windows 10 / 11 (64 bit)           | `Duvisto-Setup-X.Y.Z-x64.exe`         |
| Ubuntu / Debian                    | `Duvisto-X.Y.Z-amd64.deb`             |
| Diğer Linux                        | `Duvisto-X.Y.Z-linux-x86_64.AppImage` |

Mac'te hangisi? Elma menüsü → Bu Mac Hakkında: "Çip: Apple M…" ise Apple Silicon, "İşlemci: Intel" ise Intel.

## İlk açılış

- **macOS:** Uygulamayı Applications klasörüne sürükleyip açın. Paket Apple tarafından doğrulanmıştır; "İnternet'ten indirildi" sorusuna **Aç** demeniz yeterli.
- **Windows:** Paket henüz imzasız; "Windows bilgisayarınızı korudu" ekranında **Ek bilgi → Yine de çalıştır**.
- **Ubuntu / Debian:** `.deb` dosyasına çift tıklayın ya da `sudo apt install ./Duvisto-*.deb`.
- **AppImage:** `chmod +x Duvisto-*.AppImage`, sonra çalıştırın.

## Güncelleme

Uygulama yeni sürümleri kendisi denetler ve uygulama içinden kurar (Yardım → Güncellemeleri denetle). macOS'ta 0.6.2 ve önceki sürümler imzasız olduğundan 0.6.3'ü bir kez elle indirin; sonrası otomatik.

## Sorun bildir

Bir hata mı buldunuz, bir öneriniz mi var? **[Sorun bildir](https://github.com/duvisto/duvisto/issues/new/choose)** (uygulamada: Yardım → Sorun bildir). Sürüm numarasını (Yardım → Hakkında) ve işletim sisteminizi yazmanız yeterli.

---

Bu depo yalnızca indirmeler, sürüm notları ve geri bildirim içindir.
