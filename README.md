# Nova HGK Yapı Denetim — Taslak Web Sitesi

Nova HGK Yapı Denetim Ltd. Şti. için hazırlanan taslak site. Müşteriye tasarımı göstermek
içindir, yayına hazır değildir.

`insaat-ornek` deposundaki `01-kurumsal` şablonundan uyarlandı: koyu zemin, serif başlıklar,
uzun tek sayfa. Renkler gece laciverti + kehribar olarak değiştirildi, içerik yapı denetime
göre yeniden yazıldı.

## Açma

Derleme gerekmez. `index.html` dosyasını çift tıklamak yeterli. Yazı tipi, görsel ya da betik
dışarıdan çekilmez.

Yerel sunucuyla açmak için: `npx serve -l 4182 .`

## Müşteriyle netleştirilecekler

- **Logo:** Sitedeki amblem taslaktır (`gorseller/logo.svg`, `favicon.svg`). Firmanın kendi
  logosu kullanılacaksa başlıktaki ve alt bilgideki `marka-amblem` SVG'si değiştirilir.
- **İletişim bilgileri:** Telefon, adres ve e-posta firmanın eski sitesinin (novahgk.com,
  şu an kapalı) arama motoru kayıtlarından alındı. Güncel olmayabilir.
- **Çalışma saatleri** tahminidir.
- **Instagram** bağlantısı boş (`#`).
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
