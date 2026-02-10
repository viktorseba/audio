
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Audio Samples</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      padding: 30px;
    }

    h1 {
      margin-bottom: 5px;
    }

    h2 {
      margin-top: 0;
      font-weight: normal;
      color: #555;
    }

    .author {
      margin-bottom: 30px;
      font-style: italic;
      color: #777;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background: white;
    }

    th, td {
      border: 1px solid #ddd;
      padding: 10px;
      text-align: center;
      vertical-align: top;
    }

    th {
      background: #222;
      color: white;
    }

    .meta {
      text-align: left;
      min-width: 160px;
    }

    .spectrogram {
      width: 100%;
      max-width: 180px;
      display: block;
      margin: 0 auto 6px auto;
    }

    .audio-btn {
      font-size: 16px;
      padding: 5px 10px;
      cursor: pointer;
      border: none;
      background: #222;
      color: white;
      border-radius: 5px;
    }

    .audio-btn:hover {
      background: #444;
    }
  </style>
</head>

<body>

<h1>Master Thesis | Audio Samples</h1>
<h2>This is the title of the thesis which we dont know yet</h2>
<div class="author">Jonas Myhre Schiøtt, Viktor Sebastian Petersen</div>

<table> 
  <tr>
    <th class="meta">Category</th>
    <th class="meta">Description</th>

    <th>Ground Truth</th>
    <th>w=1.5</th>
    <th>w=3.0</th>
    <th>w=7.0</th>
  </tr>

  <!-- ROW 1 -->
  <tr>
    <td class="meta">AudioCaps 839</td>
    <td class="meta">Source 1</td>

    <!-- Cell 1 -->
    <td>
      <img src="w_exp/spec/51_gt_A_esc50.png" class="spectrogram">
      <button class="audio-btn" onclick="toggleAudio(this, 'a1')">▶</button>
      <audio id="a1">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>

    <!-- Cell 2 -->
    <td>
      <img src="w_exp/spec/51_pred_A_esc50_low.png" class="spectrogram">
      <button class="audio-btn" onclick="toggleAudio(this, 'a1')">▶</button>
      <audio id="a1">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>

    <!-- Cell 3 -->
    <td>
      <img src="w_exp/spec/51_pred_A_esc50_mid.png" class="spectrogram">
      <button class="audio-btn" onclick="toggleAudio(this, 'a1')">▶</button>
      <audio id="a1">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>

    <!-- Cell 4 -->
    <td>
      <img src="w_exp/spec/51_pred_A_esc50_high.png" class="spectrogram">
      <button class="audio-btn" onclick="toggleAudio(this, 'a1')">▶</button>
      <audio id="a1">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>
  </tr>

  <!-- ROW 2 -->
  <tr>
    <td class="meta">AudioCaps 839</td>
    <td class="meta">Source 2</td>

    <!-- Cell 1 -->
    <td>
      <img src="w_exp/spec/51_gt_B_esc50.png" class="spectrogram">
      <button class="audio-btn" onclick="toggleAudio(this, 'a1')">▶</button>
      <audio id="a1">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>

    <!-- Cell 2 -->
    <td>
      <img src="w_exp/spec/51_pred_B_esc50_low.png" class="spectrogram">
      <button class="audio-btn" onclick="toggleAudio(this, 'a1')">▶</button>
      <audio id="a1">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>

    <!-- Cell 3 -->
    <td>
      <img src="w_exp/spec/51_pred_B_esc50_mid.png" class="spectrogram">
      <button class="audio-btn" onclick="toggleAudio(this, 'a1')">▶</button>
      <audio id="a1">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>

    <!-- Cell 4 -->
    <td>
      <img src="w_exp/spec/51_pred_B_esc50_high.png" class="spectrogram">
      <button class="audio-btn" onclick="toggleAudio(this, 'a1')">▶</button>
      <audio id="a1">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>
  </tr>

  <!-- ROW 3 -->
  <tr>
    <td class="meta">AudioCaps 839</td>
    <td class="meta">Source 1 + Source 2</td>

    <!-- Cell 1 -->
    <td>
      <img src="w_exp/spec/51_gt_mix_esc50.png" class="spectrogram">
      <button class="audio-btn" onclick="toggleAudio(this, 'a1')">▶</button>
      <audio id="a1">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>

    <!-- Cell 2 -->
    <td>
      <img src="w_exp/spec/51_pred_mix_esc50_low.png" class="spectrogram">
      <button class="audio-btn" onclick="toggleAudio(this, 'a1')">▶</button>
      <audio id="a1">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>

    <!-- Cell 3 -->
    <td>
      <img src="w_exp/spec/51_pred_mix_esc50_mid.png" class="spectrogram">
      <button class="audio-btn" onclick="toggleAudio(this, 'a1')">▶</button>
      <audio id="a1">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>

    <!-- Cell 4 -->
    <td>
      <img src="w_exp/spec/51_pred_mix_esc50_high.png" class="spectrogram">
      <button class="audio-btn" onclick="toggleAudio(this, 'a1')">▶</button>
      <audio id="a1">
        <source src="audios/catdog.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
</table>

<script>
function toggleAudio(btn, id) {
  const audio = document.getElementById(id);

  // stop all other audio
  document.querySelectorAll("audio").forEach(a => {
    if (a !== audio) {
      a.pause();
      a.currentTime = 0;
    }
  });

  // reset all buttons except current
  document.querySelectorAll(".audio-btn").forEach(b => {
    if (b !== btn) {
      b.textContent = "▶";
    }
  });

  // play/pause toggle
  if (audio.paused) {
    audio.play();
    btn.textContent = "⏹";
  } else {
    audio.pause();
    audio.currentTime = 0;
    btn.textContent = "▶";
  }

  // when audio finishes → reset button to play
  audio.onended = function() {
    btn.textContent = "▶";
  };
}
</script>

</body>
</html>
