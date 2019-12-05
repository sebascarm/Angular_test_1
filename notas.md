#Angular (Framework Front-end)
----------------------
Requerido NodeJs

Sofware: https://nodejs.org/es/

Sofware Angular: https://cli.angular.io

### Ubicación
- D:\QNapDrive\Programacion\Web\Angular

### Comandos

- `node --version` (version)
- `npm install -g @angular/cli` (Instalación)
- `ng new myapp` (parado en el directorio padre crea el proyecto)
- `ng serve` (arranca servidor)
 
### Estructura
- `tsconfig.json` (archivos de config de TypeScript)
- `tslint.json` (archivos de config de TypeScript)
- `package.json` (comandos y config de paquetes de node_modules)
- `/src` (directorio de la aplicacion)

`main.ts` carga -> `app.modules.ts`
`app.modules` carga -> `app.component.ts` (contiene app-root)
`index.html` (contiene app-root)

`app.component.html` -> Agregamos `<hola-mundo></hola-mundo>`
`app.modules.ts` -> importamos componente `mi.component`
`mi.component.ts` -> declaramos el componente y exportamos 
- selector: (hola-mundo)
- templateUrl: (archivo html)
- styleUrls: [(archivo de estilo css)]
