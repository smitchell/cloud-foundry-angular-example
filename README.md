#Cloud Foundry Angular Example

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.8.

## How do I run this locally?

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## How to deploy this to Pivotal Cloud Foundry?

1) Edit the route in the manifest.yml file.
2) `cf login` or `cf t -s [space name]` to point to a test space.
3) Run `ng build --prod`. 
4) `cf push` to deploy to your test space.

