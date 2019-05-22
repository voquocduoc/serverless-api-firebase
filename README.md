# Building Serverless RESTful Web APIs with Cloud Functions, Firestore, Express

This is a simple API that saves contact information of people. 

## Requirements

```
npm install -g firebase-tools
```

## Getting Started

```
firebase login
```

## TESTTING

```
npm run serve
```

## DEPLOY

```
npm run deploy
```

## DEPLOY HOSTING

```
npm run deploy:host
```

## Firebase function enviroment

```
We use 
- set enviroment function: firebase functions:config:set env.active='dev'
- set frefix enviroment database follow enviroment: firebase functions:config:set prefixdatabase.dev='development_'
```