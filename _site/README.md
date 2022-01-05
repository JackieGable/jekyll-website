# jekyll-website
A simple Jekyll Website

# How to Setup a Simple Jekyll Website
In the terminal window type each line at the command prompt press enter after each line:
bundle init
bundle config set --local path 'vendor/bundle'
bundle add jekyll
bundle exec jekyll new --force --blank --skip-bundle .
bundle install 
bundle add wdm
bundle add webrick
bundle update
bundle exec jekyll serve --open-url http://localhost:4000/

# How to Commit the Repo to Github
