<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rioquim</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  html, body { height: 100%; }
  body {
    background-color: #8a2be2;
    font-family: Arial, Helvetica, sans-serif;
    color: #fff;
    padding: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
  }

  .indice {
    width: 100%;
    max-width: 1100px;
    background: rgba(255,255,255,0.15);
    padding: 14px 18px;
    border-radius: 14px;
    text-align: center;
    margin-bottom: 20px;
    font-size: 20px;
    font-weight: bold;
    color: #fff;
    box-shadow: 0 4px 10px rgba(0,0,0,0.3);
  }
  .indice a {
    color: #fff;
    text-decoration: none;
    margin: 0 10px;
    padding: 6px 12px;
    border-radius: 8px;
    font-weight: bold;
    transition: all 0.3s ease;
  }
  .indice a:hover { background: #fff; color: #ff8c00; transform: scale(1.1); }

  .central {
    width: 100%;
    max-width: 1100px;
    background: #ff8c00;
    border: 4px solid #fff;
    border-radius: 20px;
    padding: 25px 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.35);
  }
  h1 {
    font-size: 38px;
    font-weight: bold;
    text-align: center;
    margin-bottom: 15px;
    background: linear-gradient(45deg, #8a2be2, #fff);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
  p.lead {
    font-style: italic;
    font-size: 18px;
    text-align: center;
    line-height: 1.5;
  }
  .central img {
    display: block;
    margin: 0 auto;
    width: 80%;
    max-width: 600px;
    border-radius: 12px;
    border: 2px solid #fff;
  }
  a.social { color: #fff; text-decoration: underline; font-weight: 600; }

  section {
    width: 100%;
    max-width: 1100px;
    background: #ffa50033;
    padding: 20px;
    border-radius: 12px;
    text-align: center;
    margin-bottom: 20px;
    border: 2px solid #fff;
  }
  section h2 { margin-bottom: 12px; font-size: 22px; text-decoration: underline; }
  section img {
    margin: 15px 0;
    width: 60%;
    max-width: 400px;
    border-radius: 10px;
    border: 2px solid #fff;
  }
  ul { margin-top: 12px; display: grid; gap: 6px; list-style: none; padding-left: 0; }
  ul li::before { content: "✅"; margin-right: 8px; }

  #clientes {
    width: 100%;
    max-width: 1100px;
    background: #ff69b433;
    border-radius: 12px;
    padding: 20px;
    text-align: center;
    border: 2px solid #fff;
    margin-bottom: 20px;
  }
  #clientes h2 { font-size: 22px; text-decoration: underline; margin-bottom: 12px; }
  .clientes-frases p {
    font-size: 18px;
    font-weight: bold;
    margin: 8px 0;
    color: #fff;
    background: rgba(0,0,0,0.3);
    padding: 8px 12px;
    border-radius: 10px;
  }
  .clientes-fotos img {
    margin: 10px;
    width: 30%;
    max-width: 200px;
    border-radius: 12px;
    border: 2px solid #fff;
  }

  .contacto {
    width: 100%;
    max-width: 1100px;
    background: #ff8c0033;
    border-radius: 12px;
    padding: 20px;
    text-align: center;
    border: 2px solid #fff;
  }
  .contacto h2 { font-size: 22px; text-decoration: underline; margin-bottom: 12px; }
  .contacto p { margin: 6px 0; font-size: 16px; }
  .contacto a { color: #8a2be2; font-weight: bold; text-decoration: none; }

  .volver {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 16px;
    background: #fff;
    color: #ff8c00;
    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;
    border: 2px solid #fff;
  }
  .volver:hover { background: #f1f1f1; color: #8a2be2; }

  @media (max-width: 600px) {
    h1 { font-size: 30px; }
    .central img { width: 95%; }
    section img { width: 90%; }
    .clientes-fotos img { width: 80%; max-width: none; }
  }
</style>
</head>
<body>

<!-- ÍNDICE -->
<div class="indice">
  <a href="#inicio">Inicio</a> |
  <a href="#cloro">Cloro</a> |
  <a href="#venenos">Venenos</a> |
  <a href="#automotores">Automotores</a> |
  <a href="#articulos">Artículos de limpieza</a> |
  <a href="#clientes">Clientes</a> |
  <a href="#contacto">Contacto</a>
</div>

<!-- BLOQUE CENTRAL -->
<div class="central" id="inicio">
  <h1>Rioquim</h1>
  <img src="img/portada.png" alt="Portada Rioquim">
  <img src="img/frente.png" alt="Fr
