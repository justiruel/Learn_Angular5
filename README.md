# Learn_Angular5
## Create new project
```
ng new ng-try --style=scss --routing
```
## Generate component
```
ng g c componentName
```
## menggunakan [(ngModel)]="itemCount"
- open app.module.ts, add code below :
```
import {FormsModule} from '@angular/forms';
```
```
imports: [
    FormsModule
  ],
```
