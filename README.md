# Bütçem

Kişisel bütçe ve harcama takip uygulaması. Telefonda çalışacak şekilde tasarlandı, internet olmadan da açılır.

## Özellikler
- Günlük harcama hakkı, haftalık harcama grafiği, seriler
- Harcama, ek gelir ve istek listesi (24 saat kuralı)
- Faturalar, abonelikler, taksitler
- Birikim hedefi, kumbara, acil durum fonu
- Ay sonu karnesi ve otomatik ay analizi
- Kredi kartı ekstresinden aktarma (metin veya CSV)
- Yedek alma ve yedekten yükleme

## Verilerim nerede?
Tüm veriler **sadece kullandığın cihazın tarayıcısında** (localStorage) tutulur.
Bu depoda veya GitHub'da hiçbir kişisel veri bulunmaz.
Cihaz değiştirirken veya düzenli olarak: Ayarlar → **Yedek al**.

## Dosyalar
| Dosya | Görevi |
|---|---|
| `index.html` | Uygulamanın tamamı (HTML, CSS, JavaScript) |
| `sw.js` | İnternetsiz açılabilmesi için önbellek |
| `manifest.webmanifest` | Ana ekrana eklenince uygulama gibi görünmesi |
| `icon.png` | Uygulama simgesi |

## Güncelleme
`index.html` dosyasını değiştirdikten sonra `sw.js` içindeki `butcem-v1` değerini bir artır (`butcem-v2` gibi).
