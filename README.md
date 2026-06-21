# OpenGL Scene Viewer

An interactive 3D robot arm simulation built with OpenGL. The arm can pick up and manipulate a teapot model, with Phong lighting.

![Demo](demo/ogl-scene.gif)

- Articulated robot arm with 5 independently controllable joint groups (base, shoulder/elbow, wrist, fingers)
- Object parenting: attach the teapot to the wrist so it moves with the arm
- Switchable lighting: point light vs. spotlight (camera aligned)
- Phong shading with attenuation 
- Textured ground plane 
- Assimp-based `.obj` model loading for the held object
- Free look camera with mouse + scroll wheel

## References

- [learnopengl.com](https://learnopengl.com) — Shaders, Lighting, Model Loading
- [songho.ca/opengl/gl_cylinder.html](http://www.songho.ca/opengl/gl_cylinder.html)