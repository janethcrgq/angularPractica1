## Ejercicio 1
**¿Qué archivo de Angular hace el papel de `main.tsx`, de `App.tsx` y de `vite.config.ts`?**

En Angular, el papel de `main.tsx` lo hace `src/main.ts`, porque ahí es donde arranca la aplicación. El de `App.tsx` lo hace `src/app/app.ts`, que es el componente principal y tiene su HTML en `app.html`. Y el de `vite.config.ts` lo hace `angular.json`, que es donde se configura cómo se construye y se corre el proyecto.

## Ejercicio 2

**¿Por qué `clase()` lleva paréntesis?**

Porque `clase` es un signal, y para leer el valor de un signal hay que llamarlo como función.

**¿Para qué sirve `track`?**

Sirve para que Angular identifique cada elemento de la lista (con el `id`). Así, cuando la lista cambia, solo actualiza lo que cambió y no vuelve a crear todo. Es como el `key` de React.
