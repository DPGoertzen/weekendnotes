Introduction
============
*what does client-centric mean?
*Why are modules good for testability?
*What are RESTful web services?
*Asynchronous programming?
*It says we need the Karma library, along with node, but i don't remember installing that.

The Basics of AngularJS
=======================
*Ipv4 addresses look like this 192.168.1.1 . Ipv6 addresses look like a tire fire.
*"[Angular] is a framework that is primarily used to build single-page web applications" Why SPA?
*"Although this process is not complex, it [i.e. jquery] requires the developer to have knowledge of the entire DOM" good point. I imagine this becomes a headache in larger projects with multiple people working on the code.

Introducing Data Binding in AngularJS
=====================================
*"AngularJS takes a different approach. Instead of merging data into a template and replacing a DOM element, AngularJS creates live templates as a view."
*so ng-app doesn't need to live in the <HTML> tag?
*"the controller doesn’t have to worry about being in the mix of rendering the view. This fact virtually eliminates the concern of separating view and controller logic"
*"A value is considered dirty if it has changed since the last time the event loop ran."
*I'm amused that something called "dirty checking" is considered an efficient way to do things.
*I did not know that you could just put .controller right on the declaration of your app. Suppose it makes sense though.
*On Controllers: "The second argument is a definition function that defines how the controller will work."
*"Due to the nature of JavaScript itself and how it passes by value vs. reference, it’s considered a best-practice in Angular to bind references in the views by an attribute on an object, rather than the raw object itself." I think this is talking about that whole "primitive type" issue.
