# Rails as an API Study

Use your favorite search engine and the provided readings to research and answer
the following questions (no prior knowledge is expected).

In your answers, be sure to cite any relevant sources you consulted in your
search. We ask you to write answers in your own words in order to see how you
process what you've read. Please do not answer with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

Please note:

-   Many of the readings will mention the "view" layer. We won't be covering the
    view layer in this program.
-   For now, we'll use the `rails-api` gem to create rails applications.
    `rails-api` is set to become part of Rails 5. We will never type `rails
    new`, instead preferring `rails-api new`.

## Required Readings

-   [Starting Ruby on Rails: What I Wish I Knew | BetterExplained](http://betterexplained.com/articles/starting-ruby-on-rails-what-i-wish-i-knew/)
-   [Intermediate Rails: Understanding Models, Views and Controllers | BetterExplained](http://betterexplained.com/articles/intermediate-rails-understanding-models-views-and-controllers/)
-   [Getting Started with Rails — Ruby on Rails Guides](http://guides.rubyonrails.org/getting_started.html)
-   [The Rails Command Line — Ruby on Rails Guides](http://guides.rubyonrails.org/command_line.html)
-   [Rails Routing from the Outside In — Ruby on Rails Guides](http://guides.rubyonrails.org/routing.html)
-   [Action Controller Overview — Ruby on Rails Guides](http://guides.rubyonrails.org/action_controller_overview.html)

## Define Model Responsiblities

In your own words, define what the responsibilities of the model layer are in
Rails.

```md
The model layer is the one who actually does the work.  It is a class that
handles the dirty work of retrieving and storing data from the database. The
model also inherits the ActiveRecord class that is actually quite powerful.
It can recognize anonymous functions and match it to an equivalent.
```

## Define Controller Responsiblities

In your own words, define what the responsibilities of the controller layer are
in Rails.

```md
The controller is the classic boss. The controller dishes out orders without
resentment and effectively delegates duties to the model. They are in charge
of handling interactions such as requests and submissions.
```

## Define Router Responsiblities

In your own words, define what the router does in Rails.

```md
The router is the doorman it looks at http requests and determine which
controller action is equivalent to the request.  In rails there are seven
types of verbs while http request has 4.  Rails verb is a bit more intuitive
and is broken out into different phases.
```

## The Request-Response Cycle in Rails

Starting with a client making a GET request to a particular URL, describe how
the parts of Rails interact to produce and send a response.

[http://www.theodinproject.com/ruby-on-rails/routing](http://www.theodinproject.com/ruby-on-rails/routing)

```md
When a client makes a GET request it is sent to the router who determines what
kind of controller action needs to be taken. Then the class controller will take
over and starting issuing commands to bring the information to the user. The
controller will probably tell the model to get certain items and then display
it on the browser.

[http://gilmoursa.github.io/blog/%20Rails%20Request%20Response%20Cycle/](http://gilmoursa.github.io/blog/%20Rails%20Request%20Response%20Cycle/)



```
