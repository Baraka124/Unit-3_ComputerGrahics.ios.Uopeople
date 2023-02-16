<!DOCTYPE html>
<html>
  <head>
    <title>Bouncing Ball Animation</title>
    <style>
      body {
        margin: 0;
        padding: 0;
        overflow: hidden;
      }
    </style>
  </head>
  <body>
    <script src="https://threejs.org/build/three.min.js"></script>
    <script>
      let camera, scene, renderer, mesh;
      let directionX = 1;
      let directionY = 1;

      init();
      animate();

      function init() {
        camera = new THREE.PerspectiveCamera(
          70,
          window.innerWidth / window.innerHeight,
          0.01,
          10
        );
        camera.position.z = 1;

        scene = new THREE.Scene();

        const geometry = new THREE.BoxGeometry(0.2, 0.2, 0.2);
        const material = new THREE.MeshPhongMaterial({ color: 0xff0000 });
        mesh = new THREE.Mesh(geometry, material);
        scene.add(mesh);

        const light = new THREE.PointLight(0xffffaa, 1, 100);
        light.position.set(-1, 1, 1);
        scene.add(light);

        renderer = new THREE.WebGLRenderer({ antialias: true });
        renderer.setSize(window.innerWidth, window.innerHeight);

        document.body.appendChild(renderer.domElement);
      }

      function animate() {
        requestAnimationFrame(animate);
        mesh.position.x += 0.01 * directionX;
        mesh.position.y += 0.01 * directionY;

        if (mesh.position.x > 0.9 || mesh.position.x < -0.9) {
          directionX *= -1;
          const newColor = Math.random() * 0xffffff;
          mesh.material.color.setHex(newColor);
        }
        if (mesh.position.y > 0.9 || mesh.position.y < -0.9) {
          directionY *= -1;
          const newColor = Math.random() * 0xffffff;
          mesh.material.color.setHex(newColor);
        }

        renderer.render(scene, camera);
      }
    </script>
  </body>
</html>
