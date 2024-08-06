# Live-User-Filter
# HTML 
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Live User Filter</title>
  </head>
  <body>
    <div class="container">
      <header class="header">
        <h4 class="title">Live User Filter</h4>
        <small class="subtitle">Search by name and/or location</small>
        <input type="text" id="filter" placeholder="Search">
      </header>

      <ul id="result" class="user-list">
        <li>
          <h3>Loading...</h3>
        </li>
      </ul>
    </div>
    <script src="script.js"></script>
  </body>
</html>
