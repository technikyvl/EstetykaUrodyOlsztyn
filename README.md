# NovaCosmetics_clean_2

Zestaw przefiltrowany pod edycję w Cursorze.

## Struktura
- `assets/img` – obrazy
- `assets/css` – style
- `assets/js` – skrypty
- `assets/fonts` – fonty
- `assets/media` – wideo/audio
- `assets/files` – inne pliki
- `vendor` – biblioteki zewnętrzne (jeśli były w paczce)

## Co zrobiłem
1. Rozpakowałem oryginalny ZIP i uporządkowałem pliki do powyższej struktury.
2. Zaktualizowałem ścieżki w HTML/CSS/JS do nowych lokacji `assets/...`.
3. Usunąłem najpopularniejsze trackery (GTM/GA/FB/Hotjar), jeśli występowały.
4. Nie pobierałem zasobów z zewnętrznych CDN – jeśli w HTML nadal są absolutne linki do CDN, w paczce nie było ich kopii.

## Podsumowanie
{
  "project": "NovaCosmetics_clean_2",
  "timestamp": "2025-11-12T23:30:40.407021Z",
  "counts": {
    "html": 2,
    "css": 8,
    "js": 21,
    "img": 7,
    "fonts": 5,
    "media": 0,
    "files": 51
  },
  "changed_text_files": [
    "assets/css/site.css",
    "index.html",
    "assets/css/css2.css"
  ]
}
