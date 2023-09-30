# Instructions

Follow this 

https://michael-verschoof.medium.com/setting-up-mx-master-mouse-on-linux-aae0e2ce3962

* Install
```bash
sudo apt install cmake libevdev-dev libudev-dev libconfig++-dev
```
* Clone logiopt
```bash
git clone https://github.com/PixlOne/logiops.git
```
* Compile
```bash
cd logiops
mkdir build
cd build
cmake ..
make
```
* Install and enabled
```bash
sudo make install
sudo systemctl enable --now logid
```
