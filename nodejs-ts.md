
#### create simple nodejs + express + typescript project + keycloak

> npm init  
> npm install typescript dotenv keycloak-connect express-session @types/express @types/node ts-node nodemon rimraf
> npx tsc --init --rootDir src --outDir build --esModuleInterop --resolveJsonModule --lib es6 --module commonjs --allowJs true --noImplicitAny true
```
target: es2016
module: commonjs
lib: es6
outDir: build
rootDir: src
strict: true
esModuleInterop: true
skipLibCheck: true
forceConsistentCasingInFileNames: true

```
> mkdir src
> touch src/server.ts
```
console.log("Hello, welcome to Nodejs Project")
```

> npx tsc
> 
