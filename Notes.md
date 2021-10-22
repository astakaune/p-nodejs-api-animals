# API

GET: http://localhost:3000/
GET: http://localhost:3000/xyz/
neegzistuojantys grazina klaida 404

POST: http://localhost:3000/
siunciamas objektas

```
mole.json {
    name: 'Mole',
    size: 30,
}
```

GET: http://localhost:3000/mole/
gausim Mole objekta

PUT: http://localhost:3000/moLe/

```
{
    name: 'Mole',
    size: 50,
}
```

PUT: http://localhost:3000/mole/name/xxx/
`name` atnaujinti draudziama

DELETE: http://localhost:3000/
DELETE: http://localhost:3000/xyz/
neegzistuojantys grazina klaida 404

DELETE: http://localhost:3000/MOLE/
