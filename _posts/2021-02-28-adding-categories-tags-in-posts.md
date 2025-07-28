---
thumbnail-img: /assets/img/posts/banner2.png
layout: post
author: athil
title: Adding Multiple Categories in Posts
date: 2025-07-28T22:11:39.952Z
thumbnail: /assets/img/posts/5.png
category: '[ "guides","jekyll", "sample_category" ]'
summary: Learn how to add categories in posts
keywords: devlopr jekyll, how to use devlopr, devlopr, how to use
  devlopr-jekyll, devlopr-jekyll tutorial,best jekyll themes, multi categories
  and tags
permalink: /blog/adding-categories-tags-in-posts/
usemathjax: false
tags: jekyll
---

## Adding Multiple Categories in Posts

To add categories in blog posts all you have to do is add a **category** key with category values in frontmatter of the post :

```yml
---
category: ['jekyll', 'guides', 'sample_category']
---
```

Then to render this category using link and pages. All we need to do is,

1. Create a new file with [your_category_name].md inside categories folder.

2. Copy categories/sample_category.md file and replace the content in [your_category_name].md in that. (Please don't copy the code below its just sample, since it renders the jekyll syntax dynamically)

```jsx
---
layout: page
title: Guides
permalink: /blog/categories/your_category_name/
---

<h5> Posts by Category : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.your_category_name %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>
```

Using the category, all the posts associated with the category will be listed on
`http://localhost:4000/blog/categories/your_category_name`