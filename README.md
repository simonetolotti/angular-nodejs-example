# angular-nodejs-example
Demonstration project on how to develop and run angular project with NodeJS project

# Update

Open on Visual Studio Code, from Powershell

## Update Angular

```
npm uninstall -g @angular-cli
npm install -g @angular/cli@latest
```

## Verify Version

```
ng version
```

Angular CLI: 11.0.2
Node: 12.14.1
OS: win32 x64

## Install Express

```
npm install express --save
npm install nodemon --save-dev
```

## Install

```
npm install
cd my-app
npm install
```

## Build 

return to home folder...

```
npm run build
cd my-app
npm run build
```

# Execute 

## Execute development 

```
npm run dev
cd my-app\npm start
```

## Execute 

return to home folder...

```
npm start
```

# Deploy

## Package

```
Copy my-app\dist in a folder
On the this main folder, copy package.jason, server.bundle.js, server.js
```

## On Raspberry

create a zip, such as raspberry.zip and copy it on the target:

```
scp raspberry.zip root@192.168.1.5:/var/www/
```

From Raspberry shell, unzip it:
```
unzip raspberry.zip
```
Finally start:
```
node server.bundle.js &
```





