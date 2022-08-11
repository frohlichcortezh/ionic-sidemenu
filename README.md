<h1 align="center">Ionic Sidemenu app boilerplate</h1>
<h2 align="center">with iOS, Android and PWA</h2>
<h3 align="center">and docker soon</h3>

# Prerequisites
- [node and npm](https://nodejs.org/en/)
- [ionic](https://ionicframework.com/docs/intro/cli)

# Setup

```
npm install -g @ionic/cli
```
```
npm install @ionic/angular@latest --save
```

# Initializing

```
ionic start ionic-sidemenu sidemenu --type=angular
```

## Add android and ios 

Android
```
ionic capacitor add android
```
iOS
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