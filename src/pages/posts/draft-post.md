---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Author from '../../components/Author.astro';
title: Draft Post
# publishDate: 19 Apr 2022
name: John Chaffee
# value: 101
description: John's first test post
draft: true
---

<Author name={frontmatter.name} href="https://twitter.com/ChaffeeJohn" client:load />

blah.

```javascript
// Example JavaScript

foo = "bar"
console.log(foo)
// => "bar"
```
