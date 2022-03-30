meson build  --cross-file cross_file_ios.txt

ninja -C build

cd build

meson install
