# GLSL

### Requirements

- GLFW + GLAD
```
$ curl -L https://glad.dav1d.de/generated/tmprj12y_atglad/glad.zip -o glad.zip
$ curl -L  https://github.com/glfw/glfw/releases/download/3.3.8/glfw-3.3.8.zip -o glfw.zip
```

Unzip both, and place them in glfw and glad folders respecitvely.

- XFCE for WSL
```
$ sudo apt-get install xfce4
```

add `export DISPLAY=:0.0` to .bashrc

run startxfce4 with sudo

### Better way

- XFCE for WSL
```
$ sudo apt-get install xfce4
```

add `export DISPLAY=:0.0` to .bashrc

run startxfce4 with sudo

- GLAD + GLSL
```
$ sudo apt-get install libglfw3
$ sudo apt-get install libglfw3-dev
```

### Building binaries

```
$ g++ -pthread -o filename filename.c -lglfw -lGLU -lGL -lXrandr -lXxf86vm -lXi -lXinerama -lX11 -lrt -ldl
```
