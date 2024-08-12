# Three.js Basic Cube Example

This project demonstrates the basics of creating a 3D scene using [Three.js](https://threejs.org/). The example focuses on creating a simple textured rotating cube, illuminated by both ambient and spot lighting.

## Learning Objectives

- Understand the basic setup for a Three.js project, including creating a scene, camera, and renderer.
- Learn how to apply textures to 3D objects using `TextureLoader`.
- Explore basic lighting in Three.js with ambient and spotlights.
- Implement basic animations using the `requestAnimationFrame` method.

## Project Structure

- **index.html**: The main HTML file that includes the necessary Three.js library and the `script.js` file.
- **script.js**: The JavaScript file that sets up the 3D scene, camera, renderer, and cube. It also handles the loading of textures and the cube's rotation animation.
- **three.min.js**: The minified Three.js library.
- **style.css**: Basic CSS file to center the 3D scene in the viewport and remove scrollbars.

## Getting Started

To view the example, simply open `index.html` in a web browser. The project will render a 3D rotating cube with a metal texture applied.

## How It Works

- **Scene Setup**: A scene is created using `THREE.Scene()`, which serves as the container for all 3D objects.
- **Camera**: A perspective camera is set up with a field of view of 75, aspect ratio matching the window size, and a near and far clipping plane.
- **Renderer**: The WebGLRenderer is used to render the scene to the browser window.
- **Cube Creation**: A cube is created using `THREE.BoxGeometry` and `THREE.MeshLambertMaterial`, with a metal texture applied to it.
- **Lighting**: Ambient light provides a base level of illumination, and a spotlight is added to cast dynamic shadows.
- **Animation**: The cube is rotated continuously using a simple animation loop with `requestAnimationFrame`.

## Dependencies

- [Three.js](https://threejs.org/) - A JavaScript library for creating 3D graphics in the browser.

## License

This project is open source and available under the [MIT License](LICENSE).
