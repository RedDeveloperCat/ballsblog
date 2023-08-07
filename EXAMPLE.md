---
layout: post
title:  "Post Name Bruh"
tags: fbi-van
---

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

## add images to this thing like: 
![Image]({{ site.baseurl }}/images/image1.png)

## Keep your local repository in sync:
From now on, whenever you make changes to your local Jekyll project, commit those changes and push them to GitHub:

```bash
git add .
git commit -m "Your commit message"
git push origin master
```

Your GitHub Pages site will be updated automatically every time you push changes to the master branch.

That's it! Your Jekyll blog site should now be deployed to GitHub Pages and synced with the local repository on your machine