Go to `source` branch (deployments are pushed to `gh-pages` branch)
Create a new post in `source/_posts`
(optional) `git add source/_posts/new_post.md`
(optional) `git commit -m "new post"`
`rake gen_deploy` OR `bundle exec rake gen_deploy`

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
