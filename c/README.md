Run helloworld under macOS with c
---------------------------------------

# run helloworld

```
//check gcc
which gcc
/usr/bin/gcc
$ gcc -v
Configured with: --prefix=/Library/Developer/CommandLineTools/usr --with-gxx-include-dir=/usr/include/c++/4.2.1
Apple LLVM version 9.1.0 (clang-902.0.39.2)
Target: x86_64-apple-darwin17.6.0
Thread model: posix
InstalledDir: /Library/Developer/CommandLineTools/usr/bin


//build
$ gcc -o main main.c

//run
$ ./main
Hello,World!
```