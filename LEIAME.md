# Ionic Cpf Cnpj Mask
Cria uma máscara dinâmica que permitirá a entrada de CPF e CNPJ nos inputs do ionic (ion-input).

## Usage

Importe em seu módulo (my-component.module.ts)
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


Insira no template do componente (eg: my-component.html):

```<ion-input [cpfcnpj]></ion-input>```

