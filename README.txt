WERSJA NAPRAWIONA DLA VERCEL

Wgraj całą zawartość tego folderu do repozytorium GitHub i wykonaj nowy deploy w Vercel.

Najważniejsze:
- index.html = dashboard
- api/proxy.mjs = backendowy proxy dla danych LIVE
- package.json = wymusza moduł Node.js
- vercel.json = konfiguracja funkcji

Po wdrożeniu sprawdź:
https://TWOJ-DOMEN.vercel.app/api/proxy?url=https%3A%2F%2Fquery1.finance.yahoo.com%2Fv8%2Ffinance%2Fchart%2FSPY%3Finterval%3D1d%26range%3D5d

Jeżeli endpoint zwraca JSON z Yahoo, proxy działa.
