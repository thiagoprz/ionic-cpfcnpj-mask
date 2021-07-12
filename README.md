# Ionic Cpf Cnpj Mask
Creates a dynamic mask that will allow the input of CPF and CNPJ on ion-input.

CPF is an individual taxpayer identification number given to people living in Brazil, both native Brazilians and resident foreigners.

CNPJ is the National Registry of Legal Entities in Brazil.

## Usage

Import module on my-component.module.ts
```
import {IonicCurrencyMaskModule} from "@thiagoprz/ionic-cpfcnpj-mask";

@NgModule({
    ...
    imports: [
        ...,
        IonicCpfCnpjMaskModule
    ],
    ...
})
export class MyComponent {}
```


Insert on template component (eg: my-component.html):

```<ion-input [cpfcnpj]></ion-input>```



### Project build with Angular Cli 11.2.4

This library was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.4.

### Build

Run `ng build ionic-cpfcnpj-mask` to build the project. The build artifacts will be stored in the `dist/` directory.

### Publishing

After building your library with `ng build ionic-cpfcnpj-mask`, go to the dist folder `cd dist/ionic-cpfcnpj-mask` and run `npm publish`.

### Running unit tests

Run `ng test ionic-cpfcnpj-mask` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
