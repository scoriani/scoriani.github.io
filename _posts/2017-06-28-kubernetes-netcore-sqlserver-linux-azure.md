---
layout: post
title:  "Running a .NET Core Web API and SQL Server on Linux in a Kubernetes cluster with Azure Container Service"
date:   2017-08-02 23:48:29
categories: posts
---

Goal of this document is to highlight some of the relevant steps required to run a .NET Core API app on a Kubernetes cluster on ACS. This app is interacting with a SQL Server instance running on a Linux container as part of the same Kubernetes cluster. During the deployment i also tested several monitoring tools including Application Insights, OMS and DataDog, to understand different aspects from host metrics to application performance monitoring.

### First step: Deploy Azure Container Service Kubernetes cluster



You'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.

![My helpful screenshot]({{ site.url }}/assets/test.jpg)

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll]:    http://jekyllrb.com
