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

