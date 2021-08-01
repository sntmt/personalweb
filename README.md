# SNTMT web 2021

## development

> run
```bash
npm run server
``` 

### Snippets
> Loop de posts
```javascript
<% site.posts.forEach(post => { %>
  <li><a href="<%- post.path %>"><%- post.title %></a></li>
<% }) %>
```