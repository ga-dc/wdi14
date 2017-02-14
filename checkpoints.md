# Checkpoints

Here's a list of need to know concepts covered in each of the various weeks. Each week, we'll compile a list of everything we absolutely need to know moving forward as web developers. That is not to say that everything else we cover in class isn't important, but the things listed here are the absolute minimum requirements in order to be successful. If you find yourself looking over past weeks and are forgetting or misremembering a concept, you are highly encouraged to make sure to understand them throughout the entirety of the course(and as a developer).

## Week 1

### Javascript

- create an array stored to a variable
- create an object stored to a variable
- access values out of an array
- access values out of an object
- write a for loop
- use a loop to do something to each element of an array
- write an if/else conditional

### CLI && Git

- create a folder or file
- navigate your file system
- initialize git repo, make commits in git repo, use branches in git repo
- execute fork and pull model for git workflow (aka how to submit hw)

## Week 2

### DOM/jquery

- link script files to html
- load jQuery
- select elements in the DOM
- do things to jQuery objects like change css, text or html of an element
- get values from an input
- add an event listener to an element
- explain what a callback is

## Week 4

### Ruby

- Same programming fundamentals from week 1 for javascript only for ruby
- use the ruby `.each` method to iterate through a list and execute a block of code

### Ruby OOP
- Define a ruby class
- write an initialize method that sets instance variables
- create instances of an object using the `.new` method
- use `attr_accessor`, `attr_reader`, `attr_writer` to create getter/setter methods
- define an instance method
- define a class method
- write a ruby class that inherits from another class definition

### Active Record
- create and leverage a `Gemfile`
- link gem dependencies and other files in a ruby file
- create a database in postgres
- load a schema to a postgres database
- write a ruby class that inherits active record functionality
- write a ruby file that connects to a database
- use active record to do the following in a database:
  - create (`.create`, `.new`/`.save`)
  - read (`.all`, `.find`, `.find_by`, `.where`)
  - update (attr_accesors for columns, `.update`)
  - destroy (`.destroy`)
- leverage `has_many` and `belongs_to` helper methods to query databases and create data more effectively
- seed a database using a ruby program

### Rails

- rMVC flow
- making post, put, delete requests from forms
- rails form helper methods
- embedding ruby expressions
- configure routes.rb — nesting resources, RESTful routes, keywords except: and only:
- rake commands for db handling
- how to write a seeds.rb script
- generating models, controllers, and migrations from the command line

### AJAX, APIs
- Know distinction between synchronous & asynchronous program execution
- Know how to make all HTTP requests via AJAX
 - To **C**reate, **R**ead, **U**pdate, and **D**estroy data
- How to use promises to determine after-request behavior using `.done`, `.then`, `.fail`, `.always`
- Build an API in Rails
```rb
def index
    render json: SomeModel.all
end
```

Weeks 7-9

### Angular

- Setting & Applying an Angular module
- Injecting dependencies
 - Passing in a reference to a callback when defining Angular functionality (e.g. a controller, factory, service, route configuration, etc)
- **Using directives**
 - e.g. ng-model, ng-repeat, ng-click, ng-controller, ng-app, ui-view, ng-change, ng-if, ng-show, ng-hide, etc
- M-V-VM architecture and 2-way data-binding
- Using `ui.router` & the concept of states
 - Know what `$stateProvider` and `$state` do
 - Be able to implement `$stateProvider` and `$state`
 - Know what makes up a state (e.g. url, templateUrl, controller, controllerAs)
- Utilization of ngResource
 - Be able to build a Factory & connect to an API endpoint
- **Bonus:** Create a firebase backend (via firebase console on the web)
 - Connecting to Firebase via Angular (angularFire & firebase)
- **Bonus:** Setting up Angular on Rails

Weeks 10-11

### Express
- Create, deploy, and modify a simple Express app with views, embedded code, and data persistence
- Use Handlebars as a template engine to render views in Express
- Use and configure middleware such as body-parser for form submission
- Link to static assets in Express
- Describe the role of `npm` and `package.json`
- Explain the relationship between `require` and `module.exports`
- Understand Node and how it's used with Express

### ES6

- Understand block scoping
- Using `let` and `const`
- Use default parameters and arrow functions
- Use template literals
- Use destructuring to extract values from objects and arrays
- Leveraging destructuring for use with spread
- Understand import/export syntax with modules

### Mongo/Mongoose

- Distinguish between a SQL and NoSQL database
- Setup a local MongoDB server
- Understand documents in the context of MongoDB
- Explain how Mongoose uses schema and models
- Use Mongoose to implement CRUD
- Persist data using Mongoose embedded documents

### React

- Understand components and their role in web development
- Create and render components in the browser
- Use `props` to pass in data to a component
- Modify the `state` of a component
- Use React Router to deep link
- Use the axios library to retrieve data from a back end
- Pass state from parent components to children and vice versa
