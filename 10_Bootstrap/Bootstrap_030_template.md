# Bootstrap 030 Template

The following is a Bootstratp 5 template.

- Leave in the "viewport" meta tag. Bootstrap 5 needs it.
- Put the reference to the Bootstrap stylesheet in the head
  - The link to the stylesheet should appear **_before_** any local stylesheets. This allows the local stylesheets to override Bootstrap defaults
  - I like to put the Bootstrap CDN reference before the &lt;title> tag, and local links and &lt;style> tags after the title,
- The script tag for JavaScript should appear at the end of the body.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />

    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6"
      crossorigin="anonymous"
    />
    <title>Bootstrap</title>
    <!-- Local stylesheets go here -->
  </head>
  <body>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
```
