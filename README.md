# Introduction

image-processing-analysis-and-machine-vision-code-implementation

## How to build
### Vcpkg(recommend)

1. Download this repository

```bash
git clone git@github.com:mangosroom/image-processing-analysis-and-machine-vision-code-implementation.git
```

2. CMake 

```bash
cd image-processing-analysis-and-machine-vision-code-implementation
mkdir build
cd build
cmake -DCMAKE_TOOLCHAIN_FILE=<path to vcpkg/scripts/buildsystems/vcpkg.cmake>
```

### Windows 

1. Install opencv on your pc, Setting the environment variable. 

```
variable name = OpenCV_DIR
variable value = <path to you opencv diretory which include "OpenCVConfig.cmake">
```

2. Download this repository

```bash
git clone git@github.com:mangosroom/image-processing-analysis-and-machine-vision-code-implementation.git
```

3. CMake 

```bash
cd image-processing-analysis-and-machine-vision-code-implementation
mkdir build
cd build
cmake ..
```
4. MS build

Open the solution by Visual Studio and build.
### Linux

1. Install OpenCV

2. Download this repository

```bash
git clone git@github.com:mangosroom/image-processing-analysis-and-machine-vision-code-implementation.git
```

3. CMake & make

```bash
cd image-processing-analysis-and-machine-vision-code-implementation
mkdir build
cd build
cmake ..
make -j4
```




## Algorithmes

### Distance transform

[code](https://github.com/mangosroom/image-processing-analysis-and-machine-vision-code-implementation/tree/main/distance-transform)
[introduction of distance transform](https://mangoroom.cn/opencv/distance-transfer.html)
