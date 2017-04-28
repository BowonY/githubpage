---
layout: post
title:  "Setting up Jekyll!"
date:   2017-04-27 19:43:18 -0400
categories: jekyll update
---
##

$ gem install bundler

$ gem install jekyll

$ git init

$ git add .

$ git remote add origin https://github.com/BowonY/bowony.github.io.git

$ git branch -m master gh-pages

$ git checkout gh-pages

$ git commit -m "initial jekyll"

$ git push origin gh-pages # this was because master branch had other codes

$

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
