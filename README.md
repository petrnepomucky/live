# YeY – Kancelář pro řemeslníky (online)

Online verze YeY s přihlášením a daty v Supabase (projekt „Kancelář řemeslníků online").
Celá aplikace je v jednom souboru `index.html` – stačí ho nahrát na statický hosting (Cloudflare Pages).

- Přehled, zakázky (tři propojené panely), nabídky, faktury s QR platbou, předávací protokoly
- 14 kalkulaček obecných množství materiálu (bez katalogu)
- Kontakty s ARES, vlastní ceník prací, nastavení firmy

V Supabase → Authentication → URL Configuration nastavte Site URL a Redirect URLs na adresu, kde aplikace běží.
