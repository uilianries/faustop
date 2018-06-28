[![Build Status](https://travis-ci.org/uilianries/faustop.svg?branch=master)](https://travis-ci.org/uilianries/faustop)
# faustop

## Player com frases aleatórias do Fausto Silva

#### Install
Para instalar no sistema Linux

    mkdir build
    cd build
    cmake ..
    cmake --build . --target install

#### Package
Para criar pacote deb

    mkdir build
    cd build
    cmake ..
    cpack -G DEB
    dpkg -i faustop-0.2.0-Linux.deb


Para mudar o diretório base de instalação

    mkdir build
    cd build
    cmake .. -DCMAKE_INSTALL_PREFIX=/custom/base/path
    cpack -G DEB
    dpkg -i faustop-0.2.0-Linux.deb

#### Usage
Executar uma frase aleatória

    $ faustop

#### LICENSE
[MIT](LICENSE)
