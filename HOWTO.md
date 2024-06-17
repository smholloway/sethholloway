How to blog on GitHub Pages using Jekyll, a Ruby static site generator
1. Create a new file in `_posts` named `yyyy-mm-dd-title.md`
2. Update the front matter
```
---
layout: post
title: Title Here
type: post
---
```
3. Write your post in markdown
4. Add it to git and push to GitHub (`git add _posts/...`, `git commit -m "foo"`, `git push`)
5. Wait for the build to complete in https://github.com/{org}/{repo}/settings/pages ([https://github.com/smholloway/sethholloway/settings/pages](https://github.com/smholloway/sethholloway/settings/pages))
6. Navigate to your site and enjoy! ([https://sethholloway.com/](https://sethholloway.com))

To test, run `bundle exec jekyll serve --watch` and open http://localhost:3000

# Working with Ruby
```
rbenv install 3.1.4
rbenv local 3.1.4
gem install bundler
bundle install
rbenv rehash
```

At the time of writing, this site was using Ruby 3.1.4 and Jekyll 4.2 with the Minima theme ~3.0.
