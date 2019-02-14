# README

# night-out-planner

A javascript file that creates an interactibe website displaying events around the user's current or inputed location. 

## Demo & Tutorial

## FAQ, Technical Documentation, and API Reference

## Project Requirements

Must be a HTML/CSS/JS frontend with a Rails API backend. These should live in two separate repositories. All interactions between the client and the server should be handled asynchronously (AJAX).

Must render out a resource with at least one has-many relationship (that's two resources total) in the JSON.For example, if we were building Instagram, we might display a list of photos with associated comments. Both resources should be editable.

Must use your Rails API and a form generated by the client to create a resource and render the response without a page refresh. For example, if you create a new Photo post, and form data would be serialized, and submitted via an AJAX POST request, with the response being the new object in JSON and then appending that new photo to the DOM using JavaScript (ES6 Template Literals, can help out a lot with this).

No user authentication with passwords. When the page refreshes the current user will effectively be signed out. The way you learned this in the previous module relied on the fact that Rails was sending small pieces of data (cookies/sessions) back and forth along with every request and response. Now, we have two separate applications and need to use a slightly different pattern. We'll look at patterns for dealing with client-side auth later in the semester, so you'll have plenty of time to deal with this case.
