mmaker为多进程编译,修改自otp/lib/tools/src/make.erl，可以启动多个process进行编译,从而提高编译速度。
参考 https://github.com/litaocheng/mmake

本版本优化编译等待，一个文件编译完成后，立即进行后续文件编译,不用等待分组完成
