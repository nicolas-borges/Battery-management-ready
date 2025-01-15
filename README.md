# Battery-management-ready
We are working on a battery management system. This Python code will help us prepare all the messages. It was built to run on an Ubuntu system.

Running this code will require some pip package.

    Recommend install:
        sudo apt update
        sudo apt install can-utils
        sudo apt install python3-pip
        sudo pip3 install python-can
        sudo pip3 install matplotlib

Setting up CAN is necessary.

    Recommend on CAN:
        sudo ip link set can0 type can bitrate 500000
        sudo ip link set can0 up
