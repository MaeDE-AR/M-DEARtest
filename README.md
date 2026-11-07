# MÆDEARtest

<!DOCTYPE html>
<html lang="no">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Riktig og oppdatert lenke til AR-motoren -->
    <script type="module" src="https://googleapis.com">
    </script>
    <style>
        body { margin: 0; padding: 0; width: 100vw; height: 100vh; display: flex; justify-content: center; align-items: center; background-color: #f0f0f0; }
        model-viewer { width: 100%; height: 100%; }
    </style>
</head>
<body>
    <!-- Rettet opp taggen slik at alt står INNE i åpningstaggen -->
    <model-viewer 
        src="cube.glb" 
        ios-src="CUBE.usdc" 
        ar
        ar-modes="webxr scene-viewer quick-look" 
        camera-controls 
        touch-action="pan-y" 
        alt="En 3D-modell i AR" 
        shadow-intensity="1">
    </model-viewer>

</body>
</html>
