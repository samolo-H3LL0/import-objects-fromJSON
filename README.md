# import-objects-fromJSON
aquí te enseño a importar objetos de un JSON con javascript y typescript (o eso me parece :v)

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
import { nivel } from './config.json';

console.log(nivel)

```

Si en vez de copiar todo esto poco a poco quieren los archivos también los he subido
