<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>DevLog Journal</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>📝 DevLog Journal</h1>
    <form id="logForm">
      <input type="text" id="title" placeholder="Log title..." required />
      <textarea id="description" placeholder="What did you work on today?" required></textarea>
      <button type="submit">Add Log</button>
    </form>
    <div id="logsList"></div>
  </div>

  <script src="script.js"></script>
</body>
</html>
