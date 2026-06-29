# CSRF

## Co to jest
CSRF pozwala wykonać akcję w imieniu zalogowanego użytkownika.

## Przykład
Zmiana hasła bez wiedzy użytkownika.

## Jak testować
- forms
- change password
- email change
- delete account

## Co sprawdzać
- brak CSRF tokena
- przewidywalny token
- brak SameSite cookies

## Jak naprawić
- CSRF tokens
- SameSite cookies
- re-authentication
