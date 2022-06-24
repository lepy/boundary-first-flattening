# Docker interactive

    ~/tmp/boundary-first-flattening>
    sudo docker run -it -v `pwd`:/media ubuntu:20.04

work in ``/media``

    cd /media
    mkdir -p build
    cd build
    cmake .. -DBUILD_GUI=Off
    make -j 4
