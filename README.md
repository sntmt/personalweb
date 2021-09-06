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

###
> menu sup paginas
```javascript
<nav>
  <div><a href="/"><img class="logo" src="<%- config.root %>img/logo.png" /></a></div>
  <ul>
    <% site.pages.forEach(post=> { %>
      <li><a href="<%- config.root %><%- post.path %>">
          <%- post.title %>
        </a></li>
      <% }) %>
  </ul>
</nav>
```