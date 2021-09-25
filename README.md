# host env
   lazyoung@lazyoung:~/code/riscv64-linux/llvm-project$ lsb_release -a
No LSB modules are available.
Distributor ID:	Ubuntu
Description:	Ubuntu 20.04.3 LTS
Release:	20.04
Codename:	focal
lazyoung@lazyoung:~/code/riscv64-linux/llvm-project$ cat /proc/version
   Linux version 5.4.0-86-generic (buildd@lgw01-amd64-041) (gcc version 9.3.0 (Ubuntu 9.3.0-17ubuntu1~20.04)) #97-Ubuntu SMP Fri Sep 17 19:19:40 UTC 2021

# setup according https://zhuanlan.zhihu.com/p/258394849
   $ sudo apt install autoconf automake autotools-dev curl libmpc-dev libmpfr-dev libgmp-dev \
                 gawk build-essential bison flex texinfo gperf libtool patchutils bc \
                 zlib1g-dev libexpat-dev git \
                 libglib2.0-dev libfdt-dev libpixman-1-dev \
                 libncurses5-dev libncursesw5-dev
   $ sudo apt install 
   $ cd riscv64-linux
