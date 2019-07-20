# Overview

Blog project done in [Getting Started with Rails tutorial](https://guides.rubyonrails.org/getting_started.html) with static code analysis configured.

# Setup
_Tested on Ruby 2.5.5_
1. Setup Ruby on Rails using [tutorial](https://www.tutorialspoint.com/ruby-on-rails/rails-installation)
2. Clone or download repo.
3. Run command to install gems:  
`bundler install`
4. Create settings file with server credentials at __config/credentials.yml__ (refer to __credentials.example.yml__)
5. Run command in project root to start server:  
`ruby bin/rails server`
6. View Home page:  
http://localhost:3000/

# Development

[Rubocop](https://github.com/rubocop-hq/rubocop) - static code analyzer and formatter:  

- Check all Ruby source files:  
Run command in project root: `rubocop`

- Try to fix all Ruby source files:  
Run command in project root: `rubocop -a`

- Fix code layout (formatting):  
Run command in project root: `rubocop -x`

[Brakeman](https://github.com/presidentbeef/brakeman) - static analysis tool for security vulnerabilities  
- Find security issues:  
Run command in project root: `brakeman`
