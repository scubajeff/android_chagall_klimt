# Getting sources

repo init -u https://github.com/scubajeff/android_klimt.git -b nougat-release

repo sync

# Building sources
./build.sh <device> <clean/noclean>

./build.sh klimtlte noclean
