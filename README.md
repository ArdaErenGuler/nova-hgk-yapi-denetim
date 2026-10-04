# Nova HGK Yapı Denetim — Taslak Web Sitesi

Nova HGK Yapı Denetim Ltd. Şti. için hazırlanan taslak site. Müşteriye tasarımı göstermek
içindir, yayına hazır değildir.

`insaat-ornek` deposundaki `01-kurumsal` şablonundan uyarlandı. Sayfa düzeni kurumsal inşaat
sitelerine yaklaştırıldı: telefon şeridi, kayan slayt, sayaçlar, yuvarlak ikonlu hizmetler,
fotoğraflı kartlar, WhatsApp düğmesi. Renkler gece laciverti + kehribar.

## Açma

Derleme gerekmez. `index.html` dosyasını çift tıklamak yeterli. Yazı tipi, görsel ya da betik
dışarıdan çekilmez.

Yerel sunucuyla açmak için: `npx serve -l 4182 .`

## Müşteriyle netleştirilecekler

- **Logo:** Sitedeki amblem taslaktır (`gorseller/logo.svg`, `favicon.svg`). Firmanın kendi
  logosu kullanılacaksa başlıktaki ve alt bilgideki `marka-amblem` SVG'si değiştirilir.
- **İletişim bilgileri:** Telefon, adres ve e-posta firmanın eski sitesinin (novahgk.com,
  şu an kapalı) arama motoru kayıtlarından alındı. Güncel olmayabilir.
- **"20+ yıllık tecrübe" sayacı:** Eski sitedeki "2004'ten beri" ifadesine dayanıyor, teyit edilmeli.
- **WhatsApp düğmesi:** Numara belli olmadığı için şimdilik iletişim bölümüne iniyor.
- **KVKK metni** yok, formdaki onay kutusu göstermelik.
- **İletişim formu** bir yere bağlı değil, gönderince uyarı gösterir.

## Renkler

`style.css` dosyasının başındaki `:root` bloğundan değişir.

| Değişken | Renk | Kullanım |
| --- | --- | --- |
| `--marka` | `#e6a425` | Düğmeler, vurgular |
| `--mavi` | `#17406d` | Süreç bölümü, ikonlar, bağlantılar |
| `--gece` | `#0c1726` | Başlık, kahraman alan, koyu bölümler |

## Fotoğraflar

`gorseller/` klasöründeki fotoğraflar Unsplash'ten, `insaat-ornek` deposundan alındı.
Firmanın kendi şantiye fotoğrafları geldiğinde aynı dosya adlarıyla üzerine yazmak yeterli.
