
Nova Cosmetics – static export cleaned for editing in Cursor
===========================================================

Struktura:
- index.html        – główny plik strony (home)
- assets/css/*      – skompresowane style z Squarespace
- assets/js/*       – skrypty JS niezbędne do layoutu i animacji
- assets/img/*      – wszystkie obrazy użyte na stronie
- assets/fonts/*    – fonty webowe
- assets/media/*    – ewentualne video/audio
- assets/files/*    – pozostałe pliki (np. JSON, dane)

Wszystkie adresy typu:
- https://static1.squarespace.com/...
- //images.squarespace-cdn.com/...
- /static/...
zostały podmienione na lokalne ścieżki względne /assets/...,
tak żeby projekt działał jako czysty statyczny HTML.

Jak używać w Cursorze:
1. Utwórz nowe repo/projekt.
2. Wgraj cały folder z tymi plikami (index.html + katalog assets).
3. Ustaw prosty serwer statyczny (np. `npm install -g serve` i `serve .`)
   albo skorzystaj z wbudowanego podglądu w Cursorze.
4. Edytuj HTML/CSS/JS według potrzeb – wszystkie pliki masz lokalnie.

Jeśli będziesz dzielić sekcje na komponenty (np. React/Vite),
traktuj index.html jako źródło docelowego markup’u.
