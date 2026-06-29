# XSS (Cross-Site Scripting)

## Co to jest
XSS pozwala wstrzyknąć kod JavaScript do aplikacji i wykonać go w przeglądarce ofiary.

## Typy
- Reflected XSS
- Stored XSS
- DOM XSS

## Przykład

```html
<script>alert(1)</script>
```

## Jak testować
- input fields
- search bars
- comments
- URL parameters

## Payloady
<script>alert(1)</script>
<img src=x onerror=alert(1)>
<svg onload=alert(1)>

## Jak naprawić
- output encoding
- input sanitization
- CSP
