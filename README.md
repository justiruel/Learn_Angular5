# Learn_Angular5
## Create new project
```
ng new ng-try --style=scss --routing
```
## Generate component
```
ng g c componentName
```
## Generate service
```
ng g s serviceName
```
## Generate directive
```
ng g d directiveName
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

## Run app
```
ng serve
```
## Deploy
```
ng build --prod
```
hasilnya cek di folder <b>dist</b>

## References
- https://angular.io/guide/http
