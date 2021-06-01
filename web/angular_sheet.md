# ANGULAR CHEAT SHEET

### What is Angular?

Angular is a framework, used to develop **Single Page web applications**. Angular was developed by Google and is maintained by Google and open-source contributors. The languages used to develop web applications in Angular are HTML, CSS, TypeScript.
The first version of angular was based on javascript and hence was known as AngularJs, and all Consecutive versions are based on TypeScript and are often denoted by Angular 2+. Each year 2 Major updates of Angular are rolled out, and the latest version of angular is 12.

### Why it is used?

Some applications need to be single page, this can be easily achieved by using angular. The most common example of single page application is **Gmail**. You will often notice in the Gmail website that Gmail never refreshes itself when you open/click any page/email in it. Whereas this can not be achieved by using normal web technologies.
Apart from this Angular provides us with a **component** based approach to implement UI, which means we can split our whole User interface/application into different components. This promotes code reusability, reduces the size of the application, and results in reduced complexity in heavy projects.

#### React Js vs Angular

Apart from angular, there is a number of frameworks that provide the same functionality as angular, the question arises why choose angular?

1. Angular is a full-fledged framework, while React is a library. We can develop an app just by using Angular as it comes with most things already.
2. Typescript is future
3. Enhanced support for error handling
4. Forms and validation
5. Beautiful & Efficient add ons like Angular-Material, Google Icons, etc
6. Regular updates

### Important Commands

1. ng new <project_name> -> This command is used to create a new angular project
2. ng g c <component_name> -> This command is used to add a new component in the angular project
3. ng g s <service_name> -> This command is used to create a new service in the angular project
4. ng serve -> This command is used to run the application locally for development purpose
5. ng build --prod -> This command is used to build the project for production Environment

### Structure of Angular Project

When you first time build a project, you are welcomed by a couple of confusing Folders and Files. For a Newbie, it can be very frightening. Whereas you will be delighted to hear that almost 80% of those files are not even touched once. Below is the structure of the project and its files:

1. node*modules - Whenever you install a new \_npm package* its files get stored here, Btw it's of no use to a web developer, so you can skip it.
2. src - This is the folder where most of the important files are available, 99% times, you will be working here only
   i. app - This folder consists of actual application files - 97% times you will be working here
   ii. assets - This folder is used to stores all images, logos, etc.
   iii. environment - You can Skip this
   iv. favicon.ico - the logo of your application that will be visible on top of the browser tab
   v. index.html - this is the entry point of your application, and you will hardly change this file except you need to add the meta tag, service workers, icons, etc.
   vi. main.ts - You can Skip this
   vii. polyfils.ts - You can Skip this
   viii. styles.css - This is a CSS file, all the style classes here will become public by default and then can be accessed in the whole application.
   ix. test.ts - You can Skip this
3. All files below this - You can Skip this, as they are rubbish for us

### Pre-Concepts

Before moving onto concepts of Angular, be familiar with the following topics/processes.

1. How to create an angular project
2. How to create a new component in angular project
3. Basic OOPs concepts like code-reusability, Inheritance, Abstraction, classes.
4. JavaScript
5. TypeScript
6. Life Cycle of Angular Project

### Important Concepts in Angular

Angular is a little complex and very deep to understand, whereas there are a few concepts that you can focus more on as you'll be using only these concepts 90% of the time. I have segregated concepts into 2 parts i.e. BASIC & ADVANCE, you can move on to advanced topics once you are well versed with basic ones.

#### BASIC

1. \*ngIf
2. \*ngFor
3. ngClass
4. ngStyle
5. (click)
6. formControl, formGroup, formArray
7. Angular routing/routerOutlet
8. ngOnInit
9. Constructor

#### ADVANCE

1. Observables
2. Promises
3. OOPS in Angular
4. Working with JSON data
