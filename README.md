
# POS (point-­of-­sale)
A simple POS application for a coffee shop like Starbucks. There should
be a page for the selection of base drinks and their associated modifiers. A page for the
confirmation of purchase is also required showing the cost based on drink type and chosen
modifiers.

Examples of base drinks can be drip coffee, lattes, smoothies, etc. Each type of base drink has
the potential of being composed of several components. For example, drip coffee is only made of
coffee, while lattes are composed of espresso and steamed milk. Each drink can have modifiers
applied to them. For example, coffee can be modified by sugar or milk, while lattes can have
chocolate syrup or whipped cream added.

## Challenge
Evaluation your JavaScript knowledge and design in a simple model–view–viewmodel (MVVM) framework that
you have not previously used.

## Demo
![large-view](demo1.gif)
![phone-view](demo2.gif)

## APIs and technologies
* HTML5, CSS, JS, [Bootstrap](http://getbootstrap.com/): frone-end
* [SASS](http://sass-lang.com/): front-end 
* [Vuejs framework](http://vuejs.org/guide/#What-is-Vue-js)
* [Nodejs](https://nodejs.org/en/): back-end
* [Express](http://expressjs.com/): back-end
* [Gruntjs](http://gruntjs.com/): automation

## How to make it work on your machine after cloning on your local
* For development, you need sass on your system checkout [here](http://sass-lang.com/install).
* `npm install` will install all dependencies for the project.
* You have folder `dev`, for development.
* Install grunt-cli globally by typing `npm install -g grunt-cli`.
* In development mode, run `grunt watch` for automation purposes.
* If you just want to run the dstrubution version of the project, type `node server.js` or `npm start` in terminal, and in the browser url, type `http://localhost:3000/`

## License

The contents of this repository are covered under the [MIT License](LICENSE.txt).
