<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Inizio Questionario</title>
  <script>
    function redirectRandom() {
      const links = [
        "https://docs.google.com/forms/d/e/1FAIpQLSdVsD_W9jTwLwNSaoUPReQZZSiXTlFXqjmN4xDt7r9CIDd-PA/viewform?usp=header",  
        "https://docs.google.com/forms/d/e/1FAIpQLSeubtQRW6fFIXcaONtrX7XfY07wOo2A3ju0p2G1DfPB3nD6gw/viewform?usp=header",
        "https://docs.google.com/forms/d/e/1FAIpQLSf_UOQYkk1wh5hC9Y-FibaTUtw144gMbWLwuwhmMeSv5ENN0A/viewform?usp=header",
        "https://docs.google.com/forms/d/e/1FAIpQLSdRg68a04e_ouUL3j4uyeIGbHhkHmaS8UrAYeOhyuy9x2wKWg/viewform?usp=header"
      ];
      const randomIndex = Math.floor(Math.random() * links.length);
      window.location.href = links[randomIndex];
    }
  </script>
</head>
<body onload="redirectRandom()">
  <p>Attendi, stai per essere indirizzato al questionario...</p>
</body>
</html>
