# vorfract
vorfract is a voxel building environment which uses irregular voxels (called cells) instead of the usual cubic grid ones.
This allows voxels to have sloped/inclined faces, which are pretty useful for roofs, steep terrain and so on.

Everything is made of cells, so all changes are made using tools that recursively break/unbreak them.
Since a cell's position and shape is determined by its kernel (called a generator) and its surrounding cells, shaping objects in vorfract ultimately comes down to placing, moving or removing generator points.

Itch.io version: https://jazzprogramming.itch.io/vorfract

Github.io version: https://jazzprogramming.github.io/vorfract/
