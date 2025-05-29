<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Brava Joalheria - Loja Virtual</title>
  <style>
    /* Estilos básicos */
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #fafafa;
      color: #222;
    }
    header {
      background: #111;
      color: gold;
      padding: 1rem;
      text-align: center;
      font-size: 1.8rem;
      font-weight: bold;
      letter-spacing: 0.1rem;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1rem;
      background: #222;
      padding: 0.5rem 0;
    }
    nav button {
      background: gold;
      border: none;
      padding: 0.6rem 1.2rem;
      font-weight: bold;
      cursor: pointer;
      border-radius: 4px;
    }
    main {
      max-width: 900px;
      margin: 1rem auto;
      padding: 0 1rem;
    }
    .hidden {
      display: none;
    }
    /* Formulários */
    form {
      background: white;
      padding: 1rem;
      border-radius: 6px;
      box-shadow: 0 0 6px rgba(0,0,0,0.1);
      max-width: 400px;
      margin: 1rem auto;
    }
    form label {
      display: block;
      margin-top: 1rem;
      font-weight: bold;
    }
    form input[type="text"], form input[type="email"], form input[type="password"] {
      width: 100%;
      padding: 0.6rem;
      margin-top: 0.3rem;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1rem;
    }
    form button {
      margin-top: 1.2rem;
      background: gold;
      border: none;
      padding: 0.8rem;
      width: 100%;
      font-weight: bold;
      cursor: pointer;
      border-radius: 4px;
      font-size: 1.1rem;
    }
    /* Produtos */
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(180px,1fr));
      gap: 1rem;
      margin-top: 2rem;
    }
    .product {
      backgroun
