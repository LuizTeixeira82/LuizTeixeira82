<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
  <script src="https://raw.githack.com/jeromeetienne/AR.js/master/aframe/build/aframe-ar.js"></script>
</head>
<body>
  <a-scene embedded arjs>
    <!-- Adicione seu marcador personalizado (pode ser uma imagem ou um padrão) -->
    <a-marker preset="custom" type="pattern" url="caminho/do/marcador.patt">
      <!-- Adicione elementos 3D relacionados à liderança -->
      <a-entity position="0 0 0">
        <a-text value="Desenvolva suas habilidades de liderança!" color="black" width="2"></a-text>
        <!-- Outros elementos 3D, como modelos, gráficos, etc., podem ser adicionados -->
      </a-entity>
    </a-marker>

    <!-- Câmera padrão da AR -->
    <a-entity camera></a-entity>
  </a-scene>
</body>
</html>
