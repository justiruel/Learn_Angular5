# Learn_Angular5
## Create new project
```
ng new ng-try --style=scss --routing
```
## Generate component
```
ng g c componentName
```
## Menggunakan [(ngModel)]="itemCount"
- open app.module.ts, add code below :
```
import {FormsModule} from '@angular/forms';
```
```
imports: [
    FormsModule
  ],
```
## Enable production mode
Buka environmentsenvironment.ts, jadikan production: true
```
export const environment = {
  production: true
};
```
kaitannya adalah dengan main.ts
```
if (environment.production) {
  enableProdMode();
}
```
