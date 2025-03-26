# SuperSplat Viewer - 3D Gaussian Splat Viewer

SuperSplat Viewer is the 3d application powering https://superspl.at.

## Local Development

To initialize a local development environment for SuperSplat Viewer, ensure you have [Node.js](https://nodejs.org/) 18 or later installed. Follow these steps:

1. Clone the repository:

   ```sh
   git clone https://github.com/playcanvas/supersplat-viewer.git
   cd supersplat-viewer
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Build SuperSplat Viewer and start a local web server:

   ```sh
   npm run develop
   ```

4. Open the browser at http://localhost:3000. By default the viewer loads ./settings.json and ./scene.compressed.ply, but these can be overridden with `?settings=url&content=url`.