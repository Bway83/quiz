# Guess-what-quiz
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name ="author" content="Blaine Way">

    <title>Document</title>
<title>Guess What?</title>
<link rel="stylesheet" type="text/css" href="./style.css">
</head>

<body>
<header>
  <h1>Guess What?</h1>
  <div class="timer">Time: <span id="time">0</span></div>
</header>

<main>
  <section id="begin-screen" class="begin">
    <button id="begin">BEGIN</button>
  </section>

  <section id="questions"> </section>

  <section id="end-screen" class="hide">
    <h2>Score: <span id="score"></span> </h2>
    <form> Submit initials: <input type="text" id="initials" max="3" /></form>
    <button id="submit">Submit</button>
  </section>

  <section class="hide">
    <button>High Scores</button>
    <button>Reset Score</button>
  </section>
</main>

<script src="script.js"></script>

</body>

</html>
