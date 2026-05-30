<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Happy 18th Birthday Nura 🎂</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to bottom, #ffe6f0, #ffffff);
      color: #d63384;
      text-align: center;
    }

    .container {
      padding: 50px 20px;
    }

    h1 {
      font-size: 40px;
    }

    h2 {
      font-size: 28px;
      margin-top: -10px;
    }

    p {
      font-size: 18px;
      max-width: 600px;
      margin: 20px auto;
      line-height: 1.6;
    }

    .card {
      background: white;
      border-radius: 20px;
      padding: 30px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
      margin-top: 30px;
    }

    .btn {
      margin-top: 20px;
      padding: 12px 25px;
      border: none;
      border-radius: 20px;
      background: #ff99cc;
      color: white;
      font-size: 16px;
      cursor: pointer;
    }

    .btn:hover {
      background: #ff66a3;
    }

    footer {
      margin-top: 50px;
      font-size: 14px;
      color: #999;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>🎀 Happy 18th Birthday 🎀</h1>
    <h2>Nura 🤍</h2>

    <div class="card">
      <p>
        Hari ini adalah langkah baru dalam hidupmu, Nura 🌸  
        Usia 18 bukan hanya tentang bertambahnya umur, tapi tentang tumbuhnya mimpi, harapan, dan keberanian.
      </p>

      <p>
        Semoga di usia ini, kamu semakin kuat menghadapi dunia,  
        semakin yakin dengan dirimu sendiri,  
        dan semakin dekat dengan semua impian yang kamu inginkan ✨
      </p>

      <p>
        Jangan lupa, kamu berharga, kamu cukup, dan kamu pantas bahagia 🤍
      </p>

      <button class="btn" onclick="showMessage()">Klik untuk doa 💌</button>

      <p id="doa" style="display:none;">
        Ya Allah,  
        Panjangkan umur Nura dalam kebaikan,  
        sehatkan tubuh dan hatinya,  
        mudahkan setiap langkahnya,  
        dan kabulkan semua doa serta harapannya 🤲✨  
        Jadikan dia pribadi yang selalu bahagia, kuat, dan penuh cinta.
      </p>
    </div>

    <footer>
      dibuat dengan penuh cinta untuk Nura 💖
    </footer>
  </div>

  <script>
    function showMessage() {
      document.getElementById("doa").style.display = "block";
    }
  </script>

</body>
</html>
