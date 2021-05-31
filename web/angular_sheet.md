# ANGULAR CHEAT SHEET

### What is Angular?

Angular is a framework, used to develop **Single Page web applications**. Angular was developed by Google and is maintained by google and open source contributors. The languages used to develop web applications in Angular are HTML, CSS, TypeScript.
First version of angular was based on javascript and hence was known as AngularJs, and all Consecutive versions are based on TypeScript and are often denoted by Angular 2+. Each year 2 Major updates of Angular are rolled out, and latest version of angular is 12.

### Why it is used?

Some applications need to be single page, this can be easily achieved by using angular. The most common example of signle page application is **gmail** . You will notice in Gmail website that gmail never refreshes itself when you open/click any page/email in it. Whereas this can not be achieved by using normal web technologies.
Apart from this Angular provides us with a **component** based approach to implement UI, this means we can split our whole User interface/application into different components. This promotes code reusability, reduces size of application and greatly reduce complexity in heavy projects.

React Js vs Angular
Apart from angular there are number of frameworks which provide same functionality as angular, then question arises why choose angular?

1. Angular is a full-fledged framework, while React is a library. We can develop an app just by using Angular as it comes with most things already.
2. Typescript is future
3. Enhanced support for error handling
4. Forms and validation
5. Beautiful & Efficient add ons like Angular-Material, Google Icons etc
6. Regular updates

### Important Commands

### Structure of Angular Project

When you first time build a project, you are welcomed by a couple of confusing Folders and Files. For a Newbie it can be very frightning. Where as you will be delighted to hear that almost 80% of those files are not even touched once. Yeah, Being an angular developer i do not even know what some files are actully doing in project, because i never opened them. So below i have made it easyy for you to understand:

1. node_modules - Whenever you install a new _npm package_ its files get stored here, BTW its of no use to a web developer, so you can skip it.
2. src - This is folder where most of the important files are available, 99% times, you will be working here only
   i. app - This folder consists of actual application files - 97% times you will be working herer
   ii. assets - This folder is used to stores all images, logo etc.
   iii. environment - You can Skip this
   iv. favicon.ico - the logo of your appliction that will be visible on top of browser tab
   v. index.html - this is entry point of your application, and you will hardly change this file except you need to add meta tag, service workers, icons etc.
   vi. main.ts - You can Skip this
   vii. polyfils.ts - You can Skip this
   viii. styles.css - This is css file, all the style classes here will become public by default and then can be accessed in whole application
   ix. test.ts - You can Skip this
3. All files below this - You can Skip this, as they are rubbish for us

### Important Concepts in Angular

Angular is very very very complex and big to understand, whereas there are a few concepts which you can focus more on as you'll be using these only 90% of times.

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
