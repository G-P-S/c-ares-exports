# c-ares-exports
prebuilt binaries for c-ares library


linux-x64-release built on Ubuntu 12.04x64
./buildconf
./configure --prefix=`pwd`/../c-ares-exports/linux-x64-release  --disable-debug --enable-optimize=O3
make
make install

linux-x64-debug built on Ubuntu 12.04x64
./buildconf
./configure --prefix=`pwd`/../c-ares-exports/linux-x64-debug  --enable-debug
make
make install

linux-x86-release built on Ubuntu 12.04x64
./buildconf
./configure --prefix=`pwd`/../c-ares-exports/linux-x86-release --host=i686-linux-gnu  --disable-debug --enable-optimize=O3 "CFLAGS=-m32" "CXXFLAGS=-m32" "LDFLAGS=-m32"
make
make install

linux-x86-debug built on Ubuntu 12.04x64
./buildconf
./configure --prefix=`pwd`/../c-ares-exports/linux-x86-debug --host=i686-linux-gnu --enable-debug "CFLAGS=-m32" "CXXFLAGS=-m32" "LDFLAGS=-m32"
make
make install


linux-arm-xc6-release built on Ubuntu 12.04x64
CC=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-gcc CXX=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-g++ LD=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-ld CXXLD=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-ld STRIP=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-strip AR=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-ar AS=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-as NM=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-nm RANLIB=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-ranlib OBJDUMP=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-objdump ./configure --prefix=`pwd`/../c-ares-exports/linux-arm-xc6-release --host=arm-linux-gnueabihf --disable-debug --enable-optimize=O3
make
make install

linux-arm-xc6-debug built on Ubuntu 12.04x64
CC=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-gcc CXX=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-g++ LD=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-ld CXXLD=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-ld STRIP=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-strip AR=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-ar AS=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-as NM=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-nm RANLIB=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-ranlib OBJDUMP=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-objdump CFLAGS="-fPIC" ./configure --prefix=`pwd`/../c-ares-exports/linux-arm-xc6-debug --host=arm-linux-gnueabihf --enable-debug
make
make install


linux-arm-a7-release built on Ubuntu 12.04x64
CC=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-gcc CXX=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-g++ LD=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-ld CXXLD=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-ld STRIP=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-strip AR=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-ar AS=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-as NM=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-nm RANLIB=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-ranlib OBJDUMP=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-objdump ./configure --prefix=`pwd`/../c-ares-exports/linux-arm-a7-release --host=arm-linux-gnueabi --disable-debug --enable-optimize=O3
make
make install

linux-arm-a7-debug built on Ubuntu 12.04x64
CC=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-gcc CXX=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-g++ LD=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-ld CXXLD=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-ld STRIP=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-strip AR=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-ar AS=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-as NM=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-nm RANLIB=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-ranlib OBJDUMP=/opt/BUILD_TOOLS/arm-2009q3/bin/arm-none-linux-gnueabi-objdump ./configure --prefix=`pwd`/../c-ares-exports/linux-arm-a7-debug --host=arm-linux-gnueabi --enable-debug
make
make install

linux-arm-a9-release built on Ubuntu 12.04x64
CC=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-gcc CXX=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-g++ LD=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-ld CXXLD=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-ld STRIP=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-strip AR=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-ar AS=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-as NM=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-nm RANLIB=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-ranlib OBJDUMP=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-objdump ./configure --prefix=`pwd`/../c-ares-exports/linux-arm-a9-release --host=arm-linux-gnueabi  --disable-debug --enable-optimize=O3
make
make install

linux-arm-a9-debug built on Ubuntu 12.04x64
CC=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-gcc CXX=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-g++ LD=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-ld CXXLD=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-ld STRIP=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-strip AR=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-ar AS=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-as NM=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-nm RANLIB=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-ranlib OBJDUMP=/opt/BUILD_TOOLS/arm-2012.03/bin/arm-none-linux-gnueabi-objdump ./configure --prefix=`pwd`/../c-ares-exports/linux-arm-a9-debug --host=arm-linux-gnueabi --enable-debug
make
make install

