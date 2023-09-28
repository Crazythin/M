

```html
<!DOCTYPE html>
<html>
<head>
  <title>Dominion University - Student Login Catalog</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
    }
    
    h1 {
      text-align: center;
    }
    
    form {
      max-width: 400px;
      margin: 20px auto;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
      background-color: #f5f5f5;
    }
    
    label {
      display: block;
      margin-bottom: 10px;
    }
    
    input[type="text"],
    input[type="password"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 3px;
    }
    
    input[type="submit"] {
      width: 100%;
      padding: 10px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 3px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>Dominion University - Student Login Catalog</h1>
  <form>
    <label for="username">Username:</label>
    <input type="text" id="username" name="username" placeholder="Enter your username">
    
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" placeholder="Enter your password">
    
    <input type="submit" value="Login">
  </form>
</body>
</html>
```
