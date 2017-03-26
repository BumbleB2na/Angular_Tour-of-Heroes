This project demonstrates my progress while following [Angular's Tour of Heroes tutorial](https://angular.io/docs/ts/latest/tutorial/).  
  
Future state:  
When complete, it will look and function like [this complete demo](https://embed.plnkr.co/?show=preview).  
  
Status:  
1. Began new github repository using [Angular quickstart (seeding project)](https://github.com/angular/quickstart) as a boilerplate.  
2. Is displaying hero details like in [this demo](https://embed.plnkr.co/?show=preview).  
3. Hero list now displaying mock data with click to view details, like: [this demo](https://embed.plnkr.co/?show=preview).  
4. Wrote reusable HeroDetailComponent. Nothing visibly changed.  
5. Wrote HeroService to separate data in to own layer. AppComponent refactored to work like master class, initializing HeroService mock data and simulating data request from server. Nothing visibly changed.  
6. Dashboard view, Routing to Details view, Wrote custom RoutingModule, Wrote Partial/mini-Details view, and added app styling. It now looks like [this demo](https://angular.io/resources/live-examples/toh-5/ts/eplnkr.html).  
7. Next task is to replace mock data with HTTP calls to remote server's web API. [Left off here in tutorial](https://angular.io/docs/ts/latest/tutorial/toh-pt6.html).   