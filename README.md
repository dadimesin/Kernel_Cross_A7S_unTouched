Cross A7S
=========

    cd kernel
    
    CROSS_COMPILE=/somewhereonyourcomputer/prebuilt/linux-x86/toolchain/arm-linux-androideabi-4.4.x/bin/arm-linux-androideabi-
    
    TARGET_PRODUCT=tinno77_s9091jb
    
    ./build.sh

This will create a file in the kernel/out/kernel_tinno77_s9091jb.bin folder. 

CAUTION: You need to use the generated m4u.ko otherwise it won't boot.
