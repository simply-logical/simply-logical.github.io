# Simply Logical website #
This repository contains Simply Logical website.

# How to post #
Create a new file named `YYYY-mm-dd-title.md` in `_posts` directory to make a new blog post. You can specify the following options in your blog post:

* `layout: post`
* `title: Post title`
* `subtitle: Post subtitle!`
* `tags: [first, second]`
* `bigimg: /img/path.jpg`
* `gh-repo: simply-logical/simply-logical.github.io`
* `gh-badge: [star, fork, follow]`

Additionally, the following Markdown commands are available:

* code block
```
~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~
```

* coloured code block
~~~
```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```
~~~

* code block with line numbers
```
{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}
```

* note box
```
{: .box-note}
**Note:** This is a notification box.
```

* warning box
```
{: .box-warning}
**Warning:** This is a warning box.
```

* error box
```
{: .box-error}
**Error:** This is an error box.
```
