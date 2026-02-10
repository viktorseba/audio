<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>These are my catdogs</title>
  <style>
    body {
      font-family: Arial;
      padding: 40px;
      background: #f4f4f4;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      background: white;
    }
    th, td {
      padding: 12px;
      border: 1px solid #ddd;
      text-align: left;
    }
    th {
      background: #333;
      color: white;
    }
  </style>
</head>
<body>

<h1>My Audio Samples</h1>

<table>
  <tr>
    <th>Title</th>
    <th>Description</th>
    <th>Play</th>
  </tr>

  <tr>
    <td>Sample 1</td>
    <td>Catdog</td>
    <td>
      <audio controls>
        <source src="catdog.wav" type="audio/wav">
      </audio>
    </td>
  </tr>

  <tr>
    <td>Sample 2</td>
    <td>Also catdog</td>
    <td>
      <audio controls>
        <source src="catdog.wav" type="audio/wav">
      </audio>
    </td>
  </tr>

</table>

</body>
</html>

