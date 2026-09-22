#Hello Cmake
一个最简单的Cmake执行程序

##环境
-linux
-Ubuntu 22.04 LTS
-Cmake 3.10+
-GCC 11+

`test`
```bash
cmake -S . -Bbuild
cmake --build build -j
./build/hello
```
##输出结果
HELLO Robomaster

![Ubuntu环境证明](env.png)

![程序输出结果](output.png)
