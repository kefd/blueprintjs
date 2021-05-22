# blueprintjs  

Simplesmente a melhor Component library 

```sh
yarn add @blueprintjs/core
```

```jsx
import { Button } from "@blueprintjs/core";
 
<Button intent="success" text="button content" onClick={incrementCounter} />
```

```html
<link href="path/to/node_modules/normalize.css/normalize.css" rel="stylesheet" />
<!-- blueprint-icons.css file must be included alongside blueprint.css! -->
<link href="path/to/node_modules/@blueprintjs/icons/lib/css/blueprint-icons.css" rel="stylesheet" />
<link href="path/to/node_modules/@blueprintjs/core/lib/css/blueprint.css" rel="stylesheet" />
<!-- add other blueprint-*.css files here -->
```
or...  
```typescript
import 'normalize.css/normalize.css';  
import '@blueprintjs/icons/lib/css/blueprint-icons.css';  
import '@blueprintjs/core/lib/css/blueprint.css';
```
