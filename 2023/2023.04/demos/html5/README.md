## Known HTML5 issues:
- [x] Game loop is event based (fixed: see `window_loop()`)
- [x] No automated emsdk installation (fixed: see `demos/html5/MAKE.bat`)
- [x] Art must be cooked beforehand (fixed: see `demos/html5/MAKE.bat`)
- [x] No VFS loading (fixed)
- [x] No UI rendering (fixed)
- [x] No cooker (fixed: win,osx,linux)
- [x] No input (fixed)
- [x] No gamepads (fixed)
- [x] No multi-touch (fixed)
- [ ] No audio
- [ ] No file writing (untested)
- [ ] No glTexture1D()
- [ ] No network
- [ ] No fbos
- [ ] No callstacks
- [ ] No pbos
- [ ] Shaders require (automated?) GL->GLES translation (No postfxs, models, skyboxes, pbrs, ...) (@todo: embed Spir-v/glslcross tools?)
- [ ] Shaders: `vec2 iResolution = vec2(iWidth, iHeight); // ERROR: '=' : global variable initializers must be constant expressions`
- [ ] Shaders: `uniform float var = 1.0f; // ERROR: 'uniform' :  cannot initialize this type of qualifier`
