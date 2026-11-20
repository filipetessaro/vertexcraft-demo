# Vertexcraft Demo

Windows demo of **Vertexcraft**, crowds of animated characters for Unreal Engine 5.6 to 5.8: the animation is baked
into textures and played on the GPU, and the crowds walk, march, line up and fight. The demo is the plugin's own
showcase, packaged as a Shipping build with UE 5.8.

**Download:** [VertexcraftDemo_Win64.zip](https://github.com/filipetessaro/vertexcraft-demo/releases/latest/download/VertexcraftDemo_Win64.zip)
(296 MB). Windows 64-bit, DirectX 12. No engine needed.

Unzip it anywhere and run `Vertexcraft.exe`. A guided tour goes through five shots on its own, with the frame time at
the top right:

1. 2,200 animated characters, instances of one static mesh
2. 1,200 in the stands, each with its own idle, colour and time; the nearest 8 become real skeletal meshes
3. 600 marching along a spline, walk and run following each one's speed
4. 400 crossing a broken wall by a flow field
5. A battle of two armies of 150: Red marches in a block, Blue flanks it and charges once its wings are in

| Key | What it does |
|---|---|
| Right, Left or Space | Next or previous shot |
| 1 to 5 | Go to a shot |
| R | The same shot again (the battle starts over) |
| H | Hide the words |
| Esc | Quit |

The characters are the UEFN mannequin and the animations come from Epic Games' Game Animation Sample. They are in the
demo only, not in the plugin.

Support: contato@tessaroapps.com
