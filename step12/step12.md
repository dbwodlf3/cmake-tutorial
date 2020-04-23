mkdir debug
mkdir release

cd debug

cmake -DCMAKE_BUILD_TYPE=Debug ..

cmake --build .

./Tutorial 9

cd ../release

cmake -DCMAKE_BUILD_TYPE=Release ..

cmake --build .

./Tutorial 9