# SSRF

## Co to jest
SSRF pozwala serwerowi wykonywać requesty do innych zasobów.

## Przykład

http://localhost/admin

## Jak testować
- image URL upload
- webhooks
- PDF generators
- import URL

## Payloady
http://127.0.0.1
http://localhost
http://169.254.169.254

## Jak naprawić
- whitelist URLs
- block internal IPs
