# devise-invitable example application

Requires Ruby 1.9.2 or higher.

I borrowed the code from the following railscast and added devise invitable on top of it to learn how it works.

RailsCasts Episode #209: Devise (revised):
http://railscasts.com/episodes/209-devise-revised

## Getting Started
*   Go into the blog-invitable directory.

*   Set up the following environment variables:
```
MAIL_PASSWORD=[your gmail password]
MAIL_USERNAME=[your gmail username]
```

*   rake db:migrate

*   rails s

*   Pull up the app:

http://localhost:3000

*   Register for an account

*   After you're signed up and logged in, go to:

http://localhost:3000/users/invitation/new


