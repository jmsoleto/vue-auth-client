# vue-router-auth

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

A destacar:

- Extender el prototype de vue.$http con axios (main.js)
- El uso del atributo meta en las rutas para definir cuales son las autenticadas y cuales las libres (y las de administrador)
- La creación de un middelware que se ejecuta antes de cada ruta (router.js)
- las redirecciones que se aplican en el router.js
