## 编译

```shell
cd protobuf/cmake
mkdir build
cd build
cmake ../.. -Dprotobuf_BUILD_TESTS=OFF
make -j4
sudo make install
```
