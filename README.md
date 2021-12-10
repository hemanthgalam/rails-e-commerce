# rails-e-commerce
The purpose of this project was to:

Become familiar with Ruby and the Rails framework
Learn how to navigate an existing code-base
Use existing code style and approach to implement new features
Gain experience handling feature and bug-fix requests
**Starting**
Clone the repo to run locally
Run bundle install to install dependencies
Create config/database.yml by copying config/database.example.yml
Create config/secrets.yml by copying config/secrets.example.yml
Run bin/rake db:reset to create, load and seed db
Create .env file based on .env.example
Sign up for a Stripe account
Put Stripe (test) keys into appropriate .env vars
Optional: Mailcatcher can be used to capture outgoing emails from the server. Should you wish to view the emails, run gem install mailcatcher and then type mailcatcher to get started.
Run bin/rails s -b 0.0.0.0 to start the server
