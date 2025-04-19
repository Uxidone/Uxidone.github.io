<!DOCTYPE html>
<html lang="lv">
  <head>
    <meta charset="UTF-8" />
    <title>Uxione — Sākumlapa</title>
    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      body {
        font-family: 'Segoe UI', sans-serif;
        background: linear-gradient(135deg, #1f1c2c, #928dab);
        color: #f5f5f5;
        min-height: 100vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        text-align: center;
        padding: 2rem;
      }

      h1 {
        font-size: 3.5rem;
        margin-bottom: 0.5rem;
        background: linear-gradient(to right, #00f2fe, #4facfe);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        animation: fadeIn 1s ease-in-out;
      }

      p {
        font-size: 1.3rem;
        margin-bottom: 2rem;
        max-width: 600px;
        animation: fadeIn 1.3s ease-in-out;
      }

      a.button {
        display: inline-block;
        background-color: #00c9a7;
        color: white;
        text-decoration: none;
        padding: 14px 28px;
        font-size: 1.1rem;
        border-radius: 50px;
        transition: background-color 0.3s ease, transform 0.2s ease;
        animation: fadeIn 1.6s ease-in-out;
      }

      a.button:hover {
        background-color: #008e76;
        transform: scale(1.05);
      }

      footer {
        position: absolute;
        bottom: 20px;
        font-size: 0.85rem;
        color: rgba(255, 255, 255, 0.5);
        animation: fadeIn 2s ease-in-out;
      }

      @keyframes fadeIn {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
      }

      @media (max-width: 600px) {
        h1 {
          font-size: 2.5rem;
        }
        p {
          font-size: 1.1rem;
        }
        a.button {
          font-size: 1rem;
          padding: 12px 20px;
        }
      }
    </style>
  </head>
  <body>
    <h1>Sveicināts Uxione</h1>
    <p>Profesionāla pieeja, moderna pieredze. Uzzini vairāk par mūsu projektiem un digitālajiem risinājumiem.</p>
    <a class="button" href="/majas">Ieej vietnē</a>
    <footer>
      © 2025 Uxione. Visas tiesības aizsargātas.
    </footer>
  </body>
</html>
