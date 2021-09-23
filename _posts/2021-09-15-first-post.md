---
layout: post
title: First Post
subtitle: my lovely first post
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

I shall begin my lovely post by linking a [random](https://randomwebsite.com/) - i hope you find it highly enjoyable.

**but wait**

## there's more

allow me to show you this important table:

| 1 | 2 | 3 |
| :------ |:--- | :--- |
| ren | is | so |
| cool | bc | she |
| made | this | website |
| ha | ha | ha |


Do you like these images?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

![crepe](/assets/img/funny-weird-wtf-stock-photos-19-5a3926af95d9d__700.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
