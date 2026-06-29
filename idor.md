# IDOR

## Co to jest
IDOR to podatność, gdy użytkownik może dostać się do zasobu innego użytkownika przez zmianę ID w URL/API.

## Przykład
/user/123/orders

Zmiana na:

/user/124/orders

może ujawnić dane innego użytkownika.

## Jak testować
- sprawdzić parametry ID
- zmienić ID na inne
- porównać odpowiedzi
- sprawdzić API requests w Burp Suite

## Jak naprawić
- kontrola uprawnień po stronie backendu
- sprawdzanie właściciela zasobu
- unikanie przewidywalnych ID
