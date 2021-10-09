# luajit-2.1-compile
compile luajit 


Replace x86_64/luajit-mac with 
```
└── mac
    └── x86_64
        └── usr
            └── local
                ├── bin
                │   └── luajit-2.1.0-beta3
```

Replace luajit static libs with 
```
./android/x86/usr/local/lib/libluajit-5.1.a
./android/armv7a/usr/local/lib/libluajit-5.1.a
./android/aarch64/usr/local/lib/libluajit-5.1.a
./android/x86_64/usr/local/lib/libluajit-5.1.a
```
