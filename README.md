<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Audio Portfolio</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      padding: 40px;
    }

    h1 {
      margin-bottom: 20px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background: white;
    }

    th, td {
      padding: 12px;
      border-bottom: 1px solid #ddd;
      text-align: left;
    }

    th {
      background: #222;
      color: white;
    }

    button.audio-btn {
      font-size: 18px;
      padding: 6px 10px;
      cursor: pointer;
      border: none;
      background: #222;
      color: white;
      border-radius: 6px;
    }

    button.audio-btn:hover {
      background: #444;
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
    <td>Explosion</td>
    <td>Game SFX</td>
    <td>
      <button class="audio-btn" onclick="toggleAudio(this, 'player1')">▶</button>
      <audio id="player1">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>
  </tr>

  <tr>
    <td>Ambient Wind</td>
    <td>Background atmosphere</td>
    <td>
      <button class="audio-btn" onclick="toggleAudio(this, 'player2')">▶</button>
      <audio id="player2">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>
  </tr>

  <tr>
    <td>Footsteps</td>
    <td>Foley recording</td>
    <td>
      <button class="audio-btn" onclick="toggleAudio(this, 'player3')">▶</button>
      <audio id="player3">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>
  </tr>

</table>

<script>
function toggleAudio(btn, id) {
  const audio = document.getElementById(id);

  // pause all other audio
  document.querySelectorAll("audio").forEach(a => {
    if (a !== audio) {
      a.pause();
    }
  });

  // reset all buttons
  document.querySelectorAll(".audio-btn").forEach(b => {
    if (b !== btn) {
      b.textContent = "▶";
    }
  });

  // toggle selected audio
  if (audio.paused) {
    audio.play();
    btn.textContent = "⏸";
  } else {
    audio.pause();
    btn.textContent = "▶";
  }
}
</script>

</body>
</html>
