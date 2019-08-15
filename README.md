# Hello-World
curl -L https://github.com/git/git/archive/v2.22.0.tar.gz --output git-2.22.0.tar.gz
tar -xf git-2.22.0.tar.gz
rm git-2.22.0.tar.gz
cd git-2.22.0
make configure
./configure --prefix=/usr
make
make install
