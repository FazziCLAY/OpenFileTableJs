# OpenFileTableJs (JavaScript)
## Script for adding file tables to your site (suitable for index pages)

## Example (index.html)
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>OpenFileTableJs</title>
  <link rel="stylesheet" type="text/css" href="./style.css">
  <script src="./openfiletable.js"></script>
</head>
<body>                                                                     
  <div id="openfiletable">
    <h1 id="openfiletable_loading">Loading...</h1>
    <h2 id="openfiletable_error"></h2>
  </div>
</body>
<script type="text/javascript">
  let app = new OpenFileTable("openfiletable", ["Name", "Date", "Description"], "name", false);
  app.load("./index.json", "openfiletable_loading", "openfiletable_error");
</script>
</html>
```
check index.json file!

![image](https://user-images.githubusercontent.com/68351787/174962828-c96c8f70-e899-4178-adec-cb00063433b5.png)
