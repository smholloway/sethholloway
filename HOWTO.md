1. Go to `source` branch (deployments are pushed to `gh-pages` branch)
2. Create a new post in `source/_posts`
3. (optional) `git add source/_posts/new_post.md`
4. (optional) `git commit -m "new post"`
5. `rake gen_deploy` OR `bundle exec rake gen_deploy`

To test, run `jekyll serve` or `rake generate` then `open public/<file>`

# Working with Ruby
```
rbenv install 2.3.8
rbenv local 2.3.8
rbenv rehash
gem install bundler
bundle install
rbenv rehash
```
