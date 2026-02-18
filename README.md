<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Certificate Verification</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f6f8;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .card {
      background: white;
      padding: 30px;
      width: 400px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      text-align: center;
    }
    .verified {
      color: white;
      background: #28a745;
      padding: 10px;
      border-radius: 6px;
      font-weight: bold;
      margin-bottom: 20px;
    }
    .details {
      text-align: left;
      margin-top: 15px;
    }
    .details p {
      margin: 6px 0;
    }
    .footer {
      margin-top: 20px;
      font-size: 12px;
      color: #666;
    }
  </style>
</head>
<body>

<div class="card">
  <h2>Program Verification</h2>
  <div class="verified">VERIFIED</div>

  <div class="details">
    <p><strong>Name:</strong> John Smith</p>
    <p><strong>Program:</strong> Chess Fundamentals</p>
    <p><strong>Completion Date:</strong> January 15, 2026</p>
    <p><strong>Certificate ID:</strong> PR-2026-014</p>
  </div>

  <div class="footer">
    Verified by Data Chain Services<br>
    Scan Timestamp: <span id="timestamp"></span>
  </div>
</div>

<script>
  document.getElementById("timestamp").innerText = new Date().toLocaleString();
</script>

</body>
</html>
