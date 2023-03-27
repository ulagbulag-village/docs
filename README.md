# UlagBulag Village

Please visit https://ulagbulag.io/

## Local installation

```bash
# Install Ruby
#sudo dnf install ruby-devel rubygem-bundler

# Install the Ruby Gem
bundle install

# Initialize search data (creates search-data.json)
bundle exec just-the-docs rake search:init

# Run you local Jekyll server
bundle exec jekyll serve
```
