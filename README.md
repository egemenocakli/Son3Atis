# Son 3 Atış — Gizlilik Politikası & Destek

**Son 3 Atış** balıkçı asistanı uygulamasının mağaza (App Store / Google Play) sayfaları için hazırlanmış statik site.

| Sayfa | Dosya | İçerik |
|---|---|---|
| Gizlilik Politikası | `index.html` | Toplanan veriler, kullanım amaçları, üçüncü taraflar, KVKK hakları, izinler |
| Tanıtım & Destek | `support.html` | Uygulama tanıtımı, özellikler, SSS, sorumluluk reddi, iletişim |

İki sayfa üstteki sekme çubuğuyla birbirine bağlıdır. Bağımlılık yoktur; tüm stil dosya içindedir. Sistem temasına göre karanlık/aydınlık görünür.

## GitHub Pages ile yayınlama

1. Bu klasörün içeriğini yeni bir **public** repoya kökten (root) push edin.
2. Repo → **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main` / `/ (root)`.
3. Birkaç dakika sonra site şu adreslerde yayında olur:
   - Gizlilik: `https://<kullanıcı>.github.io/<repo>/`
   - Destek: `https://<kullanıcı>.github.io/<repo>/support.html`

Mağaza formlarında **Privacy Policy URL** alanına ilk, **Support URL** alanına ikinci bağlantıyı verin.


## Güncelleme

- Politika metni değişince `index.html` içindeki **Son güncelleme** tarihini elle güncelleyin (sabit yazılıdır, otomatik değişmez).
- Uygulama ikonu `icon.png` — `android/app/src/main/ic_launcher-playstore.png` kopyasıdır.
- İletişim adresi her iki sayfada `eolabs.dev@gmail.com` olarak geçer.
