```
<!DOCTYPE html>
<html>
  <head>
    <title>SubsLink</title>
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <%= csrf_meta_tags %>
    <%= csp_meta_tag %>

    <%= stylesheet_link_tag 'application', media: 'all', 'data-turbolinks-track': 'reload' %>
    <%= javascript_pack_tag 'application', 'data-turbolinks-track': 'reload' %>
  </head>

  <body>
    <%= render 'layouts/header' %>
      <main>
        <p id="notice"><%= notice %></p>
        <%= yield %>
      </main>
    <%= render 'layouts/footer' %>
  </body>
</html>
```/
