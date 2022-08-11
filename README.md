# Prerequisites
nodejs

# Setup

npm install -g @ionic/cli
npm install @ionic/angular@latest --save

# Initializing

```
ionic start ionic-sidemenu sidemenu --type=angular
```

## Add android and ios 

```
ionic capacitor add android

```
```
ionic capacitor add ios
```

## Add PWA

```
ng add @angular/pwa
```

Test with:
```
npm i http-server
```
```
ionic build --prod
http-server www
```