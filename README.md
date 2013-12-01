----

При подключении [Snap.svg](https://github.com/adobe-webplatform/Snap.svg) вместе с [LMD](https://github.com/azproduction/lmd) валится ошибка в модуле [snap.svg#L4134](https://github.com/adobe-webplatform/Snap.svg/blob/master/dist/snap.svg.js#L4134):<br/>
``Uncaught TypeError: Cannot call method 'on' of undefined``

Проблема только вместе со Snap.svg(с другими модулями проблем не обнаружено).
То ли я неправильно подключаю модуль с помощью LMD, то ли какая-то непонятная ошибка в Snap.svg в таком кейсе.

#### Установка
```
npm run-script init
npm run-script build
npm run-script start

open index.html
```
