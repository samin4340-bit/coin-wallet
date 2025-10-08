# coin-wallet
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>Crypto Addresses</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      background-color: black; /* 바탕색 */
      font-family: Arial, sans-serif;
      color: white; /* 글자색 */
    }
    .wallet {
      margin: 20px 0;
      text-align: center;
    }
    .wallet img {
      width: 180px;
      height: 180px;
      margin-bottom: 10px;
    }
    .label {
      font-weight: bold;
      display: block;
      margin-bottom: 6px;
      font-size: 20px;
    }
    .addr {
      font-size: 16px;
      word-break: break-all;
    }
  </style>
</head>
<body>
  <div class="wallet">
    <span class="label">ETH</span>
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=180x180&data=0x3df5d451df98438fbf4eda15290520c7707c33fd" alt="ETH QR">
    <div class="addr">0x3df5d451df98438fbf4eda15290520c7707c33fd</div>
  </div>

  <div class="wallet">
    <span class="label">BTC</span>
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=180x180&data=bc1pugmz69jhpn0lrcqnqxqg0uz9yxs3sjqnn0v96cfw2sa0mlcdsv0q757q5k" alt="BTC QR">
    <div class="addr">bc1pugmz69jhpn0lrcqnqxqg0uz9yxs3sjqnn0v96cfw2sa0mlcdsv0q757q5k</div>
  </div>

  <div class="wallet">
    <span class="label">Solana</span>
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=180x180&data=68T3TrPtU3fDiAaj3Gdcs1QaxXJp2YLLvXG7Bx1a8s76" alt="Solana QR">
    <div class="addr">68T3TrPtU3fDiAaj3Gdcs1QaxXJp2YLLvXG7Bx1a8s76</div>
  </div>
</body>
</html>