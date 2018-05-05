# Rails Templates

Quickly generate a rails app with the default [MihiVai](https://www.mihivai.com) configuration
using [Rails Templates](http://guides.rubyonrails.org/rails_application_templates.html).

Get a minimal rails 5.1+ app ready to be deployed on Heroku with Bootstrap, Simple form, debugging gems and Devise install with a generated `User` model.

```bash
rails new \
  --database postgresql \
  -m https://raw.githubusercontent.com/Joz84/rails-templates/master/devise.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```
