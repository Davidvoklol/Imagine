# Imagine

This is a project for learning more about:
- Basic Rendering concepts and pipelines
- OpenGL

> Clone repo
> ```bash
> git clone --recursive https://github.com/Davidvoklol/Imagine.git
> ```

## Dependencies
- [cmake](https://cmake.org/)
- C++ compiler

## Vendor
- [glfw](https://www.glfw.org/)
- [glad](https://glad.dav1d.de/)
- [glm](https://github.com/g-truc/glm.git)
- [stb_image.h](https://github.com/nothings/stb)

## Build and Run
> [!NOTE]
> Project options:
> - `IMAGINE_BUILD_EXAMPLES`: "ON"
>
> Change the options in [CMakePresets.json](CMakePresets.json)

### Ninja
> Debug
> ```bash
> cmake --preset Ninja-Debug
> ```
> ```bash
> cmake --build --preset Ninja-Debug
> ```

> Release
> ```bash
> cmake --preset Ninja-Release
> ```
> ```bash
> cmake --build --preset Ninja-Release
> ```

> [!NOTE]
> Executables: `build/Ninja/<config type>/bin/<example file name>`<br>
> Lib files: `build/Ninja/<config type>/lib`

### Visual Studio (Windows only)
```bash
cmake --preset Vs22
```

> Debug
> ```bash
> cmake --build --preset Vs22-Debug
> ```

> Release
> ```bash
> cmake --build --preset Vs22-Release
> ```

> [!NOTE]
> Executables: `build/Vs22/<config type>/bin/<example file name>`<br>
> Lib files: `build/Vs22/<config type>/lib`
