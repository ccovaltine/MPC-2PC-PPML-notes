# ABY实践

## 1. prepare

### 1.1 clone repository

```bash
git clone https://github.com/encryptogroup/ABY.git
```

### 1.2 install required packages

```bash
sudo apt-get install <package-name>
```

- g++ (version>=8)
- make
- cmake
- libgmp-dev
- libssl-dev
- libboost-all-dev (version>=1.66)
- doxygen
- graphviz

### 1.3 prepare external dependencies

> ABY depends on the [OTExtension](https://github.com/encryptogroup/OTExtension) and [ENCRYPTO_utils](https://github.com/encryptogroup/ENCRYPTO_utils) libraries, which are referenced using the Git submodules in the ```extern/``` directory.

ABY在编译时依赖 OTExtension 和 ENCRYPTO_utils 库，这两个库作为git子模块存在ABY/extern里。
在后续编译ABY代码时，有两个方法来添加依赖：

- 把这两个库放到C/C++标准库存放的地方——```/usr```或```/usr/local```
- 把这两个库放在任意地方（e.g. \<some-path\>），在后续编译时，在```cmake```时指定参数```CMAKE_PREFIX_PATH```为该位置：```cmake .. -DCMAKE_PREFIX_PATH=<some-path>```

方便起见，这里用的第一种方法。

## 2. build & make

### 2.1 创建&进入build文件夹

```bash
cd ABY/
mkdir build 
cd build
```

### 2.2 cmake

接下来，进行cmake——根据 CMakeLists.txt 构建项目的 Makefile ==（此处存疑——cmake的作用？CMakeLists.txt的写法？）==

  通过阅读 CMakeLists.txt 发现，要想在后续 make 时获得可运行的测试程序，需要把 CMakeLists.txt 里的 ABY_BUILD_EXE 参数设置为 ON，有两个方法：

- 直接修改 CMakeLists.txt，把代码中(第8行) ABY_BUILD_EXE 的值设置为 ON

    ```makefile
    option(ABY_BUILD_EXE "Build executables" ON)
    ```

- 在 cmake 时，指定参数 ABY_BUILD_EXE 为ON
  
    ```bash
    cmake .. -DABY_BUILD_EXE=ON
    ```

这里用的是第一种方法。
修改好 CMakeLists.txt 之后，在```ABY/build```目录下运行

```bash
cmake ..
```

这样，build 目录下就出现了：

- 目录：bin、CMakeFiles、extern、lib、src
- 文件：CMakeCache.txt、CMakeDoxyfile.in、CMakeDoxygenDefaults.cmake、cmake_install.cmake、Makefile

### 2.2 make

继续，在```ABY/build```目录下运行

```bash
make
```

相当于执行了编译过程 ==（此处存疑——make的作用？是编译这个项目吗？Makefile的写法？）==
完成后，```ABY/build/bin```里就有 15 个可执行的 test 文件了。

## 3. test
