mkdir hello
cd hello
code .

#### create file:$ nano  app.js
var msg = 'Hello World';
console.log(msg);

#### Run code :$ node app.js


#### Debug
ctrl + shift + D


##### An Express application
npm install -g express-generator

express myExpressApp --view pug

cd myExpressApp
npm install

npm start

#### Debug:$ nano launch.js
``` json
 {
    "version": "0.2.0",
    "configurations": [
    {
        "name": "Attach by Process ID",
        "processId": "${command:PickProcess}",
        "request": "attach",
        "skipFiles": [
            "<node_internals>/**"
        ],
        "type": "pwa-node"
    },
    
        {
            "name": "Launch Program",
            "program": "${workspaceFolder}/app.js",
            "request": "launch",
            "skipFiles": [
                "<node_internals>/**"
            ],
            "type": "pwa-node"
        }
    ]
}
```
