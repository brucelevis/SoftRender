=======
# SoftRender
To learn OpenGL, Implement basic graphics by OpenGL and my SoftRender at the same time.

##Win10
Build Assimp + Zlib
CMake + MINGW32

Enabled formats: 3DS B3D OBJ BLEND FBX 3D
Disabled formats: AC ASE ASSBIN ASSXML BVH COLLADA DXF CSM HMP IRRMESH IRR LWO LWS MD2 MD3 MD5 MDC MDL NFF NDO OFF OGRE OPENGEX PLY MS3D COB IFC XGL Q3D Q3BSP RAW SIB SMD STL TERRAGEN X GLTF 3MF
Configuring done

cmake --build cmake-build-debug --target assimp -- -j 8

##OSX
CMake
Add CMAKE_BUILD_TYPE  Release

