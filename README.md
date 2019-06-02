# temp-p
----
export PATH=/root/aarch64-linux-android-4.9/bin:$PATH
export CROSS_COMPILE=/root/aarch64-linux-android-4.9/bin/aarch64-linux-android-
make ARCH=arm64 O=../out merge_msm8937_64_defconfig
make ARCH=arm64 O=../out
