---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Author from '../../components/Author.astro';
title: Third Post
# publishDate: 19 Apr 2022
name: John Chaffee
# value: 101
description: John's first test post
---

<Author name={frontmatter.name} href="https://twitter.com/ChaffeeJohn" client:load />

My test post.

```javascript
// Example JavaScript

foo = "bar"
console.log(foo)
// => "bar"
```
