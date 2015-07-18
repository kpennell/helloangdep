# hello-angular-1
A simple example of Hello World in [Angular 1.x](https://angularjs.org/) syntax.

##What is this?
This example shows how to take a model property defined in a Controller and populate it within an Angular view. 

###Within the application-controller.js
A model property `place` has been added to the controller instance via `this`. Why? Controllers in Angular are simply constructors.

###Within the index.html
Via a template: As a template all that needs to be done is to add `{{ac.place}}` within our index.html document. 

Via a directive: As a directive a new HTML tag is created `<di-hello></di-hello>`. This tag expects an attribute with the model property defined on it `<di-hello place="{{ac.place}}"></di-hello>` .

##Instructions
1. Install [NodeJS](https://nodejs.org/)
2. Run `npm start` to get the application running on the web server
    * Packages needed for this application will be installed (i.e. Angular and Express)
    * The Node/Express Web Server will start
3. Go to `http://localhost:8080/src` in your web browser
4. You can also try this out at this [Plunker](http://plnkr.co/edit/JsKGud?p=preview)

##Where to go from here?
[DevelopIntelligence](http://www.developintelligence.com/) offers a variety of [classes on Angular](http://www.developintelligence.com/catalog/web-development-training/angularjs). Check out the [Introduction to AngularJS](http://www.developintelligence.com/catalog/web-development-training/angularjs/introduction-to-angularjs) or the [AngularJS Boot Camp](http://www.developintelligence.com/catalog/web-development-training/angularjs/angularjs-boot-camp) to get your team up to speed.
# helloangdep
