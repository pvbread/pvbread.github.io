<html lang="en">

<head>
    <title>
        CSRF - 02    </title>
    <meta charset="utf-8">
    <meta name="description" content="CSRF - 02">
    <link rel="stylesheet" media="all" href="https://flags.codepath.com//http/public/styles.css">
</head>

<body><link rel="stylesheet" media="all" href="https://flags.codepath.com//http/public/http_styles.css">
<div id="menu">
  <ul>
    <li><a href="https://flags.codepath.com//http/public/index.php">Public Site</a></li>
    <li><a href="https://flags.codepath.com//http/public/protected/index.php">Protected Site</a></li>
    <li><a href="https://flags.codepath.com//http/public/protected/logout.php" style="color: red;">Log out</a></li>
  </ul>
</div>

<div id="main-content">
  <h1>CSRF - 02</h1>

  <p>Only admins can update this info...</p>

  
  <form method="POST">
  	New Username:<br><br>
  	<input type="text" name="firstname"><br><br>
  	New Password:<br><br>
  	<input type="text" name="lastname">
  	<input type="hidden" name="csrf_token" value="admin">
  	<br><br>
  	<input type="submit" value="Update">
  </form>

  </div>

  </body>
  <footer>
  </footer>
</html>
