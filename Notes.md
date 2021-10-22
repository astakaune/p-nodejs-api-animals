# API

GET: http://localhost:3000/
GET: http://localhost:3000/xyz/
neegzistuojantys grazina klaida 404

POST: http://localhost:3000/
siunciamas objektas

```
latvija.json {
    name: 'Latvija',
    size: 55000,
}
```

GET: http://localhost:3000/latvija/
gausim Latvijos objekta

PUT: http://localhost:3000/laTvija/

```
{
    name: 'Latvija',
    size: 75000,
}
```

PUT: http://localhost:3000/latviJa/name/xxx/
`name` atnaujinti draudziama

DELETE: http://localhost:3000/
DELETE: http://localhost:3000/xyz/
neegzistuojantys grazina klaida 404

DELETE: http://localhost:3000/LATVIJA/
