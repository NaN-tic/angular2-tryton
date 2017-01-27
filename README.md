Angular Tryton
==============

![](example/images/ng-tryton-logo.png)

An [Angular 2](https://github.com/angular/angular) module that makes tryton
JSONRPC working in the *Angular Way*. Contains two services `trytonService` and
`sessionService` and one filter `urlTryton`.


Install
-------
```bash
npm install angular2-tryton
```
```
Usage
-----

### Import services and inject them

```typescript
import {TrytonService} from 'angular2-tryton/services/tryton-service'
import {SessionService} from 'angular2-tryton/services/session-service'

@Component({
    ...
    providers: [HeroService]
})
...
```

