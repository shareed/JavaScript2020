## [Components](https://www.youtube.com/watch?v=-jnp9FxCsYU&feature=youtu.be)
[Components](https://www.youtube.com/watch?v=1Z775bFt6xs&feature=youtu.be)
* components are made of several parts: HTML, CSS, or JavaScript brought together for reuse in a website or application
* JavaScript is used to consume the data and output the content into the DOM. JavaScript’s involvement in components is the glue that ties everything together
* Sometimes it makes sense to build several elements with similar functionality. Perhaps lots of components have click handlers that use the same callback, or a group of components shares the same style. This verbosity can be frustrating, but thankfully, it isn’t necessary to repeat yourself in code. Utilizing a Javascript function, we can create dynamic components on the fly and add them to the DOM.
* we want to create many buttons on our page. We could very quickly repeat the code there for each button we want to create, appending them to the parent each time. Although from our knowledge so far, we know that repeating ourselves is something we want to avoid. We can easily compartmentalize all of the code into a function. 