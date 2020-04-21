cmake . -B./output

cd output

make install

ctest

ctest -C Debug -D Experimental