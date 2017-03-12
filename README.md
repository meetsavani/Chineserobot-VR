# Chineserobot-VR
A simple WebVR page made using A-frame And objects

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Good Afternoon ? A-Frame</title>
    <meta name="description" content="Meet savani ? A-Frame">
    <script src="https://aframe.io/releases/0.3.2/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>

      <a-sphere position="0 0 0" radius="2" color="#FF926B"></a-sphere>
      <a-cone position="0 2 0" color="tomato" height="2.5" radius-bottom="4" radius-top="0"  ></a-cone>
      <a-sphere position="0 -2 0" radius="1" color="yellow"></a-sphere>
      <a-box position="0 0 2" rotation="0 0 0" width="1" height="1" depth="1"  color="#4CC3D9"></a-box>
   
      <a-cylinder position="0 -5 0" radius="3" height="5" color="#FFC65D"></a-cylinder>
      <a-cone position="4 -2.5 0" color="tomato" height="1" radius-bottom="1" radius-top="0"  ></a-cone>
      <a-cone position="-4 -2.5 0" color="tomato" height="1" radius-bottom="1" radius-top="0"  ></a-cone>
      <a-cylinder position="4 -5 0" radius="1" height="4" color="#FF926B"></a-cylinder>
      <a-cylinder position="-4 -5 0" radius="1" height="4" color="#FF926B"></a-cylinder>
      <a-cylinder position="-2 -9.5 0" radius="1" height="4" color="#4CC3D9"></a-cylinder>
      <a-cylinder position="2 -9.5 0" radius="1" height="4" color="#4CC3D9"></a-cylinder>
      <a-sphere position="4 -8 0" radius="1" color="yellow"></a-sphere>
      <a-sphere position="-4 -8 0" radius="1" color="yellow"></a-sphere>
      <a-sphere position="-2 -12 0" radius="1" color="yellow"></a-sphere>
      <a-sphere position="2 -12 0" radius="1" color="yellow"></a-sphere>
      <a-sky color="#ECECEC"></a-sky>
      <a-entity position="0 0 0">
      </a-entity>
    </a-scene>
  </body>
</html>

