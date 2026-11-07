# MÆDEARtest

<!DOCTYPE html>
<html lang="no">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Min AR Modell</title>
    <script type="module" src="https://googleapis.com"></script>
    <style>
        body { margin: 0; padding: 0; width: 100vw; height: 100vh; display: flex; justify-content: center; align-items: center; background-color: #f0f0f0; }
        model-viewer { width: 100%; height: 100%; }
    </style>
</head>
<body>
    <model-viewer
        src="cube.glb" 
        ios-src="CUBE.usdz" 
        ar
        ar-modes="webxr scene-viewer quick-look" 
        camera-controls 
        touch-action="pan-y" 
        alt="En 3D-modell i AR" 
        shadow-intensity="1">
    </model-viewer>

</body>
</html>

<!--<script type="module" src="https://ajax.googleapis.com/ajax/libs/model-viewer/4.4.0/model-viewer.min.js"></script>

<!-- Use it like any other HTML element -->
<!--<model-viewer alt="Cube test" src="cube.glb" shadow-intensity="1" camera-controls touch-action="pan-y"></model-viewer>
<!--ar environment-image="shared-assets/environments/moon_1k.hdr" poster="shared-assets/models/NeilArmstrong.webp"-->
