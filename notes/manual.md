## A Manual for the Dumb User

A personal manual for myself to remember how to do stuff.




## Ruby commands

`bundle install`: install gems listed in Gemfile. Checks Gemfile and Gemfile.lock, only installs **missing** or **outdated** gems.

`bundle exec jekyll serve`: serve the Jekyll site locally.

`bundle update github-pages`: update the `github-pages` gem to the latest version, and update all its dependencies. important to sync my local github-pages gem with github-pages gem on the Github Pages server.



## Facts

If you want to use a build process other than Jekyll or you do not want a deidcated branch to hold your compiled static files, use Github Actions workflow. Github provide workflow templates.