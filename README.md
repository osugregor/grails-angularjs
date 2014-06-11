grails-angularjs
================
Some components I have been creating to help mesh Grails and AngularJS together. 

*This is a WIP.*

The Idea
========
Grails is awesome, and so is AngularJS. I have been looking into ways to merge the two. Some people will argue that meshing the two will couple them together so much as they can never be seperated; if you beleive this, these components are not for you.

I live by the idea if I am changing out the front end/back end its probably time to change both of them, not just one of them, or atleast update the frameworks/libraries I am using.

Templates
---------
AngularJS Templates are plain, static, boring html files. I want dynamic, cachable templates which can utalize the grails taglib framework, messaging libraries, and any Grails plugins I see fit.

AngularJS Template Preloading
-----------------------------
Making a bunch of seperate GET requests to all those templates/partials/directives are pointless if we can send them down with the intial request.

...more on this to come
