## node install ubuntu

- sudo -i
- apt -y update
- apt -y install git libevent-dev libboost-all-dev libminiupnpc10 libzmq5 software-properties-common
- add-apt-repository ppa:bitcoin/bitcoin
- apt -y update
- apt -y install libdb4.8-dev libdb4.8++-dev
- apt -y install libqrencode3 libqrencode-dev
- apt-get -y install build-essential libtool autotools-dev automake pkg-config libssl-dev bsdmainutils python3
- apt-get -y install libminiupnpc-dev
- apt-get -y install libzmq3-dev
- apt-get -y install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler
- git clone https://github.com/GamepassNetwork/Gamepass.git
- cd Gamepass
- chmod +x ./share/genbuild.sh
- chmod +x ./autogen.sh && ./autogen.sh
- chmod +x ./configure && ./configure
- make
- make install
