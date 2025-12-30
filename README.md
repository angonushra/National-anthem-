<!DOCTYPE html>
<html lang="ha">
<head>
<meta charset="UTF-8">
<title>National Anthem of Nigeria</title>
</head>

<body style="text-align:center; font-family:Arial">

<h2>🇳🇬 National Anthem of Nigeria</h2>

<audio id="anthem" autoplay muted controls>
  <source src="anthem.m4a" type="audio/mp4">
  Browser ɗinka bai goyi bayan audio ba
</audio>

<br><br>

<button onclick="toggleSound()">🔕 / 🔉</button>

<script>
function toggleSound(){
  const audio = document.getElementById("anthem");
  audio.muted = !audio.muted;
}
</script>

</body>
</html>
