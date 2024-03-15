# Ruby_On_Rails_Page
Creating a Welcome page ruby on Rails

# Steps take

* Create the controller of the view
  
      rails generate controller Welcome index
* Update the folder "routes.rb"

      Rails.application.routes.draw do
        get 'welcome/index'

        root 'welcome#index'
      end
* Customizing the file "app/views/welcome/index.html.erb"

      <p>Hello World</p>

