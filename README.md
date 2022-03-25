### Install 
````
sudo apt-get update -y && sudo apt-get upgrade -y
sudo apt-get install ruby-full
sudo gem update
gem install jekyll bundler
sudo gem install jekyll bundler
jekyll -v
````

### Create
```
jekyll new . --force

# ...then modify the Gemfile according to the comments in that file
# ...then modify _config.yml according to the comments in that file

# had to delete Gemfile.lock first to get the commands below to work without errors
bundle update
bundle update github-pages

```

### Run
```
bundle exec jekyll serve --livereload
```
