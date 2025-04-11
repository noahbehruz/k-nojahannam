# k-nojahannam
watch fılm and lıke 
<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KinoJahannam</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #1a1a1a;
      color: #fff;
    }

    header {
      background-color: #a80000;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    .search-bar {
      margin: 20px auto;
      display: flex;
      justify-content: center;
    }

    .search-bar input {
      padding: 10px;
      width: 60%;
      border-radius: 10px;
      border: none;
      font-size: 1em;
    }

    .movies {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .movie {
      background-color: #2a2a2a;
      padding: 15px;
      border-radius: 10px;
    }

    .movie h2 {
      margin-top: 0;
    }

    .comments {
      margin-top: 10px;
    }

    .comments textarea {
      width: 100%;
      height: 60px;
      margin-top: 5px;
      padding: 10px;
      border-radius: 5px;
      border: none;
      resize: none;
    }
  </style>
</head>
<body>

  <header>
    <h1>KinoJahannam 🎬</h1>
  </header>

  <div class="search-bar">
    <input type="text" placeholder="Film qidiring...">
  </div>

  <div class="movies">
    <div class="movie">
      <h2>Film nomi</h2>
      <p>Qisqacha tavsif: Juda qiziqarli film haqida...</p>
      <div class="comments">
        <label>Fikringizni yozing:</label>
        <textarea placeholder="Bu film haqida fikringiz..."></textarea>
      </div>
    </div>
    <!-- Yana filmlar shu tarzda qo‘shiladi -->
  </div>

</body>
</html>
