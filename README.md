# zsharp
Main ZSharp repository


## Submodules

### MiniZ

[MiniZ](https://github.com/xpodev/miniz) is an object library that contains core Z# objects.

### ZS2MiniZ

[ZS2MiniZ](https://github.com/xpodev/zs2miniz) is the actual compiler which is able to read source Z# files
and compile them to MiniZ objects.

### MiniZ2IL

[MiniZ2IL](https://github.com/xpodev/miniz2il) is a platform specific compiler that takes MiniZ objects and 
compiles them to the .NET platform, allowing for intergation with the .NET ecosystem.

### ZDmp

[ZDmp](https://github.com/xpodev/zdmp) is a small project aims to help with debugging the ZS2MiniZ project.

This small program dumps a MiniZ object graph to any supported format.

Currently supported formats:
* XML
