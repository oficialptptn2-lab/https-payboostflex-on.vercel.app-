# https-payboostflex-on.vercel.app-<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>PayBoost Flex</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Informasi PayBoost Flex">
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      height: 100vh;
      font-family: 'Segoe UI', Arial, sans-serif;
      background: linear-gradient(160deg,#00c853,#00a152,#007e33);
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
    }
    .container {
      width: 100%;
      max-width: 420px;
      padding: 20px;
    }
    .card {
      background: rgba(0,0,0,0.35);
      border-radius: 20px;
      padding: 36px 28px;
      text-align: center;
      box-shadow: 0 20px 60px rgba(0,0,0,0.45);
    }
    .logo {
      font-size: 28px;
      font-weight: 700;
      letter-spacing: 0.5px;
      margin-bottom: 8px;
    }
    .subtitle {
      font-size: 14px;
      opacity: 0.9;
      margin-bottom: 22px;
    }
    .desc {
      font-size: 14px;
      line-height: 1.6;
      opacity: 0.95;
      margin-bottom: 28px;
    }
    .btn {
      display: block;
      width: 100%;
      padding: 16px;
      background: #ffffff;
      color: #007e33;
      text-decoration: none;
      border-radius: 14px;
      font-weight: 700;
      font-size: 16px;
      transition: all 0.25s ease;
    }
    .btn:hover { background: #e8f5e9; transform: translateY(-1px); }
    .admin { margin-top: 18px; font-size: 13px; opacity: 0.85; }
    .note { margin-top: 14px; font-size: 11px; opacity: 0.65; line-height: 1.4; }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <div class="logo">PayBoost Flex</div>
      <div class="subtitle">Informasi & Panduan Layanan</div>

      <div class="desc">
        Klik tombol di bawah untuk langsung chat dengan Admin Moh Hanif di Telegram.
      </div>

      <!-- LINK TELEGRAM LANGSUNG -->
      <a class="btn" href="https://t.me/user?id=7760905169">
        💬 Chat Sekarang
      </a>

      <div class="admin">
        Admin: Moh Hanif
      </div>

      <div class="note">
        Halaman informasi saja.<br>
        Gunakan aplikasi resmi untuk layanan resmi.
      </div>
    </div>
  </div>
</body>
</html>
