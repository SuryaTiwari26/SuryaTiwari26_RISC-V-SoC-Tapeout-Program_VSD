
# RISC-V Reference SoC Tapeout Program VSD
###Tools Installation
A brief description of what this project does and who it's for


## Tools Installation

All the instructions for installation of required tools can be found here:
    
## System Requirements 

6 GB RAM

50 GB HDD

Ubuntu 20.04 or higher

4 vCPU
## TOOL CHECK

### YOSYS
```$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make               # If make is not installed
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
# Yosys build depends on a Git submodule called abc, which hasn't been initialized yet. You need to run the following command before running make
$ git submodule update --init --recursive
$ make 
$ sudo make install

```
![Alt Text](https://media.canva.com/v2/image-resize/format:PNG/height:227/quality:100/uri:ifs%3A%2F%2FM%2Fd420de93-d81e-47cb-9134-071e1438fdcd/watermark:F/width:550?csig=AAAAAAAAAAAAAAAAAAAAAFpR0fJGcoh7yqJ4j6nNoZecBOWk0OjnUBCk1GlAu2Gh&exp=1758500552&osig=AAAAAAAAAAAAAAAAAAAAAPnRVOunWhtimjNmq8Uwnh4JxcAnAIcMLeR65QRuA9Aq&signer=media-rpc&x-canva-quality=thumbnail_large)


### IVERILOG

```
$ sudo apt-get update
$ sudo apt-get install iverilog
```
![Alt Text]([![i-verilog-2.png](https://i.postimg.cc/g2QSjBhB/i-verilog-2.png)](https://postimg.cc/9DPtNbJG)

###GTKWAVE
```
$ sudo apt-get update
$ sudo apt install gtkwave

```
![Alt Text]([![gtkwave3-Copy.png](https://i.postimg.cc/fTXj5TS5/gtkwave3-Copy.png)](https://postimg.cc/4mf9xG5h)
## Lessons Learned

Installed Ubuntu and configured open-source tools like Yosys, GTKWave, and Icarus Verilog for digital design.

