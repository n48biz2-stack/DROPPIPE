# [NAZWA_APLIKACJI]

Wewnętrzna integracja z Allegro REST API służąca do zarządzania własną
ofertą sprzedażową i obsługi posprzedażowej na kontach należących do
operatora aplikacji.

Aplikacja nie jest udostępniana podmiotom trzecim i nie przetwarza danych
użytkowników innych niż konta własne operatora.

## Zakres działania

- zarządzanie ofertami sprzedażowymi (tworzenie, aktualizacja, kończenie)
- pobieranie danych katalogowych i parametrów kategorii
- obsługa zamówień i komunikacji posprzedażowej
- obsługa zwrotów i reklamacji

## Wykorzystywane uprawnienia (scope)

- `allegro:api:sale:offers:read`, `allegro:api:sale:offers:write`
- `allegro:api:orders:read`, `allegro:api:orders:write`
- `allegro:api:profile:read`

## Kontakt

Operator: [Nikolas Bułka]
E-mail: [n48ubiz@gmail.com]

W sprawach dotyczących ruchu generowanego przez tę aplikację prosimy
o kontakt na powyższy adres.

## Identyfikator User-Agent

Aplikacja przekazuje w każdym żądaniu do Allegro REST API nagłówek
User-Agent w formacie: DROPPP/1.0.0 (+https://github.com/n48biz2-stack/DROPPIPE)

```
[DROPP]/[1] (+[https://github.com/n48biz2-stack/DROPPIPE])
```

zgodnie z art. 3.4(c) Regulaminu REST API Allegro.
