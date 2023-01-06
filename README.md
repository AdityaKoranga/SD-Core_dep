# SD-Core_dep

## sdcore
```bash
ENABLE_GNBSIM=false DATA_IFACE=eth2 make 5g-core
```
> extra interfaces so using eth2, and gnbsim false (bc using UEransim)

## For UERANSIM
```bash
sudo apt install make
sudo apt install gcc
sudo apt install g++
sudo apt install libsctp-dev lksctp-tools
sudo apt install iproute2
sudo snap install cmake --classic
```
```bash
make -j18
```
> -j_no. of cores

