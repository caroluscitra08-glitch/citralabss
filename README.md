<!DOCTYPE html>
<html>
<head>
  <title>CitraLabs</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f5ff;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .box {
      background: white;
      width: 90%;
      max-width: 400px;
      padding: 25px;
      border-radius: 15px;
      box-shadow: 0 5px 20px #ccc;
      text-align: center;
    }

    h1 {
      color: #2563eb;
    }

    input, textarea {
      width: 100%;
      padding: 12px;
      margin: 8px 0;
      border-radius: 8px;
      border: 1px solid #ccc;
      box-sizing: border-box;
    }

    textarea {
      height: 120px;
    }

    button {
      width: 100%;
      padding: 12px;
      background: #2563eb;
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background: #1d4ed8;
    }
  </style>
</head>

<body>

<div class="box">
  <h1>CitraLabs</h1>
  <p>Kirim pesan kepada kami</p>

  <form action="https://formsubmit.co/EMAILKAMU@gmail.com" method="POST">

    <input type="text" name="nama" placeholder="Nama kamu" required>

    <input type="email" name="email" placeholder="Email kamu" required>

    <textarea name="pesan" placeholder="Tulis pesan..." required></textarea>

    <button type="submit">Kirim Pesan</button>

  </form>
</div>

</body>
</html># 