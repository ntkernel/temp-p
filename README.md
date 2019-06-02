# temp-p
----
export PATH=/root/crcp/bin:$PATH
export CROSS_COMPILE=/root/crcp/bin/aarch64-linux-android-
make ARCH=arm64 O=../out merge_msm8937_64_defconfig
make ARCH=arm64 O=../out
