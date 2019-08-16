![BUCK](https://i.imgur.com/RXp7QTz.png)

# Buck - The Future of Cryptocurrency

BUCK for Raspberry Pi3 and Pi4 compiled from the root [Buck repository](https://github.com/buckcoin/buck) 

Precompiled Pi3 and Pi4 ARM binaries are in the [release section here](https://github.com/BuckCoin/buck-pi3-ARM/releases) 

To compile BUCK for ARM, follow all instructions from the root BUCK repository, plus:


> apt-get install g++-aarch64-linux-gnu  
> HOST=aarch64-linux-gnu ./zcutil/build.sh -j$(nproc)

Security Warnings
-----------------

**Buck is experimental and a work-in-progress.** Use at your own risk.
