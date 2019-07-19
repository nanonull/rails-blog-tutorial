# Overview

Blog project setup by [Getting Started with Rails tutorial](https://guides.rubyonrails.org/getting_started.html) with static code analysis configured.

# Setup
_Tested on Ruby 2.5.5_
1. Clone or download repo.
2. Run command in project root to start server:  
ruby bin/rails server

3. View Home page:  
http://localhost:3000/

# Development

[Rubocop](https://github.com/rubocop-hq/rubocop) - static code analyzer and formatter:  

- Check all Ruby source files:  
Run command in project root: __rubocop__

- Try to fix all Ruby source files:  
Run command in project root: __rubocop -a__

- Fix code layout (formatting):  
Run command in project root: __rubocop -x__

[Brakeman](https://github.com/presidentbeef/brakeman) - static analysis tool for security vulnerabilities  
- Find security issues:  
Run command in project root: __brakeman__
