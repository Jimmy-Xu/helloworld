Run helloworld under macOS with DOSBox+masm
--------------------------------------------

# start DOSBox under macOS

- extract DOSBox.app.zip
- double click DOSBox.app

# mount file from macOS to DOSBox

```
Z:\> mount c .
Drive C is mounted as local directory ./
```

# run helloworld in DOSBox

```
Z:\> c:
C:\> masm hello.asm
C:\> link hello.obj
C:\> hello.exe
Hello World!
```