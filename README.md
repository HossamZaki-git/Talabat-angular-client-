# Client

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.1.

## 📦 Overview

This Angular frontend integrates with a backend API to simulate a checkout and payment flow using Stripe. It’s designed for testing and development purposes.

## Setup instructions

1. Clone the repo using the code ```bash git clone https://github.com/HossamZaki-git/Talabat-angular-client.git```
2. Use Node.js version `16.20.0`  
3. Install angular cli 14 locally inside the folder of the project using the command ```bash npm install @angular/cli@14 --save-dev```
4. Open `src/app/checkout/checkout-payment/checkout-payment.component.ts`  
   At line 37, replace the Stripe key with your own:

   ```ts
   this.stripe = Stripe('YOUR_PUBLISHABLE_KEY');
   ```
5. Run the project using the command `ng serve`

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

