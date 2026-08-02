# halaqa-web

Halaqa uygulamasının tanıtım sitesi. Tek sayfalık, tamamen statik, harici
bağımlılık yok. GitHub Pages ile yayınlanır: https://enesorak.github.io/halaqa-web/

## Düzenleme
- **Metinler:** `index.html` içindeki `STR` sözlüğü (diller: `tr`, `en`, `ar`).
- **Görünüm:** bölümler `<x-dc>` içinde inline stil; `{{ t.xxx }}` STR'den gelir.
- **Ekran görüntüleri:** `assets/shots/` ve ilgili `<image-slot src="...">`.

## Yerel önizleme
    python3 -m http.server 4321
    # http://localhost:4321

`main` dalına her push, Pages'i otomatik günceller.
