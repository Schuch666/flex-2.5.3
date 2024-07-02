## flex-2.5.3
a mirror for flex lib

## FLEX lib INSTALLATION
set set the installation path "di":
```bash
export di=$(pwd)
mkdir $di
git clone https://github.com/Schuch666/flex-2.5.3.git .
./configure --prefix=$di
make
make install
```
to create a link for some programs
```bash 
ln -s $di/lib/libfl.a $di/lib/libl.a
```
