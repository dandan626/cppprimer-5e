# CH01 开始

### 编译运行程序

程序文件通常称为源文件(source file)，不同编译器使用不同的后缀命名约定，常见的包括：.cc/.cxx/.cpp/.cp/.C。   

##### 命令行运行编译器

假如编译器程序是CC，可以通过命令`$ CC prog1.cc`来编译。Windows会将可执行文件命名为`prog1.exe`，UNIX系统通常将可执行文件命名为`a.out`。运行程序只需在命令行输入`$ prog1`(windows)或`$ ./a.out`(UNIX)。   
访问main方法的返回值依赖于系统。UNIX系统中，通过`$ echo $?`来获得返回值；而Windows系统通过`$ echo %ERROELEVEL%`查看状态。
