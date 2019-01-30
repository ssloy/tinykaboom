# KABOOM! in 180 lines of bare C++

This repository is a teaching aid for my computer graphics lectures. It is not meant to produce the ultimate or even physically realistic renders. It is meant to be **simple**. This project is distributed under the [DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE](https://en.wikipedia.org/wiki/WTFPL).

**Check [the article](https://github.com/ssloy/tinykaboom/wiki) that accompanies the source code.**

This project is closely related to my  [software raytracer](https://github.com/ssloy/tinyraytracer/wiki). If you are looking for a software rasterizer, check the [other part of the lectures](https://github.com/ssloy/tinyrenderer/wiki).

In my lectures I tend to avoid third party libraries as long as it is reasonable, because it forces to understand what is happening under the hood. So, the raytracing in 180 lines of plain C++ produces this result:
![](https://raw.githubusercontent.com/ssloy/tinykaboom/master/out.jpg)

## compilation
```sh
git clone https://github.com/ssloy/tinykaboom.git
cd tinykaboom
mkdir build
cd build
cmake ..
make
```

You can open the project in Gitpod, a free online dev evironment for GitHub:

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/ssloy/tinykaboom)

On open, the editor will compile & run the program as well as open the resulting image in the editor's preview.
Just change the code in the editor and rerun the script (use the terminal's history) to see updated images.

## Homework
The possibilities are infinte. For example, you can add the environment map and some transparency:  
![](https://raw.githubusercontent.com/ssloy/tinykaboom/homework_assignment/envmap1.jpg)

Add other objects and illuminate them:
![](https://raw.githubusercontent.com/ssloy/tinykaboom/homework_assignment/envmap2.jpg)
