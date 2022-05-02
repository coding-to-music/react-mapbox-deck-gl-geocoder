# react-mapbox-deck-gl-geocoder

# 🚀 Javascript full-stack 🚀

https://github.com/coding-to-music/react-mapbox-deck-gl-geocoder

https://react-mapbox-deck-gl-geocoder.vercel.app

by ansel brandt https://github.com/anselbrandt/react-map-geocoder

https://react-map-geocoder.netlify.app

https://github.com/anselbrandt/react-map-geocoder

## Build Warnings

```java

```

## Build Errors using Heroku, fine with Vercel

https://react-mapbox-deck-gl-geocoder.herokuapp.com

```java
2022-05-02T06:58:52.669660+00:00 app[web.1]: FATAL ERROR: Ineffective mark-compacts near heap limit Allocation failed - JavaScript heap out of memory
2022-05-02T06:58:52.670471+00:00 app[web.1]: 1: 0xa3aaf0 node::Abort() [/app/.heroku/node/bin/node]
2022-05-02T06:58:52.671109+00:00 app[web.1]: 2: 0x970199 node::FatalError(char const*, char const*) [/app/.heroku/node/bin/node]
2022-05-02T06:58:52.677693+00:00 app[web.1]: 3: 0xbba45e v8::Utils::ReportOOMFailure(v8::internal::Isolate*, char const*, bool) [/app/.heroku/node/bin/node]
2022-05-02T06:58:52.677694+00:00 app[web.1]: 4: 0xbba7d7 v8::internal::V8::FatalProcessOutOfMemory(v8::internal::Isolate*, char const*, bool) [/app/.heroku/node/bin/node]
2022-05-02T06:58:52.677695+00:00 app[web.1]: 5: 0xd769e5  [/app/.heroku/node/bin/node]
2022-05-02T06:58:52.677695+00:00 app[web.1]: 6: 0xd7756f  [/app/.heroku/node/bin/node]
2022-05-02T06:58:52.677697+00:00 app[web.1]: 7: 0xd853ab v8::internal::Heap::CollectGarbage(v8::internal::AllocationSpace, v8::internal::GarbageCollectionReason, v8::GCCallbackFlags) [/app/.heroku/node/bin/node]
2022-05-02T06:58:52.678446+00:00 app[web.1]: 8: 0xd88f6c v8::internal::Heap::AllocateRawWithRetryOrFailSlowPath(int, v8::internal::AllocationType, v8::internal::AllocationOrigin, v8::internal::AllocationAlignment) [/app/.heroku/node/bin/node]
2022-05-02T06:58:52.679193+00:00 app[web.1]: 9: 0xd5764b v8::internal::Factory::NewFillerObject(int, bool, v8::internal::AllocationType, v8::internal::AllocationOrigin) [/app/.heroku/node/bin/node]
2022-05-02T06:58:52.680015+00:00 app[web.1]: 10: 0x109fc0f v8::internal::Runtime_AllocateInYoungGeneration(int, unsigned long*, v8::internal::Isolate*) [/app/.heroku/node/bin/node]
2022-05-02T06:58:52.680976+00:00 app[web.1]: 11: 0x1448e19  [/app/.heroku/node/bin/node]
2022-05-02T06:58:52.713902+00:00 app[web.1]: npm ERR! code ELIFECYCLE
2022-05-02T06:58:52.714076+00:00 app[web.1]: npm ERR! errno 1
2022-05-02T06:58:52.717345+00:00 app[web.1]: npm ERR! react-mapbox-deck-gl-geocoder@0.1.0 start: `react-scripts start`
2022-05-02T06:58:52.717401+00:00 app[web.1]: npm ERR! Exit status 1
2022-05-02T06:58:52.717467+00:00 app[web.1]: npm ERR!
2022-05-02T06:58:52.717515+00:00 app[web.1]: npm ERR! Failed at the react-mapbox-deck-gl-geocoder@0.1.0 start script.
2022-05-02T06:58:52.717559+00:00 app[web.1]: npm ERR! This is probably not a problem with npm. There is likely additional logging output above.
2022-05-02T06:58:52.724336+00:00 app[web.1]:
2022-05-02T06:58:52.726435+00:00 app[web.1]: npm ERR! A complete log of this run can be found in:
2022-05-02T06:58:52.726478+00:00 app[web.1]: npm ERR!     /app/.npm/_logs/2022-05-02T06_58_52_717Z-debug.log
2022-05-02T06:58:52.895768+00:00 heroku[web.1]: Process exited with status 1
2022-05-02T06:58:52.963143+00:00 heroku[web.1]: State changed from up to crashed
2022-05-02T06:58:52.990628+00:00 heroku[web.1]: State changed from crashed to starting
2022-05-02T06:59:03.057210+00:00 heroku[web.1]: Starting process with command `npm start`
2022-05-02T06:59:05.344757+00:00 app[web.1]:
2022-05-02T06:59:05.344772+00:00 app[web.1]: > react-mapbox-deck-gl-geocoder@0.1.0 start /app
2022-05-02T06:59:05.344772+00:00 app[web.1]: > react-scripts start
2022-05-02T06:59:05.344772+00:00 app[web.1]:
2022-05-02T06:59:08.326437+00:00 heroku[web.1]: State changed from starting to up
2022-05-02T06:59:08.074281+00:00 app[web.1]: ℹ ｢wds｣: Project is running at http://172.18.170.38/
2022-05-02T06:59:08.074470+00:00 app[web.1]: ℹ ｢wds｣: webpack output is served from
2022-05-02T06:59:08.074507+00:00 app[web.1]: ℹ ｢wds｣: Content not from webpack is served from /app/public
2022-05-02T06:59:08.074536+00:00 app[web.1]: ℹ ｢wds｣: 404s will fallback to /
2022-05-02T06:59:08.074948+00:00 app[web.1]: Starting the development server...
2022-05-02T06:59:08.074949+00:00 app[web.1]:
2022-05-02T06:59:34.413195+00:00 app[web.1]: npm ERR! code ELIFECYCLE
2022-05-02T06:59:34.413436+00:00 app[web.1]: npm ERR! errno 1
2022-05-02T06:59:34.418050+00:00 app[web.1]: npm ERR! react-mapbox-deck-gl-geocoder@0.1.0 start: `react-scripts start`
2022-05-02T06:59:34.418122+00:00 app[web.1]: npm ERR! Exit status 1
2022-05-02T06:59:34.418202+00:00 app[web.1]: npm ERR!
2022-05-02T06:59:34.418262+00:00 app[web.1]: npm ERR! Failed at the react-mapbox-deck-gl-geocoder@0.1.0 start script.
2022-05-02T06:59:34.418315+00:00 app[web.1]: npm ERR! This is probably not a problem with npm. There is likely additional logging output above.
2022-05-02T06:59:34.424599+00:00 app[web.1]:
2022-05-02T06:59:34.424704+00:00 app[web.1]: npm ERR! A complete log of this run can be found in:
2022-05-02T06:59:34.424743+00:00 app[web.1]: npm ERR!     /app/.npm/_logs/2022-05-02T06_59_34_418Z-debug.log
2022-05-02T06:59:34.596210+00:00 heroku[web.1]: Process exited with status 1
2022-05-02T06:59:34.723082+00:00 heroku[web.1]: State changed from up to crashed
2022-05-02T06:59:34.009167+00:00 app[web.1]:
2022-05-02T06:59:34.009176+00:00 app[web.1]: <--- Last few GCs --->
2022-05-02T06:59:34.009176+00:00 app[web.1]:
2022-05-02T06:59:34.009190+00:00 app[web.1]: [29:0x5b52ba0]    26993 ms: Mark-sweep 252.9 (257.8) -> 251.9 (258.0) MB, 870.5 / 0.0 ms  (average mu = 0.120, current mu = 0.026) allocation failure scavenge might not succeed
2022-05-02T06:59:34.009190+00:00 app[web.1]: [29:0x5b52ba0]    27999 ms: Mark-sweep 252.9 (258.0) -> 251.9 (258.0) MB, 983.2 / 0.0 ms  (average mu = 0.069, current mu = 0.023) allocation failure scavenge might not succeed
2022-05-02T06:59:34.009190+00:00 app[web.1]:
2022-05-02T06:59:34.009195+00:00 app[web.1]:
2022-05-02T06:59:34.009196+00:00 app[web.1]: <--- JS stacktrace --->
2022-05-02T06:59:34.009196+00:00 app[web.1]:
2022-05-02T06:59:34.009204+00:00 app[web.1]: FATAL ERROR: Ineffective mark-compacts near heap limit Allocation failed - JavaScript heap out of memory
2022-05-02T06:59:34.009956+00:00 app[web.1]: 1: 0xa3aaf0 node::Abort() [/app/.heroku/node/bin/node]
2022-05-02T06:59:34.010522+00:00 app[web.1]: 2: 0x970199 node::FatalError(char const*, char const*) [/app/.heroku/node/bin/node]
2022-05-02T06:59:34.011147+00:00 app[web.1]: 3: 0xbba45e v8::Utils::ReportOOMFailure(v8::internal::Isolate*, char const*, bool) [/app/.heroku/node/bin/node]
2022-05-02T06:59:34.011765+00:00 app[web.1]: 4: 0xbba7d7 v8::internal::V8::FatalProcessOutOfMemory(v8::internal::Isolate*, char const*, bool) [/app/.heroku/node/bin/node]
2022-05-02T06:59:34.012472+00:00 app[web.1]: 5: 0xd769e5  [/app/.heroku/node/bin/node]
2022-05-02T06:59:34.013187+00:00 app[web.1]: 6: 0xd7756f  [/app/.heroku/node/bin/node]
2022-05-02T06:59:34.013901+00:00 app[web.1]: 7: 0xd853ab v8::internal::Heap::CollectGarbage(v8::internal::AllocationSpace, v8::internal::GarbageCollectionReason, v8::GCCallbackFlags) [/app/.heroku/node/bin/node]
2022-05-02T06:59:34.014623+00:00 app[web.1]: 8: 0xd88f6c v8::internal::Heap::AllocateRawWithRetryOrFailSlowPath(int, v8::internal::AllocationType, v8::internal::AllocationOrigin, v8::internal::AllocationAlignment) [/app/.heroku/node/bin/node]
2022-05-02T06:59:34.015331+00:00 app[web.1]: 9: 0xd5764b v8::internal::Factory::NewFillerObject(int, bool, v8::internal::AllocationType, v8::internal::AllocationOrigin) [/app/.heroku/node/bin/node]
2022-05-02T06:59:34.016146+00:00 app[web.1]: 10: 0x109fc0f v8::internal::Runtime_AllocateInYoungGeneration(int, unsigned long*, v8::internal::Isolate*) [/app/.heroku/node/bin/node]
2022-05-02T06:59:34.025034+00:00 app[web.1]: 11: 0x1448e19  [/app/.heroku/node/bin/node]
```

## Environment Values

```java
REACT_APP_MAPBOX_ACCESS_TOKEN=""
```

# Mapbox Geocoder with react-map-gl

```
yarn

yarn start
```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/react-mapbox-deck-gl-geocoder.git
git push -u origin main
```

## Heroku

```java
heroku create react-mapbox-deck-gl-geocoder
```

## Heroku MongoDB Environment Variables

```java
heroku config:set

heroku config:set MONGODB_URI="your value"
```

## Push to Heroku

```java
git push heroku

# or

npm run deploy
```
