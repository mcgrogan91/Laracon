# Evan You - Vue.js Workshop

Vue.js: https://vuejs.org/

JS framework for modeling the state - templates render front end

### Components

* Pieces of functionality and display can be broken out into components
* Templates use them like they would use an html element

Vue keeps track of DOM state with a Virtual DOM - JS representation of the DOM (Much more lightweight)

When state updates, new VDOM is made and a diff is created and used to update the actual DOM
