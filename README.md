# import-objects-fromJSON
aquí te enseño a importar objetos de un JSON con javascript y typescript (o eso me parece)

**importar dignidad de un json (ejemplo)**
req: TENERLO TODO EN UN CARPETA

empezamos con el json:

ponerle nombre al archivo `dignidad.json`
```json
{
 "nivel": "no mucha"
}
```

y ahora el javascript:
```js
const dignidad = require('./dignidad.json');


/* tambien puedes usar el { nivel } para importar un solo objeto. 
si haces esto procura cambiar el console.log() de abajo a console.log(nivel) 
y el const dignidad --> a const { nivel } = require('./dignidad.json')
*/

console.log(dignidad.nivel)
```

y si se quiere y mima al typescript, más o menos así: 
```ts
import { nivel } from './dignidad.json';

console.log(nivel)

```

Si en vez de copiar mucho texto y todo esto poco a poco, si quieren los archivos también los he subido.
están en la carpeta código. si sois muy vagos tomad un index:

- [codigo](https://github.com/samolo-H3LL0/import-objects-fromJSON/tree/main/codigo)
   - [digndad.json](https://github.com/samolo-H3LL0/import-objects-fromJSON/blob/main/codigo/dignidad.json)
   - [javascript.js](https://github.com/samolo-H3LL0/import-objects-fromJSON/blob/main/codigo/javascript.js)
   - [typescript.ts](https://github.com/samolo-H3LL0/import-objects-fromJSON/blob/main/codigo/typescript.ts)

**si hay algún error abrid una issue o contactame en** `fedooragames060@gmail.com`
