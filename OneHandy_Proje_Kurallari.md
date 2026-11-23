# OneHandy: Proje Kuralları (her yeni sohbetin başında yapıştırın)

Güncelleme: 19 Kasım 2026. Bu dosya, aldığımız tüm kararları tek yerde toplar.

## 1. İşletme
- OneHandy, onehandy.ca. Yonge & Eglinton, Toronto. Pazartesi-Cumartesi 08:00-17:00, Pazar kapalı.
- Bölgeler: Yonge-Eglinton, Davisville, Lawrence Park, Leaside, Forest Hill, Mount Pleasant, Yorkville, Rosedale, Downtown Toronto, North York (yaklaşık 15 km).

## 2. Kesin kurallar
- Telefon numarası, ev adresi, e-Transfer adresi sitede ve Google profilinde yazılmaz. WhatsApp kaldırıldı. İletişim: site içindeki form penceresi, Formspree'ye gider (ücretsiz plan: ayda 50 gönderim, dosya yükleme yok), e-posta info.onehandy@gmail.com.
- Tile yok. Sigorta/lisans iddiası yok. HEPA vakum iddiası yok. Uydurma yorum/rakam yok.
- Yapısal, elektrik, tesisat tavsiyesi yok. Yapay zekâ asistanı fiyat vermez.
- API anahtarı sadece Netlify ortam değişkeninde.

## 3. Fiyat modeli (temel işçilik 120$/saat, tüm fiyatlar net)
- Ödeme: Interac e-Transfer veya Cash (aynı net fiyat). Cheque yok.
- HST %13: e-Transfer ile ödenen her şeye eklenir. Nakit ödemede toplama eklenmez. Depozito her zaman e-Transfer ile alındığı için depozitoya HST eklenir.
- Depozito: tarih onaylandıktan sonra %50. Müşteri formda ödeme yapmaz, "Request My Date".
- Condo (High-Rise): +120$. Müstakil: yok. Minimum sipariş: 450$ (tek küçük işler 450$'a yükselir).
- Çoklu iş: ikinci ve sonraki her iş kaleminden 120$ mobilizasyon düşülür.
- Oda paketleri: standart oda ≤150 sq ft. Büyük (151-250 sq ft) +%25. Daha büyük, 5+ oda, 5+ bed: özel teklif.
- Atık: Temiz alan (dahil), Small Bagged +120$, Medium/Transfer Station +240$. Caulking ve kapı ayarında atık seçeneği yok. Atık tesisi ücreti ayrıca maliyetle faturalanır.
- Malzeme dahil değil: müşteri alır ya da maliyet + makbuz + %15 tedarik/işleme ücreti. Küvet caulk silikonu dahil.
- Boya: 2 kat finish dahil. Primer ya da 3. kat gerekirse ek ürün müşteriden, ek işçilik Change Order.
- Matris: Küvet 360/+180. Mutfak backsplash 300/+150. Drywall yama+2 kat boya 360/+120 + 240 sabit boya. Kapı ayarı 270/+120. Duvar onarım+2 kat boya 1560/2400/3120/3840. Dedicated boya 1320/2040/2760/3360. Baseboard+shoemold+boya 1440/2100/2760/3360. Pre-PDI 1-4 bed 1800/2520/3120/3720. Ek: kapı boyama 200/kapı, ıslak hacim boya 90.
- Flooring: sq ft zorunlu, sadece işçilik: kurulum 6,00$/sq ft, söküm 2,52$/sq ft (tahmin, doğrulanacak). Ürün ayrı.
- İptal (öneri): 48 saat ve öncesi depozitonun %25'i kalır, kalan iade. 48 saatten az ya da gelmeme: iade yok. 48 saat öncesinde bir ücretsiz tarih değişikliği.
- Gizli hasar (Discovery Clause) ve büyük/sorunlu alan: yazılı Change Order / revize teklif.

## 4. Teknik
- Dosyalar: index.html, privacy.html, robots.txt, sitemap.xml, netlify/functions/ask.mjs. GitHub: infoonehandy-coder/onehandy (main).
- Asistan modeli gpt-6-luna (OPENAI_MODEL ile değişir). Form: Formspree (form kimliği mgakzbzp), alanlar: ad, e-posta, telefon, iki tarih, not, referans, özet. Fotoğraf formla gönderilmez, iletişimde alınır.
- Her tahminde referans numarası (OH-XXXX) üretilir, e-Transfer notuna yazılır.

## 5. Açık işler
Google doğrulaması ve Search Console, gerçek fotoğraflar, Hakkımda, yorumlar, sigorta, HST kaydı ve nakit işlerde vergi durumu (muhasebeci), fatura programı, flooring fiyatlarının doğrulanması.
