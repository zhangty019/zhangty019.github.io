---
layout: post
title: Support Generation for Robot-Assisted 3D Printing with Curved Layers
subtitle: IEEE International Conference on Robotics and Automation (ICRA), London, UK
# cover-img: /assets/img/curvedSupport/teaser.jpg
thumbnail-img: /assets/img/curvedSupport/teaser.jpg
# share-img: /assets/img/path.jpg
# gh-repo: daattali/beautiful-jekyll
# gh-badge: [star, fork, follow]
# tags: [test]
# comments: true
author: Tianyu Zhang
---

# ![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)
![printing_result](/assets/img/curvedSupport/printing_result.gif)
# <img src="/assets/img/curvedSupport/printing_result.gif" width="160" height="90" />
![hardware](/assets/img/curvedSupport/hardware.jpg){: .mx-auto.d-block :}

Robot-assisted 3D printing has drawn a lot of attention because of its capability to fabricate curved layers that are optimized according to different objectives. However, **the support generation algorithm based on a fixed printing direction for planar layers cannot be directly applied to curved layers** as the orientation of material accumulation is dynamically varied. In this project, we propose **a skeleton-based support generation method for robot-assisted 3D printing with curved layers**. 

**Here is some bold text**

## Here is a secondary heading

[This is a link to a different site](https://deanattali.com/) and [this is a link to a section inside this page](#local-urls).

Here's a table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |

How about a yummy crepe?

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

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

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})