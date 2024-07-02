## flex-2.5.3
mirror for flex lib

## FLEX lib INSTALLATION
set set the installation path:
export di=$(pwd)
./configure --prefix=$di
make
make install
to create a link for some programs
ln -s $di/lib/libfl.a $di/lib/libl.a
