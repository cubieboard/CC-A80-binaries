## Pre-built Cubieboard4 binaries

Built on 04/07/2015 @ rev c826d5c6e511f68658c57dfcb5af350a9daa7f68

$ ./cmd/cubie-fex2bin ~/sunxi-boards/sys_config/a80/a80_cubieboard4.fex a80_cubieboard4.bin
parameter num = 2
script source file Path=/home/kallisti5/sunxi-boards/sys_config/a80/a80_cubieboard4.fex
script bin file Path=a80_cubieboard4.bin
parser file ok

$ ./cmd/cubie-uboot-spl ./bin/u-boot-spl.bin a80_cubieboard4.bin boot0

boot0 file Path=/home2/kallisti5/CC-A80-binaries/./bin/u-boot-spl.bin
script file Path=/home2/kallisti5/CC-A80-binaries/a80_cubieboard4.bin
target file Path=/home2/kallisti5/CC-A80-binaries/boot0

script update boot0 ok

$ ./cmd/cubie-uboot bin/u-boot-sun9iw1p1.bin a80_cubieboard4.bin boot1

uboot file Path=/home2/kallisti5/CC-A80-binaries/bin/u-boot-sun9iw1p1.bin
script file Path=/home2/kallisti5/CC-A80-binaries/a80_cubieboard4.bin
script file Path=/home2/kallisti5/CC-A80-binaries/boot1

