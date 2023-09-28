# AngularTourOfHeroes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Completed steps in the tutorial at

https://angular.io/tutorial/tour-of-heroes

## step 1 contained lessons on


    You used ng generate to create a second HeroesComponent.
    You displayed the HeroesComponent by adding it to the AppComponent shell.
    You applied the UppercasePipe to format the name.
    You used two-way data binding with the ngModel directive.
    You learned about the AppModule.
    You imported the FormsModule in the AppModule so that Angular would recognize and apply the ngModel directive.
    You learned the importance of declaring components in the AppModule.

## step 2 lessons


    The Tour of Heroes application displays a list of heroes with a detail view.
    The user can select a hero and see that hero's details.
    You used *ngFor to display a list.
    You used *ngIf to conditionally include or exclude a block of HTML.
    You can toggle a CSS style class with a class binding.


## step 3



    You created a separate, reusable HeroDetailComponent.

    You used a property binding to give the parent HeroesComponent control over the child HeroDetailComponent.

    You used the @Input decorator to make the hero property available for binding by the external HeroesComponent.


## step 4


    You refactored data access to the HeroService class.
    You registered the HeroService as the provider of its service at the root level so that it can be injected anywhere in the application.
    You used Angular Dependency Injection to inject it into a component.
    You gave the HeroService get data method an asynchronous signature.
    You discovered Observable and the RxJS Observable library.
    You used RxJS of() to return Observable<Hero[]>, an observable of mock heroes.
    The component's ngOnInit lifecycle hook calls the HeroService method, not the constructor.
    You created a MessageService for loosely coupled communication between classes.
    The HeroService injected into a component is created with another injected service, MessageService.

## step 5


    You added the Angular router to navigate among different components
    You turned the AppComponent into a navigation shell with <a> links and a <router-outlet>
    You configured the router in an AppRoutingModule
    You defined routes, a redirect route, and a parameterized route
    You used the routerLink directive in anchor elements
    You refactored a tightly coupled main/detail view into a routed detail view
    You used router link parameters to navigate to the detail view of a user-selected hero
    You shared the HeroService with other components

## step 6


    You added the necessary dependencies to use HTTP in the application
    You refactored HeroService to load heroes from a web API
    You extended HeroService to support post(), put(), and delete() methods
    You updated the components to allow adding, editing, and deleting of heroes
    You configured an in-memory web API
    You learned how to use observables

