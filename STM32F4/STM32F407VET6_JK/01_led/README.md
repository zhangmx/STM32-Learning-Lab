# LED

## Setup

使用ioc文件生成工程，基于cmake构建工程。
其中ld文件存在bug，需要手动修改。如果重新生成的时候被覆盖，记得恢复。

## vscode cmake 插件

如果提示找不到 arm-none-eabi-gcc.exe 在cmake的配置:

```json
"cmake.additionalCompilerSearchDirs": [
  "D:\\path\\to\\xpack-arm-none-eabi-gcc-13.3.1-1.1\\bin"
]
```
