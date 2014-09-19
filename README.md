# Voxelizer

This is the **voxelizer code** in my slide: [Incarnation - Turning Real World Objects Into Perfume-World ](http://www.slideshare.net/yungluen/incarnation-turning-real-world-objects-into-perfume-world).

Voxelizer export [Perfume-World](http://perfume-world.jp) JSON format from `*.OBJ` and `*.MTL`.

![Voxelizer](https://raw.githubusercontent.com/yllan/voxelizer/master/voxelizer.png)


## Usage
---
1. Make sure your *.obj and *.mtl files have the same name. Put it into the same directory as `index.html`.
2. Set the `modelName` variable in [index.html](https://github.com/yllan/voxelizer/blob/master/index.html#L47)
3. Change the `step` variable. Bigger step means less voxels.
4. Open `index.html` in Chrome. You need to run a HTTP server to serve the file since Chrome doesn't allow AJAX throught local file URL. The easiest way is run `python -m SimpleHTTPServer` under the directory and connect to `http://localhost:8000` in Chrome.
5. After the browser rendered the voxels, click the `Save` link on the page.

## Credits
---
- Yung-Luen Lan ([@yllan](https://twitter.com/yllan))
- [three.js](http://threejs.org) by [@mrdoob](http://mrdoob.com)
- OBJMTLLoader from [@angelxuanchang](https://github.com/angelxuanchang)

## License
---
Voxelizer is available under the MIT license. See the LICENSE file for more info.