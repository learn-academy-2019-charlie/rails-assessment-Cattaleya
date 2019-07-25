# Rails Assessments

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

### 1. What are some advantages of using Ruby on Rails?
CLEANER AND MORE ORGANIZED WORK.

### 2. How does Ruby on Rails use the Model View Controller (MVC) framework?
MVC is a pattern for the architecture of a software application. It separates an application into the following components: models, controllers, and views. 

### 3. Using the information given, complete the steps for creating a new view in a rails app by filling in the blanks:

  1. Create a route: 
  
  code: 
  ```
  get '/about' => 'statics#about' 
  ```
  file: config/routes
  
  2. Create the migratiion 
  
  code: rails -g migratiion (filename)


  ```
  class statics < ApplicationController
  
  def about 
    
  end
  ```
  
  file: statics_controller.rb
  
  3. Create the View
  
  code: <div> This is about you page</div>
  
  ```
  <div>This is the About page!</div>
  ```
  
  file:about.html.erb
  
  
### 4. Look at these sets of Rails routes, they are an example of which principle/term that we touched on briefly in class? Find the term, and explain why it is important.

```
/users/       method="GET"     # :controller => 'users', :action => 'index'
/users/1      method="GET"     # :controller => 'users', :action => 'show'
/users/new    method="GET"     # :controller => 'users', :action => 'new'
/users/       method="POST"    # :controller => 'users', :action => 'create'
/users/1/edit method="GET"     # :controller => 'users', :action => 'edit'
/users/1      method="PUT"     # :controller => 'users', :action => 'update'
/users/1      method="DELETE"  # :controller => 'users', :action => 'destroy'
```

### 5. What is the public folder used for in Rails?
the public folder is used to serve static files
### 6. Write a rails route for a controller called "main" and a page called "game" that takes in a parameter called "guess"
get '/game:guess'=> =main#guess 

### 7. What are cookies for? How do they work? What is the difference between a session and a cookie?
he main difference between a session and a cookie is that session data is stored on the server, whereas cookies store data in the visitor's browser. ... Data stored in cookie can be stored for months or years, depending on the life span of the cookie. But the data in the session is lost when the web browser is closed.

### 8. In an html form, what does the "action" attribute tell you about the form?  How do you designate the HTTP verb for the form?
the action attribute contains a site location to send from data to for processing

### 9. Why would you use an instance variable in a rails controller?
to solve the problem of exposing values from controller actions to view templates

### 10. Name two rails generator commands and what files they create:
rails g migrationL...=> generates basic migration file for database management rails controller..=>generates a basic controller file

### 11. Rails has a great community and lots of free tutorials to help you learn. Here is a list of some tutorials to choose from, choose one, do it, and then report back here at least one thing you learned. You can also use a different resource if you find one that you like better. 

- https://www.tutorialspoint.com/ruby-on-rails/index.htm
- http://railsforzombies.org
- http://guides.rubyonrails.org/getting_started.html
- 
-Rails Migration allows you to use Ruby to define changes to your database schema, making it possible to use a version control system to keep things synchronized with the actual code.
