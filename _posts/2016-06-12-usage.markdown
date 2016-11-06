---
layout: post
title:  "Usage Guide"
description: Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Duis vehicula tincidunt lacus nec fringilla. Morbi molestie fringilla laoreet. Vestibulum venenatis ante in imperdiet venenatis. 
categories: jekyll update
img: image-7.jpg
categories: two
color: 37474F
author: webjeda
---

Use the guide to prepare good looking posts! The theme has a sidebar in the post layout which consists of post image, recent posts and facebook like box. This can be extended by editing the ``sidebar.html`` in **_includes** folder.

## Image

- Use 2 sizes of the same image. Keep the smaller one in ``images`` folder and the bigger one in ``images-hq`` folder.
- Make sure that both images have same name and extension.
- Mention image name in the front matter as shown below

{% highlight yml %}
---
layout: post
title:  "Some title"
categories: some category
img: image-name.jpg
---
{% endhighlight %}