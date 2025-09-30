# Flores-azules-
Para mi chico
# Flores-azules-
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ramo Hot Wheels</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; background: #fdf6f9; margin:0; padding:20px;}
    h1 { color:#d63384; margin-top:10px; }
    .ramo { display:flex; flex-direction:column; align-items:center; gap:12px; margin-top:18px; }
    .fila { display:flex; justify-content:center; gap:12px; }
    .carrito { width:150px; cursor:pointer; border-radius:10px; transition:transform .22s, box-shadow .22s; background:#fff; padding:6px;}
    .carrito:hover{ transform:translateY(-6px) scale(1.06); box-shadow:0 10px 18px rgba(0,0,0,.15);}
    #frase { margin-top:22px; font-size:1.15em; font-weight:600; color:#333; padding:12px 18px; border-radius:10px; background:#fff; display:inline-block; box-shadow:0 6px 14px rgba(0,0,0,.08); max-width:90%; }
    @media (max-width:520px){ .carrito{ width:110px;} }
  </style>
</head>
<body>
  <h1>🚗🌸 Ramo de Hot Wheels</h1>
  <p>Haz clic en un carrito para ver su mensaje especial.</p>

  <div class="ramo">
    <div class="fila">
      <img src="https://m.media-amazon.com/images/I/81sYJh8e5nL._AC_SL1500_.jpg" class="carrito" onclick="mostrarFrase(0)" alt="Carrito 1">
    </div>

    <div class="fila">
      <img src="https://m.media-amazon.com/images/I/91ibqBPdQIL._AC_SL1500_.jpg" class="carrito" onclick="mostrarFrase(1)" alt="Carrito 2">
      <img src="https://m.media-amazon.com/images/I/81OmvCUEC6L._AC_SL1500_.jpg" class="carrito" onclick="mostrarFrase(2)" alt="Carrito 3">
    </div>

    <div class="fila">
      <img src="https://m.media-amazon.com/images/I/91bTft3wlgL._AC_SL1500_.jpg" class="carrito" onclick="mostrarFrase(3)" alt="Carrito 4">
      <img src="https://m.media-amazon.com/images/I/91fxa4oaTRL._AC_SL1500_.jpg" class="carrito" onclick="mostrarFrase(4)" alt="Carrito 5">
      <img src="https://m.media-amazon.com/images/I/81SK8z4y7oL._AC_SL1500_.jpg" class="carrito" onclick="mostrarFrase(5)" alt="Carrito 6">
    </div>
  </div>

  <div id="frase"></div>

  <script>
    const frases = [
      "Gracias por enseñarme a amar ❤️",
      "Eres la luz de mis ojos ✨",
      "Me gusta estar contigo 🥰",
      "Mi pensamiento favorito eres tú día a día 💭",
      "eres muy especial para mi",
      "Eres lo mejor que me ha pasado y no lo cambiaría por nada 💖"
    ];

    function mostrarFrase(indice){
      document.getElementById("frase").innerText = frases[indice] || "";
    }
  </script>
</body>
</html>
