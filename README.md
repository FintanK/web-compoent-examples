# Web Components

These examples provide some examples of how web components are structured in different JS frameworks.

What are web components?
========================

Web Components are a set of standards currently being produced by Google engineers as a W3C specification that allow for the creation of reusable widgets or components in web documents and web applications.
The intention behind them is to bring component-based software engineering to the World Wide Web.

Angular directives vs. Custom Elements
=======================================

"Polymer (more specifically Shadow DOM) provides the ability to compose encapsulated JS, CSS, and HTML as Custom Elements, much like Angular element directives.

Angular directives are conceptually similar to Custom Elements but they are implemented without the use of the Web Components APIs. Angular directives are a way to build custom elements, but Polymer and the Web Components specification are the standards-based way to do it.

Similar to Angular, Polymer elements provide templating and bi-directional data binding. However, they also provide new functionality such as the Shadow DOM, which enables encapsulation of CSS. Angular directives don’t have any notion of style encapsulation, but Angular is expected incorporate that functionality eventually.

In the future, both will be used together. Because custom elements will be the DOM, they’ll work seamlessly with frameworks like Angular. The Angular team has said they will eventually use the underlying Web Components APIs (Custom Elements, Shadow DOM, etc.)."

From http://www.binpress.com/blog/2014/06/26/polymer-vs-angular/


# Useful Resources

W3C Specifications
====================

Web Components Current Status - https://www.w3.org/standards/techs/components#w3c_all
Custom Elements - http://w3c.github.io/webcomponents/spec/custom/
HTML Imports - http://w3c.github.io/webcomponents/spec/imports/
Shadow DOM - http://w3c.github.io/webcomponents/spec/shadow/


Polymer - https://www.polymer-project.org/1.0/
==============================================

![](https://elements.polymer-project.org/images/polymer.svg)

https://elements.polymer-project.org/
https://builtwithpolymer.org/ - Great examples of projects built with Polymer

Ember JS - http://emberjs.com/
==============================

![](http://www.gravatar.com/avatar/0cf15665a9146ba852bf042b0652780a?s=200)

https://guides.emberjs.com/v1.10.0/components/ - Ember Components


Other
=====

https://customelements.io/ - A comprehensive directory of web components which can be used for your projects.
http://caniuse.com/#search=components - Support for custom elements across browsera
