# Cod Reducere Modivo

O colecție de coduri de reducere Modivo. Le folosim pentru testarea cuvintelor cheie [cod reducere Modivo](https://cuponescu.ro/magazin/modivo), [voucher Modivo](https://cuponescu.ro/magazin/modivo), [cupon Modivo](https://cuponescu.ro/magazin/modivo), și [cod promotional Modivo](https://cuponescu.ro/magazin/modivo) de pe Cuponescu.ro.

## Instalare

Instalează `cod-reducere-modivo` prin NPM:

```bash
npm install cod-reducere-modivo
```

## Utilizare

Pachetul conține un array de obiecte reprezentând coduri de reducere.

În Node:

```javascript
var codes = require('cod-reducere-modivo')

console.log(codes)

// [
//   {
//     site: 'https://www.modivo.ro',
//     cod_reducere: 'MODIVO10',
//     reducere: '10% reducere',
//     descriere: 'Reducere de 10% la toate produsele'
//   },
//   ...
// ]
```

## Despre

Cod-reducere-modivo a fost creat de echipa de la [Cuponescu](https://cuponescu.ro/) pentru a ajuta cu testarea.
