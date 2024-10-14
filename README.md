# Physical-map
/website
    /css
        style.css
    /js
        main.js
    index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latin America & Caribbean Maps</title>
    <link rel="stylesheet" href="css/style.css">
    <!-- Leaflet.js -->
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" />
    <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>
    <!-- Cesium.js for 3D models -->
    <script src="https://cesium.com/downloads/cesiumjs/releases/1.85/Build/Cesium/Cesium.js"></script>
    <link href="https://cesium.com/downloads/cesiumjs/releases/1.85/Build/Cesium/Widgets/widgets.css" rel="stylesheet">
</head>
<body>
    <h1>Latin America & Caribbean Physical Maps and Satellite Data</h1>

    <!-- Map container -->
    <div id="map"></div>

    <!-- Google Earth integration -->
    <div id="google-earth-container"></div>

    <!-- Cesium 3D model container -->
    <div id="cesiumContainer"></div>

    <script src="js/main.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
}

#map {
    height: 400px;
    width: 100%;
    margin: 20px 0;
}

#google-earth-container {
    width: 100%;
    height: 400px;
    margin: 20px 0;
}

#cesiumContainer {
    width: 100%;
    height: 400px;
    margin: 20px 0;
}

