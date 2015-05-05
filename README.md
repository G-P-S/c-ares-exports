# c-ares-exports
prebuilt binaries for c-ares library


linux-x64 built on Ubuntu 12.04x64
./buildconf
./configure --prefix=`pwd`/../c-ares-exports/linux-x64
make
make install


linux-x32 built on Ubuntu 12.04x64
./buildconf
./configure --prefix=`pwd`/../c-ares-exports/linux-x32 --host=i686-linux-gnu "CFLAGS=-m32" "CXXFLAGS=-m32" "LDFLAGS=-m32"
make
make install


linux-arm-xc6 built on Ubuntu 12.04x64
CC=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-gcc CXX=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-g++ LD=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-ld CXXLD=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-ld STRIP=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-strip AR=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-ar AS=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-as NM=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-nm RANLIB=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-ranlib OBJDUMP=/opt/BUILD_TOOLS/gcc-linaro-arm-linux-gnueabihf-4.7-2012.11-20121123_linux/bin/arm-linux-gnueabihf-objdump ./configure --prefix=`pwd`/../c-ares-exports/linux-arm-xc6 --host=arm-linux-gnueabihf
make
make install
