<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Redirecting...</title>
    <script>
      // Array dei link ai tuoi 4 moduli Google Forms
      const urls = [
        "https://docs.google.com/forms/d/e/1FAIpQLSdVsD_W9jTwLwNSaoUPReQZZSiXTlFXqjmN4xDt7r9CIDd-PA/viewform?usp=header",  
        "https://docs.google.com/forms/d/e/1FAIpQLSeubtQRW6fFIXcaONtrX7XfY07wOo2A3ju0p2G1DfPB3nD6gw/viewform?usp=header",
        "https://docs.google.com/forms/d/e/1FAIpQLSf_UOQYkk1wh5hC9Y-FibaTUtw144gMbWLwuwhmMeSv5ENN0A/viewform?usp=header",
        "https://docs.google.com/forms/d/e/1FAIpQLSdRg68a04e_ouUL3j4uyeIGbHhkHmaS8UrAYeOhyuy9x2wKWg/viewform?usp=header"
      ];
 // Sceglie casualmente un modulo
      const index = Math.floor(Math.random() * urls.length);

      // Reindirizza all'URL selezionato
      window.location.href = urls[index];
    </script>
  </head>
  <body>
    <p>Stai per essere reindirizzato al questionario...</p>
  </body>
</html>
