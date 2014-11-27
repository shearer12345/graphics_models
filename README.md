#graphics_models

Models for 3D Computer Graphics

##Models available

 - [Stanford Bunny](stanfordBunny/) - in multiple polygon counts

##License

- each directory may have its own license
  - please check the license for the models your want to use are appropriate to your needs

##Usage

- most models are **indexed** and contain:
  - a list of vertices
  - a list of colours (probably)
  - a list of normals (probably)
  - a list of triangles, with indices into the other lists (same index for all)

- the **standard** approach to rendering indexed models is with ```glDrawElements```
  - https://www.opengl.org/sdk/docs/man/html/glDrawElements.xhtml
  - http://www.arcsynthesis.org/gltut/Positioning/Tutorial%2005.html
