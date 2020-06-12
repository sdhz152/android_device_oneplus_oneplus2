# android_device_oneplus_oneplus2 #NGK_android_kernel_oneplus_msm8994

安装

sudo apt-get install synaptic

sudo apt-get install libncurses5-dev

sudo apt-get install git-core gnupg flex bison gperf build-essential zip curl libc6-dev libncurses5-dev:i386 x11proto-core-dev libx11-dev:i386 libreadline6-dev:i386 libgl1-mesa-glx:i386 libgl1-mesa-dev g++-multilib tofrodos python-markdown libxml2-utils xsltproc zlib1g-dev:i386

sudo ln -s /usr/lib/i386-linux-gnu/mesa/libGL.so.1 /usr/lib/i386-linux-gnu/libGL.so



（注意：将“ UR_USERNAME”替换为安装ubuntu时使用的名称）

export CROSS_COMPILE=/home/"UR_USERNAME"/oneplus2-kernel/aarch64-linux-android-4.9-uber-master/bin/aarch64-linux-android-


现在在同一终端上运行以下命令：

export ARCH=arm64

export SUBARCH=arm64
