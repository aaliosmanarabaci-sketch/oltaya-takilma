# PhishGuard

PhishGuard, teyit.org için hazırlanan ve oturumlarda tek link veya QR kod ile paylaşılabilecek mobil öncelikli bir oltalama farkındalığı oyunudur.

## Kullanım

1. `index.html` dosyasını bir tarayıcıda açın.
2. Katılımcılar telefondan oyuna girip **Oyuna Başla** ile akışı başlatır.
3. Her e-postayı inceleyip **Oltalama, Sil** veya **Güvenli** seçer.
4. Açıklamayı okuyup **Sonraki Mesaj** ile devam eder.
5. Oyun sonunda kişisel doğruluk skorunu görür.

## Yayınlama

Bu proje statik bir web uygulamasıdır; backend veya giriş sistemi gerektirmez. Aşağıdaki servislerden biriyle doğrudan yayınlanabilir:

- GitHub Pages
- Netlify
- Vercel

Yayınlandıktan sonra oturumlarda URL'yi QR koda dönüştürüp katılımcılarla paylaşabilirsiniz.

## Ürün Notları

- Arayüzde teyit adı ve resmi kombine SVG logosu kullanılır.
- Mobil cihazlarda telefon çerçevesi kaldırılır ve oyun tam ekran çalışır.
- Masaüstünde tanıtım alanı ve telefon önizlemesi korunur.
- Her yeni oyunda e-posta sırası karıştırılır.
- Sonuçlar sadece oyuncunun cihazında gösterilir; kişi bazlı veri tutulmaz.
